# DevOps / SRE - Top Links Last Week

## Week 21 - Issue #80

28 links


## [The Story of Heroku](https://leerob.io/blog/heroku)

Heroku made it easy for developers to build and run applications in the cloud without managing their infrastructure. Salesforce bought Heroku for $212 million in 2010. Fifteen years later, Heroku continues to inspire the next generation of developers. The first version of Heroku created in 2007 was an in-browser code editor to make it easy to build Ruby applications and deploy them to the cloud. Developers wanted to spend less time configuring infrastructure and more time building their applications.

  

## [Container Security: Manage Secrets with Portainer](https://thenewstack.io/container-security-manage-secrets-with-portainer/)

Portainer is one of the most powerful Docker (and Docker Swarm) managers. With this tool, you can create and manage every aspect of your container deployments, including managing services, networks, images, registries, volumes, configs, stacks, orchestration, and even secrets. Portainer makes it easy to work with secrets. I've yet to come across a more straightforward method of managing/using secrets. I'm going to show you how to do just that.

  

  

## [Monitor Linux Memory Metrics in AWS CloudWatch](https://aws.plainenglish.io/monitor-linux-memory-metrics-in-aws-cloudwatch-ec3277beceab)

Here is how to install the CloudWatch agent in Ubuntu 20.04 and get memory metrics in the CloudWatch console. We can set up an Alarm to trigger notifications or any action by calling the memory metrics. We use CloudWatch to authenticate to push metrics on our EC2 EC2 instance. We then create an IAM role with the following steps. If you already have an EC2 launched, you can skip this step. Let's run this as root to avoid the Use of 's3.amazon' in every command.

  

## [Mintlify taps AI to automatically generate documentation from code](https://techcrunch.com/2022/05/30/mintlify-taps-ai-to-automatically-generate-documentation-from-code/)

Mintlify, a startup developing software to automate software documentation tasks, has raised $2.8 million in a seed round. The company's platform reads code and creates documentation to explain it, leveraging natural language processing and web scraping technologies. The proceeds will be put toward product development and doubling Mintlifying's core, three-person team by the end of the year. Mintlified is free for individual developers and integrates with Slack, Dropbox, and GitHub for automating task management and development workflows.

  

## [Introducing Terramate — An Orchestrator and Code Generator for Terraform](https://blog.mineiros.io/introducing-terramate-an-orchestrator-and-code-generator-for-terraform-5e538c9ee055)

Mineiros' Terramate is an Orchestrator and Code Generator for Infrastructure as Code (IaC) tool for Terraform. It aims to solve the problems of splitting Terraform code into smaller independent units that we call stacks. Each stack keeps its state, and the definition for the backend that Terraform uses to store its state permanently is the version of Terraform to use. We hope to solve these problems as efficiently as possible in a non-intrusive way. We also hope to use the tool to generate HCL (HCL Configuration Language)

  

---

  

## [Kubernetes Best Practices](https://spacelift.io/blog/kubernetes-best-practices)

Kubernetes (K8s) is the de-facto standard for modern cloud engineers. K8s is a notoriously complex system to use and maintain, so getting a good grasp of what you should and should not be doing will get your deployment off to a solid start. These recommendations cover common issues within three broad categories, application development, governance, and cluster configuration. Use readiness and liveness probes to ensure that requests to a pod are only directed to it when the pod is ready to serve requests.

  

## [Everything that makes working with databases easier](https://github.com/mgramin/awesome-db-tools)

Excellent Database Tools are a community-driven list of database tools that simplify working with databases for DBA, DevOps, Developers, and mere mortals. Feel free to add information about your DB tools or your favorite third-party database tools. 

  

## [Graviton 3: First Impressions](https://chipsandcheese.com/2022/05/29/graviton-3-first-impressions/)

In late May of 2022, AWS released Graviton 3 to the general public. It was the first ARM CPU to introduce the SVE instruction set to a widely accessible server CPU. Compared to Neoverse N1, ARM has dramatically improved the branch predictor and made significant speed and accuracy strides. The main BTB provides zero-bubble taken branch capability that exceeds Zen 3's. Even hitting the L2 BTB is not very expensive with just one or two pipeline bubbles per branch with 10K branches in play.

  

## [Stop putting AWS credentials in the credentials file](https://www.itscava.com/stop-putting-aws-credentials-in-the-credentials-file)

This article aims to overview what IAM Principals are and the better ways to manage your programmatic access to AWS. It's an authentication process, not a Principal, so it cannot be used directly as a principal. Instead, the provider pushes users to use IAM Roles to manage their access to SSO Identities. AWS SSO allows for authentication inside AWS by external meanings, but it does not handle authorization against AWS services. It can be a pain to manage as we know that SSO is not a principal, so needs a way to manage it.

  

## [Zero-Downtime Deployment in Kubernetes](https://blog.devgenius.io/zero-downtime-deployment-in-kubernetes-fe7470210b6a)

The "magic" where you can deliver value without notifying your users about the "maintenance period" is a deal-breaker in this era of hyper-growth. However, it's not always easy to achieve zero-downtime deployment in Kubernetes. In this post, I will guide you through creating a zero-downtime deployment using the rolling method. I'm using Google Cloud Provider (GCP) to provision the GKE cluster. But, first, we need to "manually" create our subnets, which the cluster will use.

  

## [Embrace the Mono-repo!](https://blog.devgenius.io/embrace-the-mono-repo-3efcd09a38f8)

There are generally two extremes of how software teams manage their source control. First, each discrete project or application scope has its repository. In between these extremes are hybrid repos, which are poly-mono-repos. But for most teams — mainly startups — I believe that the mono-repo is the way to go. The "Root" problem is about the file system, and there is no exact correlation between poly-recovery and micro-services.

  

## [Terraform should have remained stateless](https://www.bejarano.io/terraform-stateless/)

Terraform's official docs explain why "state is required" and why stateless Terraform "would require shifting massive amounts of complexity from one place to another," but I'm not sold on the documents' reasoning. For example, Terraform's first reason to justify using the state is that it needs a way to map configuration resources to help the provider. The second reason stated in the document is storing metadata "such as resource dependencies."

  

## [AWS SNS vs. SQS – Main Differences](https://blog.serverlessq.com/aws-sns-vs-sqs-what-are-the-main-differences)

Amazon Simple Notification Service and Amazon Simple Queue Service (SNS) are entirely different services. This blog post will explain the similarities, differences, and how to choose which service. SNS is a fully managed publish and subscribe service. SQS is poll-based and not push-based, and SNS has a many-to-one relationship. The main difference lies in the foundation of the services, the push, and poll--based service.

  

  

## [How to Set Up CI/CD Pipeline For Cloudflare Worker](https://betterprogramming.pub/how-to-set-up-ci-cd-pipeline-for-cloudflare-worker-dbd3603b9c52)

Set Up CI/CD Pipeline For Cloudflare Worker: Using GitHub Actions with Wrangler, k6, and semantic release. We'll be running smoke tests for this project whenever commits are pushed to our main branch. In this case, running a smoke test is an integration test that performs a system sanity check. We'll be using a Grafana k6 to test performance and load testing. We need a Staging environment to deploy to run our integration test against it.

  

## [What's new in Ansible Automation Platform 2.2](https://www.ansible.com/blog/whats-new-in-ansible-automation-platform-2.2)

The Ansible product team at Red Hat is thrilled to announce the general availability of Red Hat Ansible Automation Platform 2.2. The release includes numerous features and bug fixes that further solidify the de facto enterprise IT automation solution for developers to operations teams in data centers, clouds, and at the edge. New features include an automation topology viewer that allows operators to graphically visualize how automation nodes are connected. Red Hat's Ansible Certified Content Collections to be digitally signed in the Ansible automation hub.

  

## [How to create Ansible Inventory with Terraform?](https://faun.pub/how-to-create-ansible-inventory-with-terraform-a32fcbe11be6)

Terraform is the go tool to provision your infrastructure and all the VM you need to run your applications. For example, Ansible uses an inventory file to know which server to connect to and how to configure them. Terraform allows you to create the file using Terraform, then save the inventory file as a GitHub secret on Terraform again. The INI format is the most popular as it is simple, easy to ready, and generated programmatically. For each node and manager, we add a line with a unique name, IP, and user to connect with. For example, I use DigitalOcean to create one VM.

  

## [Setting up Config Connector with Terraform & Helm](https://medium.com/google-cloud/setting-up-config-connector-with-terraform-helm-8ce2f45f48a4)

Setting up Config Connector with Terraform & Helm is a Kubernetes add-on that allows you to manage Google Cloud resources. You can easily enable it for any GKE cluster matching the minimum requirements. This article will utilize a cluster scoped config connector, which means that we have only one service account provisioning all GCP resources across all namespaces. In addition, the account will need IAM permissions within the project and one specific IAM binding allowing the config connector to impersonate the GSA.

  

## [My observations of the Python ecosystem](https://blog.tanka.la/2022/05/26/my-observations-of-the-python-ecosystem/)

Pareto principle(80/20 rule) came into mind, and I started digging into the data I have about python packages and then found exciting things. Most of the top 5 python packages are created by none other than Amazon Web Services. Microsoft has the highest packages(97) in the top 1000 packages. Google has 47 packages, and their downloads contribution comes to around 4.2% of the total downloads. The average age of python packages is 7.5 years.

  

## [We use Dependabot to secure GitHub](https://github.blog/2022-05-25-how-we-use-dependabot-to-secure-github/)

GitHub rolled out Dependabot internally to keep GitHub's dependencies up to date. The tool will alert developers when a repository uses a software dependency with a known vulnerability. The issue of supply chain security has become increasingly evident in the past number of years, from the malicious flatmap-stream package to the most recent log4shell vulnerabilities. By better tracking the security of our software supply chain, we will keep GitHub and our users secure, which outweighs any potential impact on engineering teams.

  

## [Test your Amazon Web Service (AWS) services locally before deploying them into the cloud and waste…](https://medium.com/devops-techable/test-your-amazon-web-service-aws-services-locally-before-deploying-them-into-the-cloud-and-waste-49839e8afcc5)

Test your Amazon Web Service (AWS) services locally before deploying them into the cloud and waste money with LocalStack. Using LocalStack will help you test different services directly on your development machine. For example, if you use CDK to deploy your Infrastructure as Code to AWS, you can use CDK with LocakStack.

  

## [Automatically build & push a Full Stack Application onto Docker Hub using GitHub Actions](https://towardsdev.com/automatically-build-push-a-full-stack-application-onto-docker-hub-using-github-actions-fb274980202d)

GitHub Actions is an event-driven CI/CD platform that provides a means to automate and streamline your software development workflows. GitHub Actions offers workflows to build the code in your repository and run your tests. Workflows run on GitHub-hosted virtual machines or on machines that you host yourself. The various components of GitHub Actions are events, jobs, events, actions, jobs, and actions. A workflow is an automated script that runs a set of jobs when an event triggers it. The workflow script is written in a YAML file in the "./github/workflows" directory path of your GitHub repository.

  

## [PlanetScale: More Monitoring, Connections and Regions for the Database Service](https://thenewstack.io/planetscale-more-monitoring-connections-and-regions-for-the-database-service/)

PlanetScale announced new features on the road to delivering what it calls The Future Database. The company maintains that all the recent innovations in databases haven't necessarily kept the needs of developers in mind. PlanetScale's ability to record every query gives users detailed performance metrics. It eliminates installing a third-party APM and allows users to see which questions could be optimized in real-time. In addition, users will be able to extract and safely load data from PlanetScale into other platforms, such as Snowflake, Redshift, and BigQuery.

  

## [How To Speed Up GitHub Actions by Avoiding Unnecessary Work](https://betterprogramming.pub/how-to-speed-up-github-actions-by-avoiding-unnecessary-work-b51f02c6392b)

Use a monorepo tool like Nx to build and test only what is affected by the changes. Use the intelligent rebuild functionality when using Nx with a client app and multiple feature libraries. Run GitHub workflows locally instead of using CI/CD tools like Jenkins or Travis CI to run jobs on the main branch of your app. Use these tools to build, test, lint, and lint the code, but not all the workflows are necessary.

  

## [DigitalOcean Functions: A powerful serverless computing solution](https://www.digitalocean.com/blog/introducing-digitalocean-functions-serverless-computing)

DigitalOcean is committed to providing products that serve developers throughout their journey. Serverless computing has gained tremendous popularity among developers building modern apps. 25% of cloud IaaS buyers intend to utilize serverless functions in the next 12 months. Functions are snippets of code that run in response to event-based triggers, and builders of all kinds can now create serverless—functions on DigitalOcean for various purposes, including serverless APIs for your web and mobile apps. DigitalOcean has acquired Nimbella to accelerate our introduction of serverless computing.

  

## [The 10 Commandments To Survive Software Development](https://itnext.io/the-10-commandments-to-survive-software-development-and-software-projects-28deb6b8fcb2)

The 10 Commandments To Survive Software Development are ten commandments for surviving software development. Ben Hosking: Software projects are a 12-round fight. Avoid getting knocked out in the first round. Creating software is meant to be complicated. Suppose you want ten commandments on being a software developer — ten commandments of egoless programming. 

  

## [How to Find and Fix Security Vulnerabilities Using Snyk](https://ashutoshkrris.hashnode.dev/how-to-find-and-fix-security-vulnerabilities-using-snyk)

Snyk is a developer security platform for securing code, dependencies, containers, and infrastructure as code. It scans your code, reads through it, and tells you if you have any vulnerabilities in your code. The tool is compatible with many languages and comes with plugins supported by different IDEs. This tutorial will learn about a fantastic tool that helps us find vulnerabilities in our code and fix them. We will use a web application called PyGoat written in Django for a good demo.

  

## [Terramate and Terragrunt](https://blog.mineiros.io/terramate-and-terragrunt-f27f2ec4032f)

Terramate is an orchestrator and code generator for Terraform environments at scale. It is designed to be less intrusive in existing setups no matter what tooling is used. You can use it to run Terraform workflows and run maintenance or tooling for static analysis of the code found in stacks. Integrating with Git for filtering stacks based on changes based on detected changes was easy to take. We wanted to support a broad list of setups people have built without causing migration efforts.

  

## [Dynamic Kubernetes Cluster Scaling at Airbnb](https://medium.com/airbnb-engineering/dynamic-kubernetes-cluster-scaling-at-airbnb-d79ae3afa132)

Airbnb has shifted almost all online services from manually orchestrated EC2 instances to Kubernetes. We run thousands of nodes across nearly a hundred clusters to accommodate these workloads. In addition, Airbnb's infrastructure ensures our cloud spending automatically scales with demand, both up and down. We'll talk about how we dynamically size our clusters using the Kubernetes Cluster Autoscaler and highlight the functionality we've contributed to the sig-autoscaling community. These improvements add customizability and flexibility to meet Airbnb's unique business requirements.