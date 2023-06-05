# DevOps / SRE - Top Links Last Week

## Week 5 - Issue #64

  

## [A Kubernetes Documentary Shares Google’s Open Source Story](https://thenewstack.io/a-kubernetes-documentary-shares-googles-open-source-story/)

"Kubernetes: the Documentary's" is an hour-long documentary (split into two parts) collaborating with Red Hat, Google, and the Cloud Native Computing Foundation. The video "captures the story directly from the people who lived it," according to its description on YouTube. In addition, it features interviews with engineers and managers who built the software and made crucial decisions that enabled Kubernetes' growth. The CNCF's chief technology officer, Chris Aniszczyk, recalled that "It was a bit nerve-wracking having a film crew show up during the pandemic."

  

## [Automating quality checks for Kubernetes YAMLs](https://dev.to/wkrzywiec/automating-quality-checks-for-kubernetes-yamls-398)

This blog post will show how to create a simple, automated quality check of your K8s object definitions using Datree and Google Kubernetes Engine and Github Actions. The workflow will have two stages: analysis of missing configurations, quality check, and testing an example application in a real cluster (GKE) Datree analysis will stop the workflow if it finds any problems. It's essential to have a safety net like this so you can feel confident that an assistant will keep you on track even if you make a mistake or aren't aware of best practices.

  

## [Store Secrets in Repositories (Safely), and Deploy Them With Terraform](https://betterprogramming.pub/store-secrets-in-repositories-safely-and-deploy-them-with-terraform-aea79997d3a0)

Mozilla's SOPS is a tool developed and maintained by Mozilla. It lets us encrypt JSON and YAML files using different keys, like AWS KMS, GCP, age, and PGP. The tool was designed with simplicity in mind, and it comes with a CLI that you can use to encrypt and decrypt files. For the decryption, SOPS stores metadata in the created file itself and encrypts the values of the encrypted file. You can have more than one creation rule and different encryption keys for each one.

  

## [What Is Facter? A Comprehensive Guide to This Puppet Tool](https://www.cloudbees.com/blog/what-is-facter-puppet-tool)

Puppet is an open-source tool for managing today's complex business software environments. Instead of setting up dozens or hundreds of servers manually, Puppet automates the configuration of servers and services. Facter is a software tool that collects data about a Puppet node and reports it. Custom facts are built into Puppet and available as global variables, meaning you can use Facter facts to customize the way Puppet behaves. The data that Facter collects about a system is comprehensive and customizable, and customizable.

  

## [Measuring Gatsby projects build time using paid plans of popular static website hosting platforms](https://dev.to/alex_barashkov/measuring-gatsby-projects-build-time-using-paid-plans-of-popular-static-website-hosting-platforms-47pp)

Jamstack is showing rapid growth these days, bringing a new life for the concept of static sites generation. The platform could make a massive difference in build performance for developers, designers, and marketers since no one wants to wait hours to see the changes live. Gatsby Cloud did the job within two min., which is eight times faster than Netlify - 16.01$ per build minute. AWS Amplify has an option to persist cache between builds, but it does not work if your build lasts more than 15 minutes.

  

## [6 Reasons to use Feature Flags](https://betterprogramming.pub/6-reasons-to-use-feature-flags-e375ef0914c8)

Feature flags have been a secret weapon at FAANG companies for many years. They let development teams move faster, reduce the burden on DevOps and QA, and enable product teams to make better data-driven decisions. However, until recently, it was not feasible for smaller companies to fully adopt this practice due to the complexity of building and maintaining a custom feature management platform. Today, there are several good options for teams of all sizes to use feature flags. Here are six reasons you should be using feature flags in your code.

  

## [Four Ways to Improve Your AWS Lambda](https://betterprogramming.pub/four-ways-to-improve-your-aws-lambda-1cfd3a3115d6)

Here are four ways to improve the performance of your AWS Lambda function by polishing it. First, use X-Ray to inspect your code and trace your code to get to a faster and more scalable Function. Balance the cost and performance and balance the cost of execution. You can trace your code with X-Ray to see the cost per execution ratio (you can learn more from Casalboni's tool) and trace all non-AWS requests with the custom segment of your code. For example, the first invocation time is the same for all RAM tiers, and the invocation cost is increased per tier.

  

  

## [Introduction to Kubernetes: what problems does it solve?](https://medium.com/@studioalpha95/introduction-to-kubernetes-what-problems-does-it-solve-5d7b49b7db23?source=rss------docker-5)

Kubernetes is an open-source container orchestration platform for scheduling and automating containerized applications' deployment, management, and scaling. The primary node determines where to host applications (or Docker containers), decides how to put them together, and manages their orchestration. By grouping containers that make up an application into clusters, Kubernetes facilitates service discovery and enables the management of high volumes of containers throughout their lifecycles. The kubectl command-line tool lets you control Kubernetes clusters.

  

## [A Primer: Accessing Services in Kubernetes](https://blog.alexellis.io/primer-accessing-kubernetes-services/)

Kubernetes is an open-source marketplace for helm charts, apps, and DevOps CLIs. Port-forwarding tends to be the lowest common denominator, seamlessly working on any cloud or local distribution. You will almost always deploy an Ingress Controller for production and expose ports 80 and 443 via a managed LoadBalancer. The advantage here is that the LB will be like a cloud LB, publicly accessible in the cloud and accessible in any network since it uses an outgoing WebSocket, even on a captive WebSocket.

  

## [50+ Kubernetes Tools](https://jinlow.medium.com/50-kubernetes-tools-6acb01d0a876)

Since 2017, Kubernetes has dominated the container orchestration market. However, AWS has committed to K8s support and integration too. So I try to provide a comprehensive list of all K8S enhancements for your development efforts. The list includes tools that can help you create, destroy, upgrade, and maintain production-grade, highly available Kubernetes clusters from the command line. The K8s-test suite combines 2 Helm charts for network bandwidth testing and a single Kubernetes cluster load testing.

  

  

## [Running Redis at Scale — Redis Roadmap](https://betterprogramming.pub/running-redis-at-scale-redis-roadmap-607521db2a0f)

The self-documented Redis configuration file called "redis.conf" has been mentioned many times as an example of well-written documentation. It is possible to reconfigure a running Redis server without stopping or restarting it using the special commands CONFIG SET, and CONFIG GET. Redis can process new requests even if the client hasn't read the old responses. The data packets travel from the client to the server, or RTT is called network round trip time. A sound client library will offer some way of optimizing connection management by setting up a connection pool.

  

## [Precision in Technical Discussions](https://rtpg.co/2022/02/04/precision-in-technical-discussions.html)

It's ubiquitous for people to take shortcuts when describing the usage of a technical system. These statements can have multiple, slightly different meanings! Conversations quickly fall apart and end with people talking past each other. This can get even worse when using tooling with a sizeable specific vocabulary. The tooling might be at fault for "bad design decisions," but ultimately, if you're using it, you'll save yourself time to use exact words in the long run. Make sure the "Who" and "What" are being talked about; we can more quickly get to any sticking points.

  

## [Docking A Docker Container — Part 2 : Namespace, cgroup](https://blog.devgenius.io/docking-a-docker-container-part-2-c1206e7c6677)

Docker is not a virtual machine but processes with unique attributes running on the plain Linux kernel and more transparent than a virtual machine. Docker doesn't reside inside the grain, but 'namespace' and 'cgroups' do, and docker creates a cozy little environment called container using them. This is done by running the process inside 'containers' running UNIX processes in the docker container is like running them inside a virtual machine. This post talks about how you can create such an environment over Linux.

  

## [Certification in Cybersecurity](https://faun.pub/certification-in-cybersecurity-111c0c56c3bf)

Cybersecurity deals with the protection/security of internet-connected systems and devices such as the hardware, software, databases, etc., from cyber threats and cyberattacks. Cybersecurity is crucial as technology evolves and as digital methods take precedent. Organizations prefer well-versed candidates and have a complete understanding and knowledge of the subject, ensuring the organization can handle and maintain the organization's security aspects. Many certification courses are available online, which provides a complete guide to individuals who want to pursue a career.

  

## [Google Workspace goes all in on shadow IT](https://techcrunch.com/2022/02/03/google-workspace-goes-all-in-on-shadow-it/)

Google today announced a new version of Workspace, the company's productivity service that you probably still refer to as G Suite. With the latest free version, Google wants to bring more business users onto the platform by offering them the essential Workspace productivity tools — except for Gmail. The new free plan is essentially the existing entry-level Business Starter plan, but with a reduced storage quota of 15 GB (down from 30), Google is opening up a whole new world for shadow IT.

  

## [Stop doing progressive delivery manually - Use GitOps instead](https://www.weave.works/blog/stop-doing-progressive-delivery-manually-use-gitops-instead)

The term 'progressive delivery' was coined by James Governor of RedMonk to describe a set of practices such as canary releasing, blue-green deployments, A/B testing, and feature flagging. With progressive delivery, a new feature is a complete unit of work that can be deployed at any time. The benefits of progressive delivery include early feedback on any version of your application, reducing the risk of deploying new features and isolating and fixing potential problems with those features—progressive delivery results in better separation of concerns across development and ops teams.

  

## [Deploy Node.js application over Google Cloud with CI/CD](https://blog.bitsrc.io/deploy-node-js-application-over-google-cloud-with-ci-cd-36df0cc42231)

Deploy Node.js application over Google Cloud with CI/CD/CD. We will be deploying a containerized Node.JS application using Docker over Google Kubernetes Engine using Jenkins for CI (building pipelines to build, test, and upload image to Docker Hub) and ArgoCD with Helm for CD. It will sync up with our charts repo, pull images uploaded by Jenkins to Docker Hub, and apply changes to the GKE cluster infrastructure accordingly. Of course, this will work with any other application if you can write a Docker file.

  

## [Writing Serverless Business Logic With Hasura Actions and Azure Functions](https://betterprogramming.pub/writing-serverless-business-logic-with-hasura-actions-and-azure-functions-505c7c9f743b)

Using Hasura Actions and Microsoft's Azure Functions, you can write serverless business logic. This showcase shows you how to use the framework to write server-less code. You can find the code for the Azure Functions App of this showcase on my Github here. I will use .NET six and C# for this example; however, you can choose another language, of course. 

  

## [Moving Libraries to Deno: The Whys and Hows](https://itnext.io/moving-libraries-to-deno-the-whys-and-hows-58acd4a31f05)

Deno is a Node.js replacement shunning NPM, with built-in TypeScript and security through permission flags. I would argue that these are not even the main features of Deno. Opinions are my own and do not express the views of the rest of humanity. For the most part, the tools themselves are written in Rust and usually an order of magnitude faster than their JavaScript counterparts.

  

## [The Problem With Microservices](https://levelup.gitconnected.com/the-problem-with-microservices-2068f64c52e2)

What Are Microservices, When To Use them And What To Take Into Account? We discuss the benefits and problems to look out for when using a group of loosely coupled services that communicate between themselves to achieve business needs. There are various reasons you would use microservices, such as Improved Scalability, productivity, and Speed. However, microservices are harder to build and require, and adopting them without people who understand them or in smaller teams, may result in harmful consequences.

  

## [LogMeIn rebrands as GoTo, streamlines product portfolio](https://www.zdnet.com/article/logmein-rebrands-as-goto-streamlines-product-portfolio/)

LogMeIn, best known for its GoTo portfolio of products, is rebranding as GoTo. The company is attempting to simplify its product line, which falls into two categories: unified communications and collaboration and IT management and support. In addition, GoTo Resolve and GoTo Connect will be linked by a standard application and admin system, making operation easier for IT teams. The rebrand will be applied to all new GoTo products and rolled out in phases, beginning with the GoTo App.

  

## [Http Server Performance: NodeJS vs. Go](https://betterprogramming.pub/http-server-performance-nodejs-vs-go-397751e8d275)

NodeJS and Go are developing something like an ad proxy or Google Ad Buffer. Service forward ad HTTP requests to SSPs server. For this purpose, it's necessary to create many HTTP requests with minimum hardware resources. Therefore we decided to do research and compare programming languages with virtual machines. We started testing HTTP connection with the V8 engine with the NodeJS engine. We used the Fastify package to test performance. Requests per second: 12925 [\#/sec](#) (mean) time per request: 7.737 [ms](#) time (mean, across all concurrent requests) Percentage of the requests served within a particular time (ms)

  

## [A complete Prometheus based email monitoring system using docker compose](https://medium.com/@emileross/a-complete-prometheus-based-email-monitoring-system-using-docker-compose-acbd4cc3676a)

Open-source software Prometheus is an effective and reliable way of monitoring a software service like a web application. It will scan your service and notify you when it goes down. A convenient and reliable docker-compose script with complete components that runs a whole Prometheus monitoring system is included. The Compose file contains containers for Prometheus, Alertmanager, Mailhog (a test SMTP server), and some Python code acting as a target to monitor continuously.

  

  

## [When to Use Kubernetes, and When to Use Cloud Foundry](https://thenewstack.io/?p=21002226)

Julian Fischer, CEO of cloud-native services provider Anynines, talks about the benefits of Cloud Foundry and Kubernetes. We discuss the importance of a coherent data services strategy and GitOps. Finally, we spoke to Fischer about the best way to manage the two software platforms' large-scale deployments and when to use them. The podcast is available on Apple, Google, Spotify, Stitcher, TuneIn, and PlayerFM.

  

## [Demystifying Vault’s Secrets Management Solutions in Kubernetes](https://medium.com/hashicorp-engineering/demystifying-vaults-secrets-management-solutions-in-kubernetes-2b9e30a984be?source=rss------devops-5)

This article is not intended to be product documentation or a step-by-step implementation guide. Instead, it is designed for DevOps practitioners familiar with HashiCorp Vault and Kubernetes, who also have a basic understanding of secret management concepts. Secret management solutions, like Vault, have emerged to address the complexity of storing different types of secrets securely and provide a centralized, API-driven workflow to manage them across different environments. Typically, this is done by leveraging the native k8s secrets objects.

  

## [CI for APIs With the Kong Insomnia CLI and GitHub Actions](https://betterprogramming.pub/ci-for-apis-with-the-kong-insomnia-cli-and-github-actions-270eba79174d)

The Kong team has created a GitHub/workflows directory and a unit-tests.yml file. We want our test suite to be run on every new pull request. Using the npm packages wait-on and concurrently, we use this script to start our server, run the API tests, and then kill the server once the tests finish. The workflow is triggered whenever code is pushed, or a pull request is created against a branch. We can test that everything is working correctly by making a small pull request in our repo.

  

## [Cycloid Tackles DevOps for Hybrid Clouds](https://thenewstack.io/cycloid-tackles-devops-for-hybrid-clouds/)

Benjamin Brial created the Paris-based Cycloid in 2015 to help organizations smooth the path between dev and ops teams and enhance DevOps skills with the employees they already have. The Cycloid platform consists of a service catalog where the DevOps professional define the infrastructure for various environments and the governance applied to workloads on those sites. It enables self-service for developers to deploy to those sites, though they don't have to understand all the nitty-gritty details underneath those deployments. The biggest hurdles to DevOps adoption continue to be cultural more than technical.

  

## [How to Clone a Jenkins Job: The Definitive Guide](https://www.cloudbees.com/blog/how-to-clone-a-jenkins-job-the-definitive-guide)

Jenkins jobs are the basic building blocks in your continuous integration/continuous deployment (CI/CD) pipelines. It's easier to create basic job templates and copy, or "clone," them when necessary than it is to create new ones from scratch. In this post, we'll look at different types of Jenkins jobs, explore how to clone them, and discuss a few situations where cloning jobs will make your life easier. For example, a Freestyle job can execute Windows batch or Linux shell commands.

  

  

## [Writing Better Release Notes](https://simonwillison.net/2022/Jan/31/release-notes/)

Release notes are an essential part of the open-source process. The date matters a lot because I want to determine how old a release is. Make sure people can link to the release notes for a version. Use the GitHub API to show links to my most recent releases on the Datasette homepage and my personal GitHub profile. Annotated release notes accompany the official release notes. I like the GitHub releases and GitHub Actions feature, and they integrate well with GitHub Actions. I've not yet got an excellent feel for writing them for other projects, but I recommend them for your project.

  

## [Docker vs. Kubernetes](https://medium.com/@studioalpha95/docker-vs-kubernetes-37a2da0648fc?source=rss------docker-5)

Docker is an open-source containerization platform that makes it easier, safer, and faster for developers to build, deploy and manage containers. Docker is backed by a vibrant developer community that shares thousands of containers across the internet via the Docker Hub. Docker has its orchestration tool, Docker Swarm, but the most popular and robust option is Kubernetes. The process begins with a script of instructions, called a Dockerfile, which outlines how to create a Docker image and automatically executes the outlined commands. Containers represent portable, run-time environments that you can quickly startup.

  

## [OpenSSF Announces The Alpha-Omega Project to Improve Software Supply Chain Security for 10,000 OSS Projects](https://openssf.org/press-release/2022/02/01/openssf-announces-the-alpha-omega-project-to-improve-software-supply-chain-security-for-10000-oss-projects/)

Microsoft and Google support the Alpha-Omega Project with an initial investment of $5 million. The project will improve global OSS supply chain security by working with project maintainers to systematically look for new, as-yet-undiscovered vulnerabilities in open source code and get them fixed. Alpha will identify at least 10,000 widely deployed OSS projects to apply automated security analysis, scoring, and remediation guidance in the maintainer communities. In addition, project members will provide tailored help to understand and address security gaps.

  

_Datree are sponsors of the phpops project_