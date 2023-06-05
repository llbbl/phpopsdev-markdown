# DevOps / SRE - Top Links Last Week

## Week 6 - Issue #65

  

  

## [Back-end languages are coming to the front-end](https://github.com/readme/featured/server-side-languages-for-front-end)

Phoenix is a framework for the programming language Elixir and a feature called LiveView. Developers can create browser-based interfaces for real-time applications like chat rooms or Twitter status updates with LiveView. The only JavaScript required is a small amount of code that opens a WebSockets connection that handles sending input from the browser and receiving refreshed HTML/CSS from the server. Phoenix isn't the first platform to offer a way for backend developers to create front-end interfaces. Microsoft, meanwhile, released a new feature called Blazor Server that modernizes the old WebForms idea.

  

## [How To Manage Dotfiles With Chezmoi](https://betterprogramming.pub/how-to-manage-dotfiles-with-chezmoi-53cadb36b226)

How To Manage Dotfiles With Chezmoi is a step-by-step guide on managing your dotfiles. The dotfiles are config files in Unix-like systems that start with a dot, e.g., .bashrc,.zshrc,.vimrc,.gitconfig, and .gitconfig. By default, dotfiles are hidden, typically used to customize your system. Having your dotfile up on the cloud makes it incredibly easy for you to set up any new environment, like in the case of getting a new laptop.

  

## [Deploy Microk8s and the Kubernetes Dashboard for K8s Development](https://thenewstack.io/deploy-microk8s-and-the-kubernetes-dashboard-for-k8s-development/)

Microk8s is a Cloud Native Computing Foundation-certified upstream Kubernetes platform that you can run from a workstation. It's easy to get up and running, so you won't have to waste precious time deploying multiple servers. However, because the Dashboard is only accessible from within the cluster (at least not without some severe tweaking), your instance of Ubuntu must have a desktop GUI. Therefore, we'll be demonstrating on Ubuntu Desktop 20.04 with the latest version of the Ubuntu Desktop.

  

## [Sustainability with Rust](https://aws.amazon.com/blogs/opensource/sustainability-with-rust/)

Rust is a programming language implemented as a set of open-source projects. It combines the performance and resource efficiency of systems programming languages like C with the memory safety of languages like Java. In 2019, AWS was proud to become a sponsor of the Rust project. AWS is investing in the sustainability of Rust, a language we believe should be used to build sustainable and secure solutions. Data centers consume about 200 terawatt-hours per year. That's roughly 1% of all energy consumed on our planet.

  

## [A Gentle Introduction to Data Lakehouse](https://towardsdatascience.com/a-gentle-introduction-to-data-lakehouse-fc0f131f90ff)

Data Lakehouse is a new data architecture mentioned a lot in the past few years. It has been proposed to solve the pain points that old and well-established data architectures, Data Warehouse and Data Lake, are facing. The Lake House architecture consists of 5 layers: Data lakehouse architecture. Lake Lakehouse aims to connect the Data Lake with all data services such as DBs, user devices, IoT devices, and application logs. In addition, Lakehouse will provide durable, reliable, accessible, and scalable storage for a vast amount of data.

  

## [Top 10 ways machine learning may help DevOps](https://about.gitlab.com/blog/2022/02/14/top-10-ways-machine-learning-may-help-devops/)

Machine learning can enhance the innate powers of your DevOps program. GitLab's 2021 Global DevSecOps Survey: Around a third said that understanding AI or ML is the most crucial skill for future careers. ML tools can also help ensure your governance rules are followed and create a detailed audit trail. In addition, the technology can help find issues like resource leaks, wasted CPU cycles, and other problems, so you can optimize your code before it hits production, GitLab's ModelOps says.

  

  

—

  

  

## [Continuous Deploys With Bazel + Github Actions](https://levelup.gitconnected.com/continuous-deploys-with-bazel-github-actions-c508676678e8)

Bazel is a build and test framework that explicitly graphs out your dependencies. Using these pre-built rules (which we install to our Bazel WORKSPACE), we can configure BUILD.bazel files to do things like pulling a container from Docker Hub (or from AWS ECS, or wherever). We can push it to a registry like the Docker Hub registry, run tests, and run simple shell commands in your container that check for expected output. The genius of Bazel isn't the fact that you can orchestrate all these build/test steps, but you can only test+build things that have changed.

  

  

## [How to Share Data Between Docker Containers](https://thenewstack.io/how-to-share-data-between-docker-containers/)

Docker is a way of sharing data between containers within the realm of Docker. There will be times when you need to have a centralized volume of data that more than one container can share. The volume is created in the /var/lib/docker/volumes directory. 

  

## [4 Must-know DevOps principles](https://about.gitlab.com/blog/2022/02/11/4-must-know-devops-principles/)

DevOps includes a lot of the principles of Agile software development, but with a particular emphasis on breaking down development and operations silos. At their core, each has the following four must-know principles in place: Automation of the software development lifecycle. Collaboration and communication. Continuous improvement and minimization of waste. Continuous integration. Hyperfocus on user needs with short feedback loops. Continuous deployment helps automate releases. DevOps can adapt to an organization's unique needs and environment.

  

## [VMware Finds Linux Malware on the Rise](https://thenewstack.io/vmware-finds-linux-malware-on-the-rise/)

Linux is mainly secure, but it has security problems like any other operating system. You're still in danger if you don't install Linux correctly on your servers or clouds. Cyber crooks know they can make more bucks from targeting clouds wholesale than going after Windows PCs. There are currently seven significant ransomware families going after Linux. Many of these specialize in going after standard cloud configurations. To put malware in place, RATs are growing ever more popular. To evade detection, it hijacks the library loading mechanism to conceal specific directories in the /proc file system, thus hiding the crypto mining processes.

  

## [Migrating from Netlify to Cloudflare Workers Sites for 2x Performance (2020)](https://brianli.com/migrating-from-netlify-to-cloudflare-workers-sites-for-2x-performance/)

Cloudflare Workers Sites is a serverless platform that lets you run JavaScript code directly on a global network of data centers. Workers allow you to build low-latency websites, apps, and APIs because user requests are automatically routed to the nearest data center. This should be more than enough for 99% of static sites out there. When you access a static site, you point your browser to a unique URL, and the server returns a pre-generated static HTML file. Using Workers-KV is a key-value data store optimized for high read volume.

  

## [Low Latency Performance With AWS Local Zones](https://betterprogramming.pub/low-latency-performance-with-aws-local-zones-e8b805aa7529)

AWS now provides specific Availability Zones in significant cities. AWS Local Zones are newly minted edge locations AWS delivers in different metropolitan areas. Using these zones, you can achieve lower latency and more granular control over where you deploy. The best part is that each zone is explicitly labeled according to its city. There are still some specific instances that aren't allowed in some zones. According to Amazon, you can expect single-digits local ping response times.

  

## [Serverless on AWS Lambda With Micronaut + Kotlin + Graal VM](https://betterprogramming.pub/serverless-on-aws-lambda-with-micronaut-kotlin-7aac485f066e)

Caribou is a SaaS developer tool that can be installed on your GitHub account as a GitHub application and provide insights about how you are progressing on removing technical debt from your codebase. Caribou then runs an analysis after every pull request is merged. It provides real-time data about how the migration goes, the estimated finish date, who is contributing to it, and more. The main technical components needed for Caribou are A Web application to enable users to define their migrations and see all migration metrics around the code changes that they are introducing. The backend is written in Kotlin, built with a serverless architecture on AWS Lambda, using the Micronaut framework.

  

## [A Hairy PostgreSQL Incident](https://ardentperf.com/2022/02/10/a-hairy-postgresql-incident/)

It was 5:17 pm today. Just as I was wrapping up work for the day, my manager pinged me with the following chat: Hi Jeremy - we have a \< another team\> ticket - escalated to \<leader\> and \<principal\> Are you available this evening if needed for diagnostics? No obligation; just checking in to see what my availability is. Quickly thinking it over – I didn't have any plans tonight, nothing in particular on my schedule. Why not? If I can help, someone else on the team won't have to, and I don't have anything better tonight.

  

## [Multicloud Strategy: How to Get Started?](https://thenewstack.io/multicloud-strategy-how-to-get-started/)

According to HashiCorp, the state of cloud report, over 76% are already in multi-cloud today, which will be 86% in two years. This level of adoption creates enormous opportunities but with a catch: You can only enjoy the benefits of multi-cloud when you have a solid strategy. A cloud-agnostic process allows you to leverage the strengths of each provider. It also allows you to migrate these services from one provider to another according to varying costs, a point that we will cover in-depth in another section.

  

## [What Is a DevOps Framework and How Do You Establish One?](https://www.cloudbees.com/blog/what-is-a-devops-framework-and-how-do-you-establish-one)

DevOps is a culture, a philosophy, and a set of practices designed to enable rapid, efficient, and continuous software (application) development and deployment pipelines. DevOps evolved over the years (passing from the waterfall model to the Agile development model) to solve these major problems. The traditional monolithic architecture allows dependencies to build up between the application and the underlying OS used by the developers. When the operations team receives the application, each team member can have a different underlying environment/OS. This may prevent the application from running.

  

## [Build a seamless GitOps pipeline with Flux](https://www.weave.works/blog/gitops-pipeline)

GitOps is a set of principles for you to implement continuous deployment for cloud-native applications using Git as a single source of truth. With GitOps, you treat everything, including infrastructure, as source code and store it in Git. In addition, Online Git hosting platforms are vital to GitOps as they enable you to keep your code and make it easy for teams to collaborate around these cloud-hosted repositories. The list is not meant to be exhaustive but is a good indicator of today's leading GitOps tools.

  

  

  

## [Data pipeline asset management with Dataflow](https://netflixtechblog.com/data-pipeline-asset-management-with-dataflow-86525b3e21ca)

The answers to these questions are something we would like to address in this article and propose a clean solution to this problem. First, let's define some requirements that we are interested in delivering to Netflix. We also don't want to negatively affect the properties of an asset running along with every workflow instance, so if there are any issues, we can quickly identify them. Finally, we want all the workflows bundled in a durable, isolated, and consistent manner.

  

## [SSH into private machines from anywhere using Cloudflare Tunnel](https://orth.uk/ssh-over-cloudflare)

This guide uses Cloudflare Tunnel, a free-tier service. It will filter traffic to your machines through the network, including authenticating you. Because of this, your devices won't directly be exposed to threat actors and "1337 haxors". Furthermore, it is free and requires no future maintenance. By the end of this post, you'll be able to run: ssh $machine_name from anywhere in the internet-connected planet, using SSH keys. Again, it is a free service that requires no maintenance.

  

## [How to deploy a Dockerfile through a single node Kubernetes Cluster](https://blog.devgenius.io/how-to-deploy-a-dockerfile-through-a-single-node-kubernetes-cluster-7a87d01a927c)

Kubernetes is an open-source container orchestration tool developed by Google. We use MiniKube because it allows you to run a single-node Kubernetes cluster on your local computer. First, we create a Dockerfile and deploy it through a single node. The Dockerfile is the platform used to containerize your software. Next, we need to create, expose, and validate a deployment: Expose it, push it to Docker Hub, use Minikube to access the image.

  

## [Weaveworks Adds Policy as Code to Secure Kubernetes Apps](https://thenewstack.io/weaveworks-adds-policy-as-code-to-secure-kubernetes-apps/)

Weaveworks acquired Magalix, specializing in building tools for developers and security teams to codify security and compliance in their software development lifecycle. In addition, the company added policy as code through its acquisition of Seattle-based Magalix. Weaveworks CEO Alexis Richardson: "We believe that GitOps is the right way to solve customers, cloud-native application operations problems are going forward." The company believes GitOps will be a natural workflow for policy between developers and operators.

  

## [Ansible Inventory: A Guide to Creating and Using One](https://www.cloudbees.com/blog/ansible-inventory-a-guide-to-creating-and-using-one)

Ansible is an agentless system automation tool. You can use it to manage system configuration, perform maintenance tasks, and deploy software on managed nodes from a central control node. Ansible uses an inventory file to identify control nodes and organizes them into groups. The default location for your Ansible inventory is /etc/ansible/hosts, but, as you'll see below, you can override that location on the command line. The only software you need on the managed nodes is OpenSSH, and there are some workarounds for that.

  

## [Django + Celery in Kubernetes for Scheduling Tasks](https://medium.com/@bbhuiyan1/django-celery-in-kubernetes-for-scheduling-tasks-12718ef38bce)

Django is a popular web framework for Python; most of us know that Celery is an open-source distributed task queuing system. Combining these two, we can develop various solutions for various problems like scheduled notification, email sending, background processes, etc. Kubernetes is a container orchestration system that automates deployment, scaling, and management. We need to create a Dockerfile in the root directory of the Django project to run our application's DeploymentAML.

  

## [Deploy ArgoCD on AWS](https://www.modulo2.nl/blog/argocd-on-aws-with-multiple-clusters)

This tutorial covers how to handle the setup of ArgoCD in a multicluster AWS environment. It took me quite some time figuring out how to get this to work. I've tested all the commands I use on OSX; they will probably also work on Linux. If you use this on Windows, you will have to rework some templating commands. The configuration will also work with cross-account and multicluster setups by setting the trust relations between IAM roles.

  

## [My thirty years of dodging repetitive work with automation tools](https://www.tines.com/blog/my-thirty-years-of-dodging-repetitive-work-with-automation-tools)

In 2007 Yahoo announced Pipes - a web-based tool to aggregate web feeds, web pages, and other services. But it made me realize that coding just wasn't necessary for a lot of scenarios involving data, events, and APIs. For example, Google App Inventor, Scratch, Blockly, etc., all share a similar model, "relatively" easy to understand. But, it's overkill for many situations, and I have always kept my eyes open for alternatives.

  

## [Achieving Multi-Tenancy with Consul Administrative Partitions](https://www.hashicorp.com/blog/achieving-multi-tenancy-with-consul-administrative-partitions)

HashiCorp Consul's latest enterprise feature is called Administrative Partitions. It addresses customer resource inefficiencies when multiple dedicated service meshes are provisioned for different teams rather than sharing a single set of service mesh control plane resources. This leads to additional management requirements, lack of consistent governance, increased costs, and overall waste of resources. Admin Partitions provide improved multi-tenancy for teams to develop, test, and run their production services within a single Consul datacenter deployment.

  

## [How to Build and Deploy a FastAPI Task Manager App on Vercel](https://betterprogramming.pub/how-to-build-and-deploy-a-fastapi-task-manager-app-on-vercel-c3aa82b8365e?source=rss----d0b105d10f0a---4)

How to Build and Deploy a FastAPI Task Manager App on Vercel by creating a simple task manager application. FastAPI is a high-performing Python web framework for creating APIs with standard Python-type hints. This tutorial will learn how to build and deploy a Postgres FastAPI application on the cloud hosting platform Vercel. We'll also install Fastapi, Uvicorn, Sqlalchemy, and psycopg2-binary with the command below: virtualenv.

  

## [Simplest basic K8s tutorial to mount a local host directory into a pod volume example with Rancher…](https://jyeee.medium.com/simplest-basic-k8s-tutorial-to-mount-local-host-directory-into-a-pod-volume-example-with-rancher-18b4f1d75cd9)

Here is a straightforward basic K8s tutorial on mounting a local host directory into a pod volume example with Rancher Desktop. Use a volume hostPath and the provided rancher.io/local-path storage class to get going fast! A GitLab runner or Argo CI should do the rest of the deployment in production. You don't need to read the article, but it has a minimal deployment, service, and 'ingress.yaml' file as a refresher. 

  

## [Getting started with Celery and Python](http://blog.adnansiddiqi.me/getting-started-with-celery-and-python/)

In this post, I will talk about Celery, what it is, and how it is used. Celery is good for asynchronous or long-running tasks that do not require real-time interaction. However, developers can also use it to run scheduled tasks. A task is a piece of code that carries out a particular operation. Use cases include sending emails, uploading images, resizing images, and watermarking products. The basic architecture is given below: Producer, Broker, Backend, broker, Redis, and RabbitMQ.

  

## [Increase Kubernetes Network Security with Cilium](https://itnext.io/increase-kubernetes-network-security-with-cilium-ba6af15c8f5f)

  

Cilium is open-source software for providing, securing, and observing network connectivity between container workloads. Kubernetes Network Policies define network traffic rules for pods running in a cluster. This article will show how to, using Cilum, tackle the authorization concern and move to push it to the underlying platform from the application code. CILium is fueled by the revolutionary Kernel technology eBPF, which originates in the Linux kernel that can run sandboxed programs in an operating system kernel.

  

## [How I “scaled” my SaaS database and broke my app.](https://blog.devgenius.io/how-i-scaled-my-saas-database-and-broke-my-app-2ad2412ee4a3?source=rss----4e2c1156667e---4)

Sinosend is a multi-cloud architecture with a heavy reliance on resilient storage backed by Alibaba Cloud Object Storage & Cloudflare R2. As it turns out, storing a massive amount of encrypted user files at scale and having it be accessible at the edge, everywhere, all the time is not a trivial task. We believe we mostly solved the complex parts for our app due to years of trial and error dealing with poor, intermittent connections and high latency mobile networks. We've now reached 300 MAU (monthly active users). It's time to upgrade our database in the dust.