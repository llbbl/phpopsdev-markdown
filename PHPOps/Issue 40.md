# DevOps / SRE — Top Links Last Week

## Week 33 Issue #40

## [9 DevOps Rules for Startups To Move Fast In 2021](https://betterprogramming.pub/9-devops-rules-for-startups-to-move-fast-in-2021-5fca2158b001)

Infrastructure-as-code is to use a system like Terraform to write all of your infrastructure configurations in a declarative language. This allows you to use version control and enjoy all of its benefits, including code review, change tracking, etc. The biggest advantage for a startup is that you can rebuild your entire infrastructure in just a few minutes. Serverless technology is still somewhat nascent and may be challenging to set up for a complex application with Terraform. Docker lets you stand up complex infrastructure quickly and rebuild containers in a matter of seconds.

## [The Prefect Way to Automate & Orchestrate Data Pipelines](https://towardsdatascience.com/the-prefect-way-to-automate-orchestrate-data-pipelines-d4465638bac2)

Prefect is both a minimal and complete workflow management tool. It can do everything tools such as Airflow can and more. It’s a straightforward yet everyday use case of workflow management tools — ETL tools. Prefect's scheduling API is straightforward for any Python programmer. You can use PyPI, Conda, or Pipenv to install it, and it's ready to rock. It ships with a server with a beautiful UI and a beautiful server with beautiful server executions. It allows you to control your workflows in a cron-like manner.

---

## [TIL: Press '.' In a GitHub Repo for Magic](https://github.com/ansible/ansible-lint-action)

(Hint: It opens the CodeEditor) Here is a random helpful repo to try it on.  
Ansible Lint for GitHub Action allows you to run ansible-lint with no additional options. To use the action simply create an ansible lint.yml (or choose custom *.yml name) in the.github/workflows/ directory. The action has been created by Stefan Stölzle at stoe/actions.org. The Dockerfile and associated scripts and documentation in this project are released under the MIT.releasing under the. MIT.

## [Deploy Docker Image To Kubernetes Cluster Using Jenkins](https://bharathirajatut.medium.com/deploy-docker-image-to-kubernetes-cluster-using-jenkins-8182cc0a8de7)

Previously we have seen how to push the Docker image to the Docker hub using Jenkins. This article is a continuation of the previous article. In order to understand this article fully, you already need to know the CI/CD pipeline. The pre-requisite list is given below. I used the Linode Cloud server in this example including the Kubernetes cluster. NodeJS and Git are to be installed on the local computer. Create an account on BitBucket. Create a Deployment file on your local computer and test the Deployment Pipeline.

## [Why we need Kubernetes GUI Clients? Best Kubernetes GUI Clients in 2021 !](https://faun.pub/why-we-need-kubernetes-gui-clients-best-kubernetes-gui-clients-in-2021-a820053c0499)

Kubernetes Dashboard gives an overview of applications running on your cluster. Lens is an Electron-based application (support Windows, MacOS, Linux) Octant is a web UI for developers to understand what happened in the Kubernees cluster. Octant reads the cluster setting from your local ~/.kube/config / $KUBECONFIG. It is one of the powerful KuberNETes UI that I have ever used. It supports CRD and Helm3 (rare since it was released very recently.

## [Ransomware Mitigation Steps to Take Now — Or Else](https://thenewstack.io/ransomware-mitigation-steps-to-take-now-or-else/)

A proliferation of ransomware attacks has created ripple effects worldwide. Such criminal attacks have since increased in scale and magnitude, as critical hospital and infrastructure targets were shut down. IT departments are generally ill-prepared to properly mitigate the attacks or apply damage-control processes when they occur. But there are mitigating measures that can be taken that are more accessible than you might think in order for your organization to become reasonably secure against ransomware attacks. In June, the U.S. government released a memo that reflected the severity of ransomware threats.

## [An Introduction to Kubernetes Operations: Set Up a Kubernetes Cluster on AWS using kOps](https://aws.plainenglish.io/an-introduction-and-setting-up-kubernetes-cluster-on-aws-using-kops-7cfa40901d8e)

Using kops is the easiest way to get a production-grade Kubernetes cluster up and running in cloud infrastructure. It helps us to create, destroy, upgrade and maintain production, highly available and highly available clusters. The tool is free to use, but you are responsible for paying for and maintaining the underlying infrastructure created by kops. Kops is an open-source tool and it is completely free. It is currently officially supported, with DigitalOcean, GCE, and OpenStack in beta support, and Azure and AliCloud in alpha.

## [Using Envoy for Egress Traffic](https://blog.palantir.com/using-envoy-for-egress-traffic-8524d10b5ee2)

Palantir’s Network Infrastructure team will share our recent experience transitioning to Envoy to enable granular egress traffic filtering for the forward proxy in Rubix. Envoy is an open-source, high-performance edge and service proxy with built-in features for L4/L7 filtering, service discovery, dynamic configuration, and more. In this blog post, we will explain the motivation to switch from Squid to the Envoy forward proxy configuration. We wanted to shift control of egress and ingress traffic filter configuration management away from Rubix and into the Foundry platform.

## [Have your Lambda Functions Connect to RDS through RDS Proxy](https://aws.plainenglish.io/have-your-lambda-functions-connect-to-rds-through-rds-proxy-c94072560eee)

RDS Proxy is a database connection pool designed to handle and scale many concurrent connections. It is AWS’s serverless response to Lambda not being able to utilize a standard connection pool, like the one available in the mysql2 library. Using services like API Gateway, Lambda, Aurora, and RDS proxy will give you a fully serverless solution. The easiest way to set this up is to have a single security group for each of our resources (Lambda, RDS proxies)

## [How I Helped Stop an Outage While Drunk](https://betterprogramming.pub/how-i-helped-stop-an-outage-while-drunk-d811a6ef1e59)

There were network issues in the two most popular data centers where we used to host our internal services. Any requests issued to services in those data centers would timeout and fail. Multiple services had been impacted and multiple teams paged in. An update to a batch job had introduced a bug that led to massive outages in two data centers. The engineer was invited to a party at a friend’s apartment earlier that evening. He was in no state to deal with an incident, but a video chat was created to help coordinate the multi-team effort.

## [Edge Computing: Tech’s Next Trillion-Dollar Opportunity](https://devops.com/edge-computing-techs-next-trillion-dollar-opportunity/) 

By 2025, the number of connected devices in use is expected to exceed 56 billion units, according to IDC. Organizations need to process and analyze data at the point where it is both created and consumed. Edge computing is not a successor to the cloud, but another expansion of technology’s reach that represents an exceptional opportunity for investment and growth. The challenge now is that the amount of data being generated at the edge often exceeds the point when it is practical to transfer that volume of raw data across a wide area network (WAN)

## [This Week in Programming: GitHub Discussions Goes Live](https://thenewstack.io/this-week-in-programming-github-discussions-goes-live/)

GitHub announced it is moving GitHub Discussions out of beta and making it generally available. The feature was first introduced into public beta in December 2020 and made available to private repositories last March. GitHub has introduced Spamcheck, an anti-spam engine that it says is already enabled for all projects on GitLab.com and will be enabled to the self-hosted version with the release of GitLab 14.2 on Aug. 22. More features are on the way, such as taking polls and monitoring your community with “a dashboard full of actionable data”

## [Using AWS CodePipeline for deploying container images to AWS Lambda Functions](https://aws.amazon.com/blogs/devops/using-aws-codepipeline-for-deploying-container-images-to-aws-lambda-functions/)

AWS Lambda launched support for packaging Lambda functions as container images at re:Invent 2020. This post will teach you to use AWS CodePipeline to deploy docker images for microservices architecture involving multiple Lambda Functions and a common layer utilized as a separate container image. The application code used in this post is a simpler version taken from Serverless DataLake Framework (SDLF) For example, the application code is taken from SDLF, which is a simple version of Serverless.

## [10 Challenging Aspects of Software Engineering](https://betterprogramming.pub/10-challenging-aspects-of-software-engineering-928b4a776c94)

10 Challenging Aspects of Software Engineering: Backups and Preventing Accidental Deletion. Engineering time is a scarce resource, but there are some activities for which allocating more of that time can be beneficial. The most popular tool may not necessarily be the best for the best problem at hand at the hand at hand. Don’t: rush implementing the first drafts or the most popular design tool. Take as much time as needed to understand the code and the intentions behind it and question whether everything works as expected.

## [A First Impression of AWS App Runner](https://www.jeroenreijn.com/2021/08/a-first-impression-of-aws-app-runner.html)

AWS App Runner is a new service that provides organizations with a fast, simple, and secure way to deploy containerized applications on the AWS platform without managing any infrastructure. With App Runner, rather than thinking about servers or scaling, you have more time to focus on your applications. There is no native support for Parameter Store or Secrets Manager when configuring an App Runner service. The service is currently only available in a few regions: Europe (Ireland), Asia Pacific (Tokyo), US East (N. Virginia) and US West (Oregon)

## [Building Container Images with Nix](https://thewagner.net/blog/2021/02/25/building-container-images-with-nix/)

Dockerfile is de facto standard for creating container images. In this article I highlight some issues with this approach and I propose building container images with Nix. In the next section we’ll see how novice users write their Dockerfile. The ideal container image contains the application and the application’s dependencies and nothing else. This technique does and does solve all the issues raised in the previous section. The next section shows how to build a container image from scratch from a Dockerfile repository.

## [AWS introduces Amazon MemoryDB for Redis](https://www.zdnet.com/article/aws-introduces-amazon-memorydb-for-redis/)

Amazon Web Services is releasing Amazon MemoryDB for Redis, a real-time database implementation. MemoryDB is based in part on the open source Redis platform, but adds durability and persistence. AWS positions this as targeted for customers who require a full-blown database service. The new service is AWS's answer to Redis Enterprise, the company offered by Redis. It will perform micro-digit-second reads and single-digit reads, single writes and single writes of data to Flash storage.

## [4 Steps To Dockerize Your Node.js Apps](https://betterprogramming.pub/4-steps-to-dockerize-your-node-js-apps-c70037da1099?source=rss----d0b105d10f0a---4)

Docker is a unit of software that helps us package our code and our dependencies compactly. The main advantage of this is it helps our apps to run efficiently and reliably in various environments. Docker containers help us provide uniformity that Docker containers provide is crucial, especially when deploying apps for production. There are four steps to Dockerize your Node.js app using the four-step guide to Docker. The guide is based on the Docker Compose, a tool for running multicontainer apps with the Docker Engine.

## [Top 5 Best PHP Frameworks To Consider In 2021](https://blog.devgenius.io/top-5-best-php-frameworks-to-consider-in-2021-96ae1226218b)

PHP is the most extensively used programming language on the internet, powering sites like Facebook and Wikipedia. PHP frameworks enable increased productivity and the development of powerful applications on a solid and well-tested base. Frameworks can offset some of the PHP language’s shortcomings, making them a safe bet for even the most demanding applications. By the end of this article, you’ll have a firm grasp of which PHP frameworks are most suited to your unique web development requirements. PHP is fortunate in that it is one of the easiest programming languages to learn.

## [Artifact Registry: the next generation of Container Registry](https://cloud.google.com/blog/products/application-development/understanding-artifact-registry-vs-container-registry/)

Artifact Registry is a fully-managed service with support for both container images and non-container artifacts. It includes OS packages for Debian and RPM, as well as language packages for popular languages like Python, Java, and Node.org. Artifact Registry includes more than just container images: as a developer, you can store multiple artifact formats. It can use Container Analysis to scan your container images for vulnerabilities as they’re uploaded to Artifact Registry, and works directly with Binary Authorization to secure deployments.

## [IBM, Red Hat Bring Load-Aware Resource Management to Kubernetes](https://thenewstack.io/ibm-red-hat-bring-load-aware-resource-management-to-kubernetes/)

IBM Research and Red Hat OpenShift have released two open source Kubernetes solutions. IBM's Trimaran and Vertical Pod Autoscaler work to “factor in the actual usage on the worker nodes’s worker nodes,” as IBM writes in a blog post. VPA manages scale by reviewing both historic and current CPU and memory usages for containers in pods and then updating resource limits and requests based on those values. Both solutions approach the same problem from opposite sides.

## [Git 2.33](https://github.blog/2021-08-16-highlights-from-git-2-33/)

Git has better performance when there are fewer packs, since many operations scale with the number of packs in a repository. Git learned a new “geometric” repacking strategy. The idea is to determine a (small-ish) set of packs which could be combined together so that the remaining packs form a geometric progression based on object size. Git then decides that at least the first two packs will be contained in a new pack which is designed to restore the geometric progression. It then needs to figure out how many larger packs must get rolled up in order to maintain the progression.

## [Web3.Storage: Free Decentralized Storage on Filecoin](https://thenewstack.io/web3-storage-free-decentralized-storage-on-filecoin/)

Protocol Labs has launched Web3.Storage to offer developers and other users an alternative for decentralized storage. It is built on Filecoin, an open source blockchain-based payment system that can provide bookkeeping for users who wish to rent unused hard drive space. The platform will remain free indefinitely as a simple and “hassle-free” way to upload data on the redundant storage capacity that storage providers offer in exchange for cryptocurrency Filecoin block rewards. The aim was to give developers a pathway to provable storage today — without having to worry about a single provider going down and data being lost.

## [GitHub Kisses Passwords Goodbye](https://thenewstack.io/github-kisses-passwords-goodbye/)

As of Aug. 13, GitHub blocked the use of account passwords when authenticating Git operations. Instead, Git now requires you to use two-factor authentication (2FA) factors to use its core Git services. These factors can include personal access tokens; SSH keys, for developers; or OAuth or GitHub App installation tokens for integrators. GitHub warned this was coming eight months ago, but there’s still a lot of grumbling about it. Microsoft wants to see the end of passwords sooner rather than later.

## [9 Steps To Master Delegation as a Leader](https://betterprogramming.pub/9-steps-to-master-delegation-as-a-leader-176686c2c65b?source=rss----d0b105d10f0a---4)

Most leaders spend a career winging it when it comes to delegation. Delegation is too important to your success to leave it to chance. The Conference Board surveyed 78% of personnel surveyed said that their boss “routinely does work that would be more effectively done by someone at my level” If you’re a leader, the process can be a difference-maker. Just reverse-engineer the process, and your results will skyrocket. I’ll show you how.

## [Introduction to Top 5 Security, Identity, and Compliance Services with AWS](https://harsh-patel.medium.com/introduction-to-top-5-security-identity-and-compliance-with-aws-285bf0a5badd)

In this blog post, we will discuss some of the most important AWS security services that protect your data, accounts, and workloads from unauthorized access.

## [Build Docker Images Using Ansible and Packer](https://getbetterdevops.io/build-docker-images-using-ansible-and-packer/)

We will see how to configure Packer through manifests. There will be two manifests, one to build the image locally and the other remotely. We will persist the remote image in the Docker registry. For both manifests, we will use the Ansible provisioner and Docker post-processors. The prerequisites presented here are for MacOSX. For Docker, I use Docker for Desktop and for Desktop. For the Packer image, we use Terraform to deploy and configure AWS ECR.

## [I Beta Tested OpenAI’s Codex, and the Results Are Spooky Good](https://betterprogramming.pub/i-beta-tested-openais-codex-and-the-results-are-spooky-good-e282a1874c79?source=rss----d0b105d10f0a---4)

OpenAI’s Codex is a new deep-learning-driven platform that writes fully functioning software code automatically. The system can generate everything from fully-formed blog posts to recipes. It was originally debuted as part of GitHub's Copilot, a feature that helps programmers improve or update their software. Codex is based on OpenAI's wildly successful GPT-3 which was specifically trained on code and optimized to produce it. The results are spooky to watch the system rapidly type out a solution in about two seconds.

## [How To Build a Self-Updating Twitter Banner With Dynamic Content](https://betterprogramming.pub/how-to-build-a-self-updating-twitter-banner-with-dynamic-content-7c3fedcfca25?source=rss----d0b105d10f0a---4)

How To Build a Self-Updating Twitter Banner With Dynamic Content? How To build this with a simple Node.js script, the Twitter and Medium APIs, and AWS Lambda. Display your latest blog articles or your most recent followers without paying a dime. The possibilities are limitless in this article. The solution won’t result in any costs due to AWS’ free tier for Lambda. Even though we’ll be creating infrastructure at AWS, this solution won't result in costs.

## [PHP 8.1 made me delete these 30 lines of code](https://darkghosthunter.medium.com/php-8-1-made-me-delete-these-30-lines-of-code-1a6bd6a0826f)

PHP 8.1 is just around the corner, around a bunch of RFCs that got approved for the sake of making the developer write less. There are two key features that are introduced in the new version. The developer can still change the user name, but not the property. The new readonly keyword makes the property non-writable. The most common pattern is to add default values as strings, integers, floats, or null, and just then initialize it in the class constructor.