# DevOps / SRE - Top Links Last Week

## Week 42 Issue #49


## [Microservices and the layers to watch for when architecting your system](https://www.infoq.com/articles/consistency-coupling-complexity/)

GraphQL API Design is great for Backends for Frontends (BfFs) but not so great for data services. It’s been over a decade since the current incarnation of microservice architecture has been embraced by technology companies. The benefits of microservices are limited when the dependencies between them are such that changes to one necessitate changes to the others. This article focuses on how to maintain useful microservices and still benefit from the process improvements promised by the migration of monoliths to microservices.

## [Kubernetes Will Revolutionize Enterprise Database Management](https://thenewstack.io/kubernetes-will-revolutionize-enterprise-database-management/)

Kubernetes was initially designed to handle the orchestration of stateless workload. But the technology has matured, and it is time to reconsider running data on Kubernetes. There are three important technical aspects to be considered: maturity, availability and performance characteristics of running databases in containers. Most companies want to operate databases as a DBaaS (Database-Service-Service) service, including self-provisioning, including backups, monitoring and monitoring. The benefits of running a database in containers can save significant costs, and offer additional capabilities.

---

## [Please Serverless, Have an Opinion](https://thenewstack.io/please-serverless-have-an-opinion/)

Sam Farid is a software engineer in Silicon Valley who’s worked on world-scale infrastructure such as the serverless platform at Google and the anti-fraud system at YouTube. He says serverless gives you enough freedom to screw things up but not enough flexibility to prevent these errors. Serverless is an abstraction, and no matter how simple it appears, issues can arise from anywhere in the underlying infrastructure. If serverless took a stance on its surrounding ecosystem, it could’ve prevented this outage.

## [User Management in Ansible-Playbook via Jenkins Pipeline-2](https://faun.pub/user-management-in-ansible-playbook-via-jenkins-pipeline-2-317cb7f31fd7)

In this second article, I explained the Jenkins configuration and the stages of running the Ansible-Playbook, I created in the previous article, in the Jenkins pipeline. In step 3, I add the repository key to the system. Then click on the Install suggested plugins button. I have installed Jenkins and its dependencies to build Ansible tasks in Jenkins pipeline as well as the Parameterized Trigger plugin.

## [Learning Tests and How They Help Cover Every Line of Code](https://medium.com/microsoftazure/learning-tests-and-how-they-help-cover-every-line-of-code-da41c74043b)

Integration tests are crucial in complex software systems. They test groups of components and how well they’re combined and communicate with each other. Learning tests can be written to try and understand third-party APIs and components. They are Integration tests by-definition, and written prior to the actual production code in a TDD (Test Driven Development) approach. See how those tests were implemented in one service build process as part of an Integration Tests project, running alongside a Unit Tests project. The project was structured as a Monorepo and had a strict code coverage threshold definition for each service.

## [What is Apache Zookeeper?](https://bhanuka-16.medium.com/what-is-apache-zookeeper-540cdff6d45f)

Apache Zookeeper is an effort to develop and maintain an open-source server which enables highly reliable distributed coordination. ZooKeeper is a coordinating and managing service to a large set of hosts in a distributed environment. The leader is elected on the service startup and performs automatic recovery if any of the connected nodes failed. The ZooKeper data model uses Hierarchical Namespace for memory representation of its file system. Every znode is identified by a name and separated by a “/” The namespace looks similar to a Unix filesystem.

## [The Benefits and Challenges of Using Serverless Architecture for Deep Learning](https://aws.plainenglish.io/serverless-architecture-for-deep-learning-e8c1d2b3ca3)

Deep Learning involves processing huge data (the more, the better) through your neural network multiple times (sometimes 1000s) The huge data involved and the multiple iterations/passes of data through the neural network demands huge processing power. The section below proposes a decoupled, serverless architecture on AWS (using EMR, Lambda, Step Functions, DynamoDB etc.) that can run your. neural network with huge data and multiple iterations. The architecture is feasible, only with the mini-batch mode of processing data instead of processing all the data together in each.

## [Blockchain voting is overrated among uninformed but underrated among informed](https://vitalik.ca/general/2021/05/25/voting2.html)

Blockchains are a technology which is all about providing guarantees about process integrity. If a process is run on a blockchain, the process is guaranteed to run according to some pre-agreed code and provide the correct output. The trust properties they provide are not a good match for the properties that voting needs, and other kinds of software tools with different information flow and trust properties would work better. This article will discuss the security issues with existing attempts to use blockchains for voting, and how the correct solution is not to abandon blockchains but to combine them with other cryptographic technologies.

## [How to Deploy a Highly Available WireGuard® Network Management Server on Kubernetes](https://itnext.io/how-to-deploy-a-highly-available-wireguard-network-management-server-on-kubernetes-294e23c7abcb)

The day it came out, WireGuard® made OpenVPN and ZeroTier look like dinosaurs. WireGuard enables cutting edge network patterns across multi-cloud, edge, and Kubernetes. Netmaker is a platform for creating and managing WireGuard-based virtual networks. It lets you handle different types of network topologies, including full mesh, site-to-site, ingress, egress, and relaying. The end result is a virtual network based on WireGuard that will auto-update when any change occurs to any peer. V0.8.4 comes with updates to manage a highly available server so that clients wont lose connectivity.

## [10 best practices to make switching cloud providers less painful](https://cast.ai/blog/10-best-practices-to-make-switching-cloud-providers-less-painful/)

The first step to understanding whether the vendor is doing a good job is having the means for discovering SLA problems. Most cloud providers allow KMS keys to be replicated across multiple regions. If you see major incidents that lead to downtimes for large portions of regional or global services, causing customer application downtimes, it’s usually hard to miss thanks to getting reported all over the internet. The same goes for database backups and Google Cloud Platform even offers a globally replicated database called Cloud Spanner.

## [How To Create a NoOps Deployment With GitHub Actions Kubernetes and Shipa](https://betterprogramming.pub/how-to-create-a-noops-deployment-with-github-actions-kubernetes-and-shipa-18aab208fe7a)

Shipa is a platform for automating and simplifying the adoption of Kubernetes, making it smoother and simpler to use. The GitHub Action we will set up a DevOps process in minutes. We will use the shipa tool that we installed in the previous part of the article. The solution is a NoOps-like solution by using Shipa for managing Kubernetes and GitHub action to connect the source code directly with the server. The next step is to create a Python application that simply prints the data that is sent to the URL.

## [Autonomous testing of services at scale](https://engineering.fb.com/2021/10/20/developer-tools/autonomous-testing/)

Facebook’s autonomous testing tool lets developers prototype, test, and iterate on new features quickly. Testing back-end services typically involves one or more unmodified services. Facebook reuses the production infrastructure, in particular the containerization and routing systems, to build test environments. We create separate ephemeral entities within the infrastructure for each test. This results in test environments that receive no production requests without being automatically restricted from connecting to production systems. This enables certain tests to share read-only assets or APIs with the production environment.

## [Kubernetes Deep Dive: CronJob](https://aws.plainenglish.io/kubernetes-deep-dive-cronjob-4df5f64039d6)

Kubernetes Deep Dive: CronJob in k8s, a useful API object — CronJob. CronJob is a controller dedicated to managing Job objects. One CronJob object is like one line of a crontab (cron table) in Linux. It runs a job periodically on a given schedule, written in Cron format. The relationship between CronJob and Job is the same as the relationship between Deployment and ReplicaSet. It’s just that it creates and deletes Jobs based on a standard Unix Cron format expression.

## [5 Tips in Bash Scripting for Beginners](https://betterprogramming.pub/5-tips-in-bash-scripting-for-beginners-e113a2cf1510)

5 Tips in Bash Scripting for Beginners: How to interact with an end-user. How to search for a file or directory, how to concatenate multiple CSV files and how to use the find command in Unix/Linux. How to deal with headers of csv files, if you want to keep the headers of just one file then you can use the following command: (FNR) or (R) -h -r) How to get the size of each folder within one folder, if I want to remove all files, I can type: (R -h)

## [Scaling Kubernetes Clusters With Armory](https://betterprogramming.pub/scaling-kubernetes-clusters-with-armory-d8902576fbe6)

Armory’s enterprise-level distribution of Spinnaker is needed to manage large-scale Kubernetes systems. Armory is a tool for handling change management and pipeline configuration and security. We’ll look at the challenges of managing multi-cluster clusters at scale and the hurdles of handling operational environments and upgrading. We'll also look at how easy it is to run multiple Kubernetes clusters. Armory aims to be more secure and simple for users and services, coordinating multiple environments, and dealing with potentially system-breaking upgrades.

## [5 Tips for Reducing Bugs in Software Development Projects](https://betterprogramming.pub/5-tips-for-reducing-bugs-in-software-development-projects-5bc592c2881a?source=rss----d0b105d10f0a---4)

Software bugs are inevitable, but we can reduce them with various strategies. Bugs in software systems affect software quality directly. Software quality defines the future success of every software project. When programmers notice a bug, they often try to solve it by applying quick patches. Don’t be stressed while applying quick fixes for production fixes can introduce a new bug while you are working on a new one. Use these tips to prevent stress-management practices in your career and prevent future bugs that happen due to the previous fixes.

## [Basics of CI/CD](https://dev.to/kirekov/basics-of-cicd-5e16)

The primary goal of any software project is to earn money through the automation of the business process. Today we're discussing automation of a product development process itself. CI and CI are two abbreviations that stand for Continuous Integration and Continuous Delivery. This can solve the issue? Thankfully, we can apply it to a project that needs to be automated. The Jacoco plugin is a solution to the problem. It can only work if the plugin was configured since the project started. It's the most popular solution, but it's not an efficient approach.
