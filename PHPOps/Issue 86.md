# DevOps / SRE - Top Links Last Week

## Week 27 - Issue #86

  

28 links

  

## [This Week in Programming: GitHub Copilot Tests the Copyleft](https://thenewstack.io/this-week-in-programming-github-copilot-tests-the-copyleft/)

Some in the open-source community criticize GitHub for charging for its Copilot service, which assists developers with code completion. They argue that this appropriates open-source intellectual property and that developers who care about open-source software should cut ties with GitHub altogether.

  

Check out 👉️ [My Tweet Thread about Copilot and our AI Future](https://twitter.com/llbbl/status/1546502737378136065)

  

## [Vulnerability scanning for containers, Kubernetes, and IaC](https://rafael-natali.medium.com/vulnerability-scanning-for-containers-kubernetes-and-iac-dd60732a7e25)

Vulnerability scanning is important to do before deploying anything, and Trivy is a helpful tool.

  

## [What is The Edge? The Secret of Deno Fresh.](https://betterprogramming.pub/what-is-the-edge-the-secret-of-deno-fresh-4b58e217b98e)

The edge is a new code word for a service offered by cloud providers, like AWS or Azure. In the context of web development, it refers to a platform's ability to render information quickly and reliably.

  

## [6 Essential SSH Commands To Manage Remote Machines](https://betterprogramming.pub/essential-ssh-commands-new-developers-should-know-52e2e72703c8)

This article covers six essential SSH commands for managing remote machines: adding identities to the ssh-agent, connecting to new machines, forwarding the ssh-agent, connecting to multiple machines, allocating a pseudo-terminal, and enabling debug mode.

  

## [Perl is still relevant](https://stackoverflow.blog/2022/07/06/why-perl-is-still-relevant-in-2022/)

Perl is a high-level, weakly typed, interpreted language with garbage collection and excellent memory management. Its primary strength is in text processing, and it is very UNIX-friendly. Perl has a vibrant development community in CPAN, with a vast archive of Perl modules. Perl is the best run in single tasks - on its own, it is not a language with great performance.

  

## [Building a Kubernetes cluster on AWS from scratch](https://craignewtondev.medium.com/building-a-kubernetes-cluster-on-aws-from-scratch-7e1e8b0342c4)

This article walks through the process of setting up a Kubernetes cluster on AWS from scratch. It covers provisioning the necessary compute resources, configuring networking and security, and installing the software and configuration required to run a Kubernetes cluster.

  

  

—

  

## [Gitlab Pipelines vs Github Actions](https://ericfossas.medium.com/gitlab-pipelines-vs-github-actions-231e62dd87d6)

Gitlab is better for platform engineers wanting to manage many private services quickly and at scale, while Github is better for open-source projects with one-off job definitions.

  

  

## [GitGuardian Tightens Integration With GitHub to Secure Secrets](https://devops.com/gitguardian-tightens-integration-with-github-to-secure-secrets/)

GitGuardian has expanded its ability to secure code repositories by providing deeper integration with GitHub, including scanning for secrets and providing suggestions for remediation. The company has also added an API key provisioning mechanism and extended support for role-based access controls.

  

## [What are Docker, Containers, Virtual Machines, and Containerization?](https://blog.devgenius.io/what-are-docker-containers-virtual-machines-and-containerization-e68bf076edf4)

Containerization bundles the software code with all its libraries, frameworks, and other dependencies so it can be packaged and shipped as a single entity.

Docker is an open platform for developing, shipping, and running applications that enables you to separate your applications from your infrastructure.

Containers and virtual machines are very similar resource virtualization technologies. However, the key differentiator between containers and virtual machines is that virtual machines virtualize an entire machine down to the hardware layers, and containers only virtualize software layers above the operating system level.

  

## [Secure Coding: An Introduction to Principles and Practices](https://blog.magda-on-cyber.com/secure-coding-an-introduction-to-principles-and-practices-c4d491018928)

The principles of secure coding are guidelines that should be followed when writing code. These guidelines help reduce the chances of vulnerabilities in your applications. Some common coding standards include the Secure Coding Guidelines from the CERT Coordination Center, the Microsoft Security Development Lifeline, and the OWASP Top Ten. In addition, good design is important for security, as it can help to reduce the chances of vulnerabilities in your code. Following coding standards and good design, practices can help make your applications more secure.

  

## [A Shell Script to Show the Source Code of Any Docker Tag](https://chrisfrew.in/blog/a-shell-script-to-show-docker-source/)

Use this shell script to view the source code of any Docker tag!

  

## [Deploying a Secure ElasticSearch Environment on Kubernetes](https://alfred-tommy-70522.medium.com/deploying-a-secure-elasticsearch-environment-on-kubernetes-deb0f981ddf5)

To secure an ElasticSearch environment on Kubernetes, you need to:

  

1. Configure inter-node communication using mutual TLS

2. Update the elasticsearch.yml file to use the certificates

3. Set up basic authentication for ES and Kibana

4. Upgrade the helm chart(s) for ES and Kibana

  

  

## [Get started with Ansible (config management)](https://medium.com/@a.abukar/get-started-with-ansible-config-management-b19e91cf9955)

This article outlines a simple Ansible project to help readers develop their configuration management skills.

  

  

## [CI/CD: Using CodePipeline in AWS](https://faun.pub/ci-cd-using-codepipeline-in-aws-8ce28b36ff6a?source=rss----10d1a7495d39---4)

This tutorial shows you how to set up a continuous integration and deployment (CI/CD) pipeline using the AWS CodePipeline service and a GitHub repository. You will need an AWS account with the appropriate permissions to use the CodePipeline and S3 services and a GitHub account.

  

## [Using CodeBuild with GitHub](https://medium.com/@Devin007/using-codebuild-with-github-ec45f6dba29e)

CodeBuild can be used to deploy code to a Lambda function by creating a BuildSpec file and connecting it to a GitHub repo.

  

## [Redisearch — A developer’s guide to production](https://iamvishalkhare.medium.com/redisearch-e6aac3fed2d5)

This article discusses setting up and using Redisearch in a production environment. It covers how to install the Redisearch and RedisJSON modules, how to model data using Redis OM for Python, and how to CRUD data using the Flask API.

  

## [How to Orchestrate Microservices With Docker-Compose](https://betterprogramming.pub/how-to-orchestrate-microservices-with-docker-compose-5a972cbac8d5)

Docker Compose is a tool used to define and run multi-container Docker applications. It is mainly used to create containers on a single machine.

  

## [Architecture Decisions in Neon](https://neon.tech/blog/architecture-decisions-in-neon/)

We decided to build Neon with modern cloud-native architecture, separating storage and compute. We also decided to build our storage system from the ground up instead of using a SAN or third-party file system. Our storage system is designed to keep all old page versions so that operations like PITR are quick and cheap.

  

## [Terraform at Scale: Manage Multiple Accounts](https://medium.com/@whitehead.pauljay/terraform-at-scale-manage-multiple-accounts-7c5bd0c54e4b)

To manage Terraform state for multiple accounts, you can use a hub and spoke pattern with AWS to assume roles. You will need to create an IAM role named terraform-state in the hub account and configure the minimum permissions for the IAM policy. You will also need to create an IAM role named terraform-admin in all accounts whose resources will be managed by Terraform. The terraform-admin role will need to trust the terraform-state role. Finally, you will need to configure the AWS provider to assume a role in the

  

## [Running Magento2 in Kubernetes — Part 3: Deploying the application](https://medium.com/@bjoern.kraus/running-magento2-in-kubernetes-part-3-deploying-the-application-68275f56098)

This person is summarizing how to run Magento2 on Kubernetes and how to do so using the provided chart from Phoenix Media. In addition, they go over some of the different options and values that can be changed to fit needs and things to be cautious about (such as Xdebug). This person seems to think that, while there is a lot to learn, using this chart can simplify deployment.

  

## [Can You Live without Kubernetes?](https://thenewstack.io/can-you-live-without-kubernetes/)

There are three main options for container orchestration: Kubernetes, Nomad, and FaaS. Each has its pros and cons that should be considered before choosing an orchestrator.

  

## [AWS CDK — Setup a Bastion host to connect to an AWS RDS database (Aurora Serverless) —…](https://medium.com/devops-techable/aws-cdk-setup-a-bastion-host-to-connect-to-an-aws-rds-database-aurora-serverless-79da07e08cee)

You can use AWS CDK to set up a bastion host to connect to an AWS RDS database (Aurora Serverless).

  

## [How MongoDB Brought Its Serverless Database Service to the Cloud](https://thenewstack.io/how-mongodb-brought-its-serverless-database-service-to-the-cloud/)

MongoDB has introduced a new serverless option for its MongoDB Atlas database service. The company claims that Atlas Serverless can support many application requirements with little to no configuration and upfront commitments.

  

## [Path to a Perfect Go Dockerfile](https://betterprogramming.pub/path-to-a-perfect-go-dockerfile-f7fe54b5c78c)

To build a perfect Go Dockerfile, start with building a Go image, then follow the official Docker best practices for multi-stage builds. To optimize further, use alpine as the base image in the builder stage and scratch in the runner stage. Finally, use COPY instead of ADD and combine command lines to reduce the image size.

  

## [How to Orchestrate Microservices With Docker-Compose](https://betterprogramming.pub/how-to-orchestrate-microservices-with-docker-compose-5a972cbac8d5)

This article describes how to use Docker Compose to orchestrate microservices. First, you must understand Dockerfile and build a Spring Boot service into a Docker image. Then, you can use Docker Compose to manage the container.

  

## [Pyscript: A Browser-Based Python Framework for the 99%](https://thenewstack.io/pyscript-a-browser-based-python-framework/)

Pyscript is a new Python framework being developed by Anaconda. It is designed for people who are not professional developers. Pyscript is still in alpha, but the response from the Python community has been positive.

  

## [Unix Command Line Crash Course](https://itnext.io/unix-command-line-crash-course-453e409d62f5)

The article explains why Unix command-line interfaces are advantageous over graphical user interfaces and teaches the basics of how to use a Unix command-line interface. It covers commands such as ls, cd, pwd, man, cat, touch, and file.

  

## [Red Engine: Insanely Powerful Scheduler](https://itnext.io/red-engine-insanely-powerful-scheduler-7d9d8e84b58b)

Red Engine is a scheduling framework for Python that is clean, productive, and customizable. It has a unique condition syntax and over 100 built-in conditions. It also supports logical operations, task chaining, and parallelization.