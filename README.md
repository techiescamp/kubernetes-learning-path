## Hit the Star! :star:

If you are planning to use this repo for reference, please hit the star. Thanks!

## Kubernetes Learning Roadmap

The Kubernetes Learning Roadmap is constantly updated with new content, so you can be sure that you're getting the latest and most up-to-date information available. 

## Kubernetes Certification Coupon

- 🚀  CKA, CKAD, CKS, or KCNA exam aspirants can **save 40%** today using code **SCARYTECHIES** at https://kube.promo/devops. It is a limited-time offer from the Linux Foundation.
- For the best savings, opt for the CKA + CKS bundle (**$355 Savings)**. Use code **SCARYTECHIES** at https://kube.promo/bundle

>Note: You have one year of validity to appear for the certification exam after registration


## Table of Contents

- [Kubernetes Learning Roadmap](#kubernetes-learning-roadmap)
- [Kubernetes Certification Coupon](#kubernetes-certification-coupon)
- [Kubernetes Learning Prerequisites](#kubernetes-learning-prerequisites)
- [Learn Kubernetes Architecture](#learn-kubernetes-architecture)
- [$1000+ Free Cloud Credits to Launch Clusters](#1000-free-cloud-credits-to-launch-clusters)
- [Learn Kubernetes Cluster Setup & Administration](#learn-kubernetes-cluster-setup-administration)
- [Understand KubeConfig File](#understand-kubeconfig-file)
- [Understand Kubernetes Objects And Resources](#understand-kubernetes-objects-and-resources)
- [Learn About the Object YAML Structure](#learn-about-the-object-yaml-structure)
- [Learn About Pod & Associated Resources](#learn-about-pod-associated-resources)
- [Learn About Pod Dependent Objects](#learn-about-pod-dependent-objects)
- [Deploy End to End Application on Kubernetes](#deploy-end-to-end-application-on-kubernetes)
- [Learn About Securing Kubernetes Cluster](#learn-about-securing-kubernetes-cluster)
- [Learn About Kubernetes Operator Pattern](#learn-about-kubernetes-operator-pattern)
- [Learn Important Kubernetes Configurations](#learn-important-kubernetes-configurations)
- [Learn Kubernetes Best Practices](#learn-kubernetes-best-practices)
- [Learn Kubernetes Logging & Monitoring](#learn-kubernetes-logging-monitoring)
- [Learn Kubernetes Production Best Practices](#learn-kubernetes-production-best-practices)
- [Real-World Kubernetes Case Studies](#real-world-kubernetes-case-studies)
- [Kubernetes Failures/Learnings](#kubernetes-failureslearnings)
- [Learn Kubernetes Templating Tools](#learn-kubernetes-templating-tools)
- [Kubernetes Deployment Tools (GitOps Based)](#kubernetes-deployment-tools-gitops-based)


## Kubernetes Learning Prerequisites

If you want to learn Kubernetes, it's important to start with the basics. That means brushing up on your IT fundamentals first because Kubernetes builds on those. Once you have a good grasp of the basics, learning Kubernetes can be fun and easy. So don't skip the fundamentals – take some time to study them before diving into Kubernetes!

- [Learn Container concepts](https://devopscube.com/what-is-a-container-and-how-does-it-work/)<sup>Complete Guide</sup>
- [Learn Container Management Tool - Docker](https://www.freecodecamp.org/news/the-docker-handbook/) <sup>Complete Guide</sup>
- [Understand Distributed system](https://www.freecodecamp.org/news/a-thorough-introduction-to-distributed-systems-3b91562c9b3c) <sup>Blog</sup>
- [Understand Authentication & Authorization](https://www.okta.com/identity-101/authentication-vs-authorization/) <sup>Blog</sup>
- [Learn Basics of Key Value Store](https://redis.com/nosql/key-value-databases/)<sup>Blog</sup>
- [Learn the basics of REST API](https://blog.postman.com/intro-to-apis-what-is-an-api/)<sup>Blog</sup>
- [Learn YAML](https://www.educative.io/blog/yaml-tutorial?aff=KNLz)<sup>Blog</sup>
- [Understand Service Discovery](https://devopscube.com/service-discovery-explained/) <sup>Blog</sup>
- Learn Networking Basics
   - [L4 & L7 Layers (OSI Layers)](https://www.cloudflare.com/en-gb/learning/ddos/glossary/open-systems-interconnection-model-osi/)<sup>Blog</sup>
   - [SSL/TLS](https://www.cloudflare.com/en-gb/learning/ssl/how-does-ssl-work/)<sup>Blog</sup>
   - [Network Proxy Basics](https://stackoverflow.com/questions/224664/whats-the-difference-between-a-proxy-server-and-a-reverse-proxy-server)<sup>Blog</sup>
   - [DNS](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)<sup>Blog</sup>
   - [IPTables](https://www.youtube.com/watch?v=6Ra17Qpj68c)<sup>Video</sup>
   - [Software Defined Networking (SDN)](https://www.vmware.com/topics/glossary/content/software-defined-networking.html)<sup>Blog</sup>

## Kubernetes Architecture

The following image shows the high-level kubernetes architecture and how external services connect to the cluster.

![kubernetes-architecture](https://user-images.githubusercontent.com/5181260/214278898-43e50d8c-0fc3-4b5e-ae63-dc61ec8097a8.png)

Refer to the following documents to learn the Kubernetes Architecture.

- [Kubernetes Architecture Explained](https://devopscube.com/kubernetes-architecture-explained/)<sup>Blog</sup>
- [Kubernetes Garbage Collection](https://github.com/techiescamp/kubernetes-learning-path/blob/main/architecture/garbage-collection.md)<sup>Doc</sup>

## $1000+ Free Cloud Credits to Launch Clusters

Launching large clusters in the cloud can be costly. So utilize the available cloud credits to practice deploying clusters as if you work on a real project. All cloud platforms offer managed Kubernetes services.

- [GKE -Google Cloud $300 free credits](https://cloud.google.com/kubernetes-engine)<sup>Cloud Platform</sup>
- [EKS - AWS $300 free POC credits](https://pages.awscloud.com/GLOBAL_NCA_LN_ARRC-program-A300-2023.html)<sup>Cloud Platform</sup>
- [DO Kubernetes - Digital Ocean – $200 free credits](https://devopscube.com/recommends/digital-ocean-sidebar/)<sup>Cloud Platform</sup>
- [Linode Kubernetes Engine - Linode Cloud – $100 Free credits](https://devopscube.com/recommends/linode-credits/)<sup>Cloud Platform</sup>
- [Vultr Kubernetes Engine - Vultr Cloud - $250 Free Credits](https://devopscube.com/recommends/vultr-credits/)<sup>Cloud Platform</sup>
- [AKS - Azure Cloud Hosting - $200 Free Credits](https://azure.microsoft.com/en-us/free/)<sup>Cloud Platform</sup>
 
## Kubernetes Cluster Setup & Administration

As DevOps engineers, gaining a thorough understanding of each component and cluster configuration is crucial to work in production environments. Though there are various methods for deploying a Kubernetes cluster, it is advisable to learn how to set up multi-node clusters from scratch. This allows you to gain knowledge on concepts such as High Availability, Scaling, and Networking and simulates a real-world project. 

Additionally, mastering the configuration of multi-node clusters can be beneficial for interviews and building confidence in your abilities. The following are recommended ways to establish a Kubernetes cluster.

- [Kubernetes the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)<sup>Github</sup>
- [Kubeadm Cluster Setup](https://devopscube.com/setup-kubernetes-cluster-kubeadm/)<sup>Blog</sup>
- [Minikube Development Cluster ](https://devopscube.com/kubernetes-minikube-tutorial/)<sup>Blog</sup>
- [Kind Development Cluster](https://kind.sigs.k8s.io/)<sup>Official Documentation</sup>
- [Vagrant Automated Cluster](https://github.com/techiescamp/vagrant-kubeadm-kubernetes)<sup>Github</sup>

Following are some of the important cluster administrative tasks

- [Deploy Kubernetes Dashboard](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)<sup>Official Doc</sup>
- [Important Kubernetes Cluster Configurations](https://devopscube.com/kubernetes-cluster-configurations/)<sup>Blog</sup>
- [Kubeadm Cluster Upgrade](https://devopscube.com/upgrade-kubernetes-cluster-kubeadm/)<sup>Blog</sup>
- [etcd backup using etcdctl](https://devopscube.com/backup-etcd-restore-kubernetes/)<sup>Blog</sup>
- [Run CIS benchmarks using kube-bench](https://devopscube.com/kube-bench-guide/)<sup>Blog</sup>

## Understand KubeConfig File

As a DevOps engineer, it is important to become familiar with the Kubeconfig file. It is crucial for tasks such as setting up cluster authentication for CI/CD systems, providing cluster access to developers, and more.

A Kubeconfig file is a YAML file that stores information and credentials for connecting to a Kubernetes cluster. It is used by command-line tools such as kubectl and other client libraries to authenticate with the cluster and interact with its resources.

The Kubeconfig file can be used to store information for multiple clusters and users, allowing users to switch between different clusters and contexts easily. It is an important tool for managing access to and interacting with Kubernetes clusters.

Refer to the following document to learn about the Kubeconfig File in detail.

- [Kubeconfig File Explained With Practical Examples](https://devopscube.com/kubernetes-kubeconfig-file/) <sup>Blog</sup>

## Understand Kubernetes Objects And Resources

In Kubernetes, an object is a persisted entity in the cluster that represents a desired state of the system. It is created and managed by the Kubernetes API server and is stored in the etcd key-value store. Examples of Kubernetes objects include pods, services, and deployments.

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

A resource refers to a specific API URL used to access an object. Resources are typically accessed through the Kubernetes API using HTTP verbs such as GET, POST, and DELETE. For instance, the <code>/api/v1/pods</code> resource can be used to retrieve a list of v1 Pod objects. Additionally, an individual v1 Pod object can be obtained from the <code>/api/v1/namespaces/**namespace-name**/pods/**pod-name**</code> resource.

**Detailed Blog:** [Kubernetes Objects & Resources Explained](https://devopscube.com/kubernetes-objects-resources/)

## Learn About the Object YAML Structure

Every object in Kubernetes is represented/created using a YAML file. 
Kubernetes has many native objects (20+), however, every object YAML follows a hierarchical structure as shown below. 
```
apiVersion: <API version>
kind: <Kind of object>
metadata:
  name:  <Name of the object>
spec:
  <Specification of the object>>
```
Here is what each section means.

- **apiVersion:** Specifies the Kubernetes API version used for the object. 
- **kind:** Defines the type of Kubernetes object being created or modified.
- **metadata:** Contains information about the object.
- **spec:** Defines the desired state of the object, including its configuration and behavior. Under spec, there could be many subfields depending on the object type.

The structure remains the same for all native Kubernetes objects. While learning about each object, you can check the hierarchy, and you will be able to relate.

## Learn All Pod Concepts & Features 

All the essential concepts in Kubernetes center around the Pod. Understanding Pods in detail, along with their supported features, is crucial for anyone working with Kubernetes because many other objects in Kubernetes are built around them. Below are comprehensive guides that delve into various aspects of the Pod with real-world practical examples.

- [Kubernetes Pod Explained](https://devopscube.com/kubernetes-pod/) <sup>Blog</sup>
- [multi-container pods](https://www.mirantis.com/blog/multi-container-pods-and-container-communication-in-kubernetes/)<sup>Blog</sup>
- [Init Containers Explained](https://devopscube.com/kubernetes-init-containers/) <sup>Blog</sup>
- [Pod Lifecycle Phases](https://devopscube.com/kubernetes-pod-lifecycle/)<sup>Blog</sup>
- [Pod Priority, PriorityClass, and Preemption](https://devopscube.com/pod-priorityclass-preemption/)<sup>Blog</sup>
- [Pod Quality or Service - QoS](https://techiescamp.com/kubernetes-pod-qos/)<sup>Blog</sup>
- [Troubleshoot Pod](https://devopscube.com/troubleshoot-kubernetes-pods/)<sup>Blog</sup>
- [Container Lifecyle Hooks](https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/)<sup>Official Doc</sup>
- [Pod Disruption Budget](https://cast.ai/blog/pod-disruption-budgets-in-your-deployment/)<sup>Blog</sup>
- [Pod Affinity/Anti-Affinity](https://www.densify.com/kubernetes-autoscaling/kubernetes-affinity/)<sup>Blog</sup>
- [Pod Labels & Selectors](https://www.split.io/blog/kubernetes-labels-best-practices/)<sup>Blog</sup>

In the topics above, we've covered all the core concepts of Pods that are used in production-level implementations. You should practice these concepts hands-on. Once you have a solid practical understanding of Pods, you can move on to learning about objects that depend on Pods.


## Learn About Pod Dependent Objects

Running applications on a single pod can be a single point of failure. That's why Kubernetes provides various objects that use pods to make applications highly available.

### 1. ReplicaSet
Makes sure a specific number of pod replicas are running at all times. If a pod crashes, the ReplicaSet starts a new one.

**Use Case:** Good for stateless applications where you need multiple identical pods.

**Detailed Blog:** [Replicaset Guide](https://sysdig.com/learn-cloud-native/kubernetes-101/kubernetes-replicasets-overview/)

---

### 2. Deployment

Manages ReplicaSets and allows for easy updates and rollbacks. It also scales the number of pod replicas.

**Use Case:** Useful for stateless applications and when you need to update or rollback easily.

**Detailed Blog:** [Deployment Explained](https://codefresh.io/learn/kubernetes-deployment/)

---

### 3. StatefulSet

Like a Deployment, but for stateful applications. It gives each pod a unique identity.

**Use Case:** Good for databases and other stateful applications.

**Detailed Blog:** [Statefulset Explained](https://loft.sh/blog/kubernetes-statefulset-examples-and-best-practices/)

---

### 4. DaemonSet

Ensures that each node in the cluster runs a copy of a pod.

**Use Case:** Useful for node monitoring or logging agents.

**Detailed Blog:** [Daemonset Explained](https://devopscube.com/kubernetes-daemonset/)

---

### 5. Job

Creates one or more pods and ensures that a specified number of them are completed successfully.

**Use Case:** Good for batch processing tasks.

**Detailed Blog:** [Kubernetes Jobs Practical Guide](https://devopscube.com/create-kubernetes-jobs-cron-jobs/)

---

### 6. CronJob

Like a Job, but runs at specific times or intervals.

**Use Case:** Useful for scheduled tasks like backups.

**Detailed Blog:** [Kubernetes CronJobs Practical Guide](https://devopscube.com/create-kubernetes-jobs-cron-jobs/)

## Learn About Services

Applications deployed on Pods using deployments may need to be accessed either internally within the cluster by other services or externally from outside the cluster. 

The feature that facilitates this access to Pods is known as Services in Kubernetes. 

Services provide a stable IP address and DNS name, enabling seamless communication and load balancing among Pods, regardless of their lifecycle changes. This ensures that the network connectivity to applications remains consistent and reliable.


**Detailed Blog:** [Kubernetes Service Explained Visually](https://medium.com/swlh/kubernetes-services-simply-visually-explained-2d84e58d70e5)

## Learn About Ingress & Ingress Controller

Applications running inside Kubernetes require more than just a single endpoint. For instance, if you are running an e-commerce microservice application, you may need to route incoming requests to multiple backend services based on the request path. This is where the Ingress object comes into play.

Ingress Acts like a "front door" to manage incoming traffic to multiple Kubernetes backend services. It Works at Layer 7 (Application Layer) of the OSI model, meaning it can understand HTTP and HTTPS.

### Ingress

Using an Ingress object you can define a set of rules for how traffic should be routed.  For example, you can set up rules to send traffic for "www.example.com/shop" to a "shop" service and "www.example.com/blog" to a "blog" service. The only work of ingress is to maintain the routing rules.

**Detailed Blog:** [Kubernetes Ingress Explained](https://devopscube.com/kubernetes-ingress-tutorial/)

### Ingress Controller

An Ingress Controller is the part that actually makes the Ingress work. It is software  that runs inside your cluster and listens for changes to DNS/routing rules from the Ingress object.  The software could be Nginx, HAproxy, evvoy, etc. 

**Detailed Blog:** [Ingress Controller Explained With Practical Example](https://devopscube.com/setup-ingress-kubernetes-nginx-controller/)

**Ingress Controller Comparison**  [Comparison of Kubernetes Ingress controllers](https://docs.google.com/spreadsheets/d/191WWNpjJ2za6-nbG4ZoUMXMpUK8KlCIosvQB0f-oq3k/edit#gid=907731238)

### Gateway API

Gateway API is like an upgraded version of the Ingress system. It lets you define how traffic should be handled in a more detailed way. For example, you can specify different kinds of load balancing, or set up more complex routing rules.

**Official Documentation:** [Gateway API Documentation](https://gateway-api.sigs.k8s.io/)

## Deploy End to End Application on Kubernetes

<--In Progress-->

## Learn Kubernetes Logging & Monitoring

<--In Progress-->

## Learn About Securing Kubernetes Cluster

<--In Progress-->

## Learn About Kubernetes Operator Pattern

<--In Progress-->

## Learn Kubernetes Templating Tools

Helm and Kustomize are both tools that are used to manage Kubernetes manifests. They are similar in many ways but have some key differences.

Helm is a package manager for Kubernetes that allows users to easily install, manage, and upgrade applications on a Kubernetes cluster. It uses a concept called "charts" which are pre-configured sets of Kubernetes resources that can be easily deployed, upgraded, and rolled back.

Kustomize, on the other hand, is a tool that allows users to customize and configure existing Kubernetes manifests. It uses a concept called "patches" which can be applied to existing manifests to customize them for different environments and use cases. Unlike Helm, Kustomize does not include built-in support for versioning and rollback, and does not have a concept of "packages" or "repositories".

- [Learn to Create Helm Chart From Scratch](https://devopscube.com/create-helm-chart/)<sup>Hands-On Blog</sup>
- [Getting started with Kuztomize](https://devopscube.com/kustomize-tutorial/)<sup>Hands-On Blog</sup>

## Kubernetes Deployment Tools (GitOps Based)

GitOps is a technical practice that uses Git as a single source of truth for declarative infrastructure and application code. 

- [Guide to GitOps](https://www.weave.works/technologies/gitops/)<sup>Official Doc</sup>

Some popular GitOps-based tools for deploying applications to Kubernetes clusters are:

- [Argo CD](https://argo-cd.readthedocs.io/en/stable/)<sup>Official Doc</sup>
- [Argo Rollouts](https://argo-rollouts.readthedocs.io/en/stable/)<sup>Official Doc</sup>
- [FluxCD](https://fluxcd.io/)<sup>Official Doc</sup>
- [JenkinsX](https://jenkins-x.io/)<sup>Official Doc</sup>

## Learn Kubernetes Production Best Practices

- [Learn About 12 Factor Apps](https://12factor.net/) <sup>Official Guide</sup>
- [Production Readiness Checklist](https://learnk8s.io/production-best-practices)<sup>Blog</sup>
- [Recycling Kubernetes Nodes - Yelp](https://engineeringblog.yelp.com/2023/01/recycling-kubernetes-nodes.html)<sup>Blog</sup>

## Understand Capacity Planning

Capacity planning is a key aspect of Kubernetes implementation. It's essential for cost savings, performance, resource allocation, scalability, and optimization, among other things.

- [Kubernetes Node Capacity](https://www.densify.com/kubernetes-autoscaling/kubernetes-node-capacity/) <sup>Blog</sup>
- [Rightsize the requests](https://sysdig.com/blog/kubernetes-capacity-planning/)<sup>Blog</sup>
- [Kubernetes Instance Calculator](https://learnk8s.io/kubernetes-instance-calculator)<sup>Tool & Doc</sup>

## Real-World Kubernetes Case Studies

If you do not have real-world Kubernetes experience, it is better to read case studies of other companies using kubernetes.

- [List of Kubernetes User Case Studies](https://kubernetes.io/case-studies/)<sup>Official Case Studies</sup>
- [Scheduling 300,000 Kubernetes Pods in Production Daily](https://www.youtube.com/watch?v=wjy35HfIP_k) <sup>Video</sup>
- [How OpenAI Scaled Kubernetes to 7,500 Nodes](https://openai.com/blog/scaling-kubernetes-to-7500-nodes/)<sup>Blog</sup>
- [Testing 500 Pods Per Node](https://cloud.redhat.com/blog/500_pods_per_node)<sup>Blog</sup>
- [Dynamic Kubernetes Cluster Scaling at Airbnb](https://medium.com/airbnb-engineering/dynamic-kubernetes-cluster-scaling-at-airbnb-d79ae3afa132)<sup>Blog</sup>
- [Scaling 100 to 10,000 pods on Amazon EKS](https://aws.amazon.com/blogs/containers/scale-from-100-to-10000-pods-on-amazon-eks)<sup>Blog</sup>
- [Kubernetes Infrastructure At Medium](https://medium.engineering/kubernetes-infrastructure-at-medium-d9e2444932ef)<sup>Blog</sup>
- [EKS architecture to improve resiliency](https://aws.amazon.com/blogs/containers/life360s-journey-to-a-multi-cluster-amazon-eks-architecture-to-improve-resiliency/)<sup>Blog</sup>

## Kubernetes Failures/Learnings

- [Learn From Kubernetes Failure Stories](https://k8s.af/) <sup>List of Blogs</sup>
- [Reddit: The Pi-Day Outage](https://www.reddit.com/r/devops/comments/11zvig0/you_broke_reddit_the_piday_outage/)<sup>Blog</sup>
- [How a Production Outage Was Caused Using Kubernetes Pod Priorities](https://grafana.com/blog/2019/07/24/how-a-production-outage-was-caused-using-kubernetes-pod-priorities/)<sup>Blog</sup>
