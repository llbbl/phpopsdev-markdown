# DevOps / SRE - Top Links Last Week

## Week 15 - Issue #74

  

25 articles

  

## [Introducing the Google SRE Prodcast](https://cloud.google.com/blog/products/devops-sre/discover-prodcast-the-site-reliability-engineering-podcast/)

The Google SRE Prodcast is an interview-style podcast where Site Reliability Engineers discuss key SRE concepts and share their experiences, advice, and strong opinions. Throughout nine episodes, domain experts explain, challenge, and reframe everything from SLOs to what it means to be an excellent SRE. Check the SRE podcast out at https://sre.google/prodcast.com/sre-professionals-in-depth.

  

## [Inside the longest Atlassian outage](https://newsletter.pragmaticengineer.com/p/scoop-atlassian)

At the time of writing, 45% of companies have seen their access to JIRA, Confluence, OpsGenie, and other Atlassian Cloud services restored. Atlassian has gone silent in communications across their main channels such as Twitter or the community forums for most of this outage. It took until Day 9 for executives at the company to acknowledge the outage for the first time. The outage comes at a critical time when Atlassian starts to retire its Server product - which was immune to this outage - in favor of onboarding customers to its Cloud offering.

  

## [Git security vulnerability announced](https://github.blog/2022-04-12-git-security-vulnerability-announced/)

The Git project has released new versions which address a pair of security vulnerabilities. The most effective way to protect against this vulnerability is to upgrade to Git v2.35.2.2. This version changes Git's behavior when looking for a top-level .git directory to stop when its directory traversal changes ownership from the current user. In addition, the vulnerability affects the Git for Windows uninstaller, which runs in the user's temporary directory. If you are on a multi-user machine, avoid using these tools until upgrading to the latest release.

  

## [Why Akamai bought Linode](https://techcrunch.com/2022/04/14/why-akamai-bought-linode/)

Akamai announced its plans to acquire Linode, the well-loved cloud hosting service, to build its cloud and edge computing portfolio. The $900 million acquisition closed last month. The company started building out more computer-centric services throughout the previous few years. Apple, for example, is using Akamai for its Private Relay service, and other customers also want similar capabilities. Adam Karon, the company's COO and GM of its Edge Technology Group talk about what the acquisition means for its future.

  

## [Mizu – API traffic viewer for Kubernetes](https://github.com/up9inc/mizu)

The API Traffic Viewer for Kubernetes enables you to view all API communication between microservices to help you debug and troubleshoot regressions. The project is for everyone. We ask that our users and contributors take a few minutes to review our Code of Conduct. The API traffic viewer is a simple-yet-powerful API traffic viewer. It's a simple yet powerful tool that can be quickly run on any cluster (version of 1.16.0 or higher)

  

  

---

  

  

## [Atlassian finally explains the cause of ongoing cloud outage](https://www.bleepingcomputer.com/news/technology/atlassian-finally-explains-the-cause-of-ongoing-cloud-outage/)

Atlassian has revealed the exact cause of an ongoing cloud services outage the company estimates could impact some of its customers for up to two more weeks. Hundreds of customer sites were deleted on April 5th accidentally, triggering a weeks-long incident the company is still working to address. The outage resulted from communication issues between two Atlassian teams working on deactivating the "Insight – Asset Management" app used by Jira Service Management and Jira Software on all customer sites. Unfortunately, the script they used to disable the app was run using the wrong execution mode and the wrong list of IDs.

  

## [Google Allies With #github to Secure Software #SupplyChains #lowcode #nocode #DevOps #DevSecOps #AIOps #MLOps #k8s #developers #Kubernetes #Docker #designers #architects #100DaysOfCode #OpenSource #python #javascript #Developer #CodeNewbie #SRE](https://twitter.com/bamitav/status/1514962233914126341)

Google has been working with GitHub to create a forgery-proof method for signing source code as part of an ongoing effort to better secure software supply chains. The technique generates non-forgeable provenance using GitHub Actions workflows for isolation and code signing tools for authenticity provided by Sigstore. The reusable workflow also protects against interference from maintainers who could define a workflow in a way that interferes with the builder. Google expects to apply this method to securing other build systems that organizations use to construct applications.

  

## [An Introduction to JSON](https://thenewstack.io/an-introduction-to-json/)

JSON stands for JavaScript Object Notation. It is a data format interchange, which is a way of storing and transferring data. It has become widely deployed for quite a large number of use cases. The format is also used for Docker and Kubernetes manifests, so it's crucial to understand how it works for anyone interested in cloud-native development. Even desktop and server applications depend on the format built with two primary components: Dockerfile or any file created with JSON.

  

## [Build Data Factories, Not Data Warehouses](https://thenewstack.io/build-data-factories-not-data-warehouses/)

Jeremy Stanley is the co-founder and CTO of Anomalo, where he helps companies improve the quality and reliability of their data. The data warehouse is a broken metaphor in the modern data stack. He says that we should first ensure that our factory produces and ingests high-quality data. We don't know if the data we make is high quality until we have tested the finished product. We have tasked machine operators with quality control with the burden of monitoring the information itself.

  

## [Understanding Kubernetes Configurations Drifts](https://faun.pub/understanding-kubernetes-configurations-drifts-5b31b5eb401e)

Kubernetes is an open-source container orchestration platform that automates many manual tasks associated with deploying, managing, and scaling containerized applications. Configuration drift is when running clusters in infrastructure become progressively dissimilar over time, primarily because of human changes and upgrades to individual clusters. The impacts of configuration drift are lost productivity and downtime as engineers investigate code and environments to figure out what's causing the strange behavior. Fortunately, SREs can take certain precautions and steps to identify configuration drift.

  

## [How to Use Different Types of Ansible Variables](https://faun.pub/how-to-use-different-types-of-ansible-variables-912e19c8e8c5)

This blog post deep dives into Ansible Variables, which allow us to parametrize different Ansible components. Variables store values for reuse inside an Ansible project. Ansible facts are a particular type of variables that Ansible retrieves from any remote host for us to leverage them in Ansible projects. The use of variables simplifies the management of dynamic values and can potentially reduce the number of human errors. The simplest use case of variables is to define a variable name with a single value using YAML syntax.

  

## [Solomon Hykes: Dagger Brings the Promise of Docker to CI/CD](https://thenewstack.io/solomon-hykes-dagger-brings-the-promise-of-docker-to-ci-cd/)

Dagger, a new open-source tool for CI/CD pipelines, was launched into public beta last month. Co-founders Solomon Hykes, Andrea Luzzardi, and Samuel Alba worked together at Docker, which Hykes founded before leaving in 2018. Hykes: "We identified the main pain point, the main bottleneck, the glue," he said. "DevOps engineers spend most of their time gluing together many specialized tools, and the glue itself is the problem."

  

## [Tips For Taming Microservices in The Wild](https://betterprogramming.pub/tips-for-taming-microservices-in-the-wild-795b8bce4567)

Microservices are an architectural style that structures an application as a collection of loosely coupled, independently deployable, and scalable services. Polyglot architectures can be used when Development teams pick which tech stack they use for their microservices, which is why Microservices excel for large complex systems with big teams. Microservices help you break down that complexity into smaller chunks which are much easier to manage however the overall complexity of the entire system architecture becomes very complex. Here are some tips for managing that complexity to ensure you don't end up on the wrong side of that tiger enclosure.

  

## [Storage Options on AWS: Instance Store, Elastic Block Storage, and Elastic File System](https://betterprogramming.pub/storage-options-on-aws-instance-store-elastic-block-storage-and-elastic-file-system-27f9aff570b6)

These days AWS offers over 200 different services, and the number is only increasing every year. Essential services such as EC2 and S3 are being used extensively by multiple businesses. As cloud-based solutions become popular, we need to understand the capabilities of the data-related components on AWS. Elastic Block Storage or EBS is an alternative for the Instance Store that provides scalability and high performance. Elastic File System (Elastic File System) is a serverless file system that acts as a network drive from EC2 instances.

  

## [Email Syntax Validation and Existence Verification in PHP](https://betterprogramming.pub/email-syntax-validation-and-existence-verification-in-php-5f7fdad768dd)

This article teaches how to validate and verify an email with two approaches. The first approach does not require Composer and is based on SMTP validation. The second one uses a Composer dependency to ascertain and verify emails in PHP without Composer. We learned how to do it with an external library and Composer library in both ways. Finally, we looked at implementing a script to validate emails and verify if they exist in PHP.

  

## [Instead of Those Lofty Goals, Go After the Small Wins](https://www.techtello.com/small-wins/)

Do you celebrate significant victories, audacious goals, and significant milestones? We all do, but the satisfaction of doing something big vanishes like a puff of smoke. Getting habituated to major successes leads to black-and-white or all-or-nothing thinking. Instead of significant victories with outsized expectations, what if you targeted small wins? Small daily goals give a sense of progress; work that moves you forward is fulfilling and rewarding, and each step takes you closer to your destination. Charles Duhigg, the author of The Power of Habit, describes the power of small wins.

  

## [OpenSSF Selects Node.js as Initial Project to Improve Supply Chain Security](https://openssf.org/blog/2022/04/18/openssf-selects-node-js-as-initial-project-to-improve-supply-chain-security/)

Node.js is the first open-source community to be supported by OpenSSF's Alpha-Omega Project. Node.JS was downloaded over 2 billion times in 2021, according to research by RedMonk and GitHub. Almost 98% of the world's 1.9 billion websites use JavaScript, the top programming language globally. The Alpha Omega Project is committing $300k to bolster the Node.js security team and vulnerability remediation efforts through the rest of 2022.

  

## [Provisioning Freeform Configuration via AWS AppConfig & CloudFormation](https://itnext.io/provisioning-freeform-configuration-via-aws-appconfig-cloudformation-faed56b9e9f4)

Freeform configuration is an alternative way of defining feature toggles for applications that require dynamic behavior switching at runtime. This article explores an automated approach to provisioning freeform configuration that applications could use to toggle machine learning routines dynamically. The ultimate goal of this provisioning tutorial is to produce a configuration scaffold that represents the diagram above. We aim to create an AppConfig application resource that contains three environments (dev, uat, and prod). Each will have its freeform configurations inside, used to toggle machine learning.

  

## [Creating an HTTPS Lambda Endpoint without API Gateway](https://itnext.io/creating-an-https-lambda-endpoint-without-api-gateway-eb0db1f6af7a)

Amazon Web Services (AWS) recently announced Function URLs, a new in-built feature that allows you to invoke your functions through an HTTPS endpoint. The endpoint is secure using AWS Identity Access Management (IAM), but you can allow public access with optional Cross-Origin Resource Sharing (CORS) configurations and custom authorization logic. As a result, function URLs are more suited for small use-cases such as webhooks or determining the price of a cryptocurrency. This blog post will demonstrate how to create an HTTPS Lambda endpoint using Python and Terraform.

  

## [Errors are constructed, not discovered](https://ferd.ca/errors-are-constructed-not-discovered.html)

A year ago, I left the role of software engineering behind to become a site reliability engineer\* at Honeycomb.io. Since then, I've been writing many blog posts over there rather than over here. However, I recently gave a talk at IRConf (video). I am reproducing this talk because I stand behind the content, but it would also not fit the work blog's format. I'm also taking this opportunity because I don't know how many talks I'll give in the next few years.

  

## [Difference between su, su -, sudo -i, sudo -s](https://faun.pub/sudo-vs-su-8e3b92416dcf)

To get root on the server, I usually used the command `sudo -s'. Why so? I don't remember, actually, just a habit. Difference between`su,\` `su -,` `sudo -i', and`su -\` means that we run shell by root without changing a directory. The shell wouldn't import env vars (that could be set in .bash\_profile or .login). But we have another situation with i command: Run the shell specified by the target user's password database entry as a login shell.

  

## [Deploy Kubernetes (K8s) on Amazon AWS using mixed on-demand and spot instances](https://garutilorenzo.github.io/k8s-aws-terraform-cluster/)

This is only an example of deploying a Kubernetes cluster on Amazon AWS using mixed on-demand and spot instances. For a production environment, you should use EKS or ECS. The scope of this repo is to show all the AWS components needed to deploy a high available K8s cluster. You also need one VPC with private and public subnets already uploaded on your AWS account and one bastion host to reach all the private EC2 instances. The final infrastructure will be made by: two autoscaling groups, one for the Kubernetes master nodes and one for worker nodes.

  

## [The complete guide to protecting your APIs with OAuth2](https://stackoverflow.blog/2022/04/11/the-complete-guide-to-protecting-your-apis-with-oauth2/)

OAuth is one of the most popular specifications for API authentication today. It allows users to delegate access to resources without sharing their original credentials securely. OAuth2 (the version of OAuth that this article will cover) has been around since 2012 as a standard and is built on lessons from other, earlier measures, including OAuth1 and SAML. In addition, the standards body behind OAuth, the OAuth IETF working group, offers best practices for newer technologies like mobile applications or IoT devices.

  

## [Strict Development CI for PHP](https://uvinum.engineering/strict-development-ci-for-php-20d2262c95f7)

Strict Development CI for PHP explains how to manage a strict development continuous integration pipeline in PHP. We will create an example application with the same tools we use for our production project. That means respecting the best practices and standards of the PHP language. We rely on a small PHP toolset to make these tasks possible. We use unit tests, mutation testing, and pre-commit hooks to test the quality of our code. Static analysis tools take care of getting our code clean of silly bugs like syntax errors. In addition, Rector is an excellent tool that refactors our code for us.

  

## [A tiny Docker image to serve static websites](https://lipanski.com/posts/smallest-docker-image-static-website)

The smallest Docker image to serve static websites from Docker would waste bandwidth and storage. After evaluating a few static file servers with similar specs, I settled for thttpd, which has a similarly small footprint but seems more battle-tested. The image builds quickly and, at 7.77MB, is reasonably small. It will print access logs to STDOUT ( -l - ) and set the Cache-Control header to 60 seconds ( -M). There are many other neat features, like basic auth, throttling, and virtual hosts.