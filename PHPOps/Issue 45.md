# DevOps / SRE - Top Links Last Week

## Week 38 Issue #45

## [Introducing Google Cloud Deploy: Managed continuous delivery to GKE](https://cloud.google.com/blog/products/devops-sre/google-cloud-deploy-automates-deploys-to-gke/)

Google Cloud Deploy is the product of discussions with more than 50 customers to better understand the challenges they face doing continuous delivery to GKE. From cloud-native to more traditional businesses, three themes consistently emerged: cost of ownership, security and audit, and integration. As a managed service, Google Cloud deploy eliminates the scaling and maintenance responsibilities that typically come with self-managed continuous delivery solutions. Now you can reclaim the time spent maintaining your continuous delivery tooling and spend it delivering value to your customers.

## [The Case for ‘Developer Experience’](https://future.a16z.com/the-case-for-developer-experience/)

Developer experience is the sum total of how developers interface with their tools, end-to-end, day-in-and-out. With developers spending less than a third of their time actually writing code, developer experience includes all the other stuff: maintaining code, testing, security issues, addressing incidents, and more. The number of developers is currently larger than the population of Australia, growing faster than Brazil, and set to exceed Canada. We need to redefine and expand our notion of “developer experience” and the way we build, buy, and use developer tools.

---

## [No Kubernetes Needed: Amazon ECS Anywhere](https://thenewstack.io/no-kubernetes-needed-amazon-ecs-anywhere/)

Amazon has extended Elastic Container Service (ECS) as a vehicle to deliver hybrid cloud capabilities to customers. ECS was launched in 2014 — a year before Kubernetes became available — as a managed container orchestration platform for AWS customers. At re:Invent 2020, Amazon announced ECS Anywhere, the service that extends ECS’ capabilities to on-prem and other cloud environments. Amazon calls the hosts running outside of its cloud as external instances that became the third execution environment for ECS.

## [12 IT skills paying the highest premiums today](https://www.cio.com/article/3342156/it-skills-paying-the-highest-premiums-today.html)

Foote Partners has been tracking pay data on IT skills since 1999 to see which skills and certifications give the biggest boost at any given time. Pay premiums help employers track the value of specific skills, so they know how competitive the market is for candidates with those skills and how much to offer on top of the base salary. On average, market value for 621 noncertified tech skills rose just slightly in the second quarter of 2021. Meanwhile, more than 500 IT certifications decreased in market value.

## [Kubernetes Deep Dive Four: Why We Need Pod?](https://tonylixu.medium.com/kubernetes-deep-dive-four-why-we-need-pod-e88949eb7b08)

Kubernetes Deep Dive Four: Why Do We Need Pod? The atomic scheduling unit of k8s. Pod is the smallest API object in the cloud computing operating system. Google engineers found that the applications they deployed often had a relationship similar to “process and process group’s” Google engineers. There is a close relationship between these applications, so that these applications must be deployed on the same machine. A Pod is a group of one or more containers, with shared storage and network resources.

## [Implementing OpenID Connect Authentication for Kubernetes with Okta and NGINX Ingress Controller](https://www.nginx.com/blog/implementing-openid-connect-authentication-kubernetes-okta-and-nginx-ingress-controller/)

Single sign‑on (SSO) technologies can partially address these problems by eliminating all those separate usernames and passwords. Users sign in just once with an Identity Provider (IdP) to get access to many apps. But developers still must include code in their apps to interface with the SSO system. This frees developers from the burden of building, maintaining authentication logic and replicating authentication logic. An ideal location for centralized authentication and authorization in Kubernetes is at the Ingress controller, which can scrutinize all traffic entering the cluster.

## [Dell Technologies expands Dell EMC CloudIQ, eyes autonomous infrastructure](https://www.zdnet.com/article/dell-technologies-expands-dell-emc-cloudiq-eyes-autonomous-infrastructure/)

Dell is expanding support for Dell EMC CloudIQ, a cloud application that's a steppingstone to creating autonomous infrastructure. The move is likely to speed up automation in data centers and infrastructure. CloudIQ includes AIOps tools to manage issues before they become critical. Dell Technologies will outline a Level 1 to level 5 framework for autonomous operations at an Autonomous Operations event hosted by Mark Hamill. The roadmap for Dell will bring its infrastructure to level 3 of its autonomous operations model in years to come.

## [Cloud Deploy — Deployment to GKE with Skaffold and Kustomize](https://faun.pub/cloud-deploy-deployment-to-gke-with-skaffold-and-kustomize-b719c71f3c9c?source=rss----10d1a7495d39---4)

GCP just launched a new service named Cloud Deploy which is a fully managed continuous delivery service for GKE. The underlying service still uses cloud build and several tools such as skaffold and kustomize (as this story focus on those two) However we do not have to manage the infrastructure (less painful :D ) So this snippet focuses on the conceptual test of Cloud Deploy and how the experience in deploying workloads to GKE will be different. I used the different name file below for easier to see which kustomization file really is, for more proper naming please go to the official documentations.

## [Airflow High Available cluster](https://faun.pub/airflow-high-available-cluster-2f2d792ce900)

Part 2: Implementing the Airflow HA solution. I’ll provide a few screenshots from the Hetzner-Hetzner’s Airflow solution. Part 1: Installing etcd, patroni, etcd and Postgresql cluster with Patroni. Part 3: Using Airflow to run Airflow and load balancer. Part 4: Using a non-privileged user with sudo for installing and configuring the etcd/patrioti cluster. Part 5: Using the same tools as Airflow, you can install and configure the cluster using Ansible.

## [Rancher 2.6 Designed to Ease Kubernetes Cloud Deployments](https://thenewstack.io/rancher-2-6-designed-to-ease-kubernetes-cloud-deployments/)

SUSE Rancher 2.6 is aimed at making it easier for DevOps teams to deploy and manage Kubernetes environments across different cloud environments. The new version offers full lifecycle management support for clusters hosted across three major cloud providers. SUSE says its ambitions are to support organizations’ digital transformation as they pivot towards a multicloud, hybrid IT approach to infrastructure, CEO Thomas Di Giacomo told The New Stack. The latest release follows SUSE’s purchase of Rancer last year, as both companies have said they seek to combine the best of SUSE Linux and Ranchers orchestration tools.

## [How to Save 50% Cost by Migrating from Heroku to Opta on AWS](https://blog.runx.dev/how-to-save-60-cost-by-migrating-from-heroku-to-opta-on-aws-2df53bbb7e2a)

Heroku runs its servers on AWS while giving you a much simpler and nicer experience than if you DIY on your own AWS account. Opta is a cli tool that my company, RunX, has been developing to make the creation of robust, secure, environments and microservices in a user’s own cloud accounts as dead simple as possible. With Opta, a user is merely responsible for creating a small yaml file for the environment detailing the specifics of what is to be created and also one file per microservice.

## [What’s your org’s reliability mindset? Insights from Google SREs](https://cloud.google.com/blog/products/devops-sre/the-five-phases-of-organizational-reliability/)

The reliability of a software product is a property of the architecture of its system, processes, culture, as well as the mindset of the product team or organization that built it. At Google, we’ve developed a terminology to categorize and describe your organization’s reliability mindset, to help you understand how intentional your organization is in this respect. Reliability should be woven into the fabric of an organization, not just the result of a strong design ethos, says Google SREs.

## [Google on the DevOps ‘Elite’ and Everyone Else](https://thenewstack.io/google-on-the-devops-elite-and-everyone-else/)

Google’s recently published “Accelerate State of DevOps 2021’ report. 26% of respondents this year are classified as “elite,” up from 20% in 2019 and 7% in 2018. Median elite organization is definitely high performing. It delivers software on-demand, deploying code to production or releasing it to users multiple times a day. It takes less than an hour for a median elite organization to restore service after an incident, outage, or perhaps a serious security vulnerability is identified.

## [Manage Auto-generated Secrets in Your Helm Charts](https://itnext.io/manage-auto-generated-secrets-in-your-helm-charts-5aee48ba6918?source=rss----5b301f10ddcd---4)

Helm Charts allows you to pack your Kubernetes applications in a modular way and apply different deployment logic based on users’ configuration “values files” It’s common that we need to generate random secrets (e.g. JWT / session secrets or random passwords) during the first deployment. We can choose to let our Helm Chart users manually create / manage those secrets outside the Helm Chart deployment lifecycle. But it will be more convenient if Helm Chart can handle the secret auto-generation.

## [Deploying A Fargate Cluster With LocalStack And The AWS CDK](https://blog.dennisokeeffe.com/blog/2021-08-11-deploying-a-fargate-cluster-with-localstack-and-the-aws-cdk)

This post will demonstrate how we can deploy a demo Fargate cluster to LocalStack using ECS patterns defined in the AWS CDK. Prerequisites include familiarity with TypeScript and familiarity with the CDK for TypeScript. We will need the following libraries: @aws-cdk/core @aws/aws-ec2 @aws://www.cs.org/cs-ecs-patterns. At this stage, we will have the app in a basic working state. We then add a pattern construct to a stack to create a cluster.

## [How to Create a Very Inexpensive Serverless Database](https://aws.plainenglish.io/very-inexpensive-serverless-database-6ed6df489ab6)

Amazon released their S3 (Simple Storage Service) object storage product in 2006. Amazon’s S3 API allows you to read, write, and delete objects. Object storage can be used to store photos, videos, backups, etc., but can also be used as storage for data. Storage generally costs 1¢–2¢ per GB and outbound network costs for the least expensive options are generally 1¢ perGB. Google is the only one provider that claims they will scale to scale to meet your request rate rate.

## [Find Vulnerabilities in Container Images with Docker Scan](https://thenewstack.io/find-vulnerabilities-in-container-images-with-docker-scan/)

As you shift your development process to cloud native computing, you’ll find yourself working with more and more container images. Those images might be officially vetted by the company that produced them, or they might come from third-party sources that might not hold the same level of trust those larger companies have. There are a lot of tools available for this task, some of them are costly services, while others are free alternatives that are pretty simple and safe to use. To make that possible, Docker Desktop includes a handy scanning tool, the scanner is a command-line only tool.

## [Essential Cloud Concepts: Block Storage, Object Storage, File Storage](https://aws.plainenglish.io/block-storage-object-storage-file-storage-71438131abc4)

Block storage is one of the oldest forms of data storage which can be formatted for file system creation. Object storage stores the files as a whole and does not divide them. In Object storage, data is not divided into raw blocks and instead, entire data is stored as an object. The ability to edit one part of the file is not provided in object storage, unlike block storage. The best example of object storage is the Virtual machine, so the storage which we assign to the VM is another good example of block-level storage.

## [A Complete Guide to Node.js Logging](https://betterprogramming.pub/a-complete-guide-to-node-js-logging-1ba70a4a346d)

Logging is the process of recording information generated by application activities into log files. Logs are a simple way of persisting info about your application. These logs can be used to diagnose anomalies, malware activities, or unauthorized resource access in real-time by providing a live stream of log events. Log levels are the metadata for logs. The level defines the severity of a logged incident. Logging levels are so you can quickly see which logs need more attention. There are five main levels of logging. Based on the priority, it can sort as follows.

## [Removing Dependency on Docker CLI](https://itnext.io/removing-dependency-on-docker-cli-94c96fcaa024)

The insecure, blocker, and location lines must be uncommented and the location must be updated to localhost:5000. Podman needs to be restarted in order to apply the new configurations and should be able to be pushed to using localhost. The updated contents of registries.conf are shown below, the differences are the insecure, blocking, and. the location. field is used to choose the relevant. TOML table with the longest match for the input image name. The “prefix” field is. used to. choose the. relevant [[registry. table; the “ prefix” is used. If the prefix field is missing, it defaults to be the same as the. “location”

## [Web Application Security Risks: OWASP Top 10](https://faun.pub/web-application-security-risks-owasp-top-10-bb4e8afbec75)

The Open Web Application Security Project is a nonprofit open community dedicated to enabling organizations to develop, purchase, and maintain applications that can be trusted. The OWASP Top 10 is a standard awareness document for developers and web application security. It represents a broad consensus about the most critical security risks to web applications. Injection attacks are amongst the oldest and most dangerous web application attacks. They can result in data theft, data loss, data integrity, denial of service, as well as full system compromise. The Top 10 provides basic techniques to protect against these high-risk problem areas.

## [Automating quality checks for Kubernetes YAMLs](https://dev.to/wkrzywiec/automating-quality-checks-for-kubernetes-yamls-398)

In this blog post, I'll show how to create a simple, automated quality check of your K8s object definitions using Datree and Google Kubernetes Engine and Github Actions. The workflow will have two stages: analysis of missing configurations, and quality check, and testing an example application in a real cluster (GKE) Datree analysis will stop the workflow if it finds any problems. It's very important to have a safety net like this so you can feel confident that even if you make a mistake, or aren’t aware of best practices, an assistant will keep you on track.