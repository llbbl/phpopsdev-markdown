# DevOps / SRE — Top Links Last Week

## Week 29 Issue #36

## [Why You Need Kubernetes](https://medium.com/codex/why-you-need-kubernetes-511eb4948bf2)

The trick is, you have to understand Docker before learning Kubernetes. Docker is used to run multiple instances of the same application on one computer. We can run python 2 and 3 on one. computer in an isolated mode. The problem with Docker is limited to one computer, we can not run the multiple instances. of the application across the cluster. We need a container orchestration tool that is called Kubernetes. The real-time use cases of the tool include an online shopping application and a web application.

## [Upgrade Helm if You Don’t Want to Share Your Username and Password](https://thenewstack.io/upgrade-helm-if-you-dont-want-to-share-your-username-and-password/)

Helm, Kubernetes’ package manager, has been hit with a new security bug in Helm 3.61. A Helm chart repository includes an index.yaml that can contain a reference where to get the chart archive for each version of a chart. The username and password were passed to the URL location of the Helm repository by default. This occurs when Helm went to retrieve a specific chart archive on the other domain. The –pass-credentials flag restores the old behavior for a single Helm repository as an opt-in behavior.

---

_Please consider supporting the Weekly DevOps / SRE Report. Subscribe to our free [Newsletter](https://www.phpops.dev/subscribe/#/portal/signup) on our website!_

---

## [Top 10 AIops platforms](https://www.cio.com/article/3625580/top-aiops-platforms.html)

DevOps is a data-rich, back-office practice that presents a perfect sandbox for exploring the power of artificial intelligence. The tools and platforms on offer under the acronym AIops promise to apply the best artificial intelligence algorithms to the work of maintaining IT infrastructure. AIops tools generate forward-looking guesses about machine load and then watch to see if anything deviates from these estimates. Anomalies might be turned into alerts that generate emails, Slack posts, or, if the deviation is large enough, pager messages.

## [Infrastructure as Code with AWS](https://ram-vegiraju.medium.com/infrastructure-as-code-with-aws-207239573de)

Infrastructure as Code (IaC) is a key DevOps concept that is essential in the Data Science world. This enables developers to easily maintain and configure changes within a project’s resources and architecture. In this article we’ll explore an example of manually provisioning resources vs deploying a CloudFormation script to create a REST API and a serverless Lambda function on AWS. The first step will detail how to manually build and deploy these resources through the AWS console, while the second step walks through using Cloudformation to automate the exact same process.

## [This Week in Programming: Kubernetes from Day One?](https://thenewstack.io/this-week-in-programming-kubernetes-from-day-one/)

StackOverflow has put out a blog post this week arguing for why you should build on Kubernetes from day one. The post argues that the effort to set up and run the system is less than you think. The effort it would take to refactor your app later on to support containerization, the post says. Another blog post from recent weeks also comes to light on the complexity and complexity of the container orchestration system. And, another, another argues that it will eventually be replaced by something simpler: the Unix of distributed operating systems.

## [DevOps Observability from Code to Cloud](https://thenewstack.io/devops-observability-from-code-to-cloud/)

Pavan Belagatti is one of the pioneers in the field of growth hacking in India, he is also a DevOps influencer and a Google certified digital marketer. He has written over 100 articles alone on the topic of DevOps. He says monitoring and observability have taken the prime spots in the cloud native space today. In the age of waterfall software development, nobody knew what others were doing in the software development life cycle. This made companies have less visibility over their own infrastructure.

```
Modern software delivery practices have evolved over time. We have things like [GitOps](https://jfrog.com/user-conference/modernizing-ops-with-gitops/), AIOps, DataOps, etc., that enterprises employ and experiment to see which one fits well to their needs. It is not just about being agile or speedy these days; companies focus more on the stability of the infrastructure.
```

## [Approaching Infrastructure As Code With Terraform — Part 1](https://samuelarogbonlo.medium.com/approaching-infrastructure-as-code-with-terraform-part-1-86a62f63a00e)

Terraform is one of the greatest automation tools when it concerns managing and orchestrating architectures in the cloud. It has the ability to imbibe databases, CI/Cd and lots of other cool stuff that makes application architecture way easier to handle and manage. The syntax is “name of resource” “internal variable name”; the first part is given by AWS while the second is defined by the engineer. It is where you describe the vpc, subnets and other types of resources.

## [How to Create a Kubernetes Cluster and Launch WordPress with Database](https://aws.plainenglish.io/creating-a-kubernetes-cluster-and-launching-wordpress-with-database-9c2d2c0a23ae)

How to Create a Kubernetes Cluster and Launch WordPress with Database Harsh Goenka. Use Ansible and deploy a WordPress application with MySQL as a database. Create a cluster on AWS cloud with the help of Ansible. Deployment is exposed so that the outside world can connect to our pod. After everything run’s fine connect to WordPress with port no 31761 and master IP. After creating an account click install WordPress. Then update your key location inside ansible.cfg file to run wordpress.yml.

## [Kelsey Hightower, Canonical’s Mark Shuttleworth on the Linux Inflection Point](https://thenewstack.io/kelsey-hightower-canonicals-mark-shuttleworth-on-the-linux-inflection-point/)

The New Stack Makers podcast is hosted by Kelsey Hightower and Mark Shuttleworth. They discuss the role of Canonical's Ubuntu Linux distribution in the cloud native space and Kubernetes. The duo also discussed a recently released report from Canonical found that only 15.7% of respondents report using Kubernetes in production, and only 21.4% of the respondents manage more than 500 machines. The podcast is available on Apple, Google, Spotify, Stitcher, TuneIn and other platforms.

## [What is Docker? — Explained Simply](https://www.dottedsquirrel.com/docker-intro/)

Docker is a development platform and a virtualization technology that makes it easy for us to develop and deploy apps inside neatly packaged virtual containerized environments. A Docker container creates a little ring-fenced sandbox that makes sure that the environment and settings are the same everywhere. Docker containers can run on your computer or server and act like little ‘micro computers’ — each with specific jobs (i.e. hosted application/software) and their own operating system, their own. processes, processes, Memory, and Network. resources.

## [Deploying AWS Resources Using Terraform And Jenkins Pipeline](https://troy-ingram.medium.com/deploying-aws-resources-using-terraform-and-jenkins-pipeline-1c706f1a2e7c)

HashiCorp Terraform is a tool for building, changing, and versioning infrastructure that has an open-source and enterprise version. Jenkins Pipeline implements continuous deliver pipelines into Jenkins through use of plugins and a Jenkinsfile. Terraform can be used to create multi-cloud infrastructure as well as on-prem. Deploying infrastructure using Infrastructure as Code should only take approximately 3 minutes after applying the Terraform code to the infrastructure. The infrastructure is set up using Terraform and Jenkins Pipeline in the same way as AWS CloudFormation.

## [Kubernetes Installation Methods The Complete Guide](https://itnext.io/kubernetes-installation-methods-the-complete-guide-1036c860a2b3)

Kubernetes installation is one of the most challenging topics of the software. This challenge occurs because a multitude of installation methods exists. I divide these methods into five major types based on usage, ease of installation, and where to install. Single-node installation is suitable for testing, local development and CI systems. Manual cluster installation is used for deploying a minimum viable cluster for the first time. Automatic cluster installation can be done by using automation tools, scripts, or provider distributed installers.

## [Building a world class News aggregator on a coffee-a-day budget](https://medium.com/@wabz/building-a-world-class-news-aggregator-on-a-coffee-a-day-budget-c21aac8c5335)

An Australian news site and search engine is being used to index Australian news content. The site is built using vespa.ai, which is relatively unknown compared to elastic search/solr and co, but it’s extremely good and fits my requirements perfectly. Vespa is the search engine to use on mutable data sets with modern ranking methods. It is also the “augmenter” and “spiders” crawl news RSS feeds and sitemaps, looking for, visiting and scraping content.

## [Hands-on AWS Project Ideas for Beginners](https://sonsuzdesign.blog/2021/07/21/hands-on-projects-to-start-your-journey-with-amazon-web-services/)

Amazon Web Services was launched back in 2006 to provide cloud computing platforms. It provides you with services like compute power, content delivery, database storage, and other functionalities. These cloud computing solutions are secure, highly scalable, and cost-effective. Amazon Web Service Program is an initiative launched to assist aspirant developers. It manages and maintains infrastructure and hardware for you. One can avail himself of these resources for free or on a pay-per-use basis. Most of the projects are machine learning and artificial intelligence projects.

## [System Design — Choosing between AWS Lambda and AWS Fargate](https://iamkanikamodi.medium.com/system-design-choosing-between-aws-lambda-and-aws-fargate-d586f28da34)

AWS Lambda is an event-driven, serverless computing platform that is, it runs your code in response to events and automatically manages the underlying compute resources for you. Fargate makes it easy for you to focus on designing and building your applications instead of managing the infrastructure that runs them. The benefits and drawbacks of each system and which one to select based on your system design requirements are discussed in the Back with System Design Choices series, here are some next steps you can take.

## [Set up Amazon FSx for Lustre](https://aws.plainenglish.io/set-up-amazon-fsx-for-lustre-117033a133dd)

Amazon FSx for Lustre can transform an S3 bucket into a file system. FSx can be mounted as a folder on a EC2 instance. Users can run Linux-based applications on the files and FSx will synchronize the changes between S3 and the compute instance. For this tutorial and most small projects, the capacity of 1.2 TiB is enough for most projects. The journey starts with S3, and the journey begins with FSx, a free tutorial for Linux users.

## [Meet Package Hunter: A tool for detecting malicious code in your dependencies](https://about.gitlab.com/blog/2021/07/23/announcing-package-hunter/)

Package Hunter analyzes a program's dependencies for malicious code and other unexpected behavior. It currently supports testing NodeJS modules and Ruby Gems. The GitLab Security team created and tested the tool and are ready for you to use it and provide feedback. By making it publicly available, we hope to enable other projects to detect malicious code in their dependencies before it causes any harm and also to increase the general confidence in open source supply chains. The tool integrates seamlessly with GitLab. To get started, use the GitLab CI template to add a Package Hunter job to your project.

## [How Netflix Works](https://faun.pub/how-netflix-works-cbf5295d3ed5)

Netflix uses Amazon Web services and Open Connect as its content delivery network. Netflix supports a wide range of devices ranges from smartphones, smart TVs, PCs, and their different operating systems. The Netflix back-end on Amazon Web Services(AWS) works smoothly to deliver us as the users exceptional viewing experience. It all starts with you pressing that click button and a request to the Netflix servers which are mainly hosted on AWS is made. The request together with multiple other requests is forwarded to Amazon's elastic load balance to route to the traffic.

## [Privacy is an afterthought. Here's how devs can easily make it better.](https://stackoverflow.blog/2021/07/19/privacy-is-an-afterthought-in-the-software-lifecycle-that-needs-to-change/)

The key to combining privacy and innovation is baking it into the SDLC. Privacy belongs at the outset of development, not as an afterthought. The term of art for this consideration is “data privacy,” but in practice it’s the “respect” concept that may be more apt. Respectful systems are ones where choices are presented transparently to users, and the information users elect to share with the system remains under their control at all times. It doesn’t seem like too much to ask, right? In our field, it's becoming table stakes.

## [Software Supply Chains & The Modern Challenges](https://itnext.io/software-supply-chains-the-modern-challenges-e2d9e1ea8f6)

In-Toto is a framework to secure the integrity of software supply chains. It aims to provide integrity, authentication, and auditability to the supply chain as a whole. Grafeas is an open-source solution for securing your software supply chain for Kubernetes applications. Google recently announced a framework called SLSA: Supply-chain Levels for Software Artifacts. It is an end-to-end framework for ensuring the integrity. of software artifacts throughout the software supply. chain.

## [Invoking the AWS CLI with Terraform](https://faun.pub/invoking-the-aws-cli-with-terraform-4ae5fd9de277)

AWS Route53 resolver endpoint is lacking a Terraform resource for the AWS service. This does not mean we can’t create the desired resources without Terraform. We can leverage the null_resource and the provisioner local-exec to execute a command on the Terraform instance where Terraform is currently running. This is the easiest way to have Terraform execute our command using the AWS CLI command for route53resolver create-resolver-endpoint. As you can select the desired resource based on your preference based on the number of subnets or IP addresses.

## [AWS TypeScript CDK and Step Functions](https://aws.plainenglish.io/aws-typescript-cdk-and-step-functions-bbc173333aed)

This quick tutorial will show the steps for deploying a TypeScript step function composed of 3 lambdas. 1 Lambda generates a random number, there is a 1-second wait then in the step function. There is no huge business case for a step function like this but it's a starter for implementing step functions using the TypeScript CDK. This is an introductory tutorial and more work would be needed to make this production-ready but this tutorial will hopefully get you on your way.

## [Syncthing: Syncing All the Things](https://lwn.net/Articles/861978/)

Syncthing 1.17.0 is a free software that syncs up to date across multiple systems. Syncing all the things we want are always on the wrong machine. The core idea behind synchronization systems is essentially the same for all of them: ensure that those directories have the same contents on each system. The trouble is always in the details, though; from fiddly setup procedures to data corruption and security problems, there are a lot of ways in which synchronization can go wrong. There are various ways of handling older versions of files.

## [Should You Use DynamoDB or MongoDB?](https://itnext.io/should-you-use-dynamodb-or-mongodb-e77f013e9914)

DynamoDB and MongoDB libraries are structured in very different ways, making some queries less convenient. MongoDB Atlas is rolling out a new feature called serverless, which is currently in preview. With DynamoDB, we need to explicitly send filter expressions that are SQL-like conditions. When we want to filter by primary key, we must explicitly specify the key in the key field of the object.

## [Kubernetes Dashboards: Octant](https://loft.sh/blog/kubernetes-dashboards-octant/)

Octant is one of the best-known tools in the Kubernetes dashboard space. It’s a project that Bryan Liles built a lot of back when he was at Heptio. The tool ships as a Go binary and ships with a web browser for the Octant web UI. Octant has a cluster overview and sections of resources like workloads, networking, configMaps/secrets, etc. Resources in Octant seem to be grouped more by their functions, not resource types.

## [Migrating Facebook to MySQL 8.0](https://engineering.fb.com/2021/07/22/data-infrastructure/mysql/)

Facebook’s MySQL database powers some of its most important workloads. We actively develop new features in MyRocks to support our evolving requirements. The challenges include porting our custom features to the new version of mysqld server. Facebook explains how they tackled the 8.0 migration project. The team is sharing how we tackled the project — and some of the surprises we discovered in the process. Read this article by Frida Ghitis, along with a copy of this week's iReport.

## [Seven Personality Traits That Help a Developer Succeed](https://javascript.plainenglish.io/seven-personality-traits-that-help-a-developer-succeed-a7b14a61b311)

Seven Personality Traits That Help a Developer Succeed are needed to make the most of his potential. Good IT specialists are more important than ever for companies. Successful developers invent and simplify complex IT constructions so that users benefit from them in everyday life. The “press release method ” is also used for all of our new AWS services; it has proven itself in practice. It consists of writing a (fictitious) press release about a newly developed product or software. The notification should contain the advantages such an application brings for the customer and what improvements are associated with it.

## [Why I Disagree with GitHub Copilot Naysayers](https://javascript.plainenglish.io/why-i-disagree-with-github-copilot-naysayers-62a43cce6329)

GitHub Copilot is a technical preview of a new technology GitHub is working on. It works by offering you suggestions of single lines or entire functions based on the code you have already written or a comment you write. It infers your intent and then generates a suggestion based on what it has learnt from large sources of public code. There is no information in regards to the licence the code the code was licensed under. It's perfectly reasonable to assume that they would have included code that was licensed in a way that does not permit it to be used in this way.

## [A monorepo misconception – atomic cross-project commits](https://www.snellman.net/blog/archive/2021-07-21-monorepo-atomic/)

Many authors even go as far to claim that this is the only benefit of monorepos, but that particular claim makes no sense. It's not how you'd actually make backwards incompatible changes, such as interface refactoring, in a large monorepo. Instead the process would be highly incremental, and more like the following:Push one commit to change the library, such that it supports both the old and new behavior with different interfaces. Push another commit to remove the old implementation and interface from the library.

## [OOP vs. Functional Programming — Which Is Better?](https://betterprogramming.pub/oop-vs-functional-programming-which-is-better-4f0dd89b7987)

Object-oriented programming (OOP) and functional programming (FP) are programming paradigms. They're ways of coding that determine the type of tools we’ll have at our disposal. OOP is one of the most common ways of writing code and, for some reason, is the best-known paradigm out there. It tries to represent the real world through abstract constructions in your code. Within OOP, multiple tools and characteristics about it allow for even more dynamic behavior, such as: Polymorphism.

## [Is GitHub Copilot a blessing, or a curse?](https://www.fast.ai/2021/07/19/copilot/)

GitHub Copilot is a plugin to Visual Studio Code which auto-generates code for you based on the contents of the current file, and your current cursor location. It is powered by a deep neural network language model called Codex, which was trained on public code repositories on GitHub. The model learns to guess missing symbols in programming code, so it has to learn a lot about the structure and meaning of computer code. The fact that Copilot’s suggestions may be a breach of license (or require relicensing your own work under a GPL-compatible license)