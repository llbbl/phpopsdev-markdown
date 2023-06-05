# DevOps / SRE — Top Links Last Week

## Week 11 Issue #18

## [Incident Prevention For Data Teams: Introducing The 5 Pillars Of Data Observability](https://www.montecarlodata.com/introducing-the-5-pillars-of-data-observability/)

Bad data spares no one, least of all the data engineers and analysts working directly with the workflows, pipelines, and dashboards responsible for aggregating, transforming, and visualizing it. Industry leaders call this problem "data downtime," and it refers to periods of time where data is missing, erroneous, or otherwise inaccurate. Data Observability can be split into five key pillars representing the health of your data, including freshness, distribution, volume, schematics, and lineage .

## [The Distributed Data Mesh (2019)](https://martinfowler.com/articles/data-monolith-to-mesh.html)

Zhamak Dehghani is a principal technology consultant at ThoughtWorks with a focus on distributed systems architecture and digital platform strategy at Enterprise. She says the current enterprise data platform architecture is centralized, monolithic and domain agnostic aka data lake. The current generation data platforms are more or less similar to the previous generation, with a modern twist towards streaming for real-time data availability with architectures such as Kappa, unifying the batch and stream processing for data transformation with frameworks such as Apache Beam, as well as embracing cloud based managed services for storage .

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Stop re-writing pipelines! Why GitHub Actions drive the future of CI/CD](https://blog.codecentric.de/en/2021/03/github-actions-nextgen-cicd/)

The Pipeline-as-Code pattern is implemented by most CI/CD platforms today. So what could be the next evolutionary step? Based on GitHub Actions, the article outlines why open-source Pipeline-As-Code Building Blocks will take your pipelines to the next level. It's all about this "Actions" thing! And I started to think about what I experienced in my professional career using CI-CD tooling as a key piece of my toolbelt. But to really explain what my thoughts are all about, I need to go back in time more than 10 years in time .

## [The ecosystem of the Go programming language](https://henvic.dev/posts/go/)

Go is one of the most prominent general-purpose programming languages nowadays. Google, Apple, Microsoft, Amazon, and Adobe have been using the language extensively. It's the language of choice behind multiple cloud computing projects such as Kubernetes. In this article, you'll find resources to learn about Go and its ecosystem. Go 1 has a compatibility promise at the source level with the aim of building a stable platform for the growth of program and projects made with the language. Go is a concise language with regular syntax .

## [We are building a better Heroku](https://about.gitlab.com/blog/2021/03/22/we-are-building-a-better-heroku/)

GitLab introduces a better Heroku integrated into your DevSecOps workflow. GitLab integrates app packaging, container registry, deployment and certificates. The 5 minute production app does not need the Postgres and Redis backends disabled with the default build-up. The application is deployed natively to GitLab to have a single application in your DevOps workflow? How about adding the deployment natively? GitLab is a great tool to manage multi-cloud resources like AWS and GitLab's Terraform .

## [Jobs & Cronjobs in Kubernetes Cluster](https://kubernetes-advocate.medium.com/jobs-cronjobs-in-kubernetes-cluster-d0e872e3c8c8)

In this article, we will learn how to schedule jobs and cronjobs to Kubernetes Cluster. A job creates one or more Pods and will continue to retry execution of the Pods until a specified number of them successfully terminate. The Job is designed for parallel processing of independent but related work items like sending emails, rendering frames, transcoding files, scanning database keys, etc... A CronJob is just like an entry in crontab in Unix/Linux. It runs a job periodically on a given schedule .

## [Top Node.js Frameworks to use in 2021](https://javascript.plainenglish.io/top-node-js-frameworks-to-use-in-2021-4951ee5940b8)

Node.js is one of the fastest server-side web application platforms as it provides app development companies the ease of building scalable single program language web applications. Amazon, Netflix, LinkedIn, eBay, PayPal, and Reddit use this framework to create enterprise applications. Hapi.js provides scalable and robust applications that have minimal overhead and out-of-the-box functionality. Express.js supports MVC Architecture with some work. Koa.js aims to create a smaller, more expensive, and more robust platform for web and APIs .

## [Why Prometheus is an Essential Observability Tool](https://containerjournal.com/features/why-prometheus-is-an-essential-observability-tool/)

Prometheus is one of The Cloud Native Computing Foundation's "fastest-growing" projects. The time series database is especially useful for gathering metrics about Kubernetes clusters. New Relic integrates Prometheus metrics into its observability platform to help DevOps teams gather actionable data from the so-called "unknown knowns" among observability data. The real difference with observability is opening up the ability to ask questions of your system in real-time - or allowing AI to do it for you - through the data it throws off .

## [Importing an existing Infrastructure to Terraform.](https://sanoojm.medium.com/importing-an-existing-infrastructure-to-terraform-e5b80d143011)

The best time to move to IaC is during the beginning of the migration, but in case if you miss that, you still have a chance. Migrating applications/servers to the public cloud always happen in the finest lap. The entire migration team should know the technology (say, Terraform). You need a few people who are really proficient at this so that you can go faster. You need to take the risk of hitting any roadblock. It's fine to manually code the terraform HCL definitions .

## [Thinking about Observability when Coding](https://medium.com/@rohatsahin/thinking-about-observability-when-coding-565b0983735b)

The fact that the modern systems we develop are consistent, scalable, and reliable is usually one of the main priorities of our software development processes. In this article, we will show you the observability issues when we encounter while developing software. In the example charts above, since we could not see the part that caused latency after development, we first worked on seeing the problem instead of solving it, and in this way, it saved us a lot of effort to identify the problem, and it also showed that we can solve in a short time .

## [Lens — A Year In Review](https://medium.com/k8slens/lens-a-year-in-review-90c81e9c1509)

Lens is a cloud-native tool that allows Kubernetes developers, operators, and SREs to take control of their clusters like never before. Lens has over 3.5 million downloads, more than 150,000 users, and 13,200 GitHub stargazers. To date, we have closed nearly 1,000 GitHub issues spanning across bug fixes, feature updates, and overall product enhancements to Lens. Lens is staying true to our commitment to provide our community with top-tier support and ensure that issues are promptly resolved .

## [Intro to Deployment Strategies: Blue-Green, Canary, and More](https://cd.foundation/uncategorized/2021/03/18/intro-to-deployment-strategies-blue-green-canary-and-more/)

Deployment strategies are practices used to change or upgrade a running instance of an application. This blog post will discuss the different strategies and practices that can help you succeed with your production deployments. A canary deployment strategy releases an application or service incrementally to a subset of users in small phases (eg: 2%, 25%, 75%, 100% updated) A Canary deployment strategy is the lowest risk-prone to all other deployment strategies compared to other strategies. The Multi-Service Deployment strategy is used for application services that have service or version dependencies, or if you're deploying off-hours .

## [The Pitfalls of Serverless Computing](https://thechief.io/c/editorial/pitfalls-serverless-computing/)

Datadog has published the results of a survey that limits its analysis to the Serverless FaaS (Function as a Service) approach. The significant benefits of Serverless Computing necessarily come with limits and constraints that should not be overlooked or overlooked. The last year's survey of 501 IT professionals by Cloud Foundry found that companies need to be careful when switching to a Serverless architecture. Serverless is, without doubt, one of the cloud technologies on which the "Lock-in" effect is most potent, but the benefits are strong enough to offset this .

## [Pipelines: What, Why and beyond](https://rastogee-ayushi.medium.com/pipelines-what-why-and-beyond-cfb692a27ac7)

A pipeline is the process of taking code from version control and making it readily available to users of your application in an automated fashion. The purpose of a pipeline is to integrate the Development and Operations process of an application. CI is active till the code is merged into the main branch and after that CD is triggered. Pipeline is Continuous Integration and Continuous Deployment. Some popular tools to implement CI/CD pipelines are Travis, Jenkins, Argo CD, Spinnaker etc. But I would still prefer Tekton over them as: It is more intelligent in the sense that it doesn't need an additional engineer to regularly monitor and look into the pipeline .

## [Comparison of the Kubernetes Engines](https://www.kloia.com/blog/comparing-kubernetes-installation-options)

Many companies use Kubernetes to orchestrate containers nowadays. They have many options for provisioning and managing their clusters. For a highly-available, automated infrastructure, you need a framework that addresses the aspects above. We will talk about six tools to build your infrastructure framework today. These tools include EKS, AKS, GKE, Kops, K8s and GKE. Kops is a tool that helps you manage your clusters based on as-code principles. You can use the Kops cluster templating example for framework architecture .

## [[Docker] Quick Tips](https://medium.com/dev-genius/docker-quick-tips-dcc5d9a97256)

Containers are the way to go. From development environments to production. From small to big teams' collaboration and cross team smoother workflows. Plug and play different components of your system, swap versions, scaling... and the list goes on forever. Run your project everywhere and optimize as you go. Use containers to optimize your workflows and get the most out of your project. Use the containers to run your projects everywhere. Use them to help you get the best workflows you need to get your project on the ground.

## [How To Continuously Test and Deploy Your Helm Charts on Kubernetes Clusters Using Kind](https://betterprogramming.pub/how-to-continuously-test-and-deploy-your-helm-charts-on-kubernetes-clusters-using-kind-d71e3585d2dc)

Helm is a package manager-like approach to bundle applications as "charts" and "Kustomize" to package applications. Kustomize allows you to patch your original resources to produce new manifests and reach the desired configuration. In this article, I will show you how to build, test, and continuously deploy your Helm applications against real Kubernetes clusters. We will use GitLab CI and use a Docker-enabled environment, but anything will do. We will start by linting our chart using the ct utility to ensure it's working as intended .

## [7 Books to Boost your DevSecOps Career](https://thechief.io/c/editorial/7-books-boost-your-devsecops-career/)

DecvSecOps books with unique concentration areas to help you improve your cloud security game. This list comprises educating books that suit everyone - whether you're a beginner or a bit more experienced. The list includes: Epic Failures in DevSecOps: Volume 1 and Microservices Security in Action: Design secure microservices applications rather than normal enterprise applications. The book is written by a team of eight cloud security experts, including Edwin Kwan (an Application and Software Security Team Lead at Tyro Payments) and Chris Roberts .

## [Ten Signs You Don’t Understand This “Microservices” Thing](https://medium.datadriveninvestor.com/ten-signs-you-dont-understand-this-microservices-thing-b6b4ea49e12)

Microservices are small, loosely-coupled, self-contained units of software that communicate with each other via ReST or other protocols. Microservices offer a number of benefits, but the benefits won't magically materialize as you start deploying your microservices. You'll face added cost, complexity, and pain, but it's going to happen whether you like it or not. The biggest benefits of microservices lie not with the microservices themselves, but in the non-technical benefits that they unlock .

## [With Auth0 purchase, Okta Will Boost Access APIs for Developers](https://thenewstack.io/with-auth0-purchase-okta-will-boost-access-apis-for-developers/)

Okta agreed to pay $6.5 billion for Auth0, instead of continuing to compete against Auth0. Okta has targeted enterprise needs for identity and access management (IAM) for over a decade. Auth0 has channeled more of its efforts to meet what is seen as an increasingly urgent need among developers for a viable API authentication platform. The merger will make it easier to take advantage of Okta's existing top-down enterprise and go-to-market prowess in accelerating that growth .

## [Hassle-Free Database Migrations with Prisma Migrate](https://www.prisma.io/blog/prisma-migrate-ga-b5eno5g08d0b)

Prisma Migrate is a database schema migration tool that simplifies evolving the database. It makes migrations predictable and easy to verify and execute - especially for teams collaborating on a project. Migrate generates migrations as plain SQL files based on changes you make to your Prisma Schema. The generated migrations are fully customizable and allow you to use any underlying database feature, such as manipulating data supporting a migration, setting up triggers, stored procedures, and views. Migrations can be tracked in your Git repository, giving you insight into your Schema's evolution over time .

## [Docker Compose: From Local to Amazon ECS](https://www.docker.com/blog/docker-compose-from-local-to-amazon-ecs/)

Docker Compose is a very popular tool used to manage containerized applications deployed on Docker hosts. Deploying a containerized application to Amazon ECS is a most-wanted feature by many developers. We exercise how to run an application defined in a Compose file locally and how to build and ship its images to Docker Hub. This enables the images for the application frontend and backend stored in a public image registry such as Docker Hub to make them accessible from anywhere. We need to create a Docker context of the ECS type to target the platform. We assume at this point that we have AWS credentials set up in the local environment .

## [AWS: S3 storage now holds over 100 trillion objects](https://www.zdnet.com/article/aws-s3-storage-now-holds-over-100-trillion-objects/)

Amazon Web Services' cloud storage platform S3 or Simple Storage Service today stores over 100 trillion objects. AWS launched S3 publicly on March 14, 2006, four years after Amazon launched Amazon.com Web Services. S3 is designed to provide "eleven 9's of durability" meaning that an object stored in S3 has a durability of 99.999999999%. AWS S3 hit one trillion objects in 2012 while Microsoft, which launched Azure in 2008, had four trillion objects that year .

## [Gitlab default branch name changes to main](https://about.gitlab.com/blog/2021/03/10/new-git-default-branch-name/)

Git project maintainers have been listening to the development community's feedback on determining a more descriptive and inclusive name for the default branch. The default name for this initial branch was master, which is the first branch to be created when a new repository is generated. The GitLab project and its related projects will change their default branch name from master to main. The branch name change will be shipped under a feature flag under GitLab's 13.11 release, shipping on April 22, 2021. Existing projects will not be affected .

## [Nitro 2: The Docker powered development environment for Craft CMS](https://jamesmacwhite.medium.com/nitro-2-the-docker-powered-development-environment-for-craft-cms-2bb59728844e)

Nitro 2 is a tailored development environment for Craft CMS. Powered by Docker and WSL2, there is a smoother Windows environment option now available. Nitro uses official Craft CMS docker images, well suited to Craft CMS development. The add command, is for configuring an actual Craft CMS site, setting a hostname, the PHP version etc. You run this in the root of a Craft CMS project. The good news is, WSL is available on any SKU on Windows, so no more Windows 10 Pro Hyper-V dependency, that means any Windows 10 version can use Nitro .