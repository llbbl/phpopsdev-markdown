# DevOps / SRE — Top Links Last Week

## Week 21 Issue #28

## [Four steps to jumpstarting your SRE practice](https://cloud.google.com/blog/products/devops-sre/four-steps-to-jumpstarting-your-sre-practice/)

Site Reliability Engineering (SRE) is the first step to implementing SRE in an organization. It's crucial to select an application that is critical to the business. Pick an application in which the business is actively investing resources. Set realistic goals and set realistic expectations early on. Empower your teams with a learning culture and training them, i.e., in regards to knowledge, as well as empowering them. For example, higher leadership's training will look very different from practitioners’ training.

## [The cost of cloud, a trillion dollar paradox](https://a16z.com/2021/05/27/cost-of-cloud-paradox-market-cap-cloud-lifecycle-scale-growth-repatriation-optimization/)

The excess cost of cloud weighs heavily on market cap by driving lower profit margins. Dropbox detailed in its S-1 a whopping $75M in cumulative savings over the two years prior to IPO due to their infrastructure optimization overhaul. An estimated $100B of market value is being lost among 50 of the top public software companies currently utilizing cloud infrastructure, according to the authors of this post. The authors say that when you factor in the impact to market cap in addition to near term savings, scaling companies can justify nearly any level of work that will help keep cloud costs low.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Open-source tools you should be aware of to manage your cloud](https://kumomind.medium.com/open-source-tools-you-should-be-aware-of-to-manage-your-cloud-305a42fdb490)

In the cloud, it is obviously better to rely on cloud services offered by the provider, but sometimes it is better to use open-source projects to facilitate the management. This article is not dedicated to only one cloud provider, the idea is to list tools that can be used on one or multiple clouds to help in the management of the resources and sometimes, optimize the infrastructure. The command line is probably something everyone used once in their life, and sometimes it can be hard to understand how to use it.

## [Asynchronous Messaging Patterns for Microservices](https://aws.plainenglish.io/asynchronous-messaging-patterns-for-microservices-ecc99c0074bc)

There’s a sender and a receiver, there can be two dedicated message channels for request and response channels. Queue acts as a load balancer in front of the receiver, which means every message from the queue is delivered to one of the receivers. Publish-subscribe model means every subscriber will receive every message. Messages do not need to be consumed right away, the queue can flatten a peak load for the receiver. Queue can persist messages. We can also safely take receiver processes offline for maintenance work, and no danger of losing messages.

## [Reduce Kubernetes Costs Using Autoscaling Mechanisms](https://thenewstack.io/reduce-kubernetes-costs-using-autoscaling-mechanisms/)

Kubernetes comes with three built-in autoscaling mechanisms to help you do that. Horizontal Pod Autoscaler (HPA) monitors pods to understand whether the number of pod replicas needs to change. Vertical Pod AutoCaler (VPA) increases and reduces the CPU and memory resource requests of pod containers to align the allocated cluster resources with actual usage. HPA makes scaling decisions based on the observed CPU utilization values of pods, a percentage of resource requests from individual pods. VPA replaces pods that are managed by a replication controller.

## [Container Adoption Trends & Best Practices: The DevGraph Webinar Series](https://blog.engineyard.com/container-adoption-trends-best-practices-the-devgraph-webinar-series?utm_source=Medium&utm_medium=Devgraph-channel)

The panel on the latest DevGraph webinar had a lively and informative discussion regarding container adoption trends and best practices. The panel consisted of: James Rutt (Moderator): Chief Information Officer, The Dana Foundation CEO Andriy Zhylenko: CEO Portaone; Valentina Alaria: Director of Product Management, VMWare; Rahul Subramaniam: CEO DevFactory, EngineYard; Mark Hahn: Directory of Cloud Strategies and Devops, Ciber Global.

## [How 1 Change Decreased Clone Times on CI/CD Pipelines by 90%](https://blog.devgenius.io/how-1-change-decreased-clone-times-on-ci-cd-pipelines-by-90-464a42f680dd)

CI/CD pipeline helps you automate steps in your software delivery process, such as initiating code builds, running automated tests, and deploying to a staging or production environment. The tool we use for static analysis is Bitrise, we use Github actions, in Bitrise we define our own workflow which has various steps like Git clone, static analysis, UI testing, and pushing the build to hockey. We have a workflow for Github actions that does lint checks and other tasks like Unit testing and generating various reports.

## [How to setup Github Actions for PHP/Lumen+ MySQL to run automated tests](https://medium.com/@obichukwusmum/how-to-setup-github-actions-for-php-lumen-mysql-to-run-automated-tests-96071b78afb2)

The first step is to create a workflow file in your project’s root directory. Make sure you are in the root directory before running the following commands. The service env you provide will be used to set up a mysql image running inside a Docker container. The last thing you need to do to get this completely set up is create a database configuration file in the. root of your project (if you don’t already have that) It uses the database.config/database.php file in a config/database.php file.

## [Setting up Airflow on AWS EKS](https://manojbalaji1.medium.com/setting-up-airflow-on-aws-eks-385667671789)

We need to add the repo and update the helm repo to install Airflow on the Kubernetes cluster. Airflow uses a Postgres database, persistent volume to store dags code and logs, Redis database, and other components. It is recommended to use Postgres instead of MySQL for Airflow. The default username and password are admin and admin respectively. This might take some time, so please be patient, so be patient. We need the keep our AWS RDS Postgres Postgres password as a kubernetes-secret.

## [How DevOps Sites Are Battling Cryptocurrency Miners](https://thenewstack.io/how-devops-sites-are-battling-cryptocurrency-miners/)

GitLab, Microsoft, TravisCI, LayerCI, CircleCI, Render, CloudBees CodeShip, Sourcehut, and Okteto. GitLab and GitHub are among the biggest DevOps platforms to report cryptocurrency mining attacks. Microsoft’s Azure Pipelines even ended its free pipelines for new CI/CD projects in February, complaining that abuse, especially cryptocurrency miners, “has gotten substantially worse,” a Microsoft blog post said in February. Now GitLab is changing its policy to require users to provide a valid credit or debit card number.

## [Building an AWS EKS Cluster with Terraform Cloud](https://aws.plainenglish.io/building-an-aws-eks-cluster-with-terraform-cloud-53f6e20603ce)

Use Terraform modules to provision an EKS cluster with scalable, highly available, and fault-tolerant supporting architecture. Prerequisites are accounts and administrative-level credentials for Terraform Cloud, GitHub, AWS, and the AWS CLI; a Terraform-friendly IDE such as VS Code or PyCharm; and kubectl and wget. We will use Terraform to build two AWS solutions with modules: a VPC with public and private subnets, both with autoscaling groups of EC2 instances, and a load balancer for the private subnet.

## [Automated API Testing Using Postman](https://rameshwari-fegade19.medium.com/automated-api-testing-using-postman-b83dae0bad50)

API testing could be a set of quality assurance actions that embody causation calls to the API, obtaining output, and substantiating the system’s response against the outlined input parameters. Postman is a superb API testing tool for developers, QA testers and penetration testers. The approach to API testing for the most part depends on the API kind. There are net services, info genus APIs that connect applications with decibel management systems, operational systems genus APIs, and remote APIs for accessing resources set outside the device requesting them.

## [How To Track Job Applications With Notion API, Node.js and FastifyJS](https://catalins.tech/track-job-applications-with-notion-api-nodejs-and-fastifyjs)

Notion is a productivity software that allows you to create systems for knowledge management, project management and note-taking. They recently released their API to the public. You can use the API to integrate your Notion data to any application you want. This article shows you how to use the Notion API in your Node.js application. It's important to leave "Internal integration" checked, as you can see in figure 1 above. The next step is to share whatever page you wish with the newly-created integration.

## [AWS Delivers on Amazon ECS Everywhere Promise](https://containerjournal.com/topics/container-management/aws-delivers-on-amazon-ecs-everywhere-promise/)

Amazon Web Services has made generally available an instance of the Amazon Elastic Container Service (ECS) that can run in on-premises IT environments. Amazon ECS Anywhere extends an AWS effort to, in effect, become the DevOps team for deploying applications. More than 100,000 customers continue to use the service, which until now was available only on the AWS public cloud. AWS plans to follow up this offering with a similar instance of its alternative managed Kubernetes services that can be deployed anywhere.

## [Starter Guide & “Things I wish I knew before” for AWS Lambda](https://tpschmidt.com/starter-guide-things-i-wish-i-knew-before-for-aws-lambda-fe36ce2fd4cb)

There are a lot of benefits, but also trade-offs that should be considered before building your architecture solely around Lambda. This article provides you some guidance & hopefully reduces the chances of going wrong at some crossroads for your next project. There’s a lot on both sides: scalability out-of-the-box, agility and development speed. The grass is always greener on the other side: AWS evolves its services blazing-fast, limitations and other details can be already outdated.

## [Announcing CDK for Terraform 0.4](https://www.hashicorp.com/blog/announcing-cdk-for-terraform-0-4)

CDK for Terraform provides the ability to write Terraform configurations in C#, Python, TypeScript, and TypeScript. The Go language has been one of the top requests from users for Go language support. New asset construct makes it easy to reference files and folders that need to be deployed alongside newly provisioned resources. Improved Terraform Cloud integration: Output from Terraform cloud is streamed rather than displayed at the end of the run. You can download the new release by following the getting started guide in the programming language of your choice.

## [Introducing Argo Rollouts v1.0](https://blog.argoproj.io/introducing-argo-rollouts-v1-0-803e87f76ef7)

Intuit was in the midst of transitioning hundreds of services from traditional VMs onto Kubernetes in 2019. Intuit is now using Argo Rollouts to deploy new versions of its QuickBooks and TurboTax products. The project has been in production use for a few years by many of Intuit’s users and has been powering critical flagship services including QuickBooks. The Argo maintainers are proud to announce Argo rollouts v1.0. A new rollout dashboard is available in the kubectl argo rollouts plugin, with more details about what is happening during an update.

## [Understanding Software Architecture: A Complete Guide](https://sarrahpitaliya.medium.com/understanding-software-architecture-a-complete-guide-cb8f05900603)

A robust foundation is a key for developing innovative and sophisticated software that proves to be a product-market fit and solves problems for users. Software architecture refers to the highest-level framework, the skeleton of the software system. It’s one of the very first choices made for the bedrock of the system. That choice can significantly influence the flow of work, quality of the code, maintenance, deployment, and ease of development. An organized system architecture design helps in maintaining the internal quality that further improves the software.

## [Modern Full-Stack Serverless, Part II](https://dev.to/aws-builders/modern-full-stack-serverless-part-ii-94i)

At the core of many serverless applications are serverless functions. Serverless functions run your code in stateless compute containers that are event-driven, short-lived (may last for one invocation), and fully managed by the cloud provider of your choice. There are two main ways of creating APIs with Amplify: API Gateway and Lambda function. Using the Amplify CLI, you can create both the API Gateway endpoints as well as Lambda functions. These functions scale seamlessly and do not require any server operations.

## [Should we rebrand REST?](https://kieranpotts.com/rebranding-rest/)

In this blogpost I argue the case for consigning the term "REST API" to history. In its place we should adopt the terms "HTTP API" and "hypermedia API", which better differentiate two distinctive designs for the programmatic interfaces of web services. Despite being so revered, REST is widely and wildly misunderstood and misrepresented. A system that implements the REST architectural style is said to be said to have a 'RESTful' architecture. The design constraints for a RESTful system include stateless interactions between client and server.

## [Tree-Shaking: A Reference Guide](https://www.smashingmagazine.com/2021/05/tree-shaking-reference-guide/)

Tree-Shaking is a must-have performance optimization when bundling JavaScript. In this article, we dive deeper on how exactly it works and how specs and practice intertwine to make bundles leaner and more performant. Tree-shaking has been possible since the ECMAScript module (ESM) specification in ES2015, previously known as ES6. The term was first popularized in the front-end community by the Rollup team. The idea of a tree-shake algorithm can be traced back to at least the early 1990s.

## [Set Up a Highly Available WordPress Site Using Elastic Beanstalk + RDS](https://tracipotocnik.medium.com/set-up-a-highly-available-wordpress-site-using-elastic-beanstalk-rds-58ddba04d293)

The steps below outline exactly how to run a high traffic, mission critical site on WordPress…it is! I have used this setup to host a virtual event website which required a logged-in, non-cacheable experience built on WordPress for 150,000+ simultaneous users. Using those site sizes as the base, combined with EBS autoscaling, the website stayed up as our users started to register, log in, and engage with the site all at the same time. The following instructions will get you well on your way to building a highly available WordPress site on AWS.

## [Low-Code Development: A Blast From the Past](https://betterprogramming.pub/low-code-history-b756c095494f)

Low-code development platforms trace their roots back to Fourth-Generation Programming Language (4GL) 4GL is a concept that was developed from the 1970s through the 1990s, overlapping most of the development of 3GL. Rapid Application Development (RAD) gained momentum in 1990s when the concept of visually “assemble’s desktop applications by using tools like Visual Basic, Delphi, and Oracle Forms became popular. Mobile platforms emerged in 2007 as a renaissance to desktop applications on mobile devices.

## [Stop looking for silver bullets](https://josebiro.medium.com/stop-looking-for-silver-bullets-14be33391c03)

The term “cargo cult’s” comes from World War II. It means to adopt the rituals of a different culture or society in hopes of achieving a specific end without understanding the reasons those behaviors achieve those ends. The more companies I observe, the more I’m convinced cargo culting happens everywhere in the organizational chain. The underlying premise of the DORA State of DevOps reports is that company culture is a strong indicator of organizational performance. People need to understand new processes, be equipped with the proper skills to master those skills.

## [Sample CI/CD pipeline using AWS CodePipeline](https://dev.to/aws-builders/sample-ci-cd-pipeline-using-aws-codepipeline-47kh)

An AWS CI/CD pipeline automates the basic phases of continuous integration and delivery/deployment. CodePipeline will be triggered through GitHub Webhook as soon as developer pushes code in respective branches or code merge happens. CodeBuild will test/build the code based on the configuration in buildspec.yml. CodeDeploy will retrieve artifact and deploy in EC2 instance based on instructions mentioned in appspec.yml All the artifacts will be saved and retrieved in/from Amazon Simple Storage Service (S3) CloudWatch will take care of Logs, Events, Alerts, Metrics etc. Email will be sent for success/failure status.

## [Everything About AWS CDK](https://aws.plainenglish.io/everything-about-aws-cdk-94bbfc6fb35f)

Infrastructure as code is the process of managing and provisioning computer data centers through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools. The AWS Cloud Development Kit (AWS CDK) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation. Using the CDK’s library of infrastructure constructs, you can easily encapsulate AWS best practices in your infrastructure definition and share it without worrying about boilerplate logic.

## [Git Workflow for Professionals](https://itnext.io/git-workflow-for-professionals-7495c3474ebd)

Linus Torvalds created the most popular SCM (Source Control Management) tool since it’s launch in 2005. Git is a Source Control Management tool which helps team members to work on the same source code, simultaneously, with minimal conflicts. This article will detail out how the team can work together and resolve conflicts during merge. We will be using GitHub and GitHub Desktop for managing our repository. We need to first login to GitHub Desktop with our GitHub account to use Git.