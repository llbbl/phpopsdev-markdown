  

# DevOps / SRE - Top Links Last Week

## Week 34 - Issue #93

  

42 links

  

## [Acorn, a Lightweight, Portable PaaS for Kubernetes – The New Stack](https://thenewstack.io/acorn-a-lightweight-portable-paas-for-kubernetes/)

Acorn is a new application deployment framework that is open source, simple, lightweight, and portable. It was created by the founders of Rancher and followed some of the same principles that made Rancher's products click with the cloud-native community. In addition, Acorn is designed to run microservices on Kubernetes.

  

## [How To Optimize Cloud Cost With Block Storage and Snapshots | by Elvin Lari  | Better Programming](https://betterprogramming.pub/how-to-optimize-cloud-cost-with-block-storage-and-snapshots-acab43d6699f)

This article discusses optimizing cloud storage costs using block storage and snapshots. You can use AWS EBS or DigitalOcean block storage to store data beyond the lifetime of a specific instance. EBS volumes are also scalable and can be replicated automatically. Application architects should provision General Purpose SSD (gp2) volumes instead of Provisioned IOPS SSD (io1) volumes unless the running application is mission-critical and need more than 10000 IOPS or 160 MiB/s of throughput per volume. EBS snapshots are a way to back up and recover the data on a block storage volume

  

  

## [Terraformer: Converting Infrastructure Into Reusable Terraform Code | by Wenqi Glantz  | Better Programming](https://betterprogramming.pub/terraformer-converting-infrastructure-into-reusable-terraform-code-afe543ad0b15)

Terraformer helps you convert your existing infrastructure into Terraform code so you can easily replicate it in different environments.

  

## [Serverless is the New Timeshare](https://debugagent.com/serverless-is-the-new-timeshare)

Serverless is a step backward because it's difficult to debug and doesn't offer much control over code or application logic. However, it can be helpful for webhooks since they're difficult to debug.

  

## [How Snap used microservices, AWS, and Google Cloud - Protocol](https://www.protocol.com/enterprise/snap-microservices-aws-google-cloud)

Snap Inc. has redesigned its backend architecture to rely on microservices and a multicloud strategy, which has resulted in reduced latency for users and a 65% reduction in compute costs.

  

## [How Software Deployment Tools Have Changed in the Past 20 Years | by Geshan Manandhar  | Better Programming](https://betterprogramming.pub/how-software-deployment-tools-have-changed-in-the-past-20-years-7ac24723704a?source=rss------software_engineering-5)

In the past 20 years, software deployment tools have evolved from simple web interfaces and FTP clients to sophisticated container orchestrators like Kubernetes. This evolution has made deployment much easier and more reliable but has also added layers of complexity to the CI/CD process.

  

## [The container orchestrator landscape [LWN.net]](https://lwn.net/SubscriberLink/905164/e1f4d4c1ce35f8b9/)

The container orchestrator landscape is dominated by Kubernetes, which is complex but popular. Other orchestrators include Docker Compose and Swarm, which are simpler but lack some features.

  

—

  

## [Construct a Two-Tier Architecture with Terraform Cloud CI/CD | by Melissa Gibson  | Level Up Coding](https://levelup.gitconnected.com/construct-a-two-tier-architecture-with-terraform-cloud-ci-cd-c64b49c94440)

I use Terraform Cloud to deploy a two-tier architecture in AWS. I then produce a CI/CD pipeline with Github \> Terraform Cloud \> AWS. To automate the process of making updates to the code and applying the changes to the infrastructure.

  

  

## [Why your website should be under 14kB in size  | endtimes.dev](https://endtimes.dev/why-your-website-should-be-under-14kb-in-size/)

The 14 kB rule is a rule of thumb that states that your website should be under 14 kB in size to make it load faster. This is due to the TCP slow start algorithm.

  

## [Deploy a Kubernetes Cluster on Ubuntu Server Using Containerd – The New Stack](https://thenewstack.io/deploy-a-kubernetes-cluster-on-ubuntu-server-using-containerd/)

To deploy a Kubernetes cluster on Ubuntu Server, you must install Containerd and use that as your runtime engine. You also need to configure your servers' hostnames and host files, disable swaps, and install a few dependencies. Finally, you can initialize the cluster on the controller node.

  

## [Kubernetes CronJob: Automate Administrative tasks in EKS | Medium](https://hemanth-kumarm.medium.com/kubernetes-cronjob-automate-administrative-tasks-in-eks-be09cb340802)

Kubernetes provides a way to schedule tasks at a fixed schedule using CronJobs. This can automate administrative tasks such as scaling deployments up or down.

  

## [chezmoi - chezmoi](https://www.chezmoi.io/)

Chezmoi is a dotfile manager that lets you securely manage your dotfiles across multiple machines. You can install it with a single command and update your dotfiles on any machine with a single command. A quick start guide and a user guide cover the most common tasks. In addition, you can browse other people's dotfiles that use Chezmoi on GitHub and GitLab.

  

## [Log management for Serverless solutions using AWS OpenSearch and Cloudformation | FAUN Publication](https://faun.pub/application-log-management-for-serverless-solutions-using-aws-opensearch-and-cloudformation-b75ffd43bcbb)

This post is about log management for serverless solutions using AWS OpenSearch and Cloudformation. The author documents their experience writing a complete E2E application log management system as IaC for a serverless setup in AWS.

  

## [Kubernetes: Provisioning clusters on AWS with EKS | by Apoti Tech  | FAUN Publication](https://faun.pub/kubernetes-provisioning-clusters-on-aws-with-eks-f45b9b6b4018)

This guide will teach you how to create clusters on the AWS Elastic Kubernetes Service (EKS) with eksctl. By the end of the tutorial, you will automate creating three clusters (dev, staging, prod) complete with the ALB Ingress Controller in a single click.

  

## [What do you know about multi-container pod design patterns in k8s? | by Mostafa Wael  | FAUN Publication](https://faun.pub/multi-container-pods-design-patterns-in-k8s-7afa52bae380)

Multi-container Pods are simply Pods that include multiple containers that work together, and this functionality can be used to add value to applications.

  

  

  

## [Building reusable Terraform Modules — Part 1 | by Flavius Dinu  | Medium](https://medium.com/@flaviuscdinu93/building-reusable-terraform-modules-9e90aa4eef31)

This person suggests that best practices for building reusable Terraform modules include having each module in its own repository, tagging releases, using dynamic blocks, and exposing outputs. Additionally, this person recommends using pre-commit and Github Actions to maintain your code.

  

## [Building Kubernetes Multi-Container Pods | by AhmedIhab  | Medium](https://medium.com/@ahmedIhab/building-kubernetes-multi-container-pods-64a8375798e4)

Pods are the smallest, most basic deployable objects in Kubernetes and can contain one or more containers.

-The containers in a pod are tightly coupled because they share resources like network and storage volumes.

-Kubernetes allows multi-container pods because they can support helper applications that assist a primary application.

-The ambassador container is a special type of sidecar container which simplifies accessing services outside the pod.

  

## [Acorn Labs | Kubernetes Application Deployment](https://acorn.io/)

Acorn is a new, open-source tool for packaging and deploying apps on Kubernetes. It aims to simplify the process by providing a standardized artifact that can be run consistently across different environments.

  

## [Kubernetes OWASP Top 10: Intro. Recently, the OWASP Foundation… | by Alan Scott | Jul 2022 | ITNEXT](https://itnext.io/kubernetes-owasp-top-10-intro-73943be7add2)

The OWASP Foundation has introduced its latest Top 10 risks when adopting and implementing Kubernetes. This list is a great entry point to ensuring risks introduced while deploying workloads on Kubernetes can be mitigated from the outset, enabling a secure-by-design architecture.

  

## [Kubernetes Configuration Manager — Helm | by Nischal Vooda  | Medium](https://nischalvooda.medium.com/kubernetes-configuration-manager-helm-bd3c0d593a87)

Helm is a package manager for Kubernetes that allows for easier management of Kubernetes configuration files. Helm charts are composed of a `Chart.yaml` file and a templates directory, which contains the templated manifest files of Kubernetes resources. The template files expect input from a values YAML file, which contains default input parameters for a Helm chart.

  

  

## [What, Why, and How Terragrunt ?. Terraform can be used to code your… | by Yash Hirulkar  | Medium](https://yashhirulkar701.medium.com/what-and-why-terragrunt-105e06194c7c)

Terragrunt is used to manage and provision cloud infrastructure, avoiding the shortcomings of Terraform.

  

  

## [Build and Run an Ansible Execution Environment — ansible-builder and ansible-runner tools | by Ansible Pilot  | AWS Tip](https://ansiblepilot.medium.com/build-and-run-an-ansible-execution-environment-ansible-builder-and-ansible-runner-tools-c5a53084412e)

Ansible Execution Environment is the latest technology to maintain up-to-date Python dependency of the Ansible collections without interfering with your Linux system.

  

## [Renovate, a Dependabot alternative](https://blog.frankel.ch/renovate-alternative-dependabot/)

Renovate is a great tool that allows for easy updates of dependencies.

  

## [Kubernetes ConfigMap & Secrets](https://devtron.ai/blog/kubernetes-configmaps-secrets/)

Kubernetes ConfigMap & Secrets allow you to decouple configuration from pods and other Kubernetes resources. You can create them using two flags --from-literal or --from-file. Secrets are exactly similar to ConfigMaps, except they are base64 encoded.

  

## [Creating Simple Ansible Playbook. Automate your task with ansible | by Yulyano Thomas Djaya  | Medium](https://medium.com/@linolowlevel/creating-simple-ansible-playbook-b719c5829213)

Ansible is a program used to automate tasks on remote servers. In this article, the author describes how to install ansible on a Linux machine and use it to install a package on a remote server.

  

## [Create a CI/CD Pipeline with Github, CodeBuild, and Codepipeline | by Huy Le  | Medium](https://medium.com/@huyquangle0503/create-a-ci-cd-pipeline-with-github-codebuild-and-codepipeline-cc08ea2310eb)

This tutorial shows you how to create a CI/CD pipeline with Github, CodeBuild, and Codepipeline.

  

## [GitHub - jetpack-io/devbox: Instant, easy, predictable shells and containers.](https://github.com/jetpack-io/devbox)

Devbox is a command-line tool that lets you easily create isolated shells and containers. You start by defining the list of packages required by your development environment, and devbox uses that definition to create an isolated environment just for your application.

  

## [Harbor — Kubernetes — Containerd. | by Hosein Yousefi  | Medium](https://medium.com/@hosein.yousefi/harbor-kubernetes-containerd-c1f98782375e)

Harbor is an open source registry that secures artifacts with policies and role-based access control and scans images for vulnerabilities

- Harbor is a CNCF Graduated project

- Harbor components include a k-v storage layer, a data storage layer, a proxy server, and a web portal

- You can deploy Harbor on Kubernetes with Containerd

- To authenticate to Harbor, you need to download a project certificate from the dashboard and add it to your nodes

  

## [Kubernetes Failure Stories](https://k8s.af/)

A compiled list of links to public failure stories related to Kubernetes.

  

## [Argo CRDs and Kustomize: The Problem of Patching Lists | by Zach Aller  | Argo Project](https://blog.argoproj.io/argo-crds-and-kustomize-the-problem-of-patching-lists-5cfc43da288c)

Kustomize supports adding your own OpenAPI schema definition so it can figure out how properly merge arrays via strategic merging patch but has some big user interface issues. The main one being it currently only supports the replacement of the schema definition and not the addition to the pre-bundled Kubernetes resources. What this means is that currently, Kustomize bundles an OpenAPI schema with all the native Kubernetes resources like Deployments, Statefulsets, Secrets, etc. However, this causes issues for end users who use CRDs with native types within a single

  

  

## [Node.js + Database with Docker for Local Development | by Mohammad Faisal  | JavaScript in Plain English](https://javascript.plainenglish.io/node-js-database-with-docker-for-local-development-285212c5162f)

This article taught us how to create a full-fledged backend application using Node.js and any database (Postgres/MySQL, etc.). We used docker-compose to get that application server and database up and running simultaneously, which can improve our development experience.

  

## [4 Challenges Retailers Face When Adopting Kubernetes at the Edge](https://www.weave.works/blog/challenges-retailers-face-when-adopting-kubernetes)

Weaveworks has helped many retail customers adopt GitOps to manage Kubernetes clusters and application deployments at the Edge. GitOps provides a way to manage configurations and deployments automatically, schedule updates, and roll back changes if necessary. Weave GitOps also allows teams to visualize different environments in a single pane of glass.

  

## [What's new in MicroK8s v1.25? We are pleased to bring you Kubernetes… | by K. Tsakalozos  | ITNEXT](https://itnext.io/whats-new-in-microk8s-v1-25-d5b06cd82ba0)

MicroK8s v1.25 has been released with Kubernetes v1.25; try it out with:

  

"That's how easy is to install MicroK8s, the zero-ops Kubernetes for developer workstations, edge and IoT."

  

"If you haven't used MicroK8s before here are a few tips:

  

-The snap size has been reduced from 230MB to 170MB."

  

"-Strictly confined K8s are now available with the --devmode option.

  

## [Report | Azure edges out AWS as a most-used cloud by businesses | Fathym](https://www.fathym.com/blog/articles/2022/august/2022-08-19-azure-edges-out-aws)

According to the Flexera 2022 State of the Cloud report, Azure has overtaken AWS as the most-used cloud by businesses. AWS's usage has been mostly stagnant, while Azure saw a 4% growth in adoption.

  

## [Using Makefiles with Terraform.  | by Apoti Tech  | Dev Genius](https://blog.devgenius.io/using-makefiles-with-terraform-8f941494881a)

Terraform is a great tool for provisioning infrastructure. One of the best practices that evolve over time as you play more with Terraform is a directory structure that works best for your project. For example, some prefer having each component in its own directory so that modification and destruction of resources are easy. In contrast, others treat a software stack (e.g., 1 ELB + 2 instances + 1 Elasticache) as a logical unit that should reside together.

  

To make things easier, you can use Makefiles.

  

  

## [Introducing general availability of Google Cloud Certificate Manager | Google Cloud Blog](https://cloud.google.com/blog/products/identity-security/introducing-general-availability-of-google-cloud-certificate-manager/)

Google Cloud Certificate Manager is now available for general use. It makes managing and deploying public Transport Layer Security (TLS) certificates easy.

  

## [AWS Lambda: Creating a python container image | by Jake Fitzsimmons  | Medium](https://medium.com/@jake.fitzsimmons/aws-lambda-creating-a-python-container-image-68a42e2f6173)

Container images are a great way to deploy python lambda functions on a Windows machine.

  

In this article, we'll learn how to create a python container image and deploy it to AWS Lambda. We'll also learn how to create a container image from scratch.

  

## [Scaling Your Application With Kubernetes - DEV Community 👩‍💻👨‍💻](https://dev.to/pavanbelagatti/scaling-your-application-with-kubernetes-5715)

Kubernetes is a powerful tool for scaling applications, and there are several techniques you can use to scale your app. Horizontal Pod Autoscaler, Vertical Pod Autoscaler, and Cluster Autoscaler are all ways to scale your app using Kubernetes.

  

## [The Future of NGINX: Getting Back to Our Open Source Roots - NGINX](https://www.nginx.com/blog/future-of-nginx-getting-back-to-open-source-roots/)

NGINX is turning 18 and is looking back at all they have accomplished. However, they are also looking to the future and what they can do to improve. They want to ensure they are always adapting to the ever-changing open source world and giving back to the open source community.

  

## [Replacing Docker Desktop with Podman and Kind in MacOS | by Nilesh Jayanandana  | Medium](https://nilesh93.medium.com/replacing-docker-desktop-with-podman-and-kind-in-macos-c750581a3fda)

The article explains how to set up an alternative to Docker Desktop on a Macbook using Podman and Kind.

  

## [Multi-Cloud Strategies Using Microservices Architecture | by Boris Zaikin  | ITNEXT](https://itnext.io/multi-cloud-strategies-using-microservices-architecture-8320aa708c37)

microservices is an architectural pattern that allows for loosely coupled modules in an application, and it can be deployed using various container engines and orchestration systems. Additionally, microservices can be deployed using serverless architecture, a cloud service available on demand.

  

## [Upgrading Kubernetes Clusters. Due Diligence To Avoid API… | by Karthikeyan Govindaraj  | Level Up Coding](https://levelup.gitconnected.com/upgrading-kubernetes-clusters-1ac91343a3da)

If you're upgrading your Kubernetes cluster, you must do your due diligence to ensure that all the manifests for your applications and services are validated against the new version of Kubernetes. One way to do this is to create a new cluster with the target version and ask the application teams to validate their manifests against it.