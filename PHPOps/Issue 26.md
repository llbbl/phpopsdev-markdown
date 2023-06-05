# DevOps / SRE — Top Links Last Week

## Week 19 Issue #26

## [Seven Reasons You Shouldn’t Hire a DevOps Engineer](https://devops.com/seven-reasons-you-shouldnt-hire-a-devops-engineer/)

DevOps is not a title; it is a culture, not a role, says DevOps lead at Replix. Developers know their code better than anyone else, says Uri Zaidenwerg. Developers should be empowered to own their applications end to end, including deployment, security and cloud costs. Separating DevOps roles is a way of de-siloing development and operations, he says. One DevOps engineer against a tidal wave of requests and application deployment pipelines is just not sustainable.

## [ServiceNow acquires Lightstep](https://www.zdnet.com/article/servicenow-acquires-lightstep-aims-to-leverage-observability-across-enterprises/)

ServiceNow is buying application monitoring and observability company Lightstep. The company is aiming to bolster DevOps engineers' ability to build, deploy, run and monitor cloud-native apps. Lightstep plays in a crowded observability and application monitoring market that includes Dynatrace, BMC, Datadog, Sumo Logic, Splunk's SignalFx, New Relic and a host of others. ServiceNow will combine its AIOps and IT workflow automation tools to "seamlessly connect insight with action"

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Service Accounts in K8s (Kubernetes)](https://sandeepbaldawa.medium.com/service-accounts-in-k8s-kubernetes-2779ee4fb331)

K8s applications run in Pods. Pods usually need access to resources from cloud vendors like aws, gcloud, azure, etc. Service accounts come in. Service accounts can be associated with a deployment manifest. Pods are ephemeral in nature, it might belong to different namespaces, might come up and down(causing change in properties) etc. So one would have to inject the IAM-Role at a place where pods are born, so any new pods coming up would have this property available to them.

## [7 Static Analysis Tools to Secure and Build Stable Kubernetes Clusters](https://thechief.io/c/editorial/7-static-analysis-tools-to-secure-and-build-stable-kubernetes-clusters/)

The tools highlighted in this article will help you scan, analyze, and recommend best practices to help you achieve a secure and stable Kubernetes environment. By analyzing the code from the early stage, we can identify security threats and fix them before deploying. In this article, we’ll look at seven of the best open-source static code analysis tools that can help developers build secure Kubernetses clusters. Checkov is built on Python and provides its scan through multiple platforms, including Jenkins, CLI, and GitHub Markdown.

## [Machine Learning at CNN](https://medium.com/cnn-digital/accelerating-ml-within-cnn-983f6b7bd2eb)

CNN’s Data Intelligence team has adopted open-source project Metaflow. The project uses a directed acyclic graph (DAG) in Python. CNN's data science team believes they were able to test twice as many models in Q1 2021 as they did in all of 2020. CNN averaged more than 200 million unique global visitors every month of 2020. CNN is relentlessly focusing our mission to directly connect with our audience, understand what they care about most, and reach them in a way that is most accessible.

## [Percona takes first steps toward hybrid cloud](https://www.zdnet.com/article/percona-takes-first-steps-toward-hybrid-cloud/)

Percona is unveiling cloud-native implementations of MySQL, Postgres, and MongoDB. The company is announcing the preview of the three databases, based on the Kubernetes operators that it has been developing for them. The preview provides customers the operational simplicity of a cloud-based database as a service. It is not a PerCona-operated DBaaS where you go into a public cloud, but instead, a simplified control plane and some housekeeping services. In the initial preview, customers will be on the hook for configuring and deploying the.

## [Umami – An alternative to Google Analytics](https://github.com/mikecao/umami)

Umami is a simple, fast, website analytics alternative to Google Analytics. It uses Node.js 10.13 or newer with Node.JS or Postgresql database (MySQL or Post.gresql) It supports MySQL and Post.sql. A detailed getting started guide can be found at [https://umami.is/docs/](https://umami.is/docs/) The Umami App is available on GitHub and is available in the U.S. version of this article. It is available to download as soon as possible and use the latest version of the app.

## [Organizing the migration of a hundred databases to the cloud](https://medium.com/blablacar/organizing-the-migration-of-a-hundred-databases-to-the-cloud-f3b162eb4a9)

In 2019, BlaBlaCar signed a contract with Google Cloud Platform, and like many companies, we were starting our journey to the cloud. Eight data store products, one hundred clusters, and a new infrastructure with new components, patterns, and tons of possibilities. Building the team, finding the right focus, making tradeoffs, making or buying systems, changing our communication, proposing migration paths… I will share with you what ingredients we had to look for to turn this massive project into a success story.

## [Full-text search with Node.js and ElasticSearch on Docker](https://micheleriva.medium.com/full-text-search-with-node-js-and-elasticsearch-on-docker-edcea23612fd)

ElasticSearch is a search engine server built on top of Lucene with amazing distributed architecture support. The Quotes Database will allow us to store and search as many quotes as we want. We’ll be using Docker for orchestrating both the Node.js server and the ES instance on a container. We tell Docker to expose two ports: 3000, which will expose our RESTful service, and 9200, which exposes the ElasticSearch service ( EXPOSE 3000 and EXPOSE 9200 )

## [Enterprise Serverless Databases](https://leejamesgilmore.medium.com/enterprise-serverless-databases-208b8790998)

DynamoDB is less configuration and no need for the complications around VPC’s, and the needs for Nat Gateways etc. If your team is working locally on serverless development rather than in AWS directly you will need to think about local development strategies for databases. Data privacy laws and compliance around explicitly where you are storing your data, the reasons for storing it, and for how long (think GDPR or equivalents). Back up your backup strategies regardless of the database that you choose, as this is something that some organisations forget about until it is too late due to the need of shipping features quickly.

## [How to set up simple CI/CD using AWS CodePipeline with GitHub](https://aws.plainenglish.io/how-to-set-up-simple-ci-cd-using-aws-codepipeline-with-github-8dc265470184)

A step-by-step example demonstrates how to deploy a static single page website to AWS S3 using AWS CodePipeline. The pipeline will be triggered automatically when I merge a pull request into the main branch. The merge triggers the code to pull the code automatically and push it to the S3 bucket. You can also create a service role that has appropriate permissions to interact with other AWS services like S3. The pipeline name can't contain spaces or special characters. It's likely you will be able to re-use this same role for future pipelines.

## [Kickstart your Laravel Web App using Laravel Sail](https://dogcomp.medium.com/kickstart-your-laravel-web-app-using-laravel-sail-30276265e588)

Laravel Sail is a light-weight command-line interface for interacting with Laravel’s default Docker development environment. WSL stands for Windows Subsystem for Linux, it allows developers to run Linux environments directly on Windows without any “real” hosted VM. WSL 2 is a major overhaul and provides the benefits of WSL 1 with better file IO performance (20x faster). It is not like the traditional VM which may be slow to boot up, large resource overhead, and fully isolated.

## [Understanding the Differences Between AWS EKS vs. ECS — When to Use What?](https://aws.plainenglish.io/understanding-the-differences-in-aws-eks-vs-ecs-and-when-to-use-what-7ed4d9efa6dc)

Amazon EKS is a managed service that makes it easy for you to run Kubernetes on AWS. EKS establishes the control plane and API in your managed AWS infrastructure and you’re good to go. Both allow to use a mix of compute infrastructure based on the availability like AWS Fargate, AWS Outpost, AWS EC2, AWS LocalZone, AWS Wavelength No Monitoring or Operational Overhead. Both operate within the realm of AWS IAM solution (Identity & Access Management) so that you can have full control and limit over who can access ECS tasks.

## [Understanding Version Control Systems through Git](https://damsak.medium.com/understanding-version-control-systems-through-git-c021fc6d8749)

Git is the most popular Version Control system available in the market. It is a distributed version control system. Git provides various functionalities for branching, merging, and rewriting repository history. GitHub is a web-based platform used for version controlling with the help of Git’s popularity. Git does not provide any authentication mechanisms for the repository. GitHub contains free and pay-for-use tiers. There are some key differences between Git and GITHUB, which is hosted in the cloud.

## [How To Set Up a Solid DevOps Lifecycle](https://betterprogramming.pub/how-to-set-up-a-solid-devops-lifecycle-e3bd1456201)

DevOps is a set of practices that combines IT development and operations. It is mainly intended to reduce the time between when a change is committed and when the change is in production. It consists of various stages, such as continuous development, continuous integration, continuous deployment, and continuous monitoring. The DevOps lifecycle can be divided into multiple phases: development, testing, deployment, continuous monitoring, continuous delivery or continuous continuous integration. Learn about the different phases in the DevOps life cycle and what tools to use.

## [What We Wish Our Clients Knew About DevOps](https://thenewstack.io/what-we-wish-our-clients-knew-about-devops/)

Ahmed Aly builds software for Umbrage to deliver offline-first, mobile-optimized applications to global enterprise and consumer brands. He says DevOps is a strong methodology to build a solution to a core business problem and by utilizing a DevOps mindset, you can set your product, and your users, up for success. Ahmed Aly: Identifying the key features that the users truly need, building an app that is readily use and supporting it rolls out as it evolves and rolls out.

## [What AWS Lambda metrics should you definitely be monitoring?](https://blog.devgenius.io/what-aws-lambda-metrics-should-you-definitely-be-monitoring-ff2eb6619ea0)

Amazon’s Lambda service comes with seven metrics for your functions out of the box. These include Invocations, duration, error count, throttles, async delivery failures, iterator age, and concurrent executions. Amazon's Pay-for-what-you-use business model does not rely on your needs but the success of your business. If your apps are accessed more often, your organization benefits more, along with a slightly greater AWS bill. The first one million requests are free every month. After that, you pay $0.20 per million requests.

## [CI/CD Pipeline using Cloud Build with GitOps Technique](https://andriperera-98.medium.com/ci-cd-pipeline-using-cloud-build-with-gitops-technique-68b0e9d3b53)

This article looks at how to create a continuous integration and delivery (CI/CD) pipeline on Google Cloud Build using the GitHub repository. I’ll be deploying a Spring boot application on Kubernetes. I'll be creating the Deployment and service to access the Pods outside from the Cluster. The Service listens for requests on port 8080 of the target Pods. A LoadBalancer service was used to a load balancer service to expose the PodConfigMaps and Secrets.

## [Introducing Ahoy! — a Helm GUI](https://joe-bigelow.medium.com/introducing-ahoy-a-helm-gui-7d391981f9e1)

Ahoy! is an easy-to-use graphical user interface for running your Kubernetes clusters. It doesn’t hide any of the basic Helm commands behind a paywall. The open-source app is built with Electron and React and works on any OS. It is a beta product developed in partnership with OSLabs and is being developed with the Node.js child process module for communicating with the command line and running all the Helm commands featured in the application.

## [Horizontal vs Vertical Scaling: A Primer for Managers](https://www.rootstrap.com/blog/horizontal-vs-vertical-scaling/)

Deciding between horizontal and vertical scaling is an important infrastructure consideration when building out applications. The tech that allows an application to scale all happens on the back-end architecture side, meaning the servers used to run the app and languages used for interacting with the database. Making poor decisions around server scaling can add tens of thousands of dollars to your monthly server costs; or worse, cause your app to crash or slow down under heavy load. Making the right choice can be critical when making decisions around: microservices vs Monolithic system design, cloud platforms and developer preferences.

## [Starting with Ansible](https://shivam1410.medium.com/starting-with-ansible-8c1bf0e45879)

Ansible can be used for Infrastructure Automation. Ansible is mostly used when we are creating new servers, and we need to configure them according to our needs. An Ansible Playbook is the written manuscript of all the configurations you like to perform over your group of hosts. The playbook is written in YAML, and a single playbook can be. used to perform tasks over different groups of. hosts. An example of these modules is package management tools like apt, DNF, yum, etc. Read more about them here.

## [Kubernetes Basics in Under 5 Mins](https://medium.com/geekculture/kubernetes-basics-in-under-5-mins-c80cda99ccbb)

Kubernetes is a container orchestration system for web servers. It is not a replacement for Docker but a supplement to the popular Docker-based system. An understanding of containers is a prerequisite to using K8's high-level architecture. We need containers before we can orchestrate them to orchestrate web servers running in containers. We will use K8 to manage our web servers and run apps across multiple platforms. We are happy to share our knowledge of how to use the K8 system and K8.

## [Managing Technical Debt](https://medium.com/slalom-build/managing-technical-debt-8594f03f1099)

Technical debt is, at worst, a necessary evil; at best, a powerful tool. Technical debt, like financial debt, is best adopted in an intentional manner. The difference between the two is mostly determined by the intentionality with which it is introduced to the codebase and how well it is managed and proactively planned for. In this article, I will explore 10 steps that I’ve found necessary to ensure that your technical debt is not an accidental mess that requires unplanned reactions.

## [Securely using secrets in a pipeline — HashiCorp Vault + JWT Auth](https://amirsoleimani.medium.com/securely-using-secrets-in-a-pipeline-hashicorp-vault-jwt-auth-fa0a7eeb7e29)

The typical way of communicating with the Vault service is adding the VAULT_TOKEN value as a constant in the environment. But is it a safe solution? Of course not! There is another way which is more reliable and secure. In this article, I’m just trying to explain the main concept and not dive into the details on each step because If you get the concept, after this, it’s up to you how to configure the auth method, put these pieces together, or how to make up your environment to use it.