# DevOps / SRE - Top Posts Last Week

## Week 36 Issue #43

## [How Lowe’s SRE reduced its mean time to recovery (MTTR) by over 80 percent](https://cloud.google.com/blog/products/devops-sre/how-lowes-improved-incident-response-processes-with-sre/)

Lowe’s SRE team shares how they used SRE principles to decrease mean-time-to-recovery (MTTR) by over 80 percent. Lowe's went from one release every two weeks to 20+ releases daily, helping meet customer needs faster and more effectively. SRE: Monitoring, alerting tools let you detect issues as soon as they occur, and notify the right person in the shortest possible time to take action. A blameless postmortem builds on that and is a core part of an SRE culture, and our culture at Lowe's.

## [How Docker broke in half](https://www.infoworld.com/article/3632142/how-docker-broke-in-half.html)

The open-source tool that allows developers to build and run their software in a single location. It was created in 2008 as a way to make it easier for developers to move their software across the world. But the tool has never been able to turn it into a successful business model. It has now been replaced by the likes of Amazon, Google, Microsoft and other big tech companies in the world's biggest-ever software market. The company has been forced to pull back on the idea of using it as a tool to get the best out of the market.

---

## [Data pipelines: what, why and which ones](https://towardsdatascience.com/data-pipelines-what-why-and-which-ones-1f674ba49946)

A data pipeline is simply an automated chain of operations performed on data. It can be a flow that aggregates data from multiple sources and sends it off to some data warehouse, or it can perform some type of analysis on the retrieved data. UbiOps, also offers its own form of pipelines, for instance. In this article we will map out and compare a few common pipelines, as well as clarify where they fit in the general picture. All pipelines are automated, they introduce reproducibility and help to split up complex tasks into smaller, reusable components.

## [Amazon EKS Anywhere](https://github.com/aws/eks-anywhere)

Amazon EKS Anywhere enables you to easily create and operate Kubernetes clusters on-premises with your own virtual machines. It brings a consistent AWS management experience to your data center. The project is licensed under the Apache-2.0 License. It is tested using Prow, the Kubernetes CI system, which is visible at [https://prow.amazonaws.com/EKS.com/](https://prow.amazonaws.com/EKS.com/). Please read our CONTRIBUTING guide before making a pull request.

## [Facebook’s Golang Object Relational Mapper Moves to the Linux Foundation](https://thenewstack.io/facebooks-golang-object-relational-mapper-moves-to-the-linux-foundation/)

Ent, the Go entity framework, was created at Facebook and open-source in 2019. Ent helps developers work on complicated back-end applications, where they might have to deal with a large number of entity types. Facebook has decided to move the Ent project under the Linux Foundation’s governance, where it will find a vendor-neutral home for the future. Ent uses Graph concepts, such as nodes and edges, for modeling and querying data, which means the database can be either relational or graph-based.

## [How to Replace Docker with Podman on a Mac](https://www.redhat.com/sysadmin/replace-docker-podman-macos)

Podman is an easy replacement for Docker and Vagrant for Apple's Mac OSX. Using the latest version of VirtualBox, you can install Podman on your Mac using the Vagrant toolkit. The Podman-machine is now deprecated in lieu of Vagrant, so I've documented the process here. The pre-requisites are the latest and easiest way to start Podman and use Vagrant. The process is described in three main parts: the prerequisites, creating a script, and then creating the Mac app.

## [No Kubernetes Needed: Amazon ECS Anywhere](https://thenewstack.io/no-kubernetes-needed-amazon-ecs-anywhere/)

Amazon Web Services has taken a different approach to deliver hybrid and multicloud platforms. Instead of Kubernetes, Amazon chose Elastic Container Service (ECS) as the vehicle for delivering hybrid cloud capabilities to customers. Amazon ECS was launched in 2014 as a managed container orchestration platform for AWS customers. ECS is an AWS-managed service, it’s tightly integrated with various AWS services such as CloudWatch, ALB, VPC, and others. Amazon announced ECS Anywhere, the service that extends ECS to on-prem and other cloud environments.

## [A Guide to Choosing an Ingress Controller, Part 1: Identify Your Requirements](https://www.nginx.com/blog/guide-to-choosing-ingress-controller-part-1-identify-requirements/)

This is the first blog post in our series on how to choose a Kubernetes Ingress controller. Ingress controllers can provide much more than the basic functionality of moving your traffic from point A to point B. They can provide advanced traffic management to visibility to built‑in security. Choosing an Ingress Controller that doesn’t scale well or protect complex environments can prevent you from getting Kubernetes out of testing and into production. At F5 NGINX we consider it to be the foundation of any production‑grade Kubernetes deployment.

## [Unleashing GitHub Environment on Your Workflows](https://betterprogramming.pub/unleashing-github-workflow-environments-40e550fde009)

GitHub has added environments which provide support for environment protection rules, environment secrets and manual approvals. GitHub is a great tool for building and managing your CI/CD pipeline. Let’s take a look at how we can take full advantage of these new features to manage our multi-environment deployments with GitHub's environments. The workflow is triggered by changes being pushed to the main branch and it has 2 deployment jobs, one for each environment. Each deployment also uses a secret as part of the deployment.

## [3 Engineering Concepts To Boost Software Quality](https://betterprogramming.pub/3-engineering-concepts-to-boost-software-quality-bf8d673d3ed8)

Certain programming concepts are losing their importance due to insignificance in the modern world of engineering. But they are pillars for the next evolutional step. Programming these days is not like it was 20 years ago. The number of frameworks and libraries is huge. They simplify engineer’s life and at the same time, it does some harm. Developers have fewer concurrency issues such as race conditions or deadlocks leading to fewer bugs. The concept of transactions helps a lot. It is hard to imagine a real production database nowadays that doesn’t utilize transactions.

## [What Software Engineers Can Learn From Submarines](https://betterprogramming.pub/what-software-engineers-can-learn-from-submarines-2e90215d3f96)

David Marquet’s book “Turn the Ship Around! A True Story of Turning Followers into Leaders” contrasts this model with a more traditional leader-follower model. In the leader-leader model, as many responsibilities as possible are pushed down the chain of command. It encourages everyone on deck to engage with problems and to find efficient solutions. Tapping into everyone's creativity will also lead to faster, innovative solutions, which might be the difference between success and failure in a software startup.

## [GitGuardian Investigation Finds Secrets in Docker Images](https://containerjournal.com/features/gitguardian-investigation-finds-secrets-in-docker-images/)

A report published by GitGuardian finds 7% of Docker images contained at least one secret. One secret was discovered for every 500 files scanned, the report says. The report suggests Docker images are more security conscious than other types of software artifacts. The need to better protect application secrets will be part of a larger focus on securing software supply chains that has emerged in the wake of a series of high-profile breaches that has prompted many organizations reevaluating how they build and deploy modern software.

## [Awk: The Power and Promise of a 40-Year-Old Language](https://www.fosslife.org/awk-power-and-promise-40-year-old-language)

1977 Unix utility Awk can boast of a loyal band of users and seems poised to continue far into the future. In this article, I’ll explain what makes Awk special and keeps it relevant. Awk runs on inputs and a script, which comprises a set of conditions and actions. The condition is often a regular expression enclosed by slashes enclosed by braces. If the condition matches a part of the input, the action is executed. The language is more of a declarative language than a procedural one.

## [NPM package with 3M weekly downloads had a severe vulnerability](https://arstechnica.com/information-technology/2021/09/npm-package-with-3-million-weekly-downloads-had-a-severe-vulnerability/)

Popular NPM package "pac-resolver" has fixed a severe remote code execution (RCE) flaw. The vulnerability has to do with how Proxy Auto-Config (PAC) files are processed by the module. Pac-Resolver receives over 3 million weekly downloads, extending this vulnerability to Node.js applications relying on the open source dependency. A third-party tool named mongo-express has no affiliation with the package in question; MongoDB confirmed to Ars that they have no affiliation.

## [Signs of Emotionally Intelligent Developers | by Lokajit Tikayatray](https://betterprogramming.pub/7-signs-of-software-engineers-with-high-emotional-intelligence-720bf5978189)

7 Signs of Software Engineers With High Emotional Intelligence. Learn how to enhance your EQ to set your career on a high growth path. Emotional intelligence enables people to stay in control, build collaborative workplace relationships, and achieve extraordinary growth in their careers. They listen to every point intently and wait for their turn to speak. Ask questions to clarify any doubt you have on the feedback. Analyze the details to use them for self-improvement. Developers with high EQ understand that mistakes are part of learning curve.

## [Parse, don’t validate, incoming data in TypeScript.](https://itnext.io/parse-dont-validate-incoming-data-in-typescript-d6d5bfb092c8)

The hard way to parsing data is parsing, not validating, the hard way. This is a common problem in web programming. Let’s use a JavaScript validation library like yup and a type-checker like ajv. We can now parse any data to UserType with type aliases and type guards. The error prone, dangerous, not-that-well-well, dangerous code-checked code can be done in TS-type-checked. We are using type aliases to test our parsers and writing parsers for specific types can be a breeze.

## [Managing command snippets is hard; but there is hope](https://itnext.io/managing-command-snippets-is-hard-but-there-is-hope-dc6f046759bc)

Pet is a command-line tool for managing command snippets. It is written in go and written in Go. The snippets are easy to use and easy to find and navigate to web pages directly from the command line. There are also bookmarks, it would be convenient to use bookmarks to navigate to the web page directly from command line. It is possible, but cumbersome and the command has to be copied to execute it. It would be better to use a text file or have a handy gist.

## [SOLID Principles](https://faun.pub/solid-principles-a5c650fcf30)

SOLID principles are a set of principles followed in the world of object-oriented programming. These principles are widely popular since the end of 20th century and are still followed. They aim to write more simple, maintainable, extendable and understandable classes. The Single Responsibility Principle (SRP) represents the ‘S’ in SOLID. Every class/function should have one and only one responsibility. Cohesion and Coupling means the correlation between various properties and methods in a class.

## [The Mindset of Successful Developers](https://itnext.io/the-mindset-of-successful-developers-905b0aba22a8)

Software developers need to be resilient, resource and relentless to help the project be successful. Good developers are not concerned about titles or roles, they focus on creating quality software. They are passionate about the power of development and believe there is no problem that you can’t develop software for. They keep going until they have solved the problem and created the software. Good software developers are competitive and are curious about any new technique, tool or approach that would improve their software development. They will argue loud and long to make sure their idea is chosen.

## [Containers from Zero To Hero: Namespace and Cgroups](https://tonylixu.medium.com/containers-from-zero-to-hero-2-namespace-and-cgroups-eaf587396749)

Namespace is an isolation mechanism to isolate containers running on the same host. Linux creates a PID Namespace, which is the parent Namespace of other containers. This isolation means that multiple containers cannot access each other’s resources. Namespace and Cgroups are two very important/foundational container concepts: Namespace/Cgroups. In this article, we use an example to see what exactly Namespace means in docker images and a running httpd container as an example of Namespace.

## [Generating Random Numbers Is a Lot Harder Than You Think](https://betterprogramming.pub/generating-random-numbers-is-a-lot-harder-than-you-think-b121c3e75d08)

Random numbers are a crucial part of modern life, and we rely on computers to generate them for us. The most common type of random number generator is the pseudorandom number generator. This makes them “good enough” for most use cases, such as video games. But PRNGs follow a pattern, this pattern isn’t perceivable by humans. They make the game-runners in video games easily manipulate them to make it predictably random. The Mersenne Twister is still the most popular PRNG algorithm used today.

## [Centralized Logging Solution on Elasticsearch](https://aws.plainenglish.io/centralized-logging-solution-on-elasticsearch-with-real-time-anomaly-detection-4b2c479e62ea)

More and more companies are moving towards predicting the issue and fixing it beforehand. The end-to-end process from getting the call from the customer to fixing the product took around 5–8 days, 4 flights, and all the associated expenses. At this customer, we implemented a solution to stream the logs from the product in real-time to the cloud. ML models would predict the potential problem, its probability and the part to be replaced. The technician would take the part along and replace it during the visit. By switching to pro-active maintenance and repair, this company saved significant $$.