# DevOps / SRE - Top Links Last Week

## Week 44 — Issue #51


## [Microsoft launches Azure Container Apps, a new serverless container service](https://techcrunch.com/2021/11/02/microsoft-launches-azure-container-apps-a-new-serverless-container-service/)

Microsoft announced the preview launch of a serverless container service at its Ignite conference. The new service is specifically built for microservices, with the ability to quickly scale based on HTTP traffic, events or long-running background jobs. The infrastructure itself sits on top of open-source projects like Microsoft’s own Dapr application runtime and its scaling technology is powered by Kubernetes Event-Driven Autoscaling (KEDA), a project that is supported by Microsoft, Red Hat and Codit.

## [The growing complexity of modern software systems](https://www.infoworld.com/article/3639050/complexity-is-killing-software-developers.html)

Cloud Native Computing Foundation maintains an interactive graphic of the nearly 1,000 unique services that make up the cloud-native ecosystem. The explosion of choice and the pace of development make it challenging for developers to keep up with the zeitgeist, with many developers getting caught in the headlights. Cloud-native era has ushered in the potential for more accidental complexity than ever before, setting a collision course between developers who want to leverage the full toolkit available to them, and their bosses, who want them to focus on delivering value to customers.

---


## [Containers vs. pods – taking a deeper look](https://iximiuz.com/en/posts/containers-vs-pods/)

Containers could have become a lightweight VM replacement. However, the most widely used form of containers, standardized by Docker/OCI, encourages you to have just one process service per container. Kubernetes makes bolder step and chooses a group of cohesive containers, called a Pod, as the smallest deployable unit. Every pod gets a unique IP and hostname and that within a pod, containers can talk to each other via localhost. But then you learn that containers in one pod can communicate via shared memory!

## [Production Grade Code in Cloud Era](https://nadundesilva.medium.com/production-grade-code-in-cloud-era-62d3d4d4d3ec)

Programming can be graceful, meaningful and beautiful in the hands of a proper programmer. We would not have full access to applications in production environments due to various SRE and security reasons. With all these considerations, writing better code is more important than ever. In this article, I thought of sharing my thoughts based on experience in writing code as well as reviewing code, in the industry working on multiple large scale cloud native applications. I hope this will help you get started in thinking like a pro.

## [HashiCorp’s IPO filing reveals a growing business, but at a slower pace](https://techcrunch.com/2021/11/05/hashicorps-ipo-filing-reveals-a-growing-business-but-at-a-slower-pace/)

Cloud infrastructure company HashiCorp filed to go public this week. The cloud infrastructure unicorn presents an interesting mix of open source and proprietary code. The company grew about 50% in its most recent quarter from a year earlier. It has reached nine-figure revenue scale, meaning that the unicorn worth some $5 billion or so back in 2020 is going to make a splash when it lists. For investors just now picking up on the monetization possibilities that open source software can unlock in-market, the IPO should be a klaxon.

## [What is a cloud architect? A vital role for success in the cloud](https://www.cio.com/article/3282794/what-is-a-cloud-architect-a-vital-role-for-success-in-the-cloud.html)

Cloud architects are IT specialists who have the skills and knowledge to navigate complex cloud environments, lead teams, develop and implement cloud strategies. Cloud-related jobs have increased by 42% from 2018 to 2021. Cloud architect jobs are typically straight forward and posted under the title cloud architect. The average salary for a cloud architect is $128,418 per year, with a reported salary range between $82,309 to $185,208 per year depending on experience, location, and skills. There are also a variety of certification and professional development programs.

## [Lessons Learned: A severe vulnerability in the OWASP ModSecurity Core Rule Set](https://portswigger.net/daily-swig/lessons-learned-how-a-severe-vulnerability-in-the-owasp-modsecurity-core-rule-set-sparked-much-needed-change)

OWASP ModSecurity Core Rule Set (CRS) was a 'bang on the ear' for the project's maintainers, who have outlined steps to improve its security. A complete rule set bypass (CVE-2021-35368) had been discovered in June 2021. The critical bug had been present in the software for at least four years. The vulnerability bypassed the security protections offered by the in-built CRS web application firewall (WAF), meaning that malicious request body payloads could be smuggled through without being inspected.

## [Kubernetes Persistent Volumes: Examples & Best Practices](https://loft.sh/blog/kubernetes-persistent-volumes-examples-and-best-practices/)

Kubernetes uses a highly abstract storage model for retaining data. PersistentVolume (PV) is part of network storage within a cluster provided by the administrator. To use this resource, it must be requested through persistent volume claims (PVC) A PVC volume is a request for storage, which is used to mount a PV volume into a Pod. The storage mode is Filesystem, the access mode is ReadWriteOnce, the storage class is specified as slow, and the NFS plug-in type is used.

## [Variable precedence in Terraform](https://blog.devgenius.io/variable-precedence-in-terraform-f32dd283dcb9)

Terraform variables help define server details without having to remember infrastructure-specific values. They are similarly handy for reusing shared parameters like public SSH keys that do not change between configurations. The first way to successfully create the AWS instance is to provide a value for the instance_type variable, preferably from the EC2 Instance Types page. The second way to do it is to pass the value inline to the terraform apply command. Like in bash, we can also pass in environmental variables as values for variables in Terraform.

## [System design fundamentals: What is the CAP theorem?](https://www.educative.io/blog/what-is-cap-theorem)

NoSQL databases are great for distributed networks. They allow for horizontal scaling, and they can quickly scale across multiple nodes. When deciding which No.SQL database to use, it’s important to keep the CAP theorem in mind. No.SQL databases can be classified based on the two CAP features they support. CA databases can’t deliver fault tolerance. AP databases enable availability and partition tolerance, but not consistency. Apache Cassandra allows for eventual consistency because users can resync their data right after a partition.

## [Replacing Docker Desktop with Multipass, to avoid Docker Desktop fees](https://techsparx.com/software-development/docker/docker-desktop/multipass.html)

Docker is still free, but parts of the Docker ecosystem requires a fee. Multipass is lightweight virtual machine platform with which we can easily set up and run Ubuntu instances. We can then install Docker, and we can even configure multiple Linux VM's, each with a Docker instance, so we can implement a multi-node cluster to experiment with Docker Swarm or Kubernetes. We need to return to the basics of installing a virtual machine running Linux for installing Docker Engine, then somehow work some magic.

## [How to Permanently Lose Cloud Data Instantly ](https://thenewstack.io/how-to-permanently-lose-cloud-data-instantly/)

The cloud, and especially software as a service (SaaS), has become the default for the way we work. This newfound freedom comes at a cost that’s inherent to most SaaS applications. Not understanding this risk, and how to mitigate it, means companies could easily lose all the critical data they are entrusting to online software solutions. The key question to ask: Is the value you are getting from this app worth the level of data access this app has?

## [Service Mesh Testing — Tools & Frameworks (Open Source)](https://itnext.io/service-mesh-testing-tools-frameworks-open-source-7904ee222298)

Service Mesh operates between OSI Layer 4 to Layer 7, while Kubernetes Container Network Interface (CNI) provides infrastructure for Layer 2 and Layer 3 networking. As one deploys applications using Service Mesh, we need to test, ensure and measure applications are not negatively impacted with a service mesh. There are quite a few open-source tool-sets that have risen up to this challenge of testing and measuring performance impact of Service Mesh. Tools and test suites play a crucial role in understanding the impact of environment applications are deployed in.

## [Leader election in Kubernetes using client-go](https://itnext.io/leader-election-in-kubernetes-using-client-go-a19cbe7a9a85)

In this post, we’ll discuss the idea behind leader election in highly available systems. The leader election process in Kubernetes is simple. It begins with the creation of a lock object, where the leader updates the current timestamp at regular intervals as a way of informing other replicas regarding its leadership. The pod which successfully acquires the lock gets to be the new leader. The other instances should remain inactive, but ready to take over if the leader instance fails. If the leader fails to update the lock within the given interval, it is assumed to have been crashed.

## [How to Dockerize an Existing Node.js](https://aws.plainenglish.io/dockerize-an-existing-nodejs-application-and-build-a-pipeline-for-the-automation-process-bfb03fe87c53)

The first thing we need to do is to look for an already existing Node.js project on Git (you can go ahead to build one if you can) For this article, I will be making use of a repository by Kriscfoster. The first step is to create a Dockerfile that will take in the instruction to dockerize your node application. The next thing is to build the Dockerfile and tag it to a name that we can use to access it later. Once the build is successful, you can then push your code on GitHub.

## [Getting Started with Terraform and AWS — reusable template repository from scratch](https://itnext.io/getting-started-with-terraform-and-aws-reusable-template-repository-from-scratch-67e92a50603)

Terraform state, modules, workspaces, variables, outputs — getting started with the features of Terraform can be daunting. This post is intended to help you get started with Terraform and AWS in a simple and quick way. It describes a template repository for provisioning AWS cloud infrastructure using Terraform. The state backend used in the template is a S3-bucket and defined in backend.tf: Manually set up a. S3 bucket in your AWS account with a globally unique name. The standard module structure is based on the official Terraform documentation.

## [5 Things to Know About Secure Cloud Native Development](https://thenewstack.io/5-things-to-know-about-secure-cloud-native-development/)

There are now 6.5 million cloud native developers around the world, 1.8 million more than in mid-2019. A majority uses open-source Kubernetes, which has become the de facto choice for container orchestration. A recent Unit 42 study showed that 96% of third-party container images deployed on cloud infrastructure contain known vulnerabilities. Enterprises should approach the task of picking a secure and stable base image very carefully: It’s critical to continually consider what content can developers rely on and for how long.

## [Getting started with IO attacks](https://www.gremlin.com/blog/getting-started-with-io-attacks/)

An IO attack continuously reads and/or writes data to a directory on a filesystem. This means it can be used with any storage solution that can be mounted to a filesystem, including HDDs, SSDs, and network attached storage (NAS) You can configure these parameters: root directory where the attack will be executed. Mode, Block Size, Block Count, and Block Count options are only visible by clicking on “Show Advanced Options” under Volume Percentage. Increasing these options increases the amount of data written or read by the attack, which in turn increases storage bandwidth. Depending on the type of storage device, you may need to significantly increase the magnitude of the attack to see a noticeable impact.

## [A Practical Guide to CQRS](https://itnext.io/a-practical-guide-to-cqrs-af4e2d797383)

CQRS is an architectural pattern that separates read and write operations. This allows the application to scale better and perform well under a heavy load. It is useful for solving the issue of impedance mismatch — misalignment of database model and domain model. For this, I will be using.NET Core stack, MSSQL database. Demo code is available.

## [Deploy Lambda Function using GitHub Action](https://aws.plainenglish.io/deploy-lambda-function-using-github-action-fdd160fc1966)

This article is about how you can create a workflow that will auto-deploy your serverless function/s with the help of Github actions. We need to follow a few steps to deploy the project using the serverless framework. For this article I am using the Serverless framework, you can choose native if you want but the steps would remain the same. The next step is to create an env variable on GitHub and copy-paste the value from your system into it. You can include or exclude based on your project's requirements.

## [Hybrid Cloud: A Binary Choice or a Hybrid Decision?](https://aws.plainenglish.io/hybrid-cloud-a-binary-choice-or-a-hybrid-decision-264f9dd2f0d1)

In the race “back” from the Public Cloud, making the right platform choice at this strategy “inflection point” could have a huge long term impact. IDC reports that 80% of organizations are now undertaking some level of cloud data repatriation activities. For many businesses the egress costs — the cost of moving the data back out again, can stack up. Amazon Outposts, Microsoft Azure Stack and Google Anthos are each designed to keep your data in their cloud, even if it’s physically residing in your own data centre.

## [How to Deploy a Flask API](https://towardsdatascience.com/how-to-deploy-a-flask-api-8d54dd8d8b8a)

How to Deploy a Flask API using Google’s cloud service, or Google Cloud Platform (GCP) We will be using the GCP App Engine service to deploy our Flask API. We can do this by simulating the App Engine environment using gunicorn to run a local Web Server Gateway Interface (WSGI) server. To use this we will need to add App Engine to our chosen project, and then install the. App Engine extension for Python. And we also know that we’re using (in my case) Python 3.8.8.

## [An Introduction to Load Balancers for Beginners](https://aws.plainenglish.io/system-design-basics-load-balancer-5aa1c6b0f88d)

Elastic Load Balancer (ELB) can scale load balancers and applications based on real-time traffic automatically. ELB automatically distributes incoming application traffic across multiple targets and virtual appliances in one or more Availability Zones. ElB uses system health checks to learn the status of application pool members (application servers) and routes traffic appropriately to available servers, manages fail-over to high availability targets, or automatically spin-up additional capacity. Elastic Load Balancers can be configured at three levels in a system.

## [Six Ways to Take Your Terraform to the Next Level](https://itnext.io/six-ways-to-take-your-terraform-to-the-next-level-e08b3e21b243?source=rss----5b301f10ddcd---4)

Use separate Git repositories for modules you intend to share across multiple teams or to open-source. Separating modules into their own repos gives more control over what version of the sub-modules are called, rather than having to cherry-pick commits into a tag. Use a sub folder in your project for modules if you don’t need to share code across teams, or if the code in question is very specific to your project. Avoid using modules for a single resource, unless you have a very good reason for doing so.

## [10 Ways to Improve Your Python Application’s Performance](https://betterprogramming.pub/10-ways-to-improve-your-python-applications-performance-78e697e8dc2a)

gProfiler is an open-source continuous profiling tool that is far superior to the profiling tools available in Python. It is plug-and-play, so it provides seamless production profiling and no code modification is required. It can track the statistics of a wide range of languages, including Python, Java, and Go. It runs in the background and monitors all the programs automatically, all the while using fewer CPU resources. It reduces the amount of cloud space you need to use and, consequently, the money you need for the cloud environment.

## [6 Concepts To Master When Dockerizing Python Applications](https://betterprogramming.pub/6-concepts-to-master-when-dockerizing-python-applications-e5f5a6a87845)

A while ago, I began experimenting with various methods in building minimalist container images for Python applications. As a result, I would like to share some of the tips and tricks that I have learned along the way. This article covers the following key concepts: Images are built incrementally starting from top to bottom. Images come with different folder structure and one of them is as follows: The app folder contains all the relevant files and folders for your project. For example, the app folder should be the working directory and runs the main file via app.main:app instead of code.

## [Prossimo: Making the Internet Memory Safe](https://thenewstack.io/prossimo-making-the-internet-memory-safe/)

The Internet Security Research Group (ISRG) is best known for its Let’s Encrypt certificate authority, but it has also turned its hand to fixing memory problems. ISRG sponsors, via Google, a Linux kernel developer to work full time on Rust in Linux in no small part to fix its built-in C code problems. Its other projects are a memory-safe TLS module for the Apache web server, a memory safe curl data transfer utility and Rustls, a safer OpenSSL alternative.