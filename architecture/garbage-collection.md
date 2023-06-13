## 1. Kubernetes Garbage Collection

As a Kubernetes user, you might create, update, and delete various resources over time, such as pods, deployments, and services. These resource management tasks generate temporary and unwanted objects that consume system resources, like memory and storage, without providing any useful functionality. This is where garbage collection comes into play.

Garbage collection is the process of automatically identifying and removing these unwanted resources to maintain a clean and efficient system. In Kubernetes, garbage collection ensures that the system runs smoothly by preventing unnecessary resource usage and freeing up storage space.

>**Note**: Kubernetes garbage collection is designed to clean up these objects automatically. However, it's essential to understand the relationships between objects and ensure that you're properly managing them to avoid any unintended consequences. For example, The kubelet performs garbage collection on unused images every five minutes and on unused containers every minute.

- **Garbage Collection of Containers:** When you delete a Pod in Kubernetes, it's not instantly removed. Instead, it moves to the "Terminating" state, where all of its containers are killed. Even after their execution has stopped, these dead containers still exist in the system, and it's garbage collection's responsibility to remove them.
- **Garbage Collection of Pods:** When you delete Pods or when Pods become orphaned (i.e., the resources that created them have been deleted), garbage collection cleans up these Pods.
- **Garbage Collection of Images:** Kubernetes also manages the lifecycle of images inside the nodes. The kubelet performs image garbage collection to remove unused images and free up node disk space.

Here is a simplified flow:

- A Pod is marked for deletion or becomes orphaned.
- The Pod moves into a "Terminating" state.
- The containers within the Pod are killed.
- The kubelet performs garbage collection, deleting the dead containers.
- The kubelet performs garbage collection again, deleting the terminated Pods.
- If an image is no longer referenced by any Pods, the kubelet will remove it in the next image garbage collection cycle.

![mermaid-diagram-2023-06-13-123035](https://github.com/techiescamp/kubernetes-learning-path/assets/106984297/ecf96b01-80d7-4e5f-b81b-46f426eb4c90)

>**Note**: you can set up garbage collection policies to manage how it functions, including how frequently it runs and what it should prioritize. This helps keep your Kubernetes environment clean, efficient, and optimized.

