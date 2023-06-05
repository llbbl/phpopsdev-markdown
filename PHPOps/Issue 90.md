# DevOps / SRE - Top Links Last Week

## Week 31 - Issue #90

  

35 links

  

## [GitHub Repositories Weren’t Hacked](https://thenewstack.io/github-repositories-werent-hacked/)

There was a false report of a massive malware attack on GitHub when only a few repositories were affected.

  

## [CI/CD Pipeline — via Github and Code Pipeline](https://medium.com/@Ashleecooper/ci-cd-pipeline-via-github-and-code-pipeline-dd4d921a62ec)

This article covers the basics of setting up a CI/CD pipeline using Github and Code Pipeline. CI/CD pipelines help automate the process of testing and deploying new code. To set up a pipeline, you'll need to create an S3 bucket and enable website hosting. You can then complete your pipeline using CodePipeline. Once your pipeline is set up, you can test it by updating your code in the GitHub repo.

  

## [Basic OpenShift 4 Cluster setup on AWS](https://faun.pub/basic-openshift-4-cluster-setup-on-aws-7b8ea694fd41?source=rss----10d1a7495d39---4)

This blog walks through the process of setting up a primary OpenShift 4 cluster on AWS. It outlines the requirements and provides detailed instructions on how to get everything up and to run.

  

## [I still love PHP and JavaScript](https://the.scapegoat.dev/why-i-love-php-and-javascript)

I love PHP and Javascript because they're convenient, popular, and have good tooling. Their popularity means there are always newbies learning the language, which is fulfilling.

  

## [How to Talk About Software Changes](https://betterprogramming.pub/how-to-talk-about-software-changes-82dfb39cfaa)

1. Frame the problem domain

2. Explain what was missing, broken, or otherwise problematic

3. Present the change from the perspective of the user

4. Use this time to loop back to the beginning where you started

  

## [Top 6 Threat Detection Tools for Containers](https://itnext.io/top-6-threat-detection-tools-for-containers-3dd80b77777e)

A list of six threat detection tools for containers is presented, along with a brief description of each. Clair, Trivy, Secret Scanner, OpenSCAP, Kube-bench, and Threat mapper are all open-source tools that can scan for vulnerabilities and hardcoded secrets in container images and infrastructure as code files.

  

## [The Rise and Fall of Bootstrap](https://betterprogramming.pub/the-rise-and-fall-of-bootstrap-68d4cd703666)

The rise and fall of Bootstrap and how Tailwind became the go-to CSS framework.

  

--

  

## [How Kafka and Redis Solve Stream-Processing Challenges](https://thenewstack.io/how-kafka-and-redis-solve-stream-processing-challenges/)

The author discusses how Kafka and Redis can help with stream processing and how making streams the center of the world can help solve several challenges.

  

## [Terraform: Two-Tier Architecture](https://aws.plainenglish.io/terraform-two-tier-architecture-75d7d86be92c)

Terraform is an IaC (Infrastructure as Code) tool that allows you to quickly build, rebuild, and change cloud infrastructure. It is also platform agnostic, meaning it can work with any cloud provider. Additionally, its language is very human-readable, making it easier to understand code you did not create.

  

## [The Basics of Terraform!](https://aws.plainenglish.io/the-basics-of-terraform-57a66b269c43)

In this article, the author gives a rundown of the basics of Terraform and how to use it to deploy AWS infrastructure. They also go over some common errors one might encounter while using Terraform.

  

## [Application Architecture for Microservices: Sidecar Pattern](https://itnext.io/application-architecture-for-microservices-sidecar-pattern-c5c0074e8f1d)

The sidecar pattern can be used to write microservices in a single language and inject them into applications. For example, this can be done with Kubernetes based on Dynamic Admission Webhook. Furthermore, with the sidecar pattern, pods can scale up, and the network interface is explicitly created for the pod, which helps to minimize network latency.

  

## [Ubuntu Server Struggles with Post-Docker Kubernetes Installs](https://thenewstack.io/ubuntu-server-struggles-with-post-docker-kubernetes-installs/)

The writer is frustrated with the difficulty of installing Kubernetes on Ubuntu Server 22.04. They've tried multiple times and keep running into errors. They suggest using microk8s via snap as an alternative.

  

  

## [The Benefits of Static Initialization for Your AWS Lambda Functions](https://towardsdatascience.com/the-benefits-of-static-initialization-for-your-aws-lambda-functions-c7372f682188)

A serverless function is a server that automatically shuts down after 5 minutes of inactivity. Then, when it needs to be invoked again, it automatically reboots the server. You just specify dependencies in a file, and serverless functions will create a container image out of those installed dependencies, then deploy that image and those dependencies upon reboot.

  

Serverless functions are ideal for fetching data, transforming it, and sending the result to another endpoint for processing.

  

  

## [How To Use GitHub Actions Reusable Workflow](https://betterprogramming.pub/how-to-use-github-actions-reusable-workflow-8604e8cbf258)

GitHub Actions has a new reusable workflow feature that allows you to copy and paste workflows across multiple repositories. This saves time and eliminates maintenance headaches.

  

## [How a Cloud Skills Shortage Is Affecting Multicloud Adoption](https://thenewstack.io/how-a-cloud-skills-shortage-is-affecting-multicloud-adoption/)

The 2022 HashiCorp State of Cloud Strategy Survey found that a shortage of cloud skills complicates multicloud adoption for many organizations. In response, many companies are investing in centralized cloud platform teams and automated tooling.

  

## [LocalStack and AWS Parity Explained](https://localstack.cloud/blog/2022-08-04-parity-explained/)

LocalStack is a cloud emulator that strives to be compatible with AWS, meaning that when you make an API call to LocalStack, it behaves the same way AWS would. To keep up with AWS API changes, LocalStack has a weekly Github action that checks for any API changes and raises a pull request automatically. In addition, snapshot tests are used to ensure that LocalStack is consistently behaving like AWS. A snapshot test is a unique form of an integration test that records responses from AWS and compares them to responses from LocalStack. If there are any differences, the test will fail.

  

## [The Everything-As-Code Revolution and the OWASP Top 10](https://devops.com/the-everything-as-code-revolution-and-the-owasp-top-10/)

The Open Web Application Security Project (OWASP) Top 10 list is finally seeing some shakeup, with insecure design debuting on the list as the number four security risk to web applications. This change from OWASP recognizes that security needs to have a seat at the table when critical software design decisions are made. It also requires empowering security teams like the DevOps teams have been designated to own and manage the application's security design and implementation.

  

## [Explaining File Upload Vulnerabilities](https://faun.pub/explaining-file-upload-vulnerabilities-34ca48b992c1)

Unrestricted file uploads present a significant risk to web applications, as they can lead to system takeover, overloaded file systems or databases, and more. Therefore, developers should take care to validate uploaded files and store them securely. Additionally, implementing a defense-in-depth approach utilizing multiple prevention strategies is recommended.

  

## [3 Surprising Things Consul Service Mesh Can Do](https://www.hashicorp.com/blog/3-surprising-things-consul-service-mesh-can-do)

Consul can do much more than service discovery, and it's easy to use with Kubernetes.

  

## [The Future of Serverless](https://www.readysetcloud.io/blog/allen.helton/what-does-the-future-hold-for-serverless/)

The future of serverless holds a lot of potentials. We will see higher levels of abstraction, making development more straightforward. Additionally, monitoring tools will become more sophisticated and tuned to specific workloads. Infrastructure from code is a significant disruptor that will change how we deploy serverless applications.

  

## [How to Run a Simple Flask Application in a Container](https://betterprogramming.pub/how-to-run-a-simple-flask-application-in-a-container-691fbbd91fcf)

In this article, we containerized a simple Python flask application using pipenv and gunicorn. We also looked at some of the gotchas that Windows users might face.

  

## [Where Did Architecture Go?](https://www.agile-meets-architecture.com/essays/where-did-architecture-go)

Architecture is essential for agile software development but is often overlooked or deprioritized. Architects must focus on helping developers make sound architectural decisions rather than making them themselves. This can be done by providing context and guidance about what good choices look like.

  

## [How to Run an Ansible Playbook using GitHub Action?](https://couedeloalexandre.medium.com/42430dec944)

This tutorial teaches you how to use GitHub Actions to automate your provisioning from Github. You will learn how to create a workflow to validate your configuration and run your playbook against your inventory. This will allow you to set up an automated pipeline that can be triggered by a commit or pull request on GitHub with minimal overhead to manage your infrastructure.

  

## [Teleport: Securely authenticating to Kubernetes clusters with MFA](https://faun.pub/teleport-securely-authenticating-to-k8s-clusters-with-mfa-42a4d1aad440)

Teleport is a one-stop security solution that provides multi-factor authentication, granular access policies, and audit logs for access to Kubernetes resources, cloud servers, databases, and web applications. It supports PCI DSS, ISO 27001, HIPAA, FedRAMP, SOC2, and FIPS.

  

## [Stages of a CI/CD Pipeline](https://pavanbelagatti.hashnode.dev/stages-of-a-cicd-pipeline-cl6agv8cp0e8ry6nvbmn60ia9)

Continuous integration is the process of automating the integration of code changes into a shared codebase, intending to find and fix potential issues early on in the development phase. Continuous delivery automates the movement of code from a shared codebase through a testing environment to a production-like environment and, finally, to a live environment. The goal of CD is to reduce the risk of human errors and increase the release process's predictability. The CI/CD pipeline typically consists of the following stages: source, code quality analysis, test and build,

  

## [A Guide to Monitor Docker Containers](https://betterprogramming.pub/a-guide-to-monitor-docker-containers-170a0d804463)

This article covers using various commands and tools to monitor Docker containers. Docker containers can be monitored using controls included with Docker or with third-party tools. Sysdig and Weave Scope are two popular third-party tools.

  

## [7 Useful PHP Libraries You Should Use in Your Next ProjectーPart- 3](https://medium.com/codex/7-useful-php-libraries-you-should-use-in-your-next-project%E3%83%BCpart-3-62c7e98f39e1)

Farhan Tanvir lays out seven different PHP libraries - Códice, Parse It, QueryPath, URLify, HybridAuth, Imagine, and PHP help - that can be useful for various tasks in web development.

  

## [For AI to Succeed, MLOps Needs a Bridge to DevOps](https://thenewstack.io/for-ai-to-succeed-mlops-needs-a-bridge-to-devops/)

MLOps (the process of designing, building, deploying, and maintaining machine-learning models) needs to realign and mesh with DevOps workflows and best practices to make AI applications less of an obstacle course.

  

## [Pros and Cons of Public Cloud WAFs](https://thenewstack.io/pros-and-cons-of-public-cloud-wafs/)

Public cloud WAFs have some advantages, but they also have some significant downsides. As a result, they may not be the best choice for larger applications, more complex use cases, or evolving application architectures.

  

## [So, What's the Deal With Micro-Frontends?](https://betterprogramming.pub/so-whats-the-deal-with-micro-frontends-7f799ef504dc)

Micro-frontends, inspired by microservices, are independently deployable parts composed of a greater whole. They provide scalability, agility, and maintainability benefits but have operational and governance complexities.

  

## [Beginner Guide To Data Wrangling](https://faun.pub/beginner-guide-to-data-wrangling-25b5b4342680)

Data wrangling is a crucial step in the data analysis and can make the difference between getting insights from data and not. It involves understanding the data, cleaning it, and transforming it into a usable form. Several tools and techniques can help with this process, and choosing the right tool for the job is essential.

  

## [Transactional Vs. Transformational leadership — different paths to results](https://jelvix.com/blog/transactional-vs-transformational-leadership)

There are two main types of leadership styles - transactional and transformational. Transactional leaders motivate employees by offering rewards for achieved goals, while transformational leaders inspire employees to think creatively and innovatively. Both leadership styles have their benefits and drawbacks, and the most influential leaders can combine both approaches.

  

## [AWS SNS dead-letter queue (DLQ) pattern local setup](https://faun.pub/aws-sns-dead-letter-queue-dlq-pattern-local-setup-272a206da3f)

This article explains how to set up a dead-letter queue (DLQ) pattern for AWS SNS subscriptions using Localstack.

  

  

## [A Guide to Monitor Docker Containers](https://betterprogramming.pub/a-guide-to-monitor-docker-containers-170a0d804463)

This article discusses how to monitor Docker containers using various methods and tools. The report first covers using Docker's command line tools to monitor containers and then introduces the third-party tool sysdig. Weave Scope is also briefly mentioned as a visual tool for monitoring containers.

  

## [Why your daily stand-ups don't work and how to fix them](https://lucasfcosta.com/2022/08/07/how-to-improve-daily-standups.html)

  

The daily stand-up is a classic example of learned helplessness. We all know they're useless, but we tell ourselves that's just how things are and do nothing about it.

These days, we do stand-ups because that's what we are told to, not because they solve any particular problems.