# DevOps / SRE — Top Links Last Week

## Week 23 Issue #30

## [How Lowe’s meets customer demand with Google SRE practices](https://cloud.google.com/blog/products/devops-sre/how-lowes-leverages-google-sre-practices/)

Site Reliability Engineering (SRE) has been able to increase the number of releases they can support by adopting Google’s SRE framework and leveraging their partnership with Google Cloud. Lowe's has gone from one release every two weeks to 20+ releases daily. SREs are able to improve the reliability, performance, scalability and launch velocity of the services throughout all phases of the service lifecycle. To do so, we followed four key principles that allowed us to meet changing customer needs quickly and release fast and reliably.

## [Announcing HashiCorp Terraform 1.0 General Availability](https://www.hashicorp.com/blog/announcing-hashicorp-terraform-1-0-general-availability)

HashiCorp Terraform 1.0 is a major milestone for interoperability, ease of upgrades, and maintenance for your automation workflows. Terraform is already widely used by individuals and teams in companies large and small as the standard for multi-cloud provisioning and automation. This post takes a look at what’s new, and what the 1.0 designation means for Terraform users. The release is immediately available for download as well as for use in Hashi Corp Terraform Cloud.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Full cycle developers – Operate what you build (2018)](https://netflixtechblog.com/full-cycle-developers-at-netflix-a08c31f83249)

Netflix has grown to 125M global members enjoying 140M+ hours of viewing per day. Netflix has invested significantly in improving the development and operations story for its engineering teams. Edge Engineering is responsible for the first layer of AWS services that must be up for Netflix streaming to work to work. Having teams of specialists who each own a slice of the life cycle can create silos that slow down end-to-end progress. We hope that sharing our experiences inspires others to debate the alternatives and learn from our journey.

## [15 GitHub Repos That Every Developers Must Bookmark Right Now](https://viveknaskar.medium.com/15-github-repos-that-every-developers-must-bookmark-right-now-eee01db63977)

GitHub reports having over 40 million users and more than 190 million repositories making it the largest host of source code in the world. GitHub is a one-stop place where developers collaborate and contribute together that forms such a strong community and an enormous network among the developers and programmers. I have put together a list of GitHub repositories that would help you to learn and grow as a software developer. The list also contains topics about Deep Learning, DevOps tools, Debugging tools and many more which would be useful for any aspiring and experienced Python developers.

## [Prometheus, but Bigger](https://luizrojo.medium.com/prometheus-but-bigger-b678d8d6b29d)

A Kubernetes monitoring solution was created by CNCF's Thanos. Each cluster has its own set of Grafana + Query servers, its own store servers, and three receive servers (half of the cluster) Each cluster is isolated from the others, everything has to be monitored from "outside" All data is sent to a single server and then replicated to the other servers. Data ingestion is managed by a dedicated Prometheus POD running inside the clusters. The data is also sent to one of the receive servers managing the TSDB blocks.

## [Evolution of code deployment tools at Mixpanel](https://engineering.mixpanel.com/evolution-of-code-deployment-tools-at-mixpanel-210b99926cd4)

At Mixpanel, a large portion of Mixpanel’s infrastructure was running on Google Cloud Platform (GCP) At the time, Kubernetes (k8s) was emerging as the industry leader in container orchestration. Mixpanel moved off the cloud back in 2011 to dedicated hardware deployed on Softlayer. After a lot of soul-searching, we finally decided to move back to the cloud in 2016. We decided to run a POC with two of the most popular recommendations: Spinnaker and Argo.

## [Containers are tents](https://increment.com/containers/containers-vs-vms/)

Containers are useful when we think of them as a tool for solving a related, but different, set of problems. They are, in fact, exceptionally helpful—as long as you’re not trying to use them to mimic an entire operating system. The more binaries and files there are in a container image, especially ones that provide interfaces to the kernel, the more opportunities there are to claw through that tent wall and escape the container. Tents, after all, aren’t a particularly secure place to store your valuables.

## [Understanding DevOps in 2021](https://betterprogramming.pub/understanding-devops-in-2021-f3e7e496a257)

DevOps has evolved over the last decade into an entire industry encompassing agility and speed. CI/CD is Continuous Integration and Continuous Deployment. CI tests new changes quickly for problems and, assuming there are none, deploys ASAP to customers. CI and CD are processes born from the principles of Continuous Testing and DevOps. The entire process is collaborative, collaborative and automated. It's a lot harder to catch all the security flaws in an extensive application someone dumps on your desk. It's far easier, faster, and more robust to do it as you go along.

## [Multi-Cloud Setup of Kubernetes](https://faun.pub/multi-cloud-setup-of-kubernetes-add3cfa9221f)

Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications. It was originally designed by Google and is now maintained by the Cloud Native Computing Foundation. A multi-node cluster is a setup with various nodes among which one is known as the master node. The whole idea of Docker is for developers to easily develop applications, ship them into containers which can then be deployed anywhere. An Ansible Task Description: Create a Multi-Cloud Setup of K8S Cluster: Launch node in AWS (AWS)

## [SwampUP: DevOps Needs Guardrails, Not Gates, for Security](https://thenewstack.io/swampup-devops-needs-guardrails-not-gates-for-security/)

DevOps is not just about tools, but also about people and processes and governance. The way we add security into the DevOps process has been flawed, argued Alyssa Miller, S&P Global Ratings business information security officer. Static analysis should be done when code is committed, and the last step before the app moves to deployment is to do dynamic testing. The errors that these tests find should simply be added to the existing DevOps backlog, and handled in the next sprint, where they can even take top priority.

## [State of Managed Kubernetes 2021](https://medium.com/geekculture/state-of-managed-kubernetes-2021-43e8a4ca0207)

Amazon's EKS vs. AKS vs. GKE from a Developer’s Perspective (2021 Edition) Kubernetes turns seven on June 7th, with the stable release now at v1.21. The challenge of scaling Kubernetes, the complexity of managing the control plane, the API layer, and the database — that isn’t for the faint of heart.” — Deepak Singh, VP of Compute Services at AWS. “The challenge of. scaling Kubersnetes is the. challenge of managing. the control planes, the. API layer and the. database layer, the database.

## [One Way To Keep Your Website Monitoring Simple and Great](https://betterprogramming.pub/one-way-to-keep-your-website-monitoring-simple-and-great-4fea491bb5c)

User flows are the most sacred thing in our applications. User flow may never be impacted. Only the most important alerts should appear in our communication channel (e.g. the user isn’t able to log in anymore). A weekly report can help us monitor the state of the application. We can do this by combining API tests and UI tests. These tests can be managed by us or can be hosted on an online SAAS platform that has connections to our CI tools and communication channels.

## [Set Up Thanos With Multi-Tenancy To Power Up Your Prometheus](https://betterprogramming.pub/set-up-thanos-with-multi-tenancy-to-power-up-your-prometheus-70123e6ea555)

Prometheus is a well-known open source monitoring solution and the de facto standard for observability in Kubernetes environments. Design a high-availability monitoring solution based on Prometheus and Thanos with multi-tenancy enabled enabled. The solution is based on the open-source monitoring solution of Prometheus, Thanos, and Prometheus, which is now available on the market for $100,000. For more information on Prometheus, visit www.prometheus.com/promptusion.

## [Kubernetes + EKS + Blue/Green Deployment](https://medium.com/@jerome.decoster/kubernetes-eks-blue-green-deployment-99d611c596ad)

Using Terraform to create an EKS cluster, we can test Kubernetes Blue/Green Deployment on EKS. The Goal is to create a simple node server with a simple HTML page. Publish version 1.1.0.0 to 1.2.0 using the Red Parrot and Green Parrot deployment pattern. Publish the latest version of the EKS node to the ECR repository. Create an docker image and host it on ECR and host 3 different versions of the site.

## [Where is IBM’s hybrid cloud launchpad?](https://www.zdnet.com/article/where-is-ibms-hybrid-cloud-launchpad/)

In 2020s, the default choice for deploying IT systems – entrenched and new – would flip from on-premises to cloud. IBM was admittedly late to the cloud, with the big three public cloud providers having stolen the thunder. But now IBM has the opportunity to turn lemons into lemonade. IBM hopes it can become more like Red Hat, and as part of that transition, spun off of its GTS business last year to help get it there. IBM Cloud will play a strategic role for part of its portfolio.

## [Terraform 1.0 Reflects What HashiCorp Has Learned About Infrastructure-as-Code](https://thenewstack.io/terraform-1-0-reflects-what-hashicorp-has-learned-about-infrastructure-as-code/)

HashiCorp has released Terraform 1.0 as it seeks to improve its IaC platform for interoperability, ease of upgrades and maintenance for automation workflows. DevOps can still struggle on a number of fronts when relying on infrastructure as code. Terraform and Red Hat’s Ansible have emerged as leading options, according to data from a 2020 StackOverflow survey (see the charts above), with Terraform as a dominant choice for Kubernetes deployments. With Terraform Cloud and Enterprise, autonomous car startup Cruise demonstrated how it was able to reduce provisioning time by up to 75%.

## [An Explanation of AWS’ IAM Concept in Detail](https://aws.plainenglish.io/an-explanation-of-aws-iam-concept-in-detail-2f813985426e)

Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. IAM is universal (global) and does not apply to regions. It replicates data across multiple data centres around the world. Users can be given access to their own keys through IAM policy (not from the console) You can disable a user’s access key which prevents it from being used for API calls. You can use the same IAM user to manage instance in a different region.

## [Taildrop was kind of easy](https://tailscale.com/blog/2021-06-taildrop-was-easy/)

Taildrop was the main new feature we launched in Tailscale v1.8.8. It lets you transfer files between your own devices, over your point-to-point Tailscale+WireGuard mesh network, across various different OS platforms. It never stores your files in the cloud or sends them to us. It costs us, effectively, nothing to run, because it’s your bandwidth (mostly LAN bandwidth), not ours. We just bust some NATs and negotiate the session. We can give it away to everybody, for unlimited use, with no file size limits, as part of the Tailscale free plan.

## [Getting Started with Step Functions for Serverless Workflows](https://tpschmidt.com/getting-started-with-step-functions-for-serverless-workflows-8c030c2552fb)

Step functions by AWS is a service to seamlessly build an orchestrated flow of Lambda executions for different business cases. An example use-case is to send another message if the double opt-in step is not completed after a certain time. The state machine we want to create is pretty simple and only contains two states: wait & trigger notification. The first one will only delay the execution of the next step for a specific number of seconds. The second step will execute another Lambda function — which will send out a second customer notification if there’s still a need for it.

## [AWS Infrastructure Explained](https://aws.plainenglish.io/aws-infrastructure-explained-b0f4fb7b6829)

AWS CERTIFIED CLOUD PRACTITIONER PREPARATION # 2: AWS Certified Cloud Practitioner examination. In this article, we are discussing the Global Infrastructure of AWS such as Regions, Availability Zone, Local Zone, AWS Outpost, and AWS wavelength. An AWS Region is a physical cluster of data centres located in a specific geographic location. An Availability Zone is one or more data centres that contain the physical infrastructure that provides AWS services (eg data, storage, networking) There are very high-speed connections between Availability Zones within a Region.

## [Toward Vagrant 3.0](https://www.hashicorp.com/blog/toward-vagrant-3-0)

HashiCorp Vagrant started as a small project to make interacting with virtual machines for local development easy. Migrating to a Go code base will not only support developer environments of the past decade but also new development workflows, environments, and ecosystems. Vagrant 3.0 will introduce new methods for configuration but retain tooling for continued compatibility of Vagrantfiles. New client-server model will facilitate easy sharing of configuration and resources while also giving administrators power over Vagrant’s privileged actions. New architecture will allow you to run Vagrant on a remote host and secure actions on the machine.

## [How To ‘DevOps’ as a Software Developer](https://betterprogramming.pub/how-to-devops-as-a-software-developer-8b396b9c6268)

These are some central concepts of systems engineering that software developers should absolutely know. At the end of the day, they help you write better code. Know your software or code is only efficient if it can work in harmony with the system underneath. Know your operating system and its underlying disk I/O limitations. Be aware of the OS’s memory allocation. Know where your app runs, where your code does your infrastructure (or cloud) and where the infrastructure landscape (or VPCs) is set up.

## [KubeStack — A Must Use](https://shanikaperera11.medium.com/kubestack-a-must-use-117a32efd427)

KubeStack is an open-source Terraform framework for teams that want to automate infrastructure. It uses the respective cloud’s Terraform providers to manage K8s clusters which are EKS for Amazon, AKS for Azure, and GKE for Google. The developer can simulate the configuration changes you did in the specific environments for the cloud in your local machine. You can reduce the cost of interacting with the cloud provider to troubleshoot and fix your misconfigurations by using a technique called KinD (Kubernetes in Docker)

## [Making Elastic Beanstalk Deployment Production-Ready](https://aws.plainenglish.io/making-elastic-beanstalk-deployment-production-ready-b21a99319ea)

AWS Elastic Beanstalk (EB) provides all the knobs to make this easier. Getting all the settings right can be tricky and is not very intuitive. Make sure the app is highly available, fault-tolerant, and can scale itself. The app should show up as healthy on the EB console and be monitored by the service itself. For example, the app should be serving users even when deployment is going on. If you are starting up with a small app with a few users, one instance of EC2 might be sufficient for a long way.

## [You use more open source software than you think](https://github.com/readme/unseen-oss)

Tobias Koppers is the creator of webpack, an open source code bundling tool for JavaScript. Since 2014 he’s been responsible for maintaining an important component of the web version of Instagram. The near-invisibility of many open source projects creates a number of challenges for the open source ecosystem, ranging from funding the project and securing its code to ensuring compatibility between its components. Koppers says there’t always always be a major financial model for open source. For example, cURL is included in most Linux distributions and needs to be updated to support web standards.

## [A Guide to GitOps Compatible Production-like Kubernetes Cluster](https://betterprogramming.pub/a-guide-to-gitops-compatible-production-like-kubernetes-cluster-f87404391d8a)

A Guide to GitOps Compatible Production-like Kubernetes Cluster is written by Erik Mclean. In this article, we will be going through the Terraform and Ansible code used as well as the prerequisites. We will not be going in-depth about either Terraform or Ansible but will keep it simple and straight to the point. For windows users I recommend WSL with Ubuntu and WSL. For this article we will use Terraform to manage the configuration part of the cluster using Ansible.

## [5 Monitoring Characteristics SREs Must Embrace](https://thenewstack.io/5-monitoring-characteristics-sres-must-embrace/)

Site reliability engineer (SRE) functions are responsible for defining ways to measure availability and uptime, accelerate releases and reduce the costs of failures. Theo Schlossnagle: Traditional monitoring approaches are trying to solve problems that no longer exist and simply do not meet new monitoring expectations. SREs need a new, updated way to approach monitoring, he says. The true value lies in decoupling release schedules and maintenance, and allowing for independent higher-level decisions around security, resiliency and compliance.

## [AWS ECR: Probably the Cheapest Docker Registry](https://aws.plainenglish.io/aws-ecr-probably-the-cheapest-docker-registry-9ed4906612e4)

AWS Elastic Container Registry (ECR) is almost free of charge even for quite impressive infrastructures. The pricing model is this: $0.10 per GB stored per month, plus costs related to transferring the data IN and OUT from the AWS data center. The best use case for AWS ECR will be the situation when you already have your infrastructure hosted on the AWS, but even if not it’s something you should consider. We will do one IAM user with full access to the ECR and use it.

## [Pulumi: A True Infrastructure as Code Paradigm](https://betterprogramming.pub/pulumi-a-true-infrastructure-as-code-paradigm-ac07c530e219)

Pulumi is an IaC library, enabling you to manage your infrastructure in your favorite language. It is available across all common languages, such as Python, Go, Javascript, C#, Typescript, etc., and supports all major cloud providers, like AWS, Azure, and GCP. The code hardly needs any explanation. Combine this with the command pulumi up to bring up your infrastructure and pulumi destroy to decommission it. It's that simple. The library is free and easy to download.