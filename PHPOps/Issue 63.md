# DevOps / SRE - Top Links Last Week

## Week 4 - Issue #63

  

## [Google Cloud Deploy, now GA, makes it easier to do continuous delivery to GKE](https://cloud.google.com/blog/products/devops-sre/google-cloud-deploy-now-ga/)

Google Cloud Deploy eliminates the scaling and maintenance responsibilities that typically come with self-managed continuous delivery solutions. Delivery pipelines and targets are defined declaratively and retained with each release. The delivery pipeline also provides structure. That means if your delivery pipeline changes, the path to production remains durable. No more time lost troubleshooting issues on in-flight releases caused by changes made to the delivery pipeline. Now you can reclaim the time spent maintaining your continuous delivery tooling and spend it delivering value to your customers.

  

  

## [The State of Policy Management In Kubernetes](https://containerjournal.com/features/the-state-of-policy-management-in-kubernetes/)

Nirmata released it's first annual The State of Cloud-Native Policy Management report. The report surveyed 600 DevOps and security and operations professionals on their use of policy management tools in Kubernetes. Nearly 50% of respondents report having policy enforcement active in production. However, almost 6% say they are not adopting some form of K8s policy enforcement. The report says that OPA is the most widely adopted tool for implementing Kubernetes policies. But a lack of executive support was the highest hurdle for both Kyverno and OPA.

  

## [SecDevOps: When The Safety Comes First](https://jelvix.com/blog/what-is-secdevops)

63% of DevOps experts and developers say they've improved the quality and speed of their software deployments. Puppet Labs reports a 50% reduction in defects and crashes. Over 50% of surveyed companies found the DevOps approach "very difficult" In response to these concerns, SecDevOps was born. DevSecOps is the practice of bringing development and operations teams together, whereas Agile is an iterative approach that centers on collaboration, ongoing feedback, and minor, rapid releases.

  

  

## [Spice up your Infrastructure as Code with TACOS](https://itnext.io/spice-up-your-infrastructure-as-code-with-tacos-1a9c179e0783)

Infrastructure as Code IaC is a pattern where virtualized infrastructure and auxiliary services can be managed using configuration expressed in almost any language. This is especially important with creating environments on-demand and managing infrastructure on multiple providers. Standalone terraform workflow is great but quickly becomes unmanageable when used at scale. TACOS provides better visibility on what has happened in the environment regarding changes made by Terraform during the environment's lifespan. This info is easily accessible in TACOS.

  

## [SUSE unveils Rancher Desktop 1.0 for Kubernetes on your PC](https://www.zdnet.com/article/rancher-desktop-1-0-for-working-with-kubernetes-on-your-pc-arrives/)

Rancher Desktop is an open-source program that enables you to learn, experiment, or test out Kubernetes container management. It currently works on M1 and Intel Macs; Windows, via Windows Subsystem for Linux (WSL) and Linux. The desktop runs on so many platforms because it's an Electron application, which also uses Node.js and TypeScript. The application is designated as a 1.0 release, and while it's still in its early days, the SUSE team promises a stable release process.

  

—

  

## [Burning Down the House: Quantifying the Impact of Log4j](https://thenewstack.io/burning-down-the-house-quantifying-the-impact-of-log4j/)

According to a new report, the Log4j vulnerability (publicly revealed on Dec. 10) immediately impacted the people surveyed. However, only 22% of the study participants before the incident reported a moderate or significant impact from a software supply chain attack within the last 12 months. The report also shows that software, SaaS, and Internet security companies are at the frontlines of the fight against supply chain attacks. However, it might take a year or two more to determine if this will impact software quality or user experience.

  

## [Infrastructure pipelines: How are they different from application CDs?](https://blog.runx.dev/infrastructure-pipelines-how-are-they-different-from-application-cds-ce4545763820)

CI/CD pipelines have been around long enough to become a pretty standard practice for engineering teams. Infrastructure-as-Code (IaC) tools like Terraform have brought us closer to achieving true automation in infrastructure. But because of the complexity of the tools used to do this, they're still gaining traction. In this article, IaC tools like Jenkins, CircleCI, GitHub Actions, Buildkite, Harness, and others to make sure the correct checks and protections are in place when they build and deliver applications.

  

## [Automatic Resource Allocation on AWS](https://blog.devgenius.io/automatic-resource-allocation-on-aws-5907736724be)

We use Ansible to manage EC2 Auto Scaling application deployments. We will be using EC2 classic, open only necessary ports with TCP/22 (port 80) for SSH access to your instances. An Elastic Load Balancer will distribute requests among the instances we have launched into our upcoming Auto Scaled Group. We'll create an auto-scaling group and configure it to use the Launch Configuration template that an Auto-Scaling group uses to launch EC2 instances.

  

## [How To Build a CI/CD Pipeline for Kubernetes Stateful Applications](https://medium.com/@nvermande/how-to-build-a-ci-cd-pipeline-for-kubernetes-stateful-applications-aef6c8c5edc2?source=rss------kubernetes-5)

Stateful apps are built on databases, message buses, or similar systems that persist data to disk. The frontend component sits in Kubernetes and can be scaled up and down on-demand as it is usually stateless. Companies can host data sets in various formats and form-factors: Virtual Machine on-premises, PaaS services in the Public Cloud, Big Data platform, or even physical machines. We're going to focus on the toolset that enables developers to navigate through the development lifecycle of these applications efficiently.

  

## [Serverless vs. Kubernetes](https://blog.oliverjumpertz.dev/serverless-vs-kubernetes)

Kubernetes is a container orchestrator and thus needs containers to manage. It's a paradigm shift to more traditional software development, where components are developed and deployed to bare metal machines or VMs. The offer is pretty simple: You write the code, the platform handles everything else for you. The simpler your project, the easier usage gets. Devs can focus on what matters because, with Serverless, there is not much to manage anymore. 

  

## [Helm — Package Manager for Kubernetes](https://medium.com/squadcast/helm-package-manager-for-kubernetes-db068739a75d?source=rss------kubernetes-5)

Helm is an open-source package manager for Kubernetes. It wraps together all the necessary components (deployments, services, secrets, persistent volume) in a single package. Helm keeps track of individual objects that require updates. In addition, it maintains records of updates made to the application to roll back to the previous versions. It also helps automate software installation, configure software deployments and fetch relevant data. Helm is available on macOS, Linux, and Windows operating systems.

  

## [A Guide to OKRs and Overcoming the Pain of Them](https://thenewstack.io/why-okrs-suck-and-how-to-fix-them/)

The origins of OKRs date back to management influencers Andrew Grove and John Doerr in the 1970s. Larry Page, a co-founder of Google, wrote a forward in Doerr's 2017 book "Measure What Matters" in which Page said OKRs drove tenfold growth at Google. What works for Google won't work for every company, experts say. The New Stack tries to get to the bottom of how OKRs work best and how to overcome their all-too-common pitfalls.

  

## [Reasons Kubernetes is so complex](https://buttondown.email/nelhage/archive/two-reasons-kubernetes-is-so-complex/)

I've experienced the (near-universal, I think) feeling of "holy smokes, why is this thing so complicated?" as well as 'Why is it so bloody hard to debug anything?' This post attempts to commit to two specific thoughts or paradigms I have that I reach for as I try to understand why working with Kubernetes feels so hairy sometimes.

  

## [AWS Security Specialty — Key Management Service](https://betterprogramming.pub/aws-security-specialty-kms-notes-5045c505a33b)

AWS Key Management Service (AWS KMS) is a managed service that makes it easy for you to create and control the encryption keys used to encrypt your data. With its symmetric and asymmetric keys management, KMS is akin to CyberArk PAM or HashiCorp Vault products. If your organization has specific requirements to manage the Key management lifecycle, it might be necessary to use CloudHSM to manage your keys top to bottom. The keys are generated and used by KMS in all the managed services KMS supports.

  

## [Stack vs Queue — Everything You Need to Know](https://betterprogramming.pub/stack-vs-queue-55d6ea7b2f4f)

The most optimal way to build a stack and queue is to use a linked list. They allow you to achieve a time complexity of O(1) when inserting and deleting elements. There are three forms of linked lists: singly-linked, doubly linked, and circular-linked; we'll use doubly-linked lists in our example. Let's start by creating an instance variable for the top of the stack and a size instance variable.

  

## [Reverse-engineering a Discord malware](https://itnext.io/how-i-reversed-a-nodejs-malware-and-found-the-author-7dd9531b389f?source=rss----5b301f10ddcd---4)

A Discord server admin recently received a report that someone was trying to get him to download an EXE file. He downloaded the file and used the strings command to look up what was in this binary file. The code looked obfuscated and minified on a very long line. The author claims that this tool is for educational purposes and sells premium features and support. We have found the source code that was used in the bundled app. It steals all the information that it can get from the Discord client by killing the discord client.

  

## [Disposable Virtual Machines in 3 commands with Multipass](https://faun.pub/disposable-virtual-machines-in-3-commands-with-multipass-ab5afc12eba9)

Multipass is a simple tool to spin up VMs and destroy them in very few CLI lines. It is a one-liner to install in most cases: Linux: "sudo snap install multipass." Mac: "brew install multipass." You can manage the entire VM lifecycle with three commands. 

  

## [How to Create a File Integrity Monitor With Python](https://betterprogramming.pub/how-to-create-a-file-integrity-monitor-with-python-3e4bba66f4cf)

How to Create a File Integrity Monitor With Python, you can easily create one in less than 10 minutes. It is also an excellent project for aspiring penetration testers to learn about programming and hashes. Tampering with files is one of the best techniques to escalate privileges in a system and many more security risks. A File integrity monitor can help stop this. It is a good backup/last line of defense. It can be easily created using Python or a simple simple simple tool. It's a great way to keep your device safe.

  

## [The baseline for web development in 2022](https://engineering.linecorp.com/en/blog/the-baseline-for-web-development-in-2022/)

Alan Dávalos, a frontend engineer at LINE.com, analyzed 2021 to 2022. The most significant change in 2021 was the retirement of Internet Explorer (IE). Microsoft announced in May 2021, and by August, many Microsoft products, including Microsoft 365, had officially dropped support for IE. In addition, in Japan, Yahoo! JAPAN announced setting IE as a non-recommended browser in September 2021 (website in Japanese). The official retirement date for IE is scheduled for June 2022, but there are several other reasons we can consider IE fully retired.

  

## [PHP Annotated — January 2022](https://blog.jetbrains.com/phpstorm/2022/01/php-annotated-january-2022/)

PHP Annotated Monthly Update, January 2022: The PHP Foundation Update. PHP 8.0.15, 8.1.2, PHP 7.4.27 are the latest updates for the PHP language. A proposal to add operator overloading to PHP failed to pass the vote. A tool for web scraping inspired by the popular Python library, Scrapy.php. A new component to clean up untrusted HTML and protect against XSS. It could be an excellent alternative to HTML Purifier.

  

## [Introducing Certificate Manager to simplify SaaS scale TLS and certificate management](https://cloud.google.com/blog/products/identity-security/simplify-saas-scale-tls-certificate-management/)

Certificate Manager enables you to use External HTTPS Load Balancing with as many certificates or domains as you need. Wildcard certificates and DNS-based domain control authorization allow us to bring you support for wildcard certificates. Google Cloud users can also protect their SaaS users from denial of service attacks, OWASP Top 10 risks by adopting Cloud Armor. The best part of Certificate Manager is that there's no additional charge to use more than 100 certificates with the first 100 certificates.

  

## [Go & Docker Hello World!](https://medium.com/@justanotherdev/go-docker-hello-world-f092ecf7cead)

An additional Docker build stage adds unnecessary tooling as part of the buster base image. Let's build and run using Docker. We can see that we have reduced the size of our container by adding a build stage.