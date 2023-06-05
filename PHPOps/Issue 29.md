# DevOps / SRE — Top Links Last Week

## Week 22 Issue #29

## [Microservices — Things to consider for designing and monitoring microservices](https://faun.pub/microservices-things-to-consider-for-designing-and-monitoring-microservices-75aba01d39bf)

This write up is not about how to implement microservices. It’s more about what we need to consider when designing microservices architecture and when they are in use. We need to broadly agree on what microservices are. We should not be trying to answer the question of switching to microservices as a starting point, it should be about what are the problems we are trying to solve? Is microservices a good fit for a given project considering its team size and communication requirements? Is the team ready to adapt to some coding and database design changes that are always the by-product of microservices design?

## [Terraform Best Practices — Hold your state file remotely, not on your local machine](https://faun.pub/terraform-best-practices-hold-your-state-file-remotely-not-on-your-local-machine-502cd14ae76)

The Terraform ‘state’ file is a state file that maps the current status of your infrastructure with your configuration files. It is commonly stored either on a local machine, in a remote storage location (like a storage account in Azure, or S3 bucket in AWS), or in Terraform cloud. The state file can include sensitive values in plain text, and so it is recommended it is always stored on media that is encrypted-at-rest. The best practice is never to store the state file on your local machine.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Cron jobs in Node.js](https://medium.com/geekculture/cron-jobs-in-node-js-8df170445588)

The list of cron jobs use-cases is enormous: cache invalidation, reports generation, refreshing data from external sources, notifications, backups etc. Today we’ll walk through several scheduled tasks implementations from development and infrastructure perspectives. We’re still using the format developed in the 70s, it’s not intuitive at all, but don’t be afraid of it, there’ve a lot of tools, which translate asterisks, slashes and numbers to human readable format.

## [The SaaS CTO Security Checklist Redux](https://www.goldfiglabs.com/guide/saas-cto-security-checklist/)

This third edition of the SaaS CTO Security Checklist provides actionable security best practices CTOs can use to harden their security. This list is far from exhaustive, incomplete by nature since the security you need depends on your company, product, and assets. Onboarding and offboarding are important security moments for your new employees. Require everyone to use 2-factor authentication wherever possible. Encrypt all employee laptops & phones now by encrypting all laptops and your employee’s private files.

## [Microservice Architecture](https://chamalwr.medium.com/microservice-architecture-1ac57a5445cc)

Microservices is a software architecture that enables to development of larger software in a modular approach. These modules in Microservices are called “Services” These modules are called "Services" Microservices can work independently without having to depend on other services. Services of the microservice application have zero dependencies with other services when it comes to the deployment which makes it possible to independently deployable separate components without affecting or taking down the entire system offline. This helps the business processes run smoothly and fewer people intervention due to the automation of tasks.

## [This Week in Programming: Google Gets into the Open Source Insights Game](https://thenewstack.io/this-week-in-programming-google-gets-into-the-open-source-insights-game/)

Google has launched an experimental visualization tool called Open Source Insights. The tool gives users an interactive view of the dependency graph of open source software projects. Stack Overflow announced this week that it had been acquired by Prosus. DockerCon 2021 was a busy one for virtual conferences, with DockerCon running at the same time as Microsoft Build. The company says it is more so trying to lay everything out in a way that developers can see, visually, just how, well, screwed they really are.

## [Developers Share 10 Ways to Prevent and Manage Technical Debt](https://medium.com/geekculture/developers-share-10-ways-to-prevent-and-manage-technical-debt-1a0a5c8cb906)

Developers Share 10 Ways to Prevent and Manage Technical Debt. We put out a call out for real-world experiences of what helps when it comes to reducing technical debt. Here’s what they had to say about how to manage and prevent it: Treat technological debt as a tool rather than a scourge. Product owners can help prevent technical debt and manage it better than anyone else. Product Owners can aid in the prevention of technical debt, and can aid the prevention in preventing and managing it.

## [9 Questions Every CTO Must Ask Before Adopting Kubernetes](https://thechief.io/c/editorial/9-questions-every-cto-must-ask-before-adopting-kubernetes/)

The popularity and hype around Kubernetes in recent times has made it look as if you can't run your containerized applications on the cloud without it. This is not necessarily true, and it depends on the state of your organization and the applications you deploy. We will discuss some of the questions you need to ask as the CEO, CIO, or CTO of an organization on whether or not you should start using it in your organization. The ability to roll out new features and get them to market quickly is one of the benefits of the technology.

## [The Query Your Database Can’t Answer](https://www.confluent.io/blog/ksqldb-streaming-sql-the-query-your-database-cant-answer/)

Many databases are linked by one common trait: They exclusively query data at rest. When you issue a query, the database executes it by scanning the data and returning the result. The problem is that this architecture inherently puts some queries out of reach. Databases hide all the underlying complexity of query execution, indexing, concurrency control, crash recovery, replication, and so on. Confluent has been working on a new kind of database named ksqlDB that tries to do exactly that. It helps you both query your data and react to changes.

## [Most Popular Lens Extensions: June 2021](https://medium.com/k8slens/most-popular-lens-extensions-june-2021-8f88ef79aab6)

In December 2020, we launched Lens 4.0 — a release that allows extensions to plug in directly to the Lens UI, add visualizations, functionality and integrate with technologies and services around Kubernetes. We want to showcase the most popular publicly available extensions built by the Lens community. Lens Extensions are developed in TypeScript and packaged as NPM packages. The community includes well known brands from the cloud native ecosystem, as well as individual contributors. We have also been lucky to partner with some incredible partner organizations.

## [A new ProtoBuf generator for Go](https://vitess.io/blog/2021-06-03-a-new-protobuf-generator-for-go/)

Vitess has been using the Go Protocol Buffers package since its earliest releases. The main interface between applications and a Vitess database is through the MySQL protocol. Vitess is a large and complex distributed system, and all the communication between the different services in Vitess cluster is performed through GRPC. The upgrade didn't go without its hiccups, but we managed to get Vitess working with the new API and the test suite fully green after a couple of weeks of effort. The Gogo ProtoBuf project is currently unmaintained and actively looking for new ownership.

## [Terraform: Deploy A Three-Tier Architecture in AWS](https://aws.plainenglish.io/terraform-deploying-a-three-tier-architecture-in-aws-4c8ecce40790)

Infrastructure as Code (IaC) is a tool for building, changing, and versioning infrastructure that has an open-source and enterprise version. Terraform is cloud agnostic and can be used to create multi-cloud infrastructure. It allows you to provision and configure your environments in a reliable and safe way. By using code to deploy your infrastructure you gain the ability to use the same tools as developers such as version control, testing, code reviews, and CI/CD. The best practice would be to use variables and modules rather than using a single file and hard coding.

## [Cloud Cost Optimization Solutions](https://aws.plainenglish.io/cloud-cost-optimization-solutions-for-aws-azure-gcp-and-many-more-9544577cf8f2)

Cloud Cost Optimization Solutions provide more stability, flexibility, and security while reducing expenses in comparison with conventional systems. Cloud services provide infinite scalability and minimum IT costs just by billing your resources. However, even if you use all the resources assigned, cloud services charge you depending on the ordered resources. The process of reducing an organization’s total cloud costs might be called the optimization of the cloud costs. Here, a solution for cloud cost optimization might be useful so that your chores may be automated and your cloud expenditure saved.

## [What are Front End Service layers?](https://itnext.io/what-are-front-end-service-layers-4dba95db21bb)

The Front End Services layer is a tier that sits below the styling rules and components. Front Ends need to be able to make API or GraphQL queries, requesting data from the Back End, and pushing data to the Front End. Front End programming teams will usually split responsibilities, with developers who are more suited to styling and component design working more closely with the designers, and working with Back End teams. In a complex project, you need more UI developers than Front End services developers. The skills needed to make an app look the way the Design and UX specialists have envisioned are quite different to efficiently model interactions between users, data, and Back End services.

## [CI/CD Pipeline setup using GitHub Actions and AWS](https://ninuvarghese.medium.com/ci-cd-pipeline-setup-using-github-actions-and-aws-252116451a1b)

This tutorial assumes you are familiar with git commands, npm, AWS and you have a working React app that is ready to be deployed. The goal of setting up the CI/CD pipeline is to deploy your React app to AWS S3 everytime a commit is made to the master branch. To implement the pipeline, we’re going to be making use of something called GitHub actions. We are going to trigger an action whenever a change happens to our folder of our master/main (your primary branch)

## [[AWS] ECS vs EKS — What’s the Right Choice?](https://tonylixu.medium.com/aws-ecs-vs-eks-whats-the-right-choice-7f2d3af8eece)

Amazon Elastic Container Service (Amazon ECS) and Amazon Elastic Kubernetes Service are two fully managed container services. Amazon ECS is built to perform at scale, offers high availability and security, and is deeply integrated with a variety of AWS services, including Elastic Load Balancing, Amazon VPC, AWS IAM, and etc. Both services support a broad array of compute options, have deep integration with other AWS services. With ECS, users pay for AWS resources you create to store and run applications, and there are no additional pricing concerns.

## [Has DevOps killed the BA/QA/DBA Roles?](https://towardsdatascience.com/has-devops-killed-the-ba-qa-dba-roles-fbc187abdde)

The Business Analyst is a hybrid role between users and the technical team (ie. developers) Business analysts are responsible for bridging the gap between IT and the business using data analytics to assess processes, determine requirements and deliver data-driven recommendations and reports to executives and stakeholders. According to the Bureau of Labor Statistics, the BA job outlook over the next 10 years is projected to grow 11%. Despite such growth, many developers consider the BA role outmoded and largely superfluous after the DevOps renaissance.

## [How to never type passwords when using Git](https://dev.to/github/how-to-never-type-passwords-when-using-git-18bb)

There are a few ways to authenticate using Git and GitHub to ensure your code is secure. Using a client manager such as Git Credential Manager Core (GCM Core) is one way to do single-factor authentication on Linux and MacOS. You can also authenticate various applications such as editors like VS Code or Atom or other git clients like Git Kraken. If you want to try a few things other than the command line or webpage, you can authenticate with GitHub Desktop or GitHub's own command line.

## [IaC using Terraform to AWS — From nothing to something](https://faun.pub/iac-using-terraform-to-aws-from-nothing-to-something-f1ef3e51813f)

Provisioners are divided into two groups called creation-time and destroy-time provisioners. All provisioners are used to execute commands in the host machine where terraform is being run. The missing one is the file provisioner used to copy files and such from host to remote and vice-versa. We can also modify what the provisioner does on failure. We need to always carry around our tfs to every folder and create duplicates. We won’t need to do so with our central_modules folder the central_ modules folder.