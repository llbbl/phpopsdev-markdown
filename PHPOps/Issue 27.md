# DevOps / SRE — Top Links Last Week

## Week 20 Issue #27

## [1Password for Linux](https://blog.1password.com/welcoming-linux-to-the-1password-family/)

1Password for Linux is officially here. It's written in Rust, a fast and secure open source systems programming language. The user interface (UI) is written in React with Neon bindings to the Rust backend. At launch, the following distros and app stores are supported:Debian, Ubuntu, CentOS, Red Hat Enterprise LinuxSnap store. The Linux kernel keyring can establish a fully encrypted connection between 1Password and 1Password in the browser. When you use your computer’s fingerprint sensor or a Yubikey to unlock your computer, you can now use those same methods to unlock 1Password.

## [HAProxy 2.4](https://www.haproxy.com/blog/announcing-haproxy-2-4)

HAProxy 2.4 adds support for HTTP/2 WebSockets, authorization and routing of MQTT and FIX (Financial Information Exchange) protocol messages, DNS resolution over TCP, server timeouts that you can change on the fly. It adds a built-in OpenTracing integration, new Prometheus metrics, and circuit breaking improvements. Register for our live webinar to learn more about this release. The HAProxy community provides code submissions covering new functionality and bug fixes, documentation improvements, quality assurance testing, continuous integration environments, bug reports, and more.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Using Kubernetes to rethink your system architecture and ease technical debt](https://stackoverflow.blog/2021/05/19/rethinking-system-architecture-can-kubernetes-help-to-solve-rewrite-anxiety/)

This is a story about trying to rethink complex systems: the challenges you face when you try to rebuild them, the burdens you face as they grow, and how inaction itself can cause it’s own problems. Pusher Channels, our pub/sub WebSocket service used for building scalable realtime data functionality, has been around for quite a while. It was clear that we needed to do something to reduce the maintenance burden; trying to maintain a highly reliable service for our customers meant we have spent the last few years battling the inevitable build up of tech debt and legacy infrastructure.

## [On Establishing a Cloud Security Program](https://www.marcolancini.it/2021/blog-cloud-security-roadmap/)

There is a lack of a single holistic view on how to integrate everything together. I grouped these main pillars by the five functions of the NIST Cybersecurity Framework: Identify, Protect, Detect, Respond, and Recover. These are the high-level goals that will be reflected within the roadmap and mapped to actual controls that can be implemented. Follow Secure Software Development Life Cycle (SSDLC) practices for IaC, and perform code reviews to validate any change to the infrastructure to confirm no reduction to the security controls are introduced.

## [Ansible 4.0](https://groups.google.com/g/ansible-devel/c/AeF2En1RGI8)

Ansible 4.0.0 is based on the ansible-core-2.11.x package which is a major update from the one used by Ansible 3. There may be backwards incompatibilities in the core playbook language. New minor releases will occur approximately every three weeks. New releases will contain bug fixes and new features but no backwards compatibility issues. The porting guide for collections which have opted-in is available here: [http://galaxy.ansible.com/](http://galaxy.ansible.com/).

## [Python for DevOps](https://thechief.io/c/editorial/python-for-devops/)

Python is an easy-to-learn language with an extensive and customizable library and one of the most popular and active user communities. Python enables DevOps professionals to build, test, deploy, visualize and monitor the DevOps lifecycle with improved, simple, but sophisticated custom utilities. Python makes it easy to write simple scripts that can automate significant tasks involved in DevOps processes. Python is a lightweight programming language that is almost ready to run on many environments setting up any running environment. Learning this language will give you an edge in landing a job as a DevOps engineer.

## [Building end-to-end machine-learning powered applications](https://towardsdatascience.com/building-end-to-end-machine-learning-powered-applications-673ea9e9c6d3)

BaseTen is an application builder that allows users to deploy machine learning models, serve APIs, and build front-end UI without having to worry about infrastructure, deployment, or learning React. BaseTen allows the deployment of scikit-learn, Tensorflow, and PyTorch models by calling baseten.deploy from the command-line tool (installed using pip) Users can write Python code in BaseTen and it will be wrapped in an API and served. The BaseTen client enables one-line model deployment.

## [Security Will Be Instrumental for the Success of GitOps](https://thenewstack.io/security-will-be-instrumental-for-the-success-of-gitops/)

The New Stack podcast is hosted by Alex Williams, founder and publisher of the New Stack. Om Moolchandani, Cindy Blake, Frank Kim, Katie Gamanji and Sanjeev Sharma talk about the security implications of GitOps. They discuss how GitOps can be a foundation for remediating vulnerabilities throughout the development and deployment process. It is especially useful for deploying applications in Kubernetes environments but it can also be “applied elsewhere,” said Om.

## [The 7 Most Popular DEV Posts from the Past Week](https://dev.to/devteam/the-7-most-popular-dev-posts-from-the-past-week-1mnn)

Every Tuesday we round up the previous week's top posts based on traffic, engagement, and a hint of editorial curation. The typical week starts on Monday and ends on Sunday, but don't worry, we take into account posts that are published later in the week. For educational purposes, @hotpotatoc made a clone of Twitter using VueJS as its frontend and Golang as its backend server. @theowlsden reviews the basics of Git-flow and how it can help you in this article.

## [Hybrid MLOps with HashiCorp Nomad](https://thenewstack.io/hybrid-mlops-with-hashicorp-nomad/)

HashiCorp’s Nomad is a flexible workload scheduler for machine learning operations (MLOps) It aims to automate the infrastructure support and CI/CD surrounding ML models end to end. Nomad's intrinsic flexibility makes it an asset for building ML pipelines in complex, hybrid environments. It's up to you to either point and click the cluster into existence or use a provisioning tool such as the Terraform configuration. With Nomad, we get the benefit of orchestrating a single pipeline across environments out of the box.

## [Filebase’s S3-Compatible API Aims to Ease Decentralized Storage](https://thenewstack.io/filebases-s3-compatible-api-aims-to-ease-decentralized-storage/)

Filebase is offering turnkey storage services using Amazon Web Services' S3-compatible API. The company says it is working with Storj Networks and the Sia Network, and will soon include the Filecoin Network and the Arweave Network by the end of 2021. The decentralized storage space was still rather nascent in the early years, but mainstream adoption still lags. Filebase looks to solve the problem by providing an API that eases onboarding, and abstracts the interactions with the underlying networks by offering SaaS models.

## [Deploying a NodeJS application in AWS EC2](https://aws.plainenglish.io/deploying-a-nodejs-application-in-aws-ec2-c1618b9b3874)

In this lesson we will be deploying a simple Node.js application on a AWS EC2 instance. We’ll also use Nginx as a reverse-proxy so sit back and stay tuned. The first step is launching an EC2 (Elastic Compute Cloud) and to do that we will need to login into AWS and under the Services tab -> Compute, click on EC2. In step 5 we will create a tag called Name with a value of “Test-EC2” This tag is important for identifying because it will be the instance name.

## [The architecture of Uber’s API gateway](https://eng.uber.com/architecture-api-gateway/)

API gateways are an integral part of microservices architecture in recent years. An API gateway provides a single point of entry for all our apps and provides an interface to access data, logic, or functionality from back-end microservices. Uber developed a feature-rich API gateway that is capable of complex operations on the incoming and outgoing data payload across multiple protocols. All interactions to the gateway systems happen through a UI, which walks the user through a step-by-step process for creating an API.

## [Build and Deploy Docker Images to AWS using EC2 Image Builder](https://aws.amazon.com/blogs/devops/build-and-deploy-docker-images-to-aws-using-ec2-image-builder/)

NFL, an AWS Professional Services partner, is collaborating with NFL’s Player Health and Safety team to build the Digital Athlete Program. NFL, in conjunction with Amazon Professional Services, delivered an EC2 Image Builder pipeline for automating the production of Docker images. This post demonstrates how to build a secure end-to-end workflow for building secure Docker images for use in an organization. We use AWS Image Builder to build and deploy Docker images to Amazon Elastic Container Service (Amazon ECS)

## [KubeCost: Monitor Kubernetes Costs with kubectl](https://thenewstack.io/kubecost-monitor-kubernetes-costs-with-kubectl/)

Michael Dresser is a full-stack engineer at Stackwatch, creator of Kubecost. Dresser was previously at Google where he contributed to the Kubernetes project. The cost plugin for kubectl is an answer to the challenges of modern enterprise infrastructure. It's possible to find inefficiencies and improve team and operational terms. The plugin can be installed in minutes and can be easily easily installed using Krew or the latest version of the Kubectl client. The plugin is available now on GitHub.

## [The reality of PHP WebSockets](https://itnext.io/the-reality-of-php-websockets-4c680bc2bc60)

PHP could handle some sort of concurrency through using Generators. Generators are functions that can iterate over an “unknown” and return values as these are received, by pausing the function execution and waiting for the next value. The stream_socket_server function in PHP allows to create a socket that works like a Generator, along stream_set_blocking set as non-blocking. The next step is to hook into the socket socket server, and then upgrading the incoming HTTP Request connections to WebSockets connections, keeping them open in memory.

## [Why I used Ansible to trigger Terraform](https://allanjohn909.medium.com/why-i-used-ansible-to-trigger-terraform-a7724196109a)

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently. Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. The next step was then setting each pipeline for each environment. The new deployment was done with Ansible now. The new Ansible task lists were like this:Pull down the IaC code repo, pull down the config repo and run terraform.

## [Make Debugging Easy with AWS X-Ray](https://aws.plainenglish.io/make-debugging-easy-with-aws-x-ray-7ed6727cc3c9)

AWS X-Ray is the most revolutionary service that AWS has offered. It gives Visual analysis of any application in the cloud. It understands dependencies in a micro-service architecture. It reviews request behavior, finds errors and exceptions. It’s compatible with AWS Lambda, Elastic Beanstalk, ECS, ELB, API Gateway, EC2 instances. In this way, there is a lot of amazing features of the service that helps developers to analyze and debug production applications. We will see when we are sending a request to the application as a client, which service fails.

## [A Tale of Moving 4000 GitHub repositories to GitHub Actions.](https://medium.com/dazn-tech/a-tale-of-moving-4000-github-repositories-to-github-actions-362ab96b71e6)

A Tale of Moving 4000 GitHub repositories to GitHub Actions. DAZN has around 400 engineers and 4000 private repositories on GitHub. The company is looking to use GitHub Actions to manage its Continuous Integration (CI) tooling. The main challenge, managing secrets & managing secrets, managing custom repositories, managing billing for so many with custom AWS, how we’re loading secrets into our pipelines to give necessary access to repositories to give access to our pipelines, and finally how we finally managed the migration.

## [Bitbucket vs Github vs Gitlab Detailed Comparison](https://jelvix.com/blog/bitbucket-vs-github-vs-gitlab)

The majority of popular version-control tools rely on Git – a system for distributed version control. The aim is to help teams track changes and improve collaboration among developers. Git is a system that stores code, tracks its changes in real-time, and synchronizes updates on local and Cloud repositories. GitHub, GitLab, and BitBucket may differ in their offer or specific features, but the key principles remain the same. The Git vs GitHub distinction is that GitHub is a service that uses Git – but other services can use Git as well.

## [Top 5 AWS Services To Launch Any Project](https://betterprogramming.pub/top-5-aws-services-to-launch-any-project-875457b6f309?source=rss----d0b105d10f0a---4)

Elastic Beanstalk, Simple Storage Service and Lambda are some of the most popular cloud services. These services are available to developers and businesses who want to launch prototypes and products faster. The Relational Database Service, or RDS, is a dedicated service on AWS. SNS enables the building of event-based pipelines for certain services such as publish/subscribe messaging. Lambda is being adopted already by many companies for different purposes, and it keeps getting more and more traction. The simple model “only pay for what you use” makes Lambda really attractive.

## [WebContainers: Run Node.js natively in the browser](https://blog.stackblitz.com/posts/introducing-webcontainers/)

StackBlitz is the first online online tool for web development. WebContainers allow you to create fullstack Node.js environments that boot in milliseconds and are immediately online & link shareable—in just one click. The environments are not running on remote servers, instead, each environment is completely contained within your web browser. All code execution happens inside the browser's security sandbox, not on remote VMs or local binaries. All computation happens instantly within the browser security sandbox and cannot break out to your local machine. This model also unlocks some key development & debugging benefits.

## [User Treasure: AWS Cognito](https://senayktt.medium.com/user-treasure-aws-cognito-d820d1b38cd5)

AWS Cognito provides user management (register, login, logout, forgot password, reset password, etc.) and access control to our web and mobile app users quickly and easily. It also supports sign-in with social identity providers, such as Google, Facebook, Apple, and Amazon, SAML 2.0, and OpenID Connect. Amazon Cognito User Pools provide a secure user directory that scales to hundreds of millions of users with JWT (JSON Web Token) mechanism.

## [What is Multi-cloud and why it is getting so much attention?](https://rakeshjain-devops.medium.com/what-is-multi-cloud-and-why-it-is-getting-so-much-attention-61f8c470e5f0)

Multi-Cloud is a strategy where we use two or more cloud computing services from any number of different cloud vendors in a single unified network architecture. This strategy comes up with a unique set of challenges which organizations have to face. Multi-cloud approach increases the risk with having complex application deployed over multiple cloud vendors. It opens up a larger attack surface. To counter this one should have a multi-layered security approach and a mix set of vendor experts. Migration takes time! There has to be proper talent who can plan and strategize the costing part of your project.