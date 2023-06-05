# DevOps / SRE — Top Links Last Week

## Week 32 Issue #39

## [DevOps, SRE, and Platform Engineering](https://iximiuz.com/en/posts/devops-sre-and-platform-engineering/)

DevOps was a cultural shift giving development teams more control over shipping code to production. DevOps is about application development, aka business logic. SRE is just one of the ways to implement the DevOps culture - it says that it implements the particular DevOps class that implements the idea of Site Reliability Engineering and SREs. The most common approach is to provide development teams with some sort of CI/CD pipelines. The implementation could vary. I've been in setups where developers would just have. sudo on production servers.

## [Production Outages: The Biggest Test of the DevOps Culture](https://betterprogramming.pub/production-outages-the-biggest-test-of-the-devops-culture-4f82a02554b5)

DevOps as a culture, in my experience, has its roots in collaboration and understanding each other. It is when devs understand the pains of ops and vice versa, that both can support each other instead of working against each other. This promotes joint problem solving, rather than pressing blame, which ultimately results in faster resolution and fewer distractions. This is how DevOps drives the tooling and process in an organization. It is imperative to design with failure in mind in such a culture. Robust alerting and proactive monitoring ensure that failures are detected when they happen, not when users report them.

---

_Please consider supporting the weekly DevOps / SRE Report. Subscribe to our free [Newsletter](https://www.phpops.dev/subscribe/#/portal/signup) on our new website!_

---

## [Kubernetes Deployment — Rolling Updates and Rollbacks Explained](https://bharathirajatut.medium.com/kubernetes-deployment-rolling-updates-and-rollbacks-explained-e3efa6557368)

Kubernetes updates the application and rollbacks to its previous deployment if something wrong happens in the current update. This article covers the following topics: Revision, Revision, Recreate and Rolling Update strategies. How to update the application running on the cluster after created the first Deployment? And how to roll back if anything goes wrong? These two questions will come to every developer’s mind when they begin exploring Kubernetes. We always use the YAML file for Deployment. We simply edit the Deployment YAMl file and change the Docker image tag version to your latest image version.

## [Why Every Company Needs Platform Ops](https://www.nginx.com/blog/why-every-company-needs-platform-ops/)

Platform Ops is the team responsible for curating, maintaining, connecting, and securing the platform that provides DevOps teams with what they need to do their jobs. Platform Ops teams must be evangelists and teachers to ensure that all users of the platform understand why choices were made and how to get the most out of what’s available on the platform. It is an effort to strike a healthy balance between choice and chaos; it seeks to enable enterprises to shift‑left while maintaining strong security, governance, and reliability. For companies struggling to navigate the new environment of cloud‑native applications, the team becomes a crucial conduit for information and institutional knowledge.

## [3 Steps You Need To Know for a Successful GitOps Implementation](https://microtica.com/blog/3-steps-to-developing-a-successful-gitops-model/)

GitOps is a model that enables a streamline between development and operations flows. It brings them together through a central place for collaboration, Git, containing both configuration files and application code. GitOps serves organizations that develop cloud-native solutions based on containerization and microservices. It enhances the developers’ experience by enabling them to contribute with features without the need to know the underlying infrastructure. At the same time gives control to operations with code reviews and approvals. The most prominent advantages coming with implementing a GitOps model are probably standardization and consistency.

## [Monitor Your Containers with Sysdig](https://thenewstack.io/monitor-your-containers-with-sysdig/)

Sysdig collects system calls and events directly from the Linux kernel. It does (by itself) what strace, tcpdump, htop, iftop, lsof, and Wireshark do. Sysdig is a command-line tool, but it does include an ncurses user interface to make viewing this information easier. I’m going to walk you through the installation and usage of Sysdig on my server operating system of choice, Ubuntu Server 20.04.

## [Deploy an Azure DevOps Pipeline by using Terraform](https://faun.pub/deploy-an-azure-devops-pipeline-by-using-terraform-fe8d5786ec6)

In this article, I’m going to share how we can implement an Azure DevOps pipeline by using Terraform. To easily understand, I will first create a pipeline using the portal. Then I will create the same pipeline using using the same tool. We are going to use a YAML file that is on a GitHub account to run the pipeline. The pipeline will work as per the workflow mentioned on the file that's on your GitHub account. You can create or use an existing DevOps Organization with an existing pipeline.

## [Kong Updates Service Mesh to Replace Load Balancers](https://containerjournal.com/features/kong-updates-service-mesh-to-replace-load-balancers/)

Kong Mesh is designed to be deployed on top of both Kubernetes and traditional virtual machines. Version 1.4 of Kong Mesh now supports five different decentralized load balancing algorithms. Kong claims the latest release improves overall network performance by a factor of four compared to a more centralized approach based on traditional load balancers that create extra network hops in decentralized environments. The number of organizations that have deployed a service mesh in a production environment remains low, says Marco Palladino, CTO, Kong.

## [9 Simple Programming Tips from a Senior Programmer to a Junior](https://javascript.plainenglish.io/9-simple-programming-tips-from-a-senior-programmer-to-a-junior-a7f96078822b)

There are free and paid “ready” or “semi-finished products” for developers on the web. Always use GIT, even if only you are working on the project. Never stop developing, follow trends, learn about new products, try new products. Open Source is the best way to learn and correct your code from a large library over time and discover functionalities you’ve already forgotten. Open source is one of the highest-paid jobs among developers.

## [How to Provision, Configure & Deploy to Google Cloud Platform](https://blog.devgenius.io/how-to-provision-configure-deploy-to-google-cloud-platform-97dbbe36fcde)

This tutorial demo is the next demo to a series of demos I have been publishing about building and deploying a NodeJS app. This demo requires basic knowledge, understanding and familiarity of Google Cloud Platform, Docker, Kubernetes, terraform and Github Actions. In this tutorial, I’m going to demo how to deploy and run an application on GCP from my Mac. I highly recommend that you first complete these two tutorials before getting started on this: Deploying to GPC using Docker.

## [Sigstore: A Solution to Software Supply Chain Security](https://martinheinz.dev/blog/55)

sigstore is a project under CNCF umbrella that was "donated" to the foundation in March. It's main components as of right now are fulcio, rekor and cosign (more details on those a bit later) It's a collection of projects that aim to simplify software signing and transparency. Unlike other tools, with sigstore you don't need to manage private keys. You also don't have to understand ins-and-outs of security standards thanks to better UX. With all this it still provides all the required features of software signing.

## [AWS Identity service handles 400M API calls every second](https://aws.amazon.com/blogs/aws/happy-10th-birthday-aws-identity-and-access-management/)

Amazon S3 turned 15 earlier this year, and Amazon EC2 will do the same in a couple of months. Today we are celebrating the tenth birthday of AWS Identity and Access Management (IAM) Let’s take a walk through the last decade and revisit some of the most significant IAM launches. The launch set the standard for IAM, with fine-grained permissions for actions and resources, and the use of conditions to control when a policy is in effect. This model has scaled along with AWS, and remains central to IAM today.

## [5 and a Half Techniques for Effectively Writing Unit Tests in Go](https://betterprogramming.pub/5-and-a-half-techniques-for-effectively-writing-unit-tests-in-go-1b87b94abd21)

5 and a Half Techniques for Effectively Writing Unit Tests in Go.Techniques that help me having zero bugs on production, for 2 years Marko Milojevic. Unit testing was always my thing—kind of like a hobby. There was a time when I was obsessed with it. It was just important to make sure those tests are green in the end. I often did not even check the complete running(micro)service — it was enough to have green new and old unit tests.

## [🚀10 Trending projects on GitHub for web developers - 13th August 2021](https://dev.to/iainfreestone/10-trending-projects-on-github-for-web-developers-13th-august-2021-4bf2)

Mitosis writes components once, run everywhere. Compiles to Vue, React, Solid, Angular, Svelte and Liquid. Little State Machine uses React Hooks to manage state by default. React Suite is designed and implemented for use on modern desktop browsers rather than mobile browsers. It is a well-thought-out and developer-friendly UI framework. React Suite supports the latest, stable releases of all major browsers and platforms. Support Next.js to build applications. Support server side rendering. Support React 16 +.

## [The Platform Engineer](https://engineering.razorpay.com/the-platform-engineer-db2b21434911)

Many engineers assume that Platform engineering is just about building common services that are shared between multiple teams or the team that automates infrastructure delivery. Razorpay is a FinTech platform dealing with billions of dollars of transactions a month. This post explores what attributes we believe are necessary for an engineer to be successful in a Platform team. Platform engineering works on creating long-term leverage for the organization by making it easier for other engineers to build products that create value for both the customers and the company. It is usually introduced when a company has reached a certain scale, either in traffic or people.

## [Introducing public builds for AWS CodeBuild](https://aws.amazon.com/blogs/devops/introducing-public-builds-for-aws-codebuild/)

Using AWS CodeBuild, you can now share both the logs and the artifacts produced by CodeBuild projects. This blog post explains how to configure an existing CodeBuild project to enable public builds. Public builds simplify the collaboration workflow for open source projects by allowing contributors to see the results of Continuous Integration (CI) tasks. When a pull request is created in the repository, CodeBuild will start a project build and provide commit status updates during the build with a link to the public build information. This link is available as a hyperlink from the commit status message.

## [A future for SQL on the web](https://jlongster.com/future-sql-web)

In all browsers except Chrome, IndexedDB is implemented using SQLite. This makes a massive difference for what kinds of apps you can write against it. absurd-sql is a persistent backend for SQLite on the web. It doesn’t have to load the whole db into memory, and writes persist. The only function it provides is count, and the rest of the APIs just return a range of items. It is the only option for something database-like that works across all browsers.

## [5 Advanced Features of AWS S3](https://betterprogramming.pub/5-advanced-features-of-aws-s3-that-are-hidden-from-developers-11a7f8f55975)

S3 is a place to drop files and access them when needed. It has various storage classes based on access patterns. S3 has an option to enable versioning for the bucket. Encryption in S3 means that all objects in buckets are being encrypted. CORS is an HTTP-header-based mechanism that allows a server to indicate any origins (domain, scheme, port) other than own from which it should allow loading of resources. It is possible to host static websites on S3.

## [A Kubernetes User's Guide to HashiCorp Nomad Secret Management](https://www.hashicorp.com/blog/a-kubernetes-user-s-guide-to-hashicorp-nomad-secret-management)

Kubernetes and HashiCorp Nomad are mature orchestrators used for managing the lifecycle of containerized applications. A secret, in this context, means any sensitive information that you want to tightly control access, such as API keys, passwords, OAuth tokens, certificates, and SSH keys. Learn how secrets management in Kubernetes compares to HashiCorp. Vault is a powerful solution for both. In this guide, we will compare the native secrets management functionality of Kubernetes to HashCorp Vault. The goal is to give you a centralized place to manage secrets using a common workflow.

## [Deno 1.13 Release](https://deno.com/blog/v1.13)

Deno 1.13 has been tagged and released with the following features and changes. The native HTTP server API in this release is now a stable API. The built-in server-side WebSocket support is still marked unstable, but available since 1.12 via the Deno.upgradeWebSocket() function. The HTML spec authors (thanks Surma) recently added a new self.structuredClone function. It exposes the structured clone algorithm used for message passing between web workers and MessagePort in a simple, idiomatic, and synchronous API.

## [Tecton Brings Real-Time Machine Learning to MLOps](https://thenewstack.io/tecton-brings-real-time-machine-learning-to-mlops/)

Tecton has launched low-latency streaming pipelines to its feature store for machine learning (ML) feature store. The feature store is the interface between data and the model, while the feature store handles a variety of tasks, from transforming and cleaning the data, to serving the features, to logging and monitoring the health of pipelines. The new feature store automates the process of transforming streaming and real-time data, including time aggregations, into ML features in less than one second. The innovation is not in the ability to do so without a large team of dedicated engineers and potentially weeks of lead time.

## [Allstar GitHub App – continuous security enforcement for GitHub projects](https://openssf.org/blog/2021/08/11/introducing-the-allstar-github-app/)

Allstar is a GitHub app that provides automated continuous enforcement of security best practices for GitHub projects. Owners can check for security policy adherence, set desired enforcement actions, and continuously enact those enforcements when triggered by a setting or file change in the organization or project repository. The continuous nature of the enforcement protects against stealthy attacks that human enforcement might not notice. Allstar will help the open source community proactively reduce security risk while adding as little friction as possible. It is a companion to Security Scorecards, an automated tool that assesses risk to a repository and its dependencies.