# DevOps / SRE - Top Links Last Week

## Week 20 - Issue #79

  

24 links

  

## [From PHP to Next.js: What Trivago Learned Rewriting Its Web App](https://thenewstack.io/from-php-to-next-js-what-trivago-learned-rewriting-its-web-app/)

Hotel search service Trivago rewrote its frontend in Typescript on the Next.js framework, replacing a PHP codebase on Melody's homegrown JavaScript framework. From April 2020 until late 2021, the platform team created, tested, and deployed the new application, which reduced daily page size by up to 37%, increasing code releases. It was a massive undertaking, especially when nothing was inherently "wrong" or broken with the codebase. The team implemented an incredibly methodic, pragmatic approach to tackling touch engineering questions and ultimately reaching the decisions.

  

## [How to build a Helm plugin in minutes](https://www.datree.io/resources/how-to-build-a-helm-plugin-in-minutes#utm_source=phpops&utm_medium=medium_weekly)

Helm is an excellent addition to the Kubernetes ecosystem. The Helm plugin is a system that allows you to seamlessly integrate with the Helm flow and run custom code that's not part of the Helm core code. Helm knows the settings for your plugin, the command it executes when the plugin is run, and hooks for customizing the plugin lifecycle. In addition, helm provides under-documented (the closest thing I found to documentation was here) capability for hooking into the plugin's install, update or uninstall commands.

  

## [History of Web Applications](https://www.robinwieruch.de/web-applications/)

A website ranges from a marketing website for a product to a full-blown social media platform. What starts as a traditional website with HTML and CSS, returned from a web server, turns into a way more difficult full-stack application with sophisticated client-server communication and state management. This comprehensive guide shows you the evolution of web development from website to web application, where we clarify terms like the client, server, frontend, and backend.

  

## [Comparing Graviton (ARM) Performance to Intel and AMD for MySQL](https://www.percona.com/blog/comparing-graviton-performance-to-arm-and-intel-for-mysql/)

Recently, AWS presented its CPU on ARM architecture for server solutions. However, some reviewers said that Graviton does not show any significant results and, in some cases, showed fewer performance results than Intel. So, we decided to investigate it and do our research regarding Graviton performance, comparing it with other CPUs (Intel and AMD) directly for MySQL. The test is designed to be CPU bound only, so we will use a read-only test to ensure no I/O activity during the trial. Monitoring was done with Percona Monitoring and Management (PMM) OS: Ubuntu 20.04.

  

## [Nginx Modern Reference Architectures](https://github.com/nginxinc/kic-reference-architectures)

NGINX Modern Reference Architectures repository has the basics for a common way to deploy and manage modern apps. We define modern app architectures as those driven by four characteristics: scalability, portability, resiliency, and agility. Over time, we'll build more example architectures using different deployment models and options – including other clouds – and you'll be able to find those here. The project is under active development, and the current work uses Pulumi with Python. Pulumi is a modern Infrastructure as Code tool that allows you to write code (node, Python, Go, etc.) that defines cloud infrastructure.

  

  

---

  

## [Announcing the HCL Extension for Visual Studio Code 0.1](https://www.hashicorp.com/blog/announcing-the-hcl-extension-for-visual-studio-code-0-1)

HashiCorp has transitioned the community HCL Extension to an officially supported project. This change allows us to provide a consistent editing experience for Terraform users and users of other HCL-based products. The HashiCorp/syntax repository is the new home for the TextMate grammars used by this new HCL extension and the Terraform and Sentinel extensions. If you have previously installed the HCL extension under William Holroyd's namespace, you will automatically receive the Hashi Corp Extension and continue receiving future updates.

  

## [6 Metrics To Watch for on Your K8s Cluster](https://betterprogramming.pub/6-metrics-to-watch-for-on-your-k8s-cluster-76d58f08397f)

Kubernetes is not a single system the way Redis RabbitMQ or Postgres is. Instead, it combines several control plane components (for example, etcd, API server) that run our workloads on the user (data) plane over a fleet of VMs. We'll cover the most critical metrics based on k8s's metadata that form a good baseline for monitoring your workloads and ensuring they're healthy. The 90th percentile should be a good starting point for this matter.

  

## [Guidance for Choosing an Elliptic Curve Signature Algorithm](https://soatok.blog/2022/05/19/guidance-for-choosing-an-elliptic-curve-signature-algorithm-in-2022/)

Ed25519 is one of the two digital signature algorithms today that use the EdDSA algorithm framework. It uses deterministic nonces, which means you're unlikely to reproduce the Sony ECDSA k-reuse bug in your system. The other is Ed448, which targets a higher security level (224-bit vs. 128-bit) but is also slower and uses SHAKE256 (overkill) Ed448 is slower and not great for performance. If you have to meet some arbitrary compliance requirements (i.e., FIPS 140-3, CNSA), your decision is already made.

  

## [Your Ultimate Guide to Kubernetes](https://medium.com/@jatin.krr/your-ultimate-guide-to-kubernetes-78836ef73072)

Kubernetes, also known as K8s, is an open-source system for automating containerized applications' deployment, scaling, and management. Pods are the minor deployable units of computing that you can create and manage in Kubernetes. In addition, Kubernetes provides you with service discovery, load balancing, storage, and more automatic bin packing, automatic rollouts, and rollbacks automated configuration management. 

  

## [A simple tool to package and run distributed K8s application](https://github.com/sealerio/sealer)

Sealer -- Build, Share and Run Any Distributed Applications based on Kubernetes. It solves the delivery problem of complex applications by packaging distributed applications and dependencies(like databases and middleware) together. For example, we can write a Kubefile, build a CloudImage, then use a Clusterfile to run a cluster. Sealer is almost compatible with all Linux operating systems that support containerd. It takes up fewer resources, high availability is achieved through keepalived, takes fewer resources.

  

## [Kubernetes Source Code Overview — kubelet](https://able8.medium.com/kubernetes-source-code-overview-kubelet-7783234a0e4a)

The kubelet is the primary 'node agent' that runs on each node in the cluster. It makes sure that containers are running in a Pod. The code structure of the kubelet is as provided, and I will provide a further overview of the code later. The source code is based on the Kubernetes v1.24 version.

  

## [Deploy Lambdas fast with AWS CodePipeline](https://towardsdatascience.com/deploy-lambdas-fast-with-aws-codepipeline-f90b0bf5ca64)

Programmers typically spend more time testing and deploying code than making improvements if they don't have a pipeline. Using CodePipeline, you define a set of stages run on AWS, with each step containing actions in order. For example, we'll use a combination of other AWS services like CodeBuild and CloudFormation to deploy our Lambda code. First, we need to create a service role to permit access to other services on your behalf. This simple inline policy would grant your service permissions for any action on any service.

  

  

## [Next JS vs React: Which One to Use in 2022?](https://massivepixel.io/blog/next-js-vs-react/)

Next, JS is a React framework with which developers can create single-page JavaScript web applications. It's designed to take care of all the tools and configurations developers may require for React. With the help of the framework, developers can build apps that use server-side rendering. Next, JS can be an excellent choice for developing the MVP's MVP. It features less code, and it's easier to implement (once the page is done, you have to link it to the header's header).

  

## [Git Guru: The Unsung Hero Of Every Engineering Team](https://ryan-james.medium.com/23264e3316c3)

The biggest favor you can do for yourself is to become a Git Guru. Linus Torvalds invented Git in 2005 when he developed the Linux kernel. Git has grown into the most widely adopted version control system, so if you work on any software development team, you will likely be using Git. To have any chance at a successful scheduled release cycle with multiple groups contributing, Gitflow is your best bet. It is also essential to have a well-thought-through Gitflow workflow within your organization.

  

## [Apache Druid: A Real-Time Database for Modern Analytics](https://thenewstack.io/apache-druid-a-real-time-database-for-modern-analytics/)

David Wang is the VP of product marketing at Imply, where he is responsible for the company's positioning, product messaging, and technical content. He is an engineer turned marketer with a career building new categories and increasing awareness across next-gen data management, virtualization, and enterprise storage technologies. For external-facing, external analytics applications, you need to look for a database with an optimized architecture and data format built for interactivity and scale based on your needs.

  

## [Backend-as-a-Service](https://betterprogramming.pub/backend-as-a-service-f8d255052fc3)

Kubernetes has become the de-facto standard for deploying and operating containerized applications. Backend-as-a-Service is a way of building, shipping, and running applications in the cloud. With serverless, you will be able to handle business logic and computations in a flexible and scalable way without worrying about managing infrastructure and servers. Google Firebase and MongoDB Realm offer rich features and developer-friendly tools for setting up data models and configuration.

  

  

## [A Very Friendly Starting Guide for Terminal and Git](https://towardsdatascience.com/a-very-friendly-starting-guide-for-terminal-and-git-97c1757ecd4c)

A Very Friendly Starting Guide for Terminal and Git is a simple, practical, and friendly starting guide. The guide is adapted from Markus Spiske's onboarding guide for a second-year computer engineering course. The material here is only the tip of the iceberg, and there are many more commands and options to learn about. You might also be well-used, but that is not a problem! Open a computer and play with the commands like a ninja! Remember, Google is your friend!

  

## [Zitadel: The best of Auth0 and Keycloak combined](https://github.com/zitadel/zitadel)

ZITADEL combines the ease of Auth0 and the versatility of Keycloak. It provides a wide range of out-of-the-box features like secure login, self-service, OpenID Connect, and OAuth2.x, SAML2, branding, Passwordless with FIDO2, OTP, U2F, and an unlimited audit trail to improve the life of developers. We only ingest operational data from the IAM application itself. We send an initial event when any binary is started. This is an "invoked" event, along with the flags passed.

  

## [GoLang APIs: A skeleton for your future projects](https://blog.devgenius.io/golang-apis-a-skeleton-for-your-future-projects-a082dc4d6818)

GoLang APIs: A skeleton for your future projects. A well-structured skeleton reduces delivery time exponentially. This series of articles will explain every step's why and how. The main points that we focused on regarding our performance and accessibility include the essential response time, the query type, and how much data we will be exposing. In the following articles, we will be showing more in-depth practices for handlers and testing them accordingly.

  

## [Don't be afraid of Vim, learn those commands, and you are ready to go!](https://faun.pub/dont-be-afraid-of-vim-learn-those-commands-and-you-are-ready-to-go-5d5828cc9dc0)

The most essential and basic commands in Vim are the most basic commands. Don't be afraid of Vim. Learn those commands, and you are ready to go! The first thing to learn is how to open a file using Vim. To start Vim from the shell prompt, type: Vim FILENAME \<ENTER\>. For a line, use a line and copy a line that is cut and copy that line. Vim allows you to execute some commands on the terminal without using the terminal.

  

## [The Three-body Problem in Software Development](https://betterprogramming.pub/the-three-body-problem-in-software-development-74adeda6807c)

The Three-body Problem in Software Development builds up with time because we treat different parts as one big whole. We should avoid doing that. Tightly coupled features affect one another, and very loose related features can peacefully coexist within the same system without forcing change on one another. The three-body problem does not have a general closed-form solution like one or two-body problems for most initial conditions. But if we add another massive object and make the whole thing the three-body problem, items become unpredictable and chaotic.

  

## [Go Language Fuels Cloud Native Development](https://thenewstack.io/go-language-fuels-cloud-native-development/)

Go was created at Google in 2007 to improve programming productivity in an era of multicore networked machines and large codebases. In the State of Developer Ecosystem 2021, Go ranked in the top five languages developers planned to adopt and continues to be one of the fastest-growing languages. In this episode of The New Stack Makers podcast, Steve Francia, head of product: Go Language, Google, and alumni of MongoDB, Docker, and Drupal board members discuss the programming language, the new features in Go 1.18, and why Go is continuing on a path of accelerated adoption.

  

## [Site Reliability Engineer (SRE) vs. DevOps: Responsibilities, Differences, and Salaries](https://jelvix.com/blog/sre-vs-devops)

DevOps and Site Reliability Engineering (SRE) coexisted in the information technology world for more than a decade. DevOps is a set of cultural principles, approaches, and tools that improve the ability of companies to build applications and services at high speed. Product development and optimization are faster than traditional software and infrastructure management processes with DevOps. SRE focuses on system stability, which is measured as the most fundamental characteristic of any product. In addition, DevOps concentrates on automation to provide upgrades faster and save hours of monotonous work.

  

## [Terraform Best Practices for Better Infrastructure Management](https://moustakisioannis.medium.com/terraform-best-practices-for-better-infrastructure-management-49e0859b5537)

This article explores best practices for managing Infrastructure as Code (IaC) with Terraform. Terraform is one of the most used tools in the IaC space that enables us to safely and predictably apply changes to our infrastructure. We should treat our infrastructure configurations as application code and apply the same best practices that apply to all infrastructure as Code projects. The Terraform Spacelift blog is a great way to learn how to use Terraform and use advanced features.

  

## [Bubble Tea: fun, functional, and stateful way to build terminal apps](https://github.com/charmbracelet/bubbletea)

A Go framework based on The Elm Architecture, Bubble Tea is well-suited for simple and complex terminal applications. It includes a standard framerate-based renderer for high-performance scrollable regions alongside the main renderer. The non-annotated source code for this program is available on GitHub. Also, check out Bubbles, a library of standard UI components for Bubble Tea. This tutorial assumes you have a working knowledge of Go and some shared resources.