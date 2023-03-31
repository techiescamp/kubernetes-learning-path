## 1. Kubernetes Garbage Collection

As a Kubernetes user, you might create, update, and delete various resources over time, such as pods, deployments, and services. These resource management tasks generate temporary and unwanted objects that consume system resources, like memory and storage, without providing any useful functionality. This is where garbage collection comes into play.

Garbage collection is the process of automatically identifying and removing these unwanted resources to maintain a clean and efficient system. In Kubernetes, garbage collection ensures that the system runs smoothly by preventing unnecessary resource usage and freeing up storage space.

Remember that Kubernetes garbage collection is designed to clean up these objects automatically. However, it's essential to understand the relationships between objects and ensure that you're properly managing them to avoid any unintended consequences.

For example,

The kubelet performs garbage collection on unused images every five minutes and on unused containers every minute.

