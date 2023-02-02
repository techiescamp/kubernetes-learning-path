
## Hit the Star! :star:

If you are planning to use this repo for reference, please hit the star. Thanks!


Kubernetes Learning Roadmap
=================

> 🚀  CKA, CKAD, CKS, or KCNA exam aspirants can **save $60** today using code **DCUBEOFFER** at https://kube.promo/devops. It is a limited-time offer from Linux Foundation.

Prerequisites
=================

- [Learn Container concepts & Gets Hands on with Docker](https://www.freecodecamp.org/news/the-docker-handbook/) <sup>Complete Guide</sup>
- [Understand Distributed system](https://www.freecodecamp.org/news/a-thorough-introduction-to-distributed-systems-3b91562c9b3c) <sup>Blog</sup>
- [Understand Authentication & Authorization](https://www.okta.com/identity-101/authentication-vs-authorization/) <sup>Blog</sup>
- [Learn Basics of Key Value Store](https://redis.com/nosql/key-value-databases/)<sup>Blog</sup>
- [Learn the basics of REST API](https://blog.postman.com/intro-to-apis-what-is-an-api/)<sup>Blog</sup>
- [Learn YAML](https://www.educative.io/blog/yaml-tutorial?aff=KNLz)<sup>Blog</sup>
- [Understand Service Discovery](https://www.nginx.com/blog/service-discovery-in-a-microservices-architecture/) <sup>Blog</sup>
- Learn Netwoking Basics
   - [L4 & L7 Layers (OSI Layers)](https://www.cloudflare.com/en-gb/learning/ddos/glossary/open-systems-interconnection-model-osi/)<sup>Blog</sup>
   - [SSL/TLS](https://www.cloudflare.com/en-gb/learning/ssl/how-does-ssl-work/)<sup>Blog</sup>
   - [Network Proxy Basics](https://stackoverflow.com/questions/224664/whats-the-difference-between-a-proxy-server-and-a-reverse-proxy-server)<sup>Blog</sup>
   - [DNS](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)<sup>Blog</sup>
   - [IPTables](https://www.youtube.com/watch?v=6Ra17Qpj68c)<sup>Video</sup>
   - [Software Defined Networking (SDN)](https://www.vmware.com/topics/glossary/content/software-defined-networking.html)<sup>Blog</sup>

Learn Kubernetes Architecture
=================
The Following image shows the high level kubernetes architecture and how external services connect to the cluster.

![kubernetes-architecture](https://user-images.githubusercontent.com/5181260/214278898-43e50d8c-0fc3-4b5e-ae63-dc61ec8097a8.png)

Refer the follwing documents to learn the Kubernetes Architecture.

- [Kubernetes Architecture Explained](https://devopscube.com/kubernetes-architecture-explained/) <sup>Blog</sup>

Learn to Setup Kuberntes Cluster
=================

As DevOps engineers, gaining a thorough understanding of each component and cluster configuration is crucial to work in production environemnts. Though there are various methods for deploying a Kubernetes cluster, it is advisable to learn how to set up multi-node clusters from scratch. This allows you to gain knowledge on concepts such as High Availability, Scaling, and Networking, and simulates a real-world project. 

Additionally, mastering the configuration of multi-node clusters can be beneficial for interviews and building confidence in your abilities. The following are recommended ways to establish a Kubernetes cluster.

- [Kubernetes the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)<sup>Github</sup>
- [Kubeadm Cluster Setup](https://devopscube.com/setup-kubernetes-cluster-kubeadm/)<sup>Blog</sup>
- [Minikube Development Cluster ](https://devopscube.com/kubernetes-minikube-tutorial/)<sup>Blog</sup>
- [Kind Development Cluster](https://kind.sigs.k8s.io/)<sup>Official Documentation</sup>
- [Vagrant Automated Cluster](https://github.com/techiescamp/vagrant-kubeadm-kubernetes)<sup>Github</sup>

$1000+ Free Cloud Credits to Launch Clusters
=================

Launching large clusters in the cloud can be costly. So utilize the available cloud credits to practice deploying clusters as if you work on a real project. All cloud platforms offer managed Kubernetes services.

- [GKE -Google Cloud $300 free credits](https://cloud.google.com/kubernetes-engine)<sup>Cloud Platform</sup>
- [EKS - AWS $300 free POC credits](https://aws.amazon.com/eks/)<sup>Cloud Platform</sup>
- [DO Kubernetes - Digital Ocean – $200 free credits](https://devopscube.com/recommends/digital-ocean-sidebar/)<sup>Cloud Platform</sup>
- [Linode Kubernetes Engine - Linode Cloud – $100 Free credits](https://devopscube.com/recommends/linode-credits/)<sup>Cloud Platform</sup>
- [Vultr Kubernetes Engine - Vultr Cloud - $250 Free Credits](https://devopscube.com/recommends/vultr-credits/)<sup>Cloud Platform</sup>

Understand KubeConfig File
=================

As a DevOps engineer, it is important to become familiar with the Kubeconfig file. It is crucial for tasks such as setting up cluster authentication for CI/CD systems, providing cluster access to developers, and more.

A Kubeconfig file is a YAML file that stores information and credentials for connecting to a Kubernetes cluster. It is used by command-line tools such as kubectl and other client libraries to authenticate with the cluster and interact with its resources.

The Kubeconfig file can be used to store information for multiple clusters and users, allowing users to switch between different clusters and contexts easily. It is an important tool for managing access to and interacting with Kubernetes clusters.

Refer the follwing document to learn about Kubeconfig File in detail.

- [Kubeconfig File Explained With Practical Examples](https://devopscube.com/kubernetes-kubeconfig-file/) <sup>Blog</sup>


Understand Kubernetes Objects And Resources
=================

In Kubernetes, an object is a persisted entity in the cluster that represents a desired state of the system. It is created and managed by the Kubernetes API server, and is stored in the etcd key-value store. Examples of Kubernetes objects include pods, services, and deployments.

Here is an example of a Pod Object

<pre>
apiVersion: v1
kind: Pod
metadata:
  name: nginx
spec:
  containers:
  - name: nginx
    image: nginx:1.14.2
    ports:
    - containerPort: 80
</pre>

A resource is a representation of a Kubernetes object that is exposed by the Kubernetes API. It is a way for clients to interact with and manipulate objects in the cluster. 

A resource refers to a specific API URL used to access an object. Resources are typically accessed through the Kubernetes API using HTTP verbs such as GET, POST, and DELETE. For instance, the <code>/api/v1/pods</code> resource can be used to retrieve a list of v1 Pod objects. Additionally, an individual v1 Pod object can be obtained from the <code>/api/v1/namespaces/<namespace-name>/pods/<pod-name></code> resource

### Learn About Pod & Associated Resources

<--In Progress-->

### Learn About Pod Dependent Objects

<--In Progress-->

### Deploy End to End Application on Kubernetes

<--In Progress-->

### Learn About Securing Kubernetes Cluster

<--In Progress-->

### Learn About Kubernetes Operator Pattern

<--In Progress-->

### Learn Important Kubernetes Configurations

<--In Progress-->

### Learn Kubernetes Best Practices

<--In Progress-->

### Learn Kubernetes Logging & Monitoring

<--In Progress-->

Learn Kubernetes Production Best Practices/Learnings
=================

- Production Readiness Checklist 
- [Learn About 12 Factor Apps](https://12factor.net/) <sup>Official Guide</sup>
- [Learn From Kubernetes Failure Stories](https://k8s.af/) <sup>List of Blogs</sup>
- [Scheduling 300,000 Kubernetes Pods in Production Daily](https://www.youtube.com/watch?v=wjy35HfIP_k) <sup>Video</sup>

Real-World Kubernetes Case Studies 
=================

If you do not have real world Kubernetes experience, it is better to read case studies of other companies using kubernetes. 

- [List of Kubernetes User Case Studies](https://kubernetes.io/case-studies/)<sup>Official Case Studies</sup>
- [How OpenAI Scaled Kubernetes to 7,500 Nodes](https://openai.com/blog/scaling-kubernetes-to-7500-nodes/)<sup>Blog</sup>
- [Testing 500 Pods Per Node](https://cloud.redhat.com/blog/500_pods_per_node)<sup>Blog</sup>
- [Dynamic Kubernetes Cluster Scaling at Airbnb](https://medium.com/airbnb-engineering/dynamic-kubernetes-cluster-scaling-at-airbnb-d79ae3afa132)<sup>Blog</sup>

Learn Kubernetes Templating Tools
=================

Helm and Kustomize are both tools that are used to manage Kubernetes manifests. They are similar in many ways, but have some key differences.

Helm is a package manager for Kubernetes that allows users to easily install, manage, and upgrade applications on a Kubernetes cluster. It uses a concept called "charts" which are pre-configured sets of Kubernetes resources that can be easily deployed, upgraded, and rolled back.

Kustomize, on the other hand, is a tool that allows users to customize and configure existing Kubernetes manifests. It uses a concept called "patches" which can be applied to existing manifests to customize them for different environments and use cases. Unlike Helm, Kustomize does not include built-in support for versioning and rollback, and does not have a concept of "packages" or "repositories".

- [Learn to Create Helm Chart From Scratch](https://devopscube.com/create-helm-chart/)<sup>Hands-On Blog</sup>

### 16.Kubernetes Deployment Tools (GitOps Based)

<--In Progress-->
