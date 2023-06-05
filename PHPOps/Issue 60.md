# DevOps / SRE - Top Links Last Week

## Week 1 - Issue #60

  

## [Minecraft as a Kubernetes admin tool](https://eric-jadi.medium.com/minecraft-as-a-k8s-admin-tool-cf16f890de42)

KubeCraft Admin is an immersive 3D sandbox user interface to manage workloads on a container orchestrator. The project populates the world with different animals in different pens (one for each namespace). The animals each correspond to a resource in your k8s cluster. Animals will die when resources get deleted; conversely, killing an animal in Minecraft will delete the corresponding resource. The inspiration for the project came from watching a video on the MakeCode platform, which showed that it's possible through a WebSocket server to manipulate the world in Minecraft programmatically.

  

## [Don’t Leave Your Cluster Unguarded - Use Gatekeeper Instead](https://www.datree.io/resources/dont-leave-your-cluster-unguarded-use-gatekeeper-instead/#utm_source=phpops&utm_medium=medium_weekly)

  

OPA Gatekeeper is a sub-project of Open Policy Agent, specifically designed to implement OPA into a Kubernetes cluster. Gatekeeper provides a way to reduce dependency between DevOps admins and developers. It frees DevOps engineers from worrying about the developers making mistakes and provides developers with instant feedback about what went wrong and what they need to change. OPA is like a super-engine. You can write all your policies in it, then execute it with each input to check whether it violates any policies and, if so, in what way.

  

---- 

Support the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the Newsletter!

  

---- 

  

  

## [Monorepo vs Polyrepo: 5 Things You Should Consider](https://blog.bitsrc.io/monorepo-vs-polyrepo-5-things-you-should-consider-897f3b588e70)

  

A monorepo is a single repository for one or more projects. Polyrepos are the opposite of monorepos. Monorepos is responsible for source control, not source control. Monorepos have several advantages when working with polyrepos: Collaboration, collaboration, DevOps, test suites, automation scripts, infrastructure configurations in one place. However, Polyrepos requires you to either publish your shared code as a library or use git-submodule. In a Monorepo, the main advantage is that each component receives the latest version of the shared code.

  

  

## [Kubernetes Networking 101](https://www.nginx.com/blog/kubernetes-networking-101/)

The default model is kube-proxy, which is not a proxy, and isn't designed to load balance traffic, control APIs, or monitor service behaviors. A service connects pods in a cluster or network of containers such that their location on a specific node is not relevant. In this situation, this means external traffic can be routed to particular pods even as their locations change or even when they are destroyed and restarted. There are multiple services and service object types relevant to routing external traffic into Kubernetes.

  

## [6 Top DevOps Technology Trends to Watch](https://devops.com/6-top-devops-technology-trends-to-watch/)

As the world enters a post-digital era, organizations explore disruptive technology trends. Artificial intelligence, machine learning, intelligent process automation, advanced analytics, and robotic process automation (RPA) are among the top DevOps technology trends to watch. In a survey by Accenture, 94% of IT and business experts reported that emerging technologies have accelerated firms' innovation pace in the last three years. As a result, a close eye on the different trends can help organizations optimize their business processes and adapt to the changing market needs.

  

## [Monitoring CI/CD Workflows](https://faun.pub/monitoring-ci-cd-workflows-1fbf78f6b91c)

CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. This article will examine how to monitor a pipeline that uses Github Actions by using the Foresight product of Thundra, where I am employed. I chose Payara and dcm4che for this article because they have significant build and test run time to understand the difficulty of monitoring workflows. As a result, we can inspect the projects' workflow success and average duration day by day.

  

## [Ensuring Resilience for Stateful Kubernetes](https://containerjournal.com/features/ensuring-resilience-for-stateful-kubernetes/)

Kubernetes is the de-facto standard for new application deployments in the public cloud. As companies migrate more workloads into K8s, they often encounter application uptime and resiliency issues. The road to stateful, resilient operations is a long one. It requires knowledge of storage, networking, and replication. Many teams lack the capital, staffing, or expertise to do it themselves. The skillset necessary to build storage infrastructures differs significantly from what most DevOps professionals are trained to (or have time to) handle.

  

## [Deploying a Custom Docker Image Using Nginx and Saving it to Amazon ECR](https://faun.pub/deploying-a-custom-image-using-nginx-and-saving-to-amazon-ecr-644a09df2089)

  

This tutorial assumes that you have a Docker account and an AWS account. The first command you need to use is docker pull nginx:latest. This will pull the latest version of the Nginx image from Dockerhub. Next, we need to create a folder for our files to go. Once you have made the directory and the file, use your text editor to go into and edit the file you created. This is the file we will use to store our code for the program we want to make.

  

  

## [How to Scan Git Repository for Secrets & Credentials?](https://faun.pub/how-to-scan-git-repository-for-secrets-credentials-4b397e720cab)

The name of the tool is GitGuardian, but we are not going to be using the web interface of this tool. Instead, we will be using its CLI tool ggshield to generate an API and create a pipeline that will trigger based on a specific tag that we'll release at the interval of every 15 days. The pipeline will start when the tag is released. Then, it will begin this pipeline and run a ggshield scan command that will scan the last commit of the repo.

  

## [Ingress Controllers: The Swiss Army Knife of Kubernetes](https://thenewstack.io/ingress-controllers-the-swiss-army-knife-of-kubernetes/)

  

Brian Ehlert is a senior technical product manager at F5 Inc., where he product manages NGINX Ingress Controller. When deployed and configured correctly, ingress controllers can radically simplify the operation of Kubernetes clusters. They can work standalone to balance and shape traffic or work with your load balancer. Do you need both a load balancing and an ingress controller? It depends on who uses the tool and where it's being deployed. Ingress controllers can provide a granular and integrated layer to security that works for "shift-left stances and better integrates with lower stances."

  

  

## [What is Kubernetes ?—Beginner’s Guide 2022](https://shahneil.medium.com/6427f8bd578a)

A deployment runs many copies of your program and automatically replaces any that fail or become unresponsive. Deployments/Workloads are a collection of many identical Pods with no distinguishing characteristics. They assist in ensuring that one or more instances of your application are accessible to serve user requests in this fashion. There are several things like initContainers and side-car containers; we will discuss them more in our next article. First, we will be focusing on the fundamental overview to get started learning Kubernetes on our own.

  

## [Getting Started with CronJobs in Kubernetes](https://faun.pub/getting-started-with-cronjobs-in-kubernetes-d3cfce10fd9b)

Getting Started with CronJobs in Kubernetes is easy to get your application running in a Docker environment. The CronJob helps you run your task at a given schedule to define at what time it should run to complete your job. When you add a CronJob for your application, there's a separate area in the configuration file for you to set up your schedule. It could be hourly, weekly, monthly, or you can set any other time you prefer.

  

## [Will Grafana Become Easier to Use in 2022?](https://thenewstack.io/will-grafana-become-easier-to-use-in-2022/)

Grafana counts 800,000 active installs and over 10 million users, according to the open-source project's statistics. In addition, GitHub stars and forks total over 46,000 and 9,000, respectively. As a result, many users can be overwhelmed with the number of logs and other data to process for monitoring and observability. The company seeks to help users better manage the explosion of data many DevOps teams must process to interpret metrics and log data. However, an analyst at Enterprise Management Associates said it remains a work in progress.

  

## [How elite DevOps teams secure the software supply chain](https://about.gitlab.com/blog/2022/01/06/elite-team-strategies-to-secure-software-supply-chains/)

Every DevOps team should strive to be an elite team in this area, DevSecOps. Google Cloud's DevOps Research and Assessment (DORA) team concluded in its "Accelerate State of DevOps 2021 Report" Teams that integrate security practices throughout their development process are 1.6 times more likely to meet or exceed their organizational goals. In addition, elite performers that met or exceeded reliability targets were twice as likely to have security integrated into their DevOps development process.

  

## [Monitor AWS resources created by Terraform in Amazon DevOps Guru using tfdevops](https://aws.amazon.com/blogs/devops/monitor-aws-resources-created-by-terraform-in-amazon-devops-guru-using-tfdevops/)

Amazon DevOps Guru is a machine learning (ML) powered service that helps developers and operators automatically detect anomalies and improve application availability. For Terraform users, Stacklet developed an open-source tool called tfdevops, which converts Terraform state to an importable CloudFormation stack. TFdevops creates an AWS cloud formation stack with imported resources specified in the Terraform module and enables DevOps Guru to monitor the resources in that stack. The following diagram depicts our sample serverless application that includes some of the components of DevOps.

  

## [How is security managed in Kubernetes clusters?](https://blog.devgenius.io/how-is-security-managed-in-kubernetes-clusters-addefffd2b0)

The Log4j vulnerability was all over the news affecting thousands of java applications running in production sites. Cloud security combines security controls at various levels viz, application, cluster, and host OS. The topmost layer of security is at the application level and comes under the consideration of the app developers. Containerization provides the ability to isolate application data and resources from one another, but that is not enough for security isolation. They said that cluster level and underlying host OS level security should be the responsibility of the managed cloud providers.

  

## [Adding Security to the Developer’s Workflow](https://thenewstack.io/adding-security-to-the-developers-workflow/)

Rey Bango is the Senior Director of Developer and Security Relations at Veracode. He says developers today are being asked to perform tasks and accept responsibilities that might not have existed when they first started the job. The demand for developers is growing, with hiring for engineering roles up 25% year-over-year from the past two years. Only 3% of U.S. college degrees offer cybersecurity, but demand forces more schools to include application security in their curriculums. As a result, security teams are beginning to lean on developers to help manage current needs.

  

## [Want to Create REST APIs Without Any Server? Go Serverless](https://betterprogramming.pub/create-rest-apis-without-any-server-a4059f8ab443)

Serverless is a cloud-based development model where you don't need to own any servers; but instead, Developers can run independently from worrying about the operation. We will use AWS services to create our REST API for this tutorial. We will not write any code in this article as this is an article to get you familiar with how to go with designing your API without any server. AWS gives around 1M free API calls to your Lambda code, and the functions will be executed very fast because when running your code, AWS allocates resources to it and executes the code.

  

## [Tutorial: A GitOps Deployment with Flux on DigitalOcean Kubernetes](https://thenewstack.io/tutorial-a-gitops-deployment-with-flux-on-digitalocean-kubernetes/)

Weaveworks managed open-source Flux will be used to bootstrap GitOps, configure Ingress infrastructure, and finally deploy the application. This tutorial aims to show at-scale deployment targeting multiple Kubernetes clusters. We will incrementally add an ingress component (infrastructure) packaged as a Helm Chart and a web application declared in a set of YAML files to the repo, eventually reconciled across all the clusters. By the end of this step, we should have three groups running in the Digital Ocean cloud platform regions.

  

## [Kubernetes Hardening Tutorial Part 1: Pods](https://medium.com/gitguardian/kubernetes-hardening-tutorial-part-1-pods-74f823e45a26?source=rss------devops-5)

By default, the Docker container will run as the root user. If an image doesn't have a USER instruction, K8s will still allow it to do so. By adding this line in the Dockerfile, we have changed the container's user. If the image runs as root, it will fail at deployment. To lock the container in the container spec, add one line into the security context section: "Read-only."

  

## [Managing Multiple Environments with Weave GitOps](https://www.weave.works/blog/managing-multiple-environments-with-weave-gitops)

Weave GitOps allows you to manage a single application deployed into multiple environments, for example, staging and production. Managing numerous application instances across various Environments is also known as Application Portability. There are two strategies for managing different configurations of the same application in different environments. First, using GitOps, the branch to monitor can be set when the application is added to each Environment. Using Kustomize requires a little more effort and complexity to implement. Still, it ultimately provides greater flexibility while reducing the risk of accidentally merging in a staging configuration into a production environment.

  

## [FTC Says Fix Log4j Security Vulnerability or Face Its Wrath](https://thenewstack.io/ftc-says-fix-log4j-security-vulnerability-or-face-its-wrath/)

The FTC wants to make sure there's no repeat of the Equifax fiasco. The Equifax hack lost over 100-million names, social security numbers, birthdates, and home addresses. The FTC intends to use its full legal authority to pursue companies that fail to take reasonable steps to protect consumer data from exposure due to Log4j or similar known vulnerabilities in the future. The Commission concluded: "Log4j vulnerability is part of a broader set of structural issues that endanger user security"

  

## [Development Teams Should Stop Using the Term Technical Debt](https://itnext.io/development-teams-should-stop-using-the-term-technical-debt-471285fc0bf)

Ward Cunningham coined the term technical debt back in 1992. According to a Wikipedia article, technical debt is a concept in software development that reflects the implied cost of additional rework caused by choosing an easy (limited) solution instead of using a better approach that would take longer. Technical debt sounds like the development team is guilty of poor development. Development teams should stop using technical debt and explain the causes and benefits of fixing technical debt more accurately. Unfortunately, the term is terrible because it means something different to every developer who mentions it.

  

## [How I designed and built Lumeno’s recruitment search engine](https://itnext.io/how-i-designed-and-built-lumenos-recruitment-search-engine-d8918b3500)

Lumeno is an (in-development) portfolio site for software developers. It also includes article publishing and tweet-style mini-posts for more minor announcements like open-source projects. Unfortunately, the Lumeno search engine is just a large database query. I could have built the Query within a single class; however, this also becomes unwieldy over time. So instead, I opted to extract each query feature to a dedicated Class. The class will return the Query with any relevant modifications made to it.

  

\<sub\>*Datree are sponsors of the phpops project*\</sub\>