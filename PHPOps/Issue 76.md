# DevOps / SRE - Top Links Last Week

## Week 17 - Issue #76

  

27 

  

## [Prevent Kubernetes misconfigurations during development with this open-source tool](https://opensource.com/article/22/4/kubernetes-policies-config-datree)

  

Datree is an open-source command-line solution that enables Kubernetes admins to create policies and best practices they want the team to follow. The tool runs automatic checks on every resource in a given path. Datree aims to help admins gain maximum production stability with minimum time and effort by enforcing policies before misconfigured resources reach production. This way, they can catch mistakes before their code moves to production/collaborative environments. Using tools like Datree can be an excellent foundation for cultivating a DevOps culture.

  

## [Post-incident review on the Atlassian April 2022 outage](https://www.atlassian.com/engineering/post-incident-review-april-2022-outage)

The Post-Incident Review (PIR) can be downloaded as a PDF file. This PIR provides the exact details of the incident, outlines the steps we took to recover and describes how we will prevent situations like this from happening in the future. We hope the details and actions outlined in this document show that Atlassian will continue to provide a world-class cloud platform and a robust portfolio of products.

  

## [ArgoCD Best Practices](https://www.datree.io/resources/argocd-best-practices-you-should-know)

  

In this article, we'll explore some of the best practices of Argo that I've found and learn how we can validate our custom resources against these best practices. For every Rollout, we can define a list of steps with one of two fields: setWeight and PauseConditions. Argo uses these steps to manipulate the pause and the Rollout to trigger the reaction of the next Rollout. There is only a single supported resource name for each specific kind of ConfigMap and Secret resource.

  

  

## [New from Anaconda: Python in the Browser](https://www.anaconda.com/blog/pyscript-python-in-the-browser)

PyScript is a framework that allows users to create rich Python applications in the browser using a mix of Python with standard HTML. PyScript aims to give users a first-class programming language with consistent styling rules, is more expressive and is easier to learn. The browser works everywhere (laptops, tablets, and phones) and is secure, robust, and stable. We hope to see the popularity and adoption of HTML, CSS, and JavaScript rises alongside Python, ultimately making the web a more friendly and hackable place for everyone.

  

## [Security Turbulence in the Cloud: Survey Says…](https://threatpost.com/security-turbulence-in-the-cloud-survey-says/179437/)

Threatpost polled 400+ readers about security challenges in the cloud. Misconfigurations and data exposure is the biggest threat to cloud deployments. According to the poll results, data privacy and regulatory issues are just the tips of the iceberg. Almost a quarter (24 percent) said they had no confidence in their organization's cloud security. Just 8 percent said they feel "highly" confident in their cloud security, and the majority felt bullish (68 percent). When asked if they've implemented a zero-trust architecture for access management, 53 percent said, "not yet but plan to," and 17 percent said it confused them.

  

## [Founding Uber SRE](https://lethain.com/founding-uber-sre/)

This is my personal story of starting the SRE organization at Uber. We were about twenty people within an engineering organization of about two hundred, rapidly on its way to two thousand. The infrastructure teams were:

The Developer Tools team.

The Infrastructure Engineering team is laser-focused on outpacing Postgres' appetite for disk space.

A team in Denmark primarily focused on deployment tooling.

The InfraOps team did everything else.

Uber's monolith had become difficult: migrations were risky, and deployments included many teams'.

  

## [Remote Development With JetBrains Gateway and Gitpod](https://blog.jetbrains.com/blog/2022/04/28/jetbrains_partners_with_gitpod/)

JetBrains Gateway is our solution for remote development. It is a standalone app that will connect to a remote server via SSH. It will download and install an IDE as a backend service and open a project hosted on the remote machine. All language processing happens in your Gitpod environment while working locally with a rich, thin client. IntelliJ IDEA, GoLand, PyCharm, and PhpStorm are currently supported. Gitpod is a well-known open-source orchestration and provisioning platform for automated developer environments.

  

---

  

## [GitHub Desktop 3.0 brings better integration for your pull requests](https://github.blog/2022-04-26-github-desktop-3-0-brings-better-integration-for-your-pull-requests/)

Version control should be simple and easy, so you can focus on what matters. GitHub Desktop hits a significant milestone with the release of version 3.0. New features include improved support for git operations, like squashing, reordering, or amending commits. Users can also re-run failed or individual GitHub Action checks to ensure your code is ready for production. Support for high-signal pull request notifications is also a significant addition to GitHub Desktop. Try them today by downloading GitHub Desktop!

  

## [How do I solve complex problems?](https://blog.devgenius.io/how-do-i-solve-complex-problems-728cdcefdedd)

The ability to solve problems distinguishes excellent software developers. Most people approach issues differently; some use technique x, others technique y. I don't think there is a predefined method of solving a problem. Instead, I use a process that I have seen some of my favorite engineers use, proving to get the job done. The aim is to "write twice and code once" only after relooking at what I have written down, always keeping in mind that this is the absolute solution that is constantly improved.

  

## [Three Ways CI/CD Adoption Can Benefit Your DevOps Team](https://thenewstack.io/three-ways-ci-cd-adoption-can-benefit-your-devops-team/)

Automation is a crucial enabler for achieving success in DevOps. CI/CD (continuous integration/delivery) automates software development workflows to help teams cut down on manual tasks and ship software to customers quickly. Here are three ways organizations can benefit from investing in automation and DevOps to build higher-quality software faster and collaborate more effectively. First, automated testing ensures that code remains stable, secure, and release-ready.

  

## [Best practices to keep your projects secure on GitHub](https://github.blog/2022-04-28-best-practices-to-keep-your-projects-secure-on-github/)

The median JavaScript project on GitHub uses just ten open-source dependencies directly. That's probably not surprising if you've written any JavaScript lately, but what is surprising is that the same repository ends up with 683 transitive dependencies. With Dependable, you can catch vulnerable dependencies, but you can also fix them. It automatically checks your dependency files for outdated requirements and opens individual pull requests for any it finds. It then notifies you and suggests fixes, enabling you to work on the latest, most secure releases continuously.

  

## [A Simple Definition of the CI/CD Pipeline](https://medium.com/@rldsn/a-simple-definition-of-the-ci-cd-pipeline-8a48169be938)

The CI/CD pipeline combines continuous Integration, Delivery, and Deployment. It is a powerful combination of automation tools to build, test and deploy code. Continuous Integration is intended to be used in combination with automated tests, and it is often coupled with a software development process called Test-Driven Development. Continuous Delivery expands upon Continuous Integration as its goal is to package the tested code into an artifact that can be deployed at any time through manual releases. Continuous Deployment goes one step further in that the release of a build to end-users is automatic if none of the previous tests fail.

  

## [My toolbox: HttpToolkit](https://itnext.io/my-toolbox-httptoolkit-c86239b130b)

A while back, I discovered HttpToolkit and use it almost daily (when developing). For example, I often need to find out the details of HTTP requests to reverse-engineer some API or understand error responses. HhttpToolkit uses a different approach, taps into the user code, and operates as a proxy server. This is extremely handy when I want to adjust my mock server rules. In addition, the details screen becomes editable, and you can modify, e.g., header fields of the request like the marked accept-header.

  

## [Using AWS Lambda Function URL to build a Serverless backend for Slack](https://itnext.io/using-aws-lambda-function-url-to-build-a-serverless-backend-for-slack-a292ef355a5d)

It uses AWS Lambda Function URL to build a Serverless backend for Slack. A Slack app that integrates with the Giphy API can be made using Lambda function URLs. The code is available on GitHub, and the sample app presented in this blog is a trimmed-down version of GipHy for Slack. The solution will be integrated as a Slash Command in Slack, and the end-user (you!) will invoke it from a Slack workspace using /awesome \<your search term\> (where awsome is nothing but the name of the search term). This, in turn, invokes the function URL (the configuration is covered later in the blog), which takes care of the rest.

  

## [Unknown Values: The Secret to Terraform Plan](https://log.martinatkins.me/2021/06/14/terraform-plan-unknown-values/)

Terraform has its language, rather than just using some general-purpose language to generate a data structure and operating on that. Terraform's innovations over its competitors when we first built it can propose actions based on the difference between configuration and existing state. When you apply the plan, Terraform then runs that program, ensuring along the way that it'll either do what the project said it would do or generate an error explaining why it can't (e.g., because the outside world changed in the meantime)

  

## [Rust vs. GO](https://itnext.io/rust-vs-go-cc38b7048181)

Go and Rust are relatively new languages (Rust is the new kid on the block) that try to overcome the criticisms of "`C++` "while sharing similar syntax. Both languages, although created to achieve different goals, share many similarities. This article will give you a quick overview of both languages, their advantages, and their drawbacks. We will review some real-world use cases where we will recommend one language over the other. Go has a small footprint, yet it covers many use cases such as microservices, stream processing, CLIs, etc.

  

## [Four Eras of JavaScript Frameworks](https://www.pzuraq.com/blog/four-eras-of-javascript-frameworks)

JavaScript has evolved massively in the last few decades of JavaScript development, and how far we've come. I think we can roughly divide it into four main eras. Each era had its main themes and central conflicts, and in each one, we learned vital lessons as a community and advanced slowly but surely.

  

## [SonarSource raises $412M to scan codebases for bugs and vulnerabilities](https://techcrunch.com/2022/04/26/sonarsource-raises-412m-to-scan-codebases-for-bugs-and-vulnerabilities/)

SonarSource has raised $412 million in a funding round at a $4.7 billion valuation. The cloud-based code quality management service detects reliability and vulnerability issues in code. CEO Olivier Gaudin says he launched the company to enable developers to administer best code quality practices that, in theory, could help to fix problematic code. One report estimates the impact of buggy software at $2.84 trillion per year in software development, increasing costs. The company competes in the static analysis software market, which one firm predicts could be worth $1.74 billion by 2022.

  

## [Why Your PRs Aren't Improving Quality](https://betterprogramming.pub/why-your-prs-arent-improving-quality-9f5b52a08b89)

There is often a false equivalency that PRs are code reviews. But the PR review itself is likely a big context switch for the reviewer. The code is already written at the PR point, and all who participate are subject to the sunk cost fallacy. It is unlikely that a team lead or peer would point out that an approach is sub-optimal or should be scrapped or request significant changes. Instead, most PRs will focus on Obvious, isolated logic errors. Bad practices and style (but lint rules can be used for this)

  

## [The Forces Opposing Quality Assurance](https://itnext.io/the-forces-opposing-quality-assurance-a14544a82105)

Quality assurance isn't a static property that stands the test of time; it's a decaying and ephemeral trait that we must care for and nurture through deliberate actions and processes across all company layers. Unfortunately, quality assurance has failed to keep up with the ever-growing challenges of modern applications. The author suggests that quality assurance is a symptom of the complexity of current systems and inadequate diligence to maintain quality assurance. He says that without deliberate actions to sustain and preserve Quality, a standard software system will slowly and surely move closer to that border, eventually producing an impactful incident.

  

## [Storage Options on AWS: S3 and RDS](https://betterprogramming.pub/storage-options-on-aws-s3-and-rds-d4d14b45d33c)

S3 is the cheapest storage option among the rest on Amazon's cloud platform. S3 has different storage classes based on the data access patterns. We receive enhanced performance for the frequent access data but at a slightly higher price. Relational Database Service (RDS) is a service on AWS for managing relational databases. It allows having a relational database in a secure, isolated environment. Amazon Aurora offers an Amazon Aurora database engine compatible with Postgres, Oracle, Microsoft SQL Server, Oracle, and Oracle.

  

## [How to Push an Initial Commit To a New GitHub Remote With a Single Shell Command](https://betterprogramming.pub/how-to-push-an-initial-commit-to-a-new-github-remote-with-a-single-shell-command-66d59b638f22)

How to Push an Initial Commit To a New GitHub Remote With a Single Shell Command? How to reduce the complexity of using command-line interfaces with a single command: gh new. The GitHub command creates a remote and pushes whatever it finds in the current folder. It can only be run in the original folder and not the subfolder you'd use because it will run gh new in the. Original folder. If you have a local repository, the command will fail, citing that the. The directory is not yet a git repository.

  

## [Design, Diagram, and Deploy a 3-tier Architecture Using AWS Console](https://betterprogramming.pub/aws-console-creating-a-3-tier-architecture-f44e226e5842)

The 3-tier architecture includes:

A presentation tier (web layer for the client).

A logic tier (the application layer).

A data-tier (containing a database layer).

The first step is creating a VPC, subnets, internet gateway, and edit route tables. Creating a web tier can be accessed from the Internet, and it can ping the application tier. Creating an application load balancer for the web tier (Internet-facing) and application tiers is necessary to ensure that those instances in a private subnet can communicate with the application tiers.

  

## [What is a "Bug" Anyways?](https://betterprogramming.pub/what-is-a-bug-anyways-dd5700e89589)

What is a bug? We need a more specific classification of software bugs to handle them appropriately. We need to break up bugs into three categories and how to deal with them. If you think I've got it wrong, please tell me in the comments. Quibbles can be defined as "Small imperfections in your software that you could easily ship with" If you do not know how long a bug will take to fix, You must work on it now. If it will only take a few hours to resolve and you cannot ship without fixing it, then there is no reason not to take care of it now.

  

## [How To Access A Docker Container — Secure Shell vs. Docker Attach](https://faun.pub/how-to-access-a-docker-container-secure-shell-vs-docker-attach-7d1aa944a2c6)

An essential skill while working with Docker containers is knowing how to connect to a running container to modify data, debug, or execute commands. The most helpful order for accessing a container through a shell is performed by executing docker exec. Sometimes you will be using containers that did not have any shell installed. Using Alpine Docker images, you can attach a shell to the container using a sh-shell. You can exit the attached shell anytime by pressing control + d or by typing exit within the shell. The docker attach command attaches your terminal's standard input, output, and error to the running container.

  

## [Common Issues with Kubernetes Deployments and How to Fix Them](https://odsc.medium.com/common-issues-with-kubernetes-deployments-and-how-to-fix-them-dd3b949df87)

Common Issues with Kubernetes Deployments and Fix Them: Common Errors and how to fix them. The most common error is the user specifying an incorrect container image or tag not available in the container repository. Another reason for the unavailability of a container is using invalid credentials to authenticate against the repository. When a node is shut down or crashed, its state changes to NoReady, indicating an issue with the node, multiple problems can cause the Kubernetes node not ready state, such as the lack of resources in the node to run the Pod.

  

## [Dive into Kubernetes Healthchecks (part 2)](https://hmh.engineering/a9f83eb712d5)

This is the second part of our series on K8s (K8s) about how to test the health of a service. We will focus on what we need to do to ensure the service is ready to work correctly. We also need to consider the impact of a failing service on other services that depend on it. 

  

## [EKS Blueprints: IaC Modules for Production-Ready Kubernetes](https://itnext.io/eks-blueprints-iac-modules-for-production-ready-kubernetes-48032d5ce88)

AWS team announced EKS Blueprints: IaC Modules for Production-Ready Kubernetes. Bootstrapping an EKS cluster with popular tools and security controls to bootstrap a more production-ready cluster. EKS also provides a template to create soft multi-tenancy based on namespaces and RBAC roles with pre-wired aws-auth configs. The initial launch of AWS Blueprints supports Terraform and AWS CDK, with Pulumi available in preview.