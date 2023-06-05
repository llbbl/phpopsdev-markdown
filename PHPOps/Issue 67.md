# DevOps / SRE - Top Links Last Week

## Week 8 - Issue #67

27 links


## [GitHub’s database of security advisories is now open source](https://github.blog/2022-02-22-github-advisory-database-now-open-to-community-contributions/)


The GitHub Advisory Database is the largest database of vulnerabilities in software dependencies globally. GitHub is publishing the entire contents of the Advisory Database to a new public repository to make it easier for the community to benefit from this data. Since the database's inception, the data has been licensed under a Creative Commons license, making it forever accessible and usable by the community. To contribute to a security advisory, you can suggest changes or provide more context on packages, affected versions, impacted ecosystems, and more.


## [Cron + Docker = The Easiest Job Scheduler You’ll Ever Create](https://levelup.gitconnected.com/cron-docker-the-easiest-job-scheduler-youll-ever-create-e1753eb5ea44)


I have created the most accessible job scheduler to schedule jobs in Linux. The solution has two components: Cron and Docker. Cron + Docker is the key to making the most accessible job scheduling tool you'll ever use. It can run anywhere I want it to, without messing with dependencies, and consistently run in the same way. A crontab command is a simple tool that takes jobs defined in a cron table file, a "configuration file that specifies shell commands to run periodically or on a schedule." 


## [Just Ansible It](https://blog.devgenius.io/just-ansible-it-55156e1cdec8)


Ansible is an open-source automating tool for provisioning, configuration management, application deployment, and infrastructure, also known as infrastructure as a code (IaC). Ansible was presented to solve the problem of redundant work on multiple servers, such as preparing the production virtual machines to java. It takes quite some time to prepare it on one machine, so what would happen if you needed that on 10+ virtual machines? Ansible came to solve that problem with its "playbook," which has tasks to do some action on the target servers.

  

## [How SREs Benefit From Feature Flags](https://devops.com/how-sres-benefit-from-feature-flags/)

  

Feature flags are a technique in software engineering that allows developers to turn specific features on or off at application runtime. Site reliability engineers (SREs) should work closely with developers to ensure that the applications they support include feature flags. SREs can leverage feature flags as a way of keeping the core SRE goal: Maximizing reliability. Feature flags minimize the risk associated with fast-moving software development pipelines. They allow teams to experiment with new application functionality while safeguarding against buggy feature implementations.

  

## [Automate and Configure Your RDS Database With Terraform](https://betterprogramming.pub/automate-and-configure-your-rds-database-with-terraform-898fd4b8990d)

  

Automate and Configure Your RDS Database With Terraform. I will assume that you already have your aws credentials configured and terraform installed. You're also familiar with configuring an S3 bucket as Terraform backend — so I will mainly focus on the module's sections and go thru the deployment part briefly at the end. The project will deploy a few items, such as One bastion host group located in a public subnet, that will allow you to ssh tunnel to your database + the associated security group.

  

  

## [We're choosing Rust, and not Go, C++, or Node.js](https://symless.com/blog/we-are-choosing-rust-and-heres-why)

  

Rust (not Go or `C++`) for the Synergy 3 background service (currently written in Node.js) because we believe it will give our customers a better experience. Java wasn't considered. The service provides auto-discovery (though mDNS), keeps the configuration synchronized between all computers, and provides other future features such as 1-click auto-update for all computers. Rust is a bit more green than other languages, and the Rust community is the most welcoming to trans people (thinking about our hiring strategy)

  

  

## [Docker, Containers & Confusions](https://faun.pub/docker-containers-confusions-2e2768530144)

  

There is a lot of confusion about the common questions around Docker, containers, Kubernetes, and related technologies. I have compiled all these understandings and tried to clarify as much as possible. I will start from the basics and try to explain the confusion about the questions mentioned above by going through the chronological order of evolution for different technologies and tools around containers. Kubernetes was released as an open-source container orchestration system for automating deployment, scaling, and managing containerized applications.

  

  

## [An Introduction to Kubernetes (aka K8s) and the Main Kubernetes Components for Beginners](https://aws.plainenglish.io/what-is-kubernetes-k8s-and-main-kubernetes-components-1-50919e5fd066)

  

Kubernetes Components are Node, Pod, Service, Ingress, ConfigMap, Secret, Volumes, Deployment, StatefulSet, and Stateful Set. Each Pod has an internal IP address to communicate with each other. For example, one Pod can have an application, and another can have a database. The Pod is an abstraction over a container and provides a running environment on top of the container. We want our application to be accessible from a browser, and for this, we need to create an external service.

  

  

## [Harness brings GitOps to its software delivery platform](https://techcrunch.com/2022/02/24/harness-brings-gitops-to-its-software-delivery-platform/)

  

Harness's ML-enhanced software delivery platform is getting on the GitOps train. The company is building its GitOps platform on ArgoCD, a declarative GitOps tool for Kubernetes. Harness counts some of the world's largest retailers and banks among its customers. It is now offering a SaaS-style GitOps service that ads enterprise capabilities on the platform. It's enterprise-grade GitOps. Bansal said that people love GitOps, but it's been hard for them to use it.

  

  

## [Terraform — Provision Amazon EKS Cluster using Terraform](https://medium.com/devops-mojo/terraform-provision-amazon-eks-cluster-using-terraform-deploy-create-aws-eks-kubernetes-cluster-tf-4134ab22c594?source=rss------kubernetes-5)

  

Terraform is an Infrastructure as Code tool that lets you define cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. The purpose of this article is to create Amazon EKS Cluster using Terraform. You can interact with the AWS resources, such as VPC, EKS, S3, EC2, and many others. Terraform uses the Terraform backend to specify the location of the backend Terraform state file on S3 and the DynamoDB table used for the state file locking.

  

  

  

## [Devtron: Open-Source Software Delivery Workflow for K8s](https://blog.devgenius.io/devtron-open-source-software-delivery-workflow-for-k8s-23bd136efe06)

  

Devtron is an open-source software delivery tool designed for Kubernetes workloads to simplify the setup. It pulls together several open source components (e.g., ArgoCD, Clair, external secrets, Minio) to provide a managed GitOps experience. It integrates with all the popular Git providers and can build Docker images and deploy Helm charts. The complete list of configuration settings is listed on the documentation website, along with instructions to modify per AWS/Azure settings.

  

  

## [4 Reasons Why Your Company Should Have More Than One AWS Account](https://aws.plainenglish.io/4-reasons-why-your-company-should-have-more-than-one-aws-account-74c0110f5672)

  

Most companies start their journey on Amazon Web Services with a single account. Having one account for every client allows for a clean separation of costs between them. Data transfer costs are a significant cost driver in many large-scale applications. The more accurate you can pin down the costs per client, the better your pricing will be. In addition, the multi-account architecture allows you to split out the parts that need compliance. Using existing services like AWS Control Tower guardrails makes this setup even safer.

  

  

## [Kubernetes for dummies: Deployment auto-scaling](https://itnext.io/kubernetes-for-dummies-deployment-auto-scaling-28ad0f9da1df)

  

In this post, we reviewed how to implement auto-scaling with Kubernetes. In the next post, we will create a GCP cluster with auto-healing. The HPA controller will query the resources every 15s (default) and adjust based on the thresholds vs. actual consumption. In the next post of the series, we can play with kubectl apply to create more resilient clusters. 

  

  

## [Stupid Simple Service Mesh in Kubernetes](https://www.suse.com/c/rancher_blog/stupid-simple-service-mesh-in-kubernetes/?fbclid=IwAR0yd4iJOggarmSVvwaTJTr390UDueYje_eRLT9Jk1XMJur1JamEyIHhK6I)

  

We use Service Mesh to set up a Service Mesh in Kubernetes using Istio. This tutorial explains the importance of using Service Mesh when working with microservices-based applications. Next, we will use the same services but configure our Service Mesh. Service meshes using sidecars, which it automatically injects into your pods. The sidecars will handle all the cross-cutting concerns, such as authentication, authorization, retry mechanisms, and rate-limiting. Finally, we'll build a sample application to explain the basic functionalities and structure of the service mesh.

  

  

  

## [GitOpsify Cloud Infrastructure with Crossplane and Flux](https://itnext.io/gitopsify-cloud-infrastructure-with-crossplane-and-flux-d605d3043452)

  

We will learn how to use Flux and Crossplane to manage Kubernetes cloud resources. We will use these tools to help Development Teams get up to speed using our Cloud Infrastructure. Flux exposes several components in the form of Kubernetes CRDs and controllers that assist with expressing a workflow with the GitOps model. The tools we will use are Flux as a GitOps engine. You could achieve the same with ArgoCD or Rancher Fleet. In a real-world scenario, we would manage Crossplane also using Flux, but for demo purposes, we are focusing on the application level.

  

  

  

## [How to configure Security Headers in Nginx](https://faun.pub/how-to-configure-security-headers-in-nginx-aac883201ff2?source=rss----10d1a7495d39---4)

  

In my previous blog, we talked about How to configure Nginx as a load balancer; today, we will talk about six Nginx Header used to add security layers. The Nginx header includes HTTP Strict Transport Security (HSTS) Content Security Policy (CSP), XSS-Protection (XSS) X-Frame-Options (X-Frame), and Access-Control-Allow-Origin (ACES). You should add the header to the server block.

  

  

## [Improve the Performance of PHPunit](https://betterprogramming.pub/improve-phpunit-performance-by-parallelization-using-liuggio-fastest-ff0abc111078)

  

There are multiple ways how to parallelize PHPUnit tests using Liuggio-fastest. Fastest runs a PHPUnit command per file and then parses the result. Paratest can give you a single test result with code coverage. However, it can be problematic with more complex test setups that wrap the PHPUnit executable. Using Symfony's PHPUnit-bridge or numut/testing-framework, Fastest can be helpful if you need different config files for other test files.

  

  

## [What’s the Purpose of Code Reviews?](https://betterprogramming.pub/the-purpose-of-code-review-c9942ee551e2)

  

The primary purpose of code review is to ensure that the code health of the codebase improves over time. An empty codebase would be perfectly healthy, but the primary goal of engineering teams would be building or maintaining products by building new features or resolving existing bugs which is achieved by making changes to the code. Although reviewers have ownership and responsibility for reviewing the code, they want to ensure it stays consistent and maintainable. A uniform code is easier to understand and thus more maintainable.

  

## [Avoiding the Top 10 NGINX Configuration Mistakes](https://www.nginx.com/blog/avoiding-top-10-nginx-configuration-mistakes/)

  

NGINX engineers often see the same configuration mistakes we've seen over and over in other users' configurations. This blog looks at 10 of the most common errors, explaining what's wrong and how to fix it. For example, the ````worker_connections```` directive sets the maximum number of simultaneous connections a worker process can have open (the default is 512). In modern UNIX distributions, the default limit is 1024. There is also a system‑wide limit on the number of file descriptors per process.

  

  

## [5 Tips to Speed Up Your Node.js Performance](https://medium.com/@mertcanarguc/5-tips-to-speed-up-your-node-js-performance-1166451308b4)

  

Node.js is an event-driven I/O server-side JavaScript environment and single-threaded event loop based on the V8 Engine. This article will discuss five ways to make Node.JS faster and optimal work. Redis is a more complex version of Memcached. Redis always served and modified data in the server's main memory. It also reduces the time to open web pages and makes your site faster. Using Redis, we can store cache using SET and GET. Besides that, Redis also can work with complex data types.

  

  

## [How to secure anything](https://github.com/veeral-patel/how-to-secure-anything)

  

In this repo, I aim to document a process for securing anything, whether it's a medieval castle, an art museum, or a computer network. Security engineering isn't about adding a bunch of controls to something. It's about coming up with security properties you'd like a system to have, choosing mechanisms that enforce these properties, and assuring yourself that your security properties hold. The process I like for securing things: We follow as many general best practices as possible. We write down our security policies or high-level security goals and develop a security model or spec we follow to satisfy our policies. We can then turn our policy into a more detailed specification.

  

## [Getting Started With Kubernetes Ingress Controllers](https://blog.getambassador.io/getting-started-with-kubernetes-ingress-controllers-f3b669d19b31)

  

Kubernetes is an open-source container orchestration platform that automates container deployment, management, scaling, and networking. Pods are the smallest deployable units of computing that you can create and manage. In practice, situations, where you have to create or delete a pod directly, are infrequent. Instead, you tell a deployment the state you want, and the deployment object will maintain that state. Service is an abstraction that defines a logical set of Pods and a policy to access them.

  

  

## [The internet was designed with a narrow waist](https://www.oilshell.org/blog/2022/02/diagrams.html)

  

The Narrow Waist concept, interface, or protocol solves an interoperability problem. Byte streams and text are essential "narrow waists" in software, particularly in #distributed-systems. This is a big deal in practice, but it doesn't have to be this way. In the next few posts, I'll review some Unix fallacies, i.e., local complaints which are ignorant of the large-scale architecture. I think we're still writing distributed systems the "wrong" way.

  

  

  

## [The Pros and Cons of Node.js Web App Development: A Detailed Look](https://javascript.plainenglish.io/the-pros-and-cons-of-node-js-web-app-development-a-detailed-look-c91a22f013c)

  

Node.js is a popular tool in web development, with 49.9% of developers across the globe have used it. It offers many advantages over traditional web application frameworks like Ruby on Rails or ASP.NET. However, while it boasts excellent performance and scalability, it also comes with some serious downsides that you should consider before jumping into development. In this blog post, we will take a detailed look at the pros and cons of Node.JS web app development so that you can reach a definite conclusion on whether to choose.

  

  

## [The Composable Enterprise: A Guide](https://blog.bitsrc.io/the-composable-enterprise-a-guide-609443ae1282)

  

Gartner predicts that by 2023, 30% of new applications will be "packaged" as new business capabilities. As a result, the modern enterprise must move away from monoliths. We will review the fundamentals of the transformation of enterprise composability. The guide is a guide to how the modern enterprise can become composable.

  

  

## [Kubernetes — Debugging NetworkPolicy (Part 1)](https://faun.pub/debugging-networkpolicy-part-1-249921cdba37)

  

There's even a section in the documentation devoted to what you can't do with network policies, and some of the items in that section seem to be a bit mind-boggling. For example, there is no log of network security events (for example, blocked or accepted connections). There are also significant features not listed in the document above that you might incorrectly be hoping were available. For instance, if your cluster does not have a suitable network plugin, NetworkPolicy resources will have no effect.

  

  

## [Using APIs with Low-Code Tools: 9 Best Practices](https://thenewstack.io/using-apis-with-low-code-tools-9-best-practices/)

  

Low-code and no-code tools are gaining rapid adoption in enterprises. They allow users to accomplish technical work without coding skills without needing coding skills. But how do you ensure the tools your organization chooses integrate well with the APIs you need to be productive? First, take an inventory of your current APIs — and their users — and who's using them. When low-code software connects to your APIs and critical infrastructure, security and data problems can also be an issue. For example, Germany has laws around health and finance that may be some concerns.