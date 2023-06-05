# DevOps / SRE - Top Links Last Week

## Week 13 - Issue #72

  

23 articles

  

  

## [The Black Swan Events in Distributed Systems](https://betterprogramming.pub/the-black-swan-events-in-distributed-systems-d6a5d51adddf)

The Black Swan Events in Distributed Systems look at a real-life metastable failure. This class of incidents that continue to keep going even after the initial trigger has been removed are called metastable failures. These incidents can cause system outages for an extended time; it could be hours or even days. The Infamous EC2 and RDS Service Disruption are so important that we should know about them to learn from these events. Although this type of event happens ever so rarely, when they do occur, they cause havoc.

  

## [We don’t use a staging environment](https://squeaky.ai/blog/development/why-we-dont-use-a-staging-environment)

Squeaky uses pre-live environments, such as development, staging, and feature-level environments, to test our latest changes before they end up in front of our users. We only have two environments: our laptops and production, and our main branch. We have a flat branching strategy, and all changes get merged back into the main branch and get back into production. We believe it's helping us ship faster and lower the number of issues on production. There are various elements to our approach, but most importantly: we only merge code that is ready to go live in production.

  

## [Integrating with GitHub Actions – CI/CD pipeline to deploy a Web App to Amazon EC2](https://aws.amazon.com/blogs/devops/integrating-with-github-actions-ci-cd-pipeline-to-deploy-a-web-app-to-amazon-ec2/)

Continuous Integration and Continuous Delivery (CI/CD) is among the essential things to start building. In addition, CI/CD practice reduces the time it takes to release new software updates by automating deployment activities. In this post, you will use GitHub Actions and AWS CodeDeploy to deploy a sample Java SpringBoot application to Amazon Elastic Compute Cloud (Amazon EC2) instances in an Autoscaling group. The solution utilizes the following services: GitHub Actions, CodeDeploy, and GitHub. CodeDeploy is a deployment service that automates application deployments to Amazon EC2 instances.

  

## [The Okta Mess Is Even Worse Than It Appears](https://thenewstack.io/the-okta-mess-is-even-worse-than-it-appears/)

Hacking group LAPSUS$ revealed they'd gotten their way into Okta's systems and showed off screenshots. Okta said an attack had been made on Okta's computer via a third-party customer support engineer's computer. The attacker had started a Remote Desktop Protocol (RDP) session on the laptop. From there, the attacker used the SuperUser application. Okta states that it only gives read access to some files despite the scary name.

  

## [Software Estimation: Points vs. Time](https://betterprogramming.pub/software-estimation-points-vs-time-b5a953e00f11)

Some teams prefer to estimate in units of time, such as hours or days. Others prefer to use story or effort points to represent the amount of effort over time. Here are some examples of when I would recommend using points to estimate your project using time. When a team is in constant flux, it may be easier to estimate using a range of time. Remember to use a unit of measurement that works for the team, and yes, you may be choosing between points and time.

  

---

  

## [Deployed in a Day: Github Actions, Docker, and AWS App Runner](https://betterprogramming.pub/deployed-in-a-day-github-actions-docker-aws-app-runner-2f72ae0f52a7)

The process below outlines how I used Github Actions, Docker, and AWS App Runner to take the applications mentioned above to deploy their applications in the cloud. The approach below will work for any frameworks that play nicely with Docker. For example, as part of a training program I run for trainee software engineers, we build a simple application that allows users to create, edit and delete employees. The approach is quite simple as cloud providers provide a limited number of ways to host your database in the cloud.

  

## [APISIX, an API Gateway the Apache way](https://blog.frankel.ch/apisix-api-gateway/)

Apache Web Server and Apache Tomcat were designed to serve purely static content. However, web servers also had to route requests to other components. As a result, web apps took a bigger and bigger share of the interactions between a server and its surrounding ecosystem. When your infrastructure relies on a piece of infrastructure, you need to keep its downtime minimum. This means configuring redundancy of critical components and directing requests to the available ones. Routing was not simple routing anymore, but load balancing between several identical servers.

  

## [High Availability and Load Balancing for Kubernetes API](https://betterprogramming.pub/high-availability-ha-load-balancing-lb-kubernetes-k8s-api-alpine-keepalived-haproxy-fe577e40c80)

Software-only High Availability and Load Balancing for your Kubernetes API Using Alpine Linux, HAProxy, and keepalived. I will show you how to quickly set up highly available and load-balanced access to your API using nothing else than software components. For this lab, I have used k3s deployed on k3OS, forming a. highly available Kubernetes cluster with embedded DB using three server nodes. The setup will incorporate the following software tools: Alpine Linux (Alpine), HAproxy, keepalive, and Alpine Linux. HAproxy is responsible for monitoring the proxy nodes and maintaining a floating IP address.

  

## [Basics of Container Isolation](https://blog.devgenius.io/basics-of-container-isolation-5eabdb258409)

The docker binary was a magical tool that allowed me to create docker images and spin up fully isolated containers. In this post, I'll try to distill down the concepts of Container Isolation using cgroups, namespaces, and chroot. In Linux, control groups (cgroups) are a kernel feature that allows isolating the usage of resources such as CPU, Memory, Disk IO, and networks for a set of processes. You can create your cgroup for a particular resource (say memory) by creating a directory under the cgroup directory.

  

## [Cloudflare: speed up WordPress with Automatic Platform Optimization plugin](https://rtfm.co.ua/en/cloudflare-speed-up-wordpress-with-automatic-platform-optimization-plugin/)

The rtfm.co.ua blog is relatively slow for users. For WordPress, Cloudflare created a plugin Automatic Platform Optimization (APO), which will automatically do all the necessary operations, although that will cost you $5/month. For now, you can configure all settings required in just one click on the plugin page. First, you need to register an account directly from the plugin's page to start with the plugin. Then, add your website's name servers to Cloudflare.

  

## [A Detailed Look at AWS RDS Databases](https://aws.plainenglish.io/detail-summary-aws-rds-databases-part-1-7bbc32f2dd52)

Here is a guide on setting up and using RDS at the enterprise level. RDS is nothing but Relational Database Service, a service to host and support different Databases. Current Supported Databases are Postgresql, Oracle, Oracle, and Microsoft SQL Server. These databases are launched inside a VPC to provide only access to resources present in the VPC. Therefore, we should host these RDS in a Private VPC and connect them through security groups from public-facing EC2 instances.

  

## [Supabase Functions on Deno Deploy](https://deno.com/blog/supabase-functions-on-deno-deploy)

Supabase Functions allows you to deploy code globally on edge within seconds. This feature is built on top of our Deno Deploy infrastructure, including auto-scaling and auto-caching by default. The new Functions product joins an impressive suite of managed solutions, including a database, storage, and a user management system. Getting started with Supabase functions only takes minutes.

  

## [Provider Support Comes to the Terraform Private Registry](https://www.hashicorp.com/blog/provider-support-comes-to-the-terraform-private-registry)

HashiCorp Terraform uses code to provision and manages any infrastructure. To help build that code, our community and tech partners publish providers and modules to share with all Terraform users. Now the private registry supports providers as well as modules. This new feature allows teams to centralize and distribute privately maintained providers, and it also brings several usability and security advantages to your organization's use of public providers. As of March 2022, we have more than 1,900 providers in the public registry.

  

## [A Foolish Consistency: Consul at Fly.io](https://fly.io/blog/a-foolish-consistency/)

Fly.io runs applications by transmogrifying Docker containers into Firecracker micro-VMs running on our hardware worldwide, connected with WireGuard to a global Anycast network. From a working container, your app can be running worldwide in minutes. We've sunk considerable energy into keeping São Paulo, Sydney, Singapore, and points between consistent views of what's running on Fly. We run a distributed database that attempts to be a source of truth for which services are currently running. The service catalog lives in Consul. The catalog is vital to space travel.

  

## [8 GitHub Actions for Faster Code Reviews - /src/ blog](https://www.software.com/src/github-actions-for-faster-code-reviews)

GitHub Actions provide teams with a way to streamline their development workflows in GitHub. GitHub Events trigger Actions, which then run custom workflows. These workflows can automate tasks like labeling pull requests, running linters, and deploying production build. In addition to Actions, GitHub Apps, such as Axolo, provide deeper integrations with your codebase to extend your workflows to extend the toolkit. Finally, with the 10k+ marketplace, there are even more ways to remix your own GitHub Actions in the marketplace.

  

## [A Look at Feature Lifecycle in Software Release Cycle](https://betterprogramming.pub/a-look-at-feature-lifecycle-in-software-release-cycle-3a43f9745e77)

This article looks at the lifecycle of developing features; not every new idea is implemented. Therefore, we have a real-world example feature for each section. The feature is where the who, what, why, when, where, and how of the new feature is defined. The project is hosted at devapi.com and hosted by the team at devmys.com.

  

## [Developer-Owned Security at High Velocity](https://thenewstack.io/developer-owned-security-at-high-velocity/)

Development velocity is the speed at which a company can deliver great software. Software is built to provide impactful products to customers faster and generate high business value. The top 25% of high-velocity companies enjoy 4-5 times higher revenue growth and 55% higher innovation. 

  

## [Docker founder launches Dagger, a new DevOps platform](https://techcrunch.com/2022/03/30/docker-founder-launches-dagger-a-new-devops-platform/)

Docker founder Solomon Hykes has been quietly working on his next startup, Dagger, launching into public beta today. The startup aims to build what the team calls a "DevOps operating system" Hykes says the DevOps process remains a bottleneck. Dagger lets DevOps engineers write their pipelines as declarative models in CUE (which stands for "configure, unify, execute"). Engineers can describe their pipelines and connect the different pieces, all in code.

  

## [What Is Zero Trust Security?](https://thenewstack.io/what-is-zero-trust-security/)

Zero Trust is a framework for security in which all users of an application, software, system, or network, inside or outside of an organization, must be authenticated, verified, and frequently validated before being granted access to specific data or tools within the company's network. In the zero trust framework, networks can be in the cloud, hybrid, or on-premise with employees in any location. The assumption is that no users or devices are to be trusted with access without meeting the necessary validation requirements.

  

  

## [Setting up a NodeJS API with TypeScript: Part 1](https://itnext.io/setting-up-a-nodejs-api-with-typescript-part-1-9f7c152b2af6)

This article aims at developers who are at least somewhat familiar with NodeJS development and will help you get a minimalist yet complete server up and running in no time. It will not explain every concept used in detail. For ease of development, we will use Express for handling the routes. For example, Express is a minimalist web framework for NodeJS. It does not have TypeScript support; however, we can find declaration files for Node and Express. This will allow us to access classes, interfaces, types, and most TypeScript goodies.

  

## [Understanding the Dependency Inversion Principle](https://betterprogramming.pub/exploring-the-most-commonly-used-design-principle-dependency-inversion-principle-f9a8401ab6fb)

The SOLID principles are the beacons that guide developers to create better designs and avoid code stinks at all times. They're used to help developers create clean, readable, and easily changeable software. Understanding the Dependency Inversion Principle (DIP) means inverting the direction of dependency. DIP is achieved by adding a stable abstract interface between the caller and the callee. The high-level functions should not depend on low-level modules; both should depend on abstractions.

  

## [Introduction to CI/CD with GitHub Actions](https://randiltennakoon.medium.com/introduction-to-ci-cd-with-github-actions-9808d8a960c9)

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your… docs. GitHub Actions can be considered as a platform to automate developer workflows. These workflows are written in YAML. We took the last two lines from the Syntax Checker tool in the Python Syntax marketplace. 

  

## [The Challenge of Scaling WebSockets](https://thenewstack.io/the-challenge-of-scaling-websockets/)

Matthew O'Riordan, Ably's CEO and technical co-founder, explain why WebSockets are hard to scale. The main challenge is that connections to your server need to be persistent. So for every user to see one another, they must be connected to the same WebSocket server. This means that the number of active users you can support is directly related to how much hardware your server has. And once you reach a few hundred to a few thousand users, you will need to scale your hardware.