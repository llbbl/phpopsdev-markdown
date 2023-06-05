# DevOps / SRE - Top Links Last Week

## Week 35 - Issue #94

  

25 links

  

## [Where Can Heroku Free Tier Users Go? – The New Stack](https://thenewstack.io/where-can-heroku-free-tier-users-go/)

1. Salesforce is discontinuing the free tier for Heroku, which will impact millions of applications and websites.

2. This is likely because Salesforce no longer has any strategic interest in growing Heroku's customer base.

3. Render is the closest alternative for most Heroku users, and we've seen tremendous growth since Heroku's April security incident.

  

## [What are the four Golden Signals?](https://www.gremlin.com/blog/four-golden-signals/)

The Golden Signals are four key metrics teams should monitor on each user-facing system to ensure reliability and a good user experience.

  

## [Testing Ansible Automation with Molecule Pt. 2 | by Phil Critchfield | Contino Engineering  | Medium](https://medium.com/contino-engineering/testing-ansible-automation-with-molecule-pt-2-7e2ff5a70bcc)

This post explores using Molecule to deploy a Laravel website. It discusses using Molecule to deploy multiple containers, validate database tasks, confirm idempotency, and ensure code meets linting standards.

  

## [Microsoft's Arm-based Azure VMs are ready to roll | ZDNET](https://www.zdnet.com/article/microsofts-arm-based-azure-vms-are-ready-to-roll/)

Microsoft is releasing VMs on Azure that is Arm-based. These VMs will be available in multiple regions and can run a variety of Linux OS distributions and Windows 11.

  

## [GIT Branching Strategies in 2022. Collaboration in software development… | by Manuel Herrera López  | FAUN Publication](https://faun.pub/git-branching-strategies-in-2022-83938c5784d8?source=rss----10d1a7495d39---4)

The most significant advantage of a Git branch is that it's 'lightweight,' meaning that data consists of a series of snapshots, so with every commit you make, Git takes a picture of what your files look like at that moment and stores a reference to that snapshot. So these branches aren't just copies of the file system but simply a pointer to the latest commit. This Strategy also adds a new layer of flexibility, in which you can take any path.

  

  

---

  

  

## [Validate Crossplane Compositions with Datree | by Piotr  | ITNEXT](https://itnext.io/validate-crossplane-compositions-with-datree-f52061cdb1b7)

The blog discusses the importance of testing and validation for Crossplane compositions written in YAML. It explains that the ultimate goal is for compositions to be generated automatically and that there are three levels of testing/validation: custom policies validation, conformance testing, and acceptance testing.

  

## [Python — Moto, Why You Should Use | by Tony  | Dev Genius](https://blog.devgenius.io/python-moto-why-you-should-use-8a8152209aec)

Moto is a Python library that allows you to mock out AWS resources for testing purposes. You can install it using pip, and it decorates functions or classes, creating a mock out of AWS resources handling calls in the decorated code block. A simple example of how to use it to test code that creates an AWS S3 bucket.

  

## [Kubernetes Probes Explained. Probes are nothing but the checker to… | by Mohan Raj Ravi  | Medium](https://medium.com/@mohansujay22054044/kubernetes-probes-explained-9b41424b4b85)

Probes are used in Kubernetes to check whether a service is functioning as desired. There are three types of probes: startup, liveness, and readiness. Probes can be implemented using different methods, such as HTTP, command, TCP, and gRPC.

  

  

## [How to Run Databases in Kubernetes | by Javier Ramos  | ITNEXT](https://itnext.io/stateful-workloads-in-kubernetes-e49b56a5959)

Kubernetes is an excellent platform for running stateful workloads such as databases, thanks to features like StatefulSets. However, running databases in Kubernetes can be complex and requires extra functionality, such as operators managing daily operations.

  

## [K8s — Node IP vs Pod IP vs Cluster IP | by Tony | Geek Culture  | Medium](https://tonylixu.medium.com/k8s-node-ip-vs-pod-ip-vs-cluster-ip-65f75d4432b8)

The k8s cluster has three IP addresses: Node IP, Pod IP, and Cluster IP. Node IP is the server's IP address that is treated as a node. Pod IP is the IP address of the Pod, assigned by the docker0 NIC (If you use Docker runtime). Finally, cluster IP is a virtual IP, a fake IP network.

  

## [The Introduction of Service Mesh. It is a networking model that sits at a… | by JIN  | Dev Genius](https://blog.devgenius.io/the-introduction-of-service-mesh-710d9b566df0)

Service mesh is a networking model that sits at a layer above individual services to manage communication between them. It is composed of a series of lightweight network proxies that are transparent to the application. Service mesh ensures that requests travel reliably through a complex topology of services.

  

## [Optimize Your Go Dockerfile for Size and Speed | by Bertrand Quenin  | Better Programming](https://betterprogramming.pub/modern-rest-api-with-go-and-postgresql-e0070aa1b383)

You can use Alpine Linux to create tiny container images

-Multi-stage builds are an excellent way to keep your images small

-Compose is a tool for defining and running multi-container Docker applications

-In development, you may need to expose Postgres ports to the host

  

  

## [Package and Deploy Your Application Using Helm Chart | by Amit Kumar  | FAUN Publication](https://faun.pub/package-and-deploy-your-application-using-helm-chart-21f0c568e65c)

This blog shows how Helm Chart packages and deploys an application on a minikube cluster. Helm Chart defines configurations in values.yaml file and uses these values to create and manage k8s objects.

  

## [How are Microservices different from APIs | by Hardik Shah  | Dev Genius](https://blog.devgenius.io/how-are-microservices-different-from-apis-614e5c02e7e8)

Microservices are individual services that work together to create an application, while APIs are how different services can communicate with each other.

  

## [Kustomize Introduction](https://nicolasbarlatier.hashnode.dev/introduction-kubernetes-and-kustomize-how-to-easily-customize-any-resource-configuration-with-kustomize)

Kustomize is a simple tool that can be used to make declarative changes to your configurations without touching a template. For example, with Kustomize, you can apply changes with overlays to the original file's transformation without touching it.

  

  

## [How I Became An AWS Serverless Hero | Ready, Set, Cloud!](https://www.readysetcloud.io/blog/allen.helton/how-i-became-an-aws-serverless-hero/)

AWS Serverless Hero is a community recognition program highlighting individuals who have helped others within the AWS serverless community through blog posts, newsletters, podcasts, and community engagement. There are no specific criteria for becoming an AWS Serverless Hero, but Tyler thinks being passionate, sharing, and helping others is an excellent place to start.

  

## [Create a CI/CD Pipeline with Github, CodeBuild, and Codepipeline | by Huy Le  | AWS in Plain English](https://medium.com/@huyquangle0503/create-a-ci-cd-pipeline-with-github-codebuild-and-codepipeline-cc08ea2310eb)

A CI/CD pipeline is a best practice for DevOps and Agile development responsible for the entire application or website production process. To set one up on AWS, you can use CodePipeline and Github.

  

## [A Quick Intro to Automated Testing | by Nico Anastasio  | FAUN Publication](https://faun.pub/a-quick-intro-to-automated-testing-3043946e30d5)

In this article, the author discusses the importance of automated testing, different types of tests, and how to get started with PHPUnit.

  

## [Terraform — Module Introduction. What is Terraform Module? | by Tony  | Dev Genius](https://blog.devgenius.io/terraform-module-introduction-3647c7511d0c)

In Terraform, a module is a folder containing a set of Terraform code. Modules encapsulate groups of resources dedicated to one task, reducing the code you have to develop for similar infrastructure components. Terraform modules are essential for writing high-quality Terraform code and improving code reusability.

  

## [Kubernetes Command Line Tooling | Shorts | by Vishnu Deva  | Medium](https://vishnudeva.medium.com/kubernetes-command-line-tooling-dd8a2b600af3)

This article covers four necessary tools for your Terminal to make life easier when working with Kubernetes: kube-ps1, kubectl-aliases, kubectl-tree, and K9s. All of these tools are designed to make it easier to work with Kubernetes, whether by providing aliases for kubectl commands, showing resource relationships, or providing a graphical interface.

  

## [Becoming a Systems Architect](https://wojtekmandrysz.com/blog/systems-architect/)

The author became a systems architect without meaning to and now wants to share his story in hopes of helping others in a similar situation. He talks about how he became interested in computers and programming at a young age and eventually ended up working in the mobile app development industry. He also talks about how he transitioned into systems engineering and finally realized that this is what he had always wanted to do.

  

  

  

## [Refresh Secrets for Kubernetes Applications with Vault Agent](https://www.hashicorp.com/blog/refresh-secrets-for-kubernetes-applications-with-vault-agent)

Vault Agent can be used to manage secrets for Kubernetes applications without the need to modify application code directly. This approach can be done by injecting Vault Agent as a sidecar, configuring it to cache secrets, and defining annotations to tell Vault Agent what secrets to manage and how to refresh them.

  

## [Diving Into Clean Architecture. Architecting for event-driven… | by Martin Cerruti  | Better Programming](https://betterprogramming.pub/diving-into-clean-architecture-2769ced23802)

Clean architecture is a testable, event-focused, and layered architecture that's a magnificent go-to architecture if you don't have a clear idea of what you're building.

  

## [The Truth About Enterprise Security Architectures In 3 Minutes | by Supun Sandeeptha  | AWS in Plain English](https://supunsandeeptha.medium.com/the-truth-about-enterprise-security-architectures-in-3-minutes-847b8cd51a78)

The business world has changed with more and more businesses starting to use IoT with their operations and other extensive technologies. Unfortunately, it's not the same threats that companies are facing today. Given all the new threats and challenges, security professionals should be able to understand the business objectives and try to support them using the enterprise security architecture. There are a few frameworks that help security professionals to achieve this goal. 

  

The SABSA security framework is for businesses that are based on risk and the risks associated with it. This security framework particularly doesn't offer any specific controls or relies upon.

  

## [Git's database internals IV: distributed synchronization | The GitHub Blog](https://github.blog/2022-09-01-gits-database-internals-iv-distributed-synchronization/)

Git is a distributed database that uses fetch and push to synchronize selected parts of repositories. These commands require sharing just enough of the Git object data, and Git uses several mechanisms to efficiently compute a small set of objects to communicate without requiring a complete list of things on each side of the exchange.