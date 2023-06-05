# DevOps / SRE — Top Links Last Week

## Week 30 Issue #37

## [What the Heck is a Data Mesh?](https://cnr.sh/essays/what-the-heck-data-mesh)

Data meshes have clearly struck a nerve. Some don’t understand them, while others believe they’re a bad idea. Zhamak Dehghani identifies four data mesh principles:Domain-oriented decentralized data ownership and architecture Data as a product Self-serve data infrastructure as a platform Federated computational governance Federated governance is a key component of the data mesh. To demystify these principles, I’ll use the modern service stack for comparison.Modern service stacks have a few important characteristics:Decentralized microservice API ownership and. architecture.

## [Choosing a Well-Architected CI/CD approach: Open Source on AWS](https://aws.amazon.com/blogs/devops/choosing-a-well-architected-ci-cd-approach-open-source-on-aws/)

When building a CI/CD platform, it is important to make an informed decision regarding every underlying tool. This post explores evaluating the criteria for selecting each tool focusing on a balance between meeting functional and non-functional requirements, and maximizing value. The first decision is whether to go with an open source solution for managing code or with AWS-managed solutions, such as AWS CodeCommit. Gitlab provides both source control services, as well as built-in CI tools, called Gitlab CI. Gitlab Runners are responsible for running CI jobs, and the actual jobs are stored in Gitlab’s git repository along with product code.

---

_Please consider supporting the Weekly DevOps / SRE Report. Subscribe to our free [Newsletter](https://www.phpops.dev/subscribe/#/portal/signup) on our website!_

---

## [Secure and analyse your Terraform code using AWS CodeCommit, AWS CodePipeline, AWS CodeBuild and tfsec](https://aws.amazon.com/blogs/devops/secure-and-analyse-your-terraform-code-using-aws-codecommit-aws-codepipeline-aws-codebuild-and-tfsec/)

HashiCorp Terraform is one of the popular IaC tools for customers on AWS. The infrastructure goes through a CI/CD pipeline created on AWS using AWS CodeCommit, AWS CodePipeline, Amazon CodeBuild, and Amazon ECR. To do this, we utilize AWS tools and the Open Source tfsec tool, a static analysis security scanner for your Terraform code, including more than 90 preconfigured checks with the ability to add custom checks. This will help mitigate security risks within our infrastructure deployment pipelines.

## [Cosign 1.0!](https://blog.sigstore.dev/cosign-1-0-e82f006f7bc4)

Cosign has been tested on 13 OCI registries and is now packaged in five different package managers. Cosign 1.0 is the first general availability release for production use. We’re working on better key management stories, rich attestation support, SBOM integrations, end to end policy system support, and stabilizing the rest of the “experimental” features that make cosign work well with the other sigstore projects. We plan on taking the Tekton Chains project to beta later this summer, and GA by the end of the year.

## [10 Common Mistakes When Building Analytical Data Models](https://betterprogramming.pub/10-common-mistakes-when-building-analytical-data-models-814c763d1b70)

10 common pitfalls when designing schemas and tables for analytics. Building data assets is an ongoing process. Treating data modeling as a one-off project is unrealistic. Building tables and ETL processes that are too big is a good way to avoid repetitive multi-join queries. Denormalized analytical schemas often provide a significantly better user experience with no negative impact on performance. Building tables that require an extensive number of joins hurts query performance and, for many, is unpleasant to work with. There is no “best” data modeling.

## [DevOps Journey — How to get certified in Terraform](https://bradmccoydev.medium.com/devops-journey-how-to-get-certified-in-terraform-c0bce1caa3d)

The command formats configurations ( *.tf ) in the current directory for easy readability and consistency with terraform’s formatting conventions. How do you make files to have syntactically valid and internally consistent? The command will check and report errors within modules, attribute names, and value types. If your configuration is valid, Terraform will return a success message. The command to show the current state of the infrastructure applied is shown in the.tfstate. It shows a record of what resources Terraform has created and will manage/destroy going forward.

## [Amazon EKS Upgrade Journey From 1.20 to 1.21](https://marcincuber.medium.com/amazon-eks-upgrade-journey-from-1-20-to-1-21-caf1475deaa4)

In version 1.20, Kubernetes used Dockershim, which allowed Kubernetes to use Docker as a container. Docker is still fully functional, but we should be migrating away from it asap. With the latest release of EKS 1.21 we can finally make use of containerd as a. runtime. The default. runtime for. the default will still be Docker, and you can opt-in to containerd. by adding a --container-runtime containerd option to your user data.

## [Six Years of Professional Clojure](https://engineering.nanit.com/6-years-of-professional-clojure-2b61cb6c1983)

Aims to build a team of software engineers practicing mainly with Clojure as their tool. Nanit’s backend group became larger and the question regarding choosing Clojure as our main programming language rose over and over again mainly due to the lack of experienced engineers. Pure functions are easier to test, refactor and compose together into more complex functions: They are free of side effects. Side effects include network IO, disk interaction or mutating the system state. Pure functions don’t have to have multiple inheritance or inheritance. They are not dependent in external state to compute their return value. Their output relies solely on their arguments.

## [Thinking about “traceability”](https://blog.cryptographyengineering.com/2021/08/01/thinking-about-traceability/)

A few weeks ago WhatsApp sued the Indian government over new legislation that could undermine its end-to-end encryption software. The legislation requires social media and messaging companies to include the ability to “trace” the source of harmful viral content. Tracing back to a content originator requires that the provider must be able to identify a file received at some end-user’s account, and then trace the content back to the WhatsApp account that originally sent it. In WhatsApp, all messages (as well as file attachments) are encrypted directly from sender to recipient, using an encryption key that WhatsApp doesn't possess.

## [AWS ECS Cluster using the EC2 Launch Type](https://aws.plainenglish.io/aws-ecs-cluster-using-the-ec2-launch-type-cb5ae2347b46)

AWS ECS Cluster using the EC2 Launch Type and host a simple application. I will create a cluster in one region spreading instances across three availability zones. All instances will be isolated inside a private subnet and will be accessible from the internet only by the load balancer or SSH. I've used the default route (0.0/0) for the destination, but you can put a more specific one depending on your case. In this tutorial, I will show you step-by-step how to create from scratch.

## [Speed up your workflows with GitHub-Actions](https://ezioguga.medium.com/speed-up-your-workflows-with-github-actions-b3928069443f)

GitHub Actions is a tool/service provided by GitHub which helps you to build, test and deploy your applications. In this Demo, I’ll show you how to set up your GitHub runner in your EC2 Instance in AWS and execute your workflows from there with the sample NodeJS project. We use a simple NodeJS application when you hit the base URL which is [http://localhost:5000](http://localhost:5000/), it should give you the “API Running” Text Text. The change will be detected and trigger automatically changes to your GitHub repository.

## [Jenkins Tutorial — Part 2 — Pipeline Variables](https://itnext.io/jenkins-tutorial-part-2-pipeline-variables-5e4783aa2c07?source=rss----5b301f10ddcd---4)

Variables are the most important part of the pipelines that able us to making repeatable pipelines and separating codes from configurations. In this article, I will introduce ways of define and using variables in the pipelines. Variables can be defined globally on the entire pipeline or in the specific pipeline stage. You can define your environment variables in both — global and per-stage — simultaneously. Globally defined variables can be used in all stages but stage defined. variables can only be used within that stage.

## [An Introduction to Chaos Engineering in AWS](https://thecraftman.medium.com/chaos-engineering-in-aws-ccefbd13ffbd)

Chaos Engineering is the discipline of experimenting on a distributed system in order to build confidence in the system’s capability to withstand turbulent conditions in production. Chaos Engineering practice lets you experiment with an entity in production which you might not expect it to be happening, identify system behavior, and identify loopholes in system behavior and fix it. The Principle of Chaos was created by Engineers from Engineers from Netflix based on their experience with which they created applications for Netflix using AWS using AWS. An example of Chaos Engineering in AWS could be an example of the same deployment in the deployment in different regions and availability zones.

## [How To Design For Operational Excellence in Software Application](https://iamkanikamodi.medium.com/how-to-design-for-operational-excellence-in-software-application-d268132d34e3)

Some best operational practices and lessons built up over time can be leveraged to make sure your software is running properly, your customers are taken care of, and your team resolves defects in a timely manner. Resiliency is system’s ability to recover from a fault and maintain persistency of service. Routinely test for/with failure: Chaos, Stress, Soak Tests and Scaling Best Practices. Automate operational scaling with Scaling Planners like CloudTune for EC2 in AWS.

## [Developer Careers Are Stuck in a Loop — Eat → Sleep → Code → Repeat](https://blog.devgenius.io/developer-careers-are-stuck-in-a-loop-eat-sleep-code-repeat-1393dcb359aa)

Developer Careers are stuck in Groundhog day coding loop which sees them working harder but their careers are stalling. Developers get great at writing code but there is no focus or momentum in their career. Don’t do project work outside of work, this is your time and it should be spent furthering your career by getting new knowledge (certifications) or new technical skills (practicing a skill and writing code) The more skills you have, the more you are worth the most you are.

## [5 must-have command line Kubernetes tools](https://itnext.io/5-must-have-command-line-kubernetes-tools-b90bdb843ce6?source=rss----5b301f10ddcd---4)

Kubectl krew plugin manager is a command-line-based tool for Kubernetes. Kubectx and Kubens plugins are written in Go and modify kubeconfig switching to a new context or namespace. Kube-ps1 can be used in combination with kubectx, kubens and kube-p1. Stream logs with kail can stream logs of pods based on different matching criteria, for example, pods that are matching matching criteria.

## [How To Contribute to Open Source as a Beginner](https://catalins.tech/getting-started-with-open-source-how-to-contribute-as-a-beginner)

Open-source software is software whose source code is available to anyone. As a result, people can see the implementation of the software and even contribute themselves to it. In this article, you will learn how to make your first open-source contributions with the help of Hashnode documentation. The most notable benefits are as follows: contributing to popular software can bring great satisfaction knowing that lots of people use your code. By contributing, you can learn new skills such as communication, writing, problem-solving, creativity skills. It is a great way to accelerate your developer career.

## [Signs of a Health Development Team](https://levelup.gitconnected.com/signs-of-a-health-development-team-4bef16b287d8)

There are several characteristics that distinguish a high performing team from an underperforming team. High performing teams are eager to advance your product to the next level. They are proactive in shaping the future of their work because they take ownership and pride in pushing to be better. The best developers will ensure that they aren’t a single point of failure, and that will include educating and pushing the team around them to know anything necessary and still function at a high level in their absence. A good team will always want to give you options and be ready to help you come up with the best solution.

## [In Defense of Package Managers](https://dlorenc.medium.com/in-defense-of-package-managers-31792111d7b1)

Package managers are one of the most maligned pieces of software in common use today. They are anything developers run to install packages, but most of the criticism is misdirected. Linux distributions began to appear in 1992, but the first appeared in 1992 to appear about a dozen years ago. The big change has been the shift from “stable distros” to “rolling distros,” and finally to ‘no distros’. It’s not their fault you use 1000 unmaintained libraries full of CVEs. Developers have a very selfish view of the software ecosystem — they only care about their code.

## [🚀10 Trending projects on GitHub for web developers - 30th July 2021](https://dev.to/iainfreestone/10-trending-projects-on-github-for-web-developers-30th-july-2021-bnc)

Tracking.js library brings computer vision algorithms and techniques into the browser environment. Welcome to Welcome UI library created by Welcome to the jungle, a customizable design system with react, styled-components and styled-system. Waypoint allows developers to define their application build, deploy, and release lifecycle as code, reducing the time to deliver deployments through a consistent and repeatable workflow. It is the technology that enables the AWS Development Kit to deliver polyglot libraries from a single codebase.

## [Scaling to trillions of metric data points](https://engineering.razorpay.com/scaling-to-trillions-of-metric-data-points-f569a5b654f2)

Razorpay is one of the first companies in the country to have gone with a production-grade Kubernetes infrastructure (somewhere late 2016) Razorpay wanted to ensure applications and infrastructure should have very little friction to emit and consume metrics. By 2018, Razorpay had close to 30+ services in production on AWS using Prometheus. We encountered a number of performance issues at scale. We were looking to answer the following: How do we scale Prometheus with the increasing workload? How do. we retain metrics for a longer. period of time and still be able to. query faster? How. do we make a highly available system with unlimited storage capacity, which can be added on top of Prometheus.

## [Everything You Need to Know About AWS ElastiCache](https://aws.plainenglish.io/everything-you-need-to-know-about-aws-elasticache-c4bf7ad93332)

Amazon ElastiCache is an in-memory cache in the cloud that scales horizontally. Memcached is great for basic object caching, but there is no persistence for the data. Redis is a more sophisticated solution with enterprise features like persistence, replication, Multi-AZ and failover. And it also supports sorting and ranking data for example, for gaming leaderboards. The Washington Post used Amazon ElastsiCache when building a content management platform optimized for speed. The next AWS post will be on S3! Stay tuned!

## [Cloud Foundry HTTP 2 Project Thwarted by GoLang Indifference](https://thenewstack.io/cloud-foundry-http-2-support-thwarted-by-golang-indifference/)

A project to bring HTTP/2 to the CloudFoundry application development platform ran into a roadblock when the keepers of the Go Language did not respond to requests for supporting the HTTP-2 over TCP “upgrade flow” process. The project team doesn’t want to take on the responsibility for supporting such a potentially widely-used function. Cloud Foundry Go Router reverse proxy removes headers that would let a CF application know it can send and receive. The issue is currently marked as “under investigation” by GoLang maintainers.

## [Announcing HashiCorp Vault 1.8](https://www.hashicorp.com/blog/vault-1-8)

HashiCorp Vault 1.8 is now available for general availability. Vault provides secrets management, data encryption, and identity management for any application on any infrastructure. Vault Diagnose is a new operator-centric command focused on providing a clear description of what is working in Vault, and what is not working. The command focuses on why Vault cannot serve requests, but will also warn on configurations or statuses that it deems to be unsafe in some way. The release also includes many additional new features, workflow enhancements, general improvements, and bug fixes.

## [Highway to Helm: How to efficiently manage chart sources](https://medium.com/@adevinta/f5749ba8031e)

Helm charts are composed of a set of files following a well-defined structure. Those files are then packaged into a tarball, uploaded and indexed in a chart repository so it can be used by Helm. Collocating the chart and the application with your application code is easier to manage, as there are several options to fix the problem by using a single Git repository with all chart sources. We’ll discuss the different factors that make one more suitable than the other, depending on your organizational structure.

## [The Blind Men and the Elephant](https://medium.com/nerd-for-tech/the-blind-men-and-the-elephant-6fe1fa6c5a0c)

The Blind Men and the Elephant parable is similar to the parable of the blind men and the elephant. We humans have a tendency to claim absolute truth based upon our own limited, subjective experiences. Individual technologies and frameworks are useful, but transient, tools of our trade. Most will pass and ultimately be replaced. There are no perfect and no best choices — only the compromises that can be made to work. We all have more to learn and rationally responding to criticism is one way to do that.

## [Why Software Development Slows Down When You Try to Speed It Up](https://blog.devgenius.io/why-software-development-slows-when-you-try-to-speed-it-up-ef2fe32de404)

The faster software development tries to go, the more mistakes and the lower the quality. Shortcuts lower quality and technical debt builds up and slows everything down. Software development is a loser’s game, you build momentum by reducing mistakes, bugs and errors. The goal of the bid is to win the bid, not create a realistic project plan, not to create an accurate estimate of delivery timelines. Decisions on a software project are made with emotions and hope, not logic. The key motivation for leaders on projects is to meet the deadlines. Quality is fastest way to get code into production.

## [A Short History of Malware Protection in macOS](https://eclecticlight.co/2021/07/26/a-short-history-of-malware-protection-in-macos/)

Apple introduced code signatures in 2007 and introduced App Sandbox in June 2012. It is now a requirement for apps in the App Store, but some older apps have enjoyed exemptions ever since. Apple has added another set of checks with the introduction of notarization in Mojave in 2018. No requirements are currently imposed on signing certificates used beyond those of existing Gatekeeper controls on the first launching of quarantined apps, which now include checks for signing certificates too. Apple’s use of online OCSP checks came under fire in November 2020, driving it to take immediate steps to protect privacy.

## [API Security 101: Broken Function Level Authorization](https://blog.shiftleft.io/api-security-101-broken-function-level-authorization-4ed1e553042)

The OWASP API Security 101 series focuses on the top ten vulnerabilities that threaten web applications. Today, we discuss the security vulnerabilities that affect APIs. These issues are caused by missing or misconfigured access controls. Broken object-level authorization happens when access control is not properly implemented on these endpoints, and attackers can view or operate on resources that they should not have access to. These issues can manifest themselves in many ways, so let’s look at a few examples today.

## [Netcat – All you need to know](https://blog.ikuamike.io/posts/2021/netcat/)

Netcat is a tool that reads and writes data across network connections using the TCP/IP / networking swiss army knife. There are several variants of netcat but most of the core functionality and command line options are very similar. In this article we’ll look at different applications and how it can be useful in day to day activities of a pentester, security professional, sysadmin etc… The commands to use can be seen by running netcat -h to see the options available.

## [Don’t Worry, GitHub Copilot Won’t Put Your Job on Autopilot](https://betterprogramming.pub/dont-worry-github-copilot-won-t-put-your-job-on-autopilot-738a936a41bf)

The Github Copilot as the name suggests is considered to be working as your copilot. The tool at the point of time is working on improving its performance as there could be many lines of code that might not even compile. GitHub Copilot will play the role of a copilot and help us with suggestions which earlier need to be searched after extensive traversing of search engines. It tries to understand the context of your editor, by the function name or the comment typed, it sends that context to the Github pilot service.