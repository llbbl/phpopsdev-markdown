# DevOps / SRE - Top Links Last Week

## Week 41 Issue #48


## [Introducing Anthos for VMs and tools to simplify the developer experience](https://cloud.google.com/blog/topics/hybrid-cloud/introducing-anthos-for-vms-and-other-app-modernization-tools/)

Anthos was originally designed to run applications in containers. Anthos for VMs allows you to shift VMs onto Anthos with KubeVirt, an open-source virtualization API for Kubernetes. The new Anthos Multi-Cloud API lets you provision and manage GKE clusters running on AWS and Azure infrastructure directly from the Google Cloud Console. The Anthos control plane can connect to your active vSphere environment and attach your vSphere VMs, allowing you to apply consistent security and policies.

## [GitLab Inc. takes The DevOps Platform public](https://about.gitlab.com/blog/2021/10/14/gitlab-inc-takes-the-devops-platform-public/)

GitLab was the first company to publicly live stream the entire end-to-end listing day at Nasdaq. CEO: "Every company must become a software company or they’ll be disrupted" CEO: GitLab's mission is to ensure that everyone can contribute. GitLab is the leading DevOps platform with an estimated 30 million registered users. It also has more than 2,600 contributors in its open source community, which it lists as a competitive strength. We plan to maintain our startup ethos by continuing to do the following:.

---

## [Ubuntu 21.10](https://ubuntu.com/blog/ubuntu-21-10-has-landed)

Ubuntu 21.10 is the most productive environment for cloud-native developers and AI/ML innovators across the desktop, devices and cloud. The new Firefox snap, published by Mozilla, improves security and guarantees access to both the latest and the extended support release versions of the browser. The number of snaps published in the store has grown by 25%, and the snap store now serves over 10 million systems daily. The latest LTS Docker Images from Canonical include Grafana, Prometheus, and NGINX.

## [The newest Ubuntu Linux, Impish Indri, arrives](https://www.zdnet.com/article/the-newest-ubuntu-linux-impish-indri-arrives/)

Ubuntu 21.10, Impish Indri, is Canonical's latest Ubuntu Linux release. It's the short-term -- nine months of support -- predecessor to the company's next long-term support (LTS) version, Ubuntu 22.04. New programs include LibreOffice 7.2 office suite, Thunderbird 91 e-mail client, Firefox 92 web browser. New tools for developers include the all-new PHP 8 and GCC 11.2. The latest LTS Docker Images are backed by Canonical for Ubuntu's full, 10-year support life.

## [GitLab’s mega IPO](https://techcrunch.com/2021/10/16/techcrunch-exchange-gitlabs-mega-ipo/)

GitLab CEO Sid Sijbrandij talks about the massive GitLab IPO. GitLab's strong net retention metrics helped with revenue predictability, he says. He says open-source code is now a boon to companies hoping to build long-term relationships with developers. Cloudflare is moving into the “storage as a service’s market, but it will not be utterly titanic if we see titanic tech companies with a global footprint that offer a particular flavor of digital service.

## [Pulumi Releases a Kubernetes Operator](https://thenewstack.io/pulumi-releases-a-kubernetes-operator/)

Infrastructure-as-code cloud engineering platform provider Pulumi made its Pulumi Kubernetes Operator generally available this week. New 1.0 release brings many enhancements including support for GitOps workflows with branch tracking and private Git repos. The Pulumi Automation API is largely influenced by the company’s experience building the Pulumi Operator, which embeds Pulumi deployments inside Kubernetes, offering a new interface for managing cloud infrastructure. In addition to support for branch tracking, the Operator also now supports access to private Git repositories.

## [Gitlab CI/CD — Understand The Basics](https://faun.pub/gitlab-ci-cd-understand-the-basics-95e603ba92e2)

GitLab Runner is an application that works with GitLab CI/CD to run jobs in a pipeline. They can also run inside a Docker container or be deployed into a Kubernetes cluster. Types of Runners are available globally and can automatically be allocated based on their availability. For this, you have to register a runner and you can only use it in a specific project or can also use it for a specific stage of your pipeline. To register a specific runner, follow the commands on your Ubuntu Machine and read the guide carefully.

## [Microservices vs Monolith: The Ultimate Comparison 2021](https://faun.pub/microservices-vs-monolith-the-ultimate-comparison-2021-8747201ed53)

In the emerging trend of microservices, debates over Microservices vs Monoliths are inevitable. The microservice architecture provides tangible benefits like scalability and flexibility and is a cost-effective way for creating heavy applications. Tech giants like Netflix, Amazon, and Oracle generally implement microservices in one application or the other. The monolith approach is losing its value as it poses risks to current software delivery methodologies. Let’s talk about the pros and cons of the two architectural styles.

## [Introducing Ambassador Cloud Developer Edition](https://blog.getambassador.io/introducing-ambassador-cloud-developer-edition-bf0712aff0c2)

Ambassador Cloud Developer Edition lets you set up a “developer control plane” to code, ship, and run apps using Kubernetes. Ambassador Cloud is based on a developer-first workflow. It includes a context-aware Heads-Up Display that lets you manage your apps and services throughout the entire development lifecycle. It visualizes real-time data from the API, Swagger, and OpenAPI docs into human-readable metadata to help you discover, inspect, and take action on critical information to resolve incidents across all your environments.

## [Hello, Opta Local](https://blog.runx.dev/hello-opta-local-150c04be6db5)

Developers can quickly iterate without having to maintain a docker-compose environment or deal with the long wait times of deploying to the public cloud. Opta Local will let you test and iterate your code on a Kubernetes cluster running on your own machine; and then use the same infrastructure-as-code Opta files to deploy to AWS, GCP or Azure.

## [Scaling Indexing and Search – Algolia New Search Architecture](http://highscalability.com/blog/2021/10/11/scaling-indexing-and-search-algolia-new-search-architecture.html)

Search engines need to support fast scaling for both Read and Write operations. This scaling method brings drawbacks, such as Write operations unnecessarily hurting the Read performance and using a significant amount of duplicated CPU at indexing. To support more Write operations, we split the data into several smaller pieces called shards and added more CPUs to build these shards. This model allows parallelization of the majority of read and write operations for better performance. The indexing CPU can become even more expensive when the search engine also computes a vector-based index.

## [Nomad vs. Kubernetes](https://www.nomadproject.io/docs/nomad-vs-kubernetes)

Kubernetes aims to provide all the features needed to run Linux container-based applications including cluster management, scheduling, service discovery, monitoring, secrets management and more. Nomad only aims to focus on cluster management and scheduling and is designed with the Unix philosophy of having a small scope while composing with tools like Consul for service discovery/service mesh and Vault for secret management. The system is a single binary, both for clients and servers, and requires no external services for coordination or storage. By default, Nomad is distributed, highly available, and operationally simple.

## [How to win at CORS](https://jakearchibald.com/2021/cors/)

CORS (Cross-Origin Resource Sharing) is hard because it's part of how browsers fetch stuff. It started with the first web browser over 30 years ago. Since then it's been a constant source of development; adding features, improving defaults, and papering over past mistakes without breaking too much of the web. To make things interactive, I built an exciting new app: CORS is hard. It's hard to explain why CORS came into existence, and how it fits into other kinds of fetches.

## [A Detailed Understanding of VPC Flow Logs in AWS](https://aws.plainenglish.io/detailed-understanding-of-vpc-flow-logs-821a5acd75af)

VPC Flow Logs are a feature of VPC in AWS which allows you to capture all happenings (IP traffic going to and from the network interfaces) at the network interface level in VPC. These all captured information can be published into S3 or CloudWatch based upon your requirements. Flow logs can help you with a number of tasks, such as: Diagnosing overly restrictive security group rules, monitoring the traffic that is reaching your instance and determining the direction of the traffic. You can even query on these massive data using Amazon QuickSight, which is used for analytical purposes.

## [Automate Provisioning of Kubernetes Clusters on AWS with Terraform](https://faun.pub/automate-provisioning-of-kubernetes-clusters-on-aws-with-terraform-61ff6aaf8ead)

In this article, we are going to create an EKS cluster using terraform. In the previous article we created the cluster using an AWS management console. We will use Terraform to create a VPC with all the subnets and configurations inside the VPC. The VPC is a control plane that is managed by AWS. We need to create worker nodes and connect them to the master node. We also need to set the availability zone depending on the region using data in Terraform. We can then get all the availability zones from the region specified in the provider.

## [Kubernetes Deep Dive Ten: StatefulSet Topology](https://tonylixu.medium.com/kubernetes-deep-dive-ten-statefulset-topology-82512a20bdf2)

Kubernetes Deep Dive: StatefulSet Topology is an orchestration function in k8s. It abstracts the application state in the real world into two situations: Topology status. Multiple instances of the application are not completely peer-to-peer. This means that multiple instances of it are not peer-based. These instances must be started in a certain order, for example, the master node A must start before the slave node B. And if you delete the two Pods A and B, they must strictly follow this order when they are created again. If you delete one Pod, the newly created Pod must have the same network ID as the original Pod, so that the original.