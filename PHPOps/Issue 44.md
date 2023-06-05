# DevOps / SRE - Top Links Last Week

## Week 37 Issue #44

## [Inside GitLab’s IPO filing](https://techcrunch.com/2021/09/17/inside-gitlabs-ipo-filing/)

DevOps software firm GitLab filed to go public on Friday. The company's S-1 filing lists a placeholder $100 million raise estimate. GitLab raised $286 million at a post-money valuation of $2.75 billion in its last private-market transaction. In its fiscal year ended January 31, 2021, GitLab’s revenue rose roughly 87% to $152.2 million from a year earlier. Its gross profit rose around 86% and operating loss widened nearly 67% in the past two fiscal years.

## [Foreman 3.0](https://theforeman.org/2021/09/foreman-30-is-here.html)

Foreman 3.0 is an important milestone on the road to modernizing Foreman’s user interface. In this release, our main focus is on the host detail page. Foreman is an open source project that helps system administrators manage servers throughout their lifecycle, from provisioning and configuration to orchestration and monitoring. Foreman scales well to multiple locations (offices, data centers, etc) and multiple organizations, allowing you to grow without losing your single source of infrastructure truth. It is deployed in many organizations, managing from 10s to 10,000s of servers. It provides comprehensive interaction facilities including a web frontend, CLI and RESTful API which enables you to build higher level business logic on top of a solid foundation.

---

## [FinOps – introduction, origins and next steps](https://faun.pub/finops-introduction-origins-and-next-steps-bcdaa8b82417)

Financial Operations is the intersection of people, process and technology as it relates to managing the financial operations of a business. The most important concept is unit economics. We should always measure our cloud spend against a business metric e.g. total revenue, shipments made, paid subscribers, customer orders. FinOps is a culture that can be followed or adopted by taking into account factors such as the following principles: Cloud business value-driving decisions. Cloud usage is the responsibility of everyone in the organization.

## [How To Automate Application Deployments Using Terraform and AWS CodeDeploy](https://jaydenaung.medium.com/how-to-automate-application-deployments-using-terraform-and-aws-codedeploy-6b074773acdd)

An important aspect of DevOps is automating the deployment of your apps, and the release of new features. In this lab, I’ll show you how can use Terraform to automate the creation of AWS infrastructure, and work with AWS CodeDeploy to automate deployment of a sample application. This lab focuses on automation capability of Terraform, and is designed to make you understand how CodeDeploy works. We will need the required AWS-managed policy ARNs in your AWS accounts to use this lab.

## [How to use Terratag to automatically manage tags and labels for your Terraform Code](https://about.gitlab.com/blog/2021/09/14/gitlab-together-with-terratag-open-source-to-help-you-manage-terraform-resources/)

When using infrastructure as code (IaC) on a public cloud provider, it's important to use tags and labels to organize your IaC. Terratag, an open source project developed by env0, can be used with Terraform and placed on top of the GitLab CI/CD platform. This gives users a range of solutions for running CI/CC for Terraform code and managing it on a large scale. All major cloud providers support tagging/labeling for most of their resources using their Terraform provider.

## [Upgrading Istio without Downtime](https://thenewstack.io/upgrading-istio-without-downtime/)

As of Aug 24, Istio 1.9 is no longer supported. This means that your older versions are no longer receiving critical patches and updates. An outage in the ingress gateway will have an immediate impact on your end users. This blog will explain an architecture and process that will help you get your Istio deployment back into compliance and set you up for easier upgrades in the future. The proposed architecture is based on the proposed architecture laid out below, which might save you a number of hours and allow you to catch up safely and more efficiently. It also makes sense that during an upgrade, the existing control plane deployment remain in place.

## [8 Common Mistakes When Using AWS ECS to Manage Containers](https://dashbird.io/blog/aws-ecs-containers/)

In this article, we’ll discuss potential pitfalls that we came across when configuring ECS task definitions. We'll also examine some general best practices for working with containers in production. One common source of potential problems is the network configuration in the “run task” API. AWS suggests passing sensitive data to ECS tasks by referencing the secret ARN from AWS Systems Manager Parameter Store or AWS Secrets Manager in the environment variables in the task definition. Don’t define your passwords in plain text as Value:

## [Timeseries Databases on AWS](https://aws.plainenglish.io/timeseries-databases-on-aws-236677f739db)

QuestDB outperformed TimescaleDB for read and write performance. QuestDB is one of the leading time-series databases in the world. Amazon Timestream is a serverless database built from scratch, unlike some other databases based on existing open-source projects. The other day, I came across GridDB and Netflix’s Atlas, which are in-memory databases. Choosing a timeseries database will require you to explore these databases in much more detail. Running time series databases in cloud is easier than ever now with cloud platforms like AWS and Azure.

## [Software, the engineering part](https://blog.devgenius.io/software-the-engineering-part-87172d48f337)

Software teams are there to solve clients problems, to find ways to use technology to makes clients life easier. The software itself creates a set of problems that we need to solve. In Inviting Disaster [Chi01], James R. Chiles refers to these as “cracks in the system’s” In any system, these cracks trigger because of some human error in any part of the system. The best we can do is to design our systems to react to those failure modes and minimize the damage.

## [7 Best Serverless Applications Security Practices](https://aws.plainenglish.io/7-serverless-applications-security-best-practices-d04be33c7752)

An AWS Lambda function is an example of a microservice which can be part of a serverless architecture. Microservices architecture is very different from monolithic application architecture. Serverless applications are also at risk of OWASP top ten application vulnerabilities because serverless functions such as Lambda still execute code. We’ve also started seeing security challenges that come with the hype. 7 Best Serverless Security Practices are based on the best practices in securing your serverless applications. For a typical traditional application, the only entry point is via exposed APIs so the attack surface is predictable.

## [SCRAP: A Quality Code Checklist for Programmers](https://javascript.plainenglish.io/scrap-a-quality-code-checklist-for-programmers-2b961950686)

The letter “R” of SCRAP defines that software must behave in the same way. The software needs to have a “good reputation” in the environment in which it is working. The more complex the code, the more time it takes to implement it, and the more complex it is. The letter "R" is the letter ‘R’ for Scalability and “resiliency” It is synonymous with “recovery.”

## [Getting started with CPU attacks](https://www.gremlin.com/blog/getting-started-with-cpu-attacks/)

CPU attacks let you consume CPU capacity on a host, container, Kubernetes resource, or service. Even small amounts of CPU can reveal unexpected behaviors on our systems. These behaviors can manifest as poor performance, unresponsiveness, or instability. Gremlin gives you fine-grained control over the attack, including: CPU Capacity, number of cores, and the magnitude of the attack. As with all Gremlin attacks, you can run a CPU attack on multiple systems simultaneously. This is called the blast radius and magnitude.

## [Streamline Your GitHub Actions With Composite Actions](https://betterprogramming.pub/streamline-your-github-actions-with-composite-actions-a8ebc6d28f6b)

The GitHub blog published a post unveiling composite actions to reduce duplication. With GitHub actions, it is quite easy to set this up: create a workflow where everything is contained in a single job. The actions/cache works in a standard way:Provide one or multiple folder(s) path to cache. The content to be cached is resolved at the end of the job. Given a key, if a cache is found, the content is restored at the step the action is called. Using the cache actions, the GitHub action grows like this:

## [Why Not Signal?](https://dessalines.github.io/essays/why_not_signal.html)

Signal became the top downloaded app in January 2021, after WhatsApp, the most popular messaging app in the world, became acquired by Facebook, and announced its sharing of data with its new parent, Signal. Signal’s exploding popularity among messaging apps, has lead many activists to re-open Signal's case. Signal was overlooked due to its underdog status in the tech world, its courting of the open source community, and its colorful founder, Moxie Marlinspike. The US government was (and possibly remains) itself a primary funder of Signal. It is in effect the same CIA misinformation organizations from the 1950s:

## [5 Metrics of Software Leadership](https://betterprogramming.pub/the-metrics-of-software-leadership-208fd61153a1)

If you deliver what is perceived as garbage to the end-user, then you are delivering garbage. Quality is garbage, bug return rates are high, new bug rates are through the roof, test cases are failing, happy scenarios don’t make it past the first gate. Monitoring for quality in your delivery will come down to bug rates (how fast are they coming in) and returning bugs (why is this bug being reopened) If you have someone running QA, they will report on the rest of the test cases passed or fail, good, bad, or ugly of regression.

## [How Do Authentication and Authorization Differ?](https://thenewstack.io/how-do-authentication-and-authorization-differ/)

Authentication and authorization sound similar, but authentication and authorization are two different concepts that need to be separate steps in an access policy. The terms are sometimes used almost interchangeably — or as a portmanteau that suggests they’re the same thing.Authentication is verifying that a user is who they say they are: authorization is giving them permission to access a resource or perform a specific function. The principles will seem familiar, suggested Alex Weinert, director of identity security at Microsoft.

## [Software. Farming. Productivity.](https://blog.code-inspector.com/software-farming-productivity-d41307fef0cf)

The number of software engineers in the world will almost double in ten years, says Delange. Delange: It seems unrealistic to imagine that the demand for software engineers will be satisfied solely by hiring more workers. We need to standardize the software stack to simplify how we develop software, Delange says. We also need to have more tools to increase productivity and eventually automate software production. The former is a reality today (with tools increase productivity) while the latter will take more than 10 years to produce meaningful results.

## [Top 10 Things That Destroy Developers’ Productivity](https://levelup.gitconnected.com/top-10-things-that-destroy-developers-productivity-81f67461ec83)

A study shows that once there is an involuntary distraction, it takes an average of 23 minutes and 15 seconds to get back to the task. When it happens, you can no longer focus on the task at hand. The psychological need to win the argument hijacks the recipients’ attention hijacks their focus. The impact on productivity is not just for the duration of the meeting, but for the psychological effect on developers’ focus too. Set up a meeting to go over the topic, avoid unnecessary back and forth through email. Politely decline the invites where you feel you are going to neither contribute nor gain anything valuable.

## [What Makes a Good DevOps Engineer?](https://betterprogramming.pub/what-makes-a-good-devops-engineer-f627f3a78f81)

A DevOps engineer has been involved with finding, interviewing, and hiring DevOps engineers for various organizations, both large and small. From that vast ocean of resumes and LinkedIn profiles, a few trends have emerged that I would like to share with you. Certifications don’t matter as much as some people think, it only means they know how to study for a test. Critical thinking is a valuable and hard-to-find skill these days, but there are ways to do it for good reasons.

## [3 Effective Strategies for a Merge Request That’s Just Too Big](https://betterprogramming.pub/3-effective-strategies-for-a-merge-request-thats-just-too-big-9a8a6d1b9351)

Merge requests are a fundamental and critical process for software engineers at any seniority level. 100 lines of code is a good cutoff for a large merge request, especially if there are more junior engineers on the team. A sign that MRs could be too large could be a lack of feedback and communication. Merge requests may seem tedious, but they are well worth the effort, especially for the sake of maintaining the codebase. Decide Team Standards for breaking up large MRs. Identify shared logic, document your reasoning, and speak up when an MR has overgrown.

## [Stop Technical Debt Before It Damages Your Company](https://thenewstack.io/stop-technical-debt-before-it-damages-your-company/)

A new generation of technical debt has emerged from SaaS platforms that are creating massive sprawl across the enterprise. Healthcare companies are spending the highest percentage of their budgets on technical debt, with banking and finance close behind. More than two-thirds of IT leaders surveyed agreed that technical debt poses a fundamental limit on their ability to innovate, and 64% said that it will continue to have a major influence on their strategies in the future. By understanding and acting the root causes of the problem, every organization has the power to chip away at the problem.

## [F5 acquires cloud security startup Threat Stack for $68 million](https://techcrunch.com/2021/09/20/f5-acquires-cloud-security-startup-threat-stack-for-68-million/)

Applications networking company F5 has announced it’s acquiring Threat Stack, a Boston-based cloud security and compliance startup, for $68 million. Threat Stack specializes in cloud security for applications and provides customers with real-time threat detection for cloud infrastructure and workloads. F5 bought multi-cloud management startup Volterra for $500 million in May. The acquisition, which is expected to close in F5’s first-quarter fiscal year 2022, is subject to closing conditions.

## [5 Most Popular GitHub Repositories to Learn Web Development](https://javascript.plainenglish.io/5-most-popular-github-repositories-to-learn-web-development-71953ac7ae91)

GitHub is the largest open-source community. There are a million resources available on GitHub for you to learn almost anything you may want. So, I have curated a list of the most popular GitHub repositories that I am personally using to learn Web Development. I have included all that you need to be a web developer: Web Developer-Roadmap, Free Programming Books, Front End Checklist, Clean Code JavaScript and You Don’t Know JS. The list is based on suggestions and first-hand experience of front-end developers who have been working in industry for years.

## [Tracing SSL/TLS connections using eBPF](https://blog.px.dev/ebpf-openssl-tracing/)

This post will demonstrate how to use eBPF to trace encrypted connections that operate over SSL. BPF can be used to interrupt the execution of a program at virtually any point—much like how one can set a breakpoint in an application using a. debugger. This post is part of our ongoing series sharing how you can use eBf to. debug applications without recompilation or redeployment. The BPF kprobe approach works well for all plain-text traffic, but will not work for encrypted connections.

## [Testing Kubernetes Operators using GitHub Actions and Kind](https://medium.com/@christopherlenard/testing-kubernetes-operators-using-github-actions-and-kind-c4086d37dd30?source=rss------continuous_integration-5)

In this article, we’ll cover linting, unit testing, integration testing, docker build and docker build. We'll also cover a good strategy for managing secrets in Github. You can add secrets to Github and call them in Actions using the get-key-vault-secrets Github Action. We start up a Kind cluster to run our operator against Kubernetes version 1.20.7.7. We’re going to add secrets as environment variables to satisfy this requirement.

## [Kubexpose: A Kubernetes Operator, for fun and profit!](https://itnext.io/kubexpose-a-kubernetes-operator-for-fun-and-profit-f528586eee07)

Any Kubernetes cluster will work ( minikube, kind, Docker Desktop, on the cloud, whatever...). Deploy the Operator and other components (CRD etc) to test things out. Create a kubexpose resource — which will help you access ngnix Deployment over the Internet. To try out other scenarios such as trying to Deployment and/or Service - the Operator will reconcile or bring things back to the state as specified in the resource. The Operator will also delete the Service and Deployment which were created for this resource.

## [Software development in containers — a cookbook](https://itnext.io/software-development-in-containers-a-cookbook-2ba14d07e535?source=rss----5b301f10ddcd---4)

Multi-stage builds reduce the attack surface, decreasing vulnerabilities. Multistage builds are safer, and it also reduces image size. Container images should be small and contain only components/packages necessary for the containerized workload to work correctly. Docker-compose specification is a developer-focused standard for defining cloud and platform-agnostic container-based applications. It is fully portable, so you can run it locally or in. Azure Container Instances. You can download Kompose to convert docker-composing files to Kubernetes manifests.

## [A Review of “Kill It with Fire: Manage Aging Computer Systems”](https://www.usenix.org/publications/loginonline/kill-it-fire)

Instead of the mechanics of refactoring, Kill It With Fire focuses on how to structure teams tackling modernization projects that have failed previously. Instead of primarily approaching the problem of modernization from a software engineering perspective, Bellotti draws on lessons from Site Reliability Engineering (SRE) and the broader area of software operations work. Human factors are at least as important in decision making as the technical aspects of problems, as well as the human factors involved in decision-making. Kill it With Fire deals always with software as a running system, not a codebase.

## [Elixir and Kubernetes: A love story](https://david-delassus.medium.com/elixir-and-kubernetes-a-love-story-721cc6a5c7d5)

Kubernetes has been heavily adopted in many companies as the deployment and application orchestration solution. Most tutorials about Elixir only talk about building a webapp with Phoenix framework. But in the Erlang/Elixir ecosystem, those problems look like they are already solved. This article is the first of a series of articles that will cover how to build an Elixir cluster on Kubernetes. We’ll see how to set up an Elixir/Kubernetes cluster using the language that compiles to Erlang and is run on the BEAM.