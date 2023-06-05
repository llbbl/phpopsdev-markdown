# DevOps / SRE - Top Links Last Week

Week 47 — Issue #54

  

## [DNS Spoofing on Kubernetes Clusters](https://blog.aquasec.com/dns-spoofing-kubernetes-clusters)

  

 An attacker can run malicious code on a Kubernetes cluster can, with no special permissive permissions, successfully spoof DNS responses to all the applications running on the cluster, and from there execute a MITM (Man In The Middle) on all network traffic of pods. In this blog, I’m mostly going to concentrate on the default configurations, just for setting a common ground. The ClusterFirst DNS policy is a default for pods, it is rare to use a different policy. This is how pods communicate with each other on the same node.

  

## [7 DevOps skills for Machine Learning Operations](https://towardsdatascience.com/7-devops-skills-for-machine-learning-operations-7cf54b19adc0)

  

 DevOps Engineers are expected to know Git concepts and workflows such as Gitflow, GitHub flow, or custom alternatives. CI/CD knowledge is also mandatory in a DevOps Engineer’s toolbelt. Infrastructure as code should be used since the early days of an MLOps project. MLOps teams usually rely upon managed cloud services for data processing, storage, and model training, which means infrastructure provisioning is not exactly related to networks or virtual machines but to buckets, database-like services, and cloud schedulers.

  

  

## [7 Tips for Building a Multi-Tenant Cloud Service over AWS](https://alonkollmann.medium.com/7-tips-for-building-a-multi-tenant-cloud-service-over-aws-bd6a287637c0)

  

 A year ago, Hysolate started a new multi-tenant cloud service at the beginning of the year. We decided to share some of our insights on how to build a new product from scratch. Here are a few tips: Start with a single region and avoid supporting multiple regions early on. Avoid the AWS Elasticsearch Service (now Amazon Opensearch Service) and Elasticsearch. Use Lambda@Edge to run custom code right at the CDN edge. Consider Fargate over K8s and Kubernetes to eliminate the hassle of maintaining a cluster.

  

  

## [Run as the Root Account](https://www.garyshood.com/root/)

  

 Rambo, First Blood Part 1, ran as the user account john instead of being powerful and running as root. Rambo is awesome because he ran as root, and Colonel Trautman, who is running as Root, contacts Rambo over the radio, telling Rambo to come back to base and surrender himself. In this version, Rambo turns himself in, instead of getting to shoot that sherrif a couple times. That's probably the worst movie ever. He told the Colonel that he would be making his own decision that day, and it was the right one.

  

  

## [20 Amazing GitHub Repositories Every Developer Should Follow](https://towardsdatascience.com/20-amazing-github-repositories-every-developer-should-follow-d8ce4c728351)

  

 GitHub is the central place to host open-source projects and share resources among the developer community. With 45 million public repositories, GitHub offers every form of knowledge sharing for the developers, including open source projects, libraries, learning platforms, interview preparation, CV writing tips, knowledge base, and many more. In this article, I will list 20 excellent GitHub repositories with high popularity, usability, demand, and high demand. This list will be inclusive and will not focus on a particular programming language or target group.

  

  

## [UNDERSTANDING CYBER ATTACKS AS A BEGINNER](https://faun.pub/importance-of-understanding-social-engineering-as-a-threat-a85a39f1953c?source=rss----10d1a7495d39---4)

  

 Hackers execute an attack every 39 seconds or 2,244 daily from research (University of Maryland) 134 million credit cards were exposed costing Heartland Payment Systems over $145 million in compensation for fraud payments alone. It takes an average of 206 days to identify a breach and it takes about 314 days to contain a breach — IBM. As a novice in cybersecurity, you must be able to discern between threats and the various forms they take, as well as to detect vulnerabilities in your organization. In this article, we will discuss Threats, Vulnerabilities, and Incident response.

  

## [All you need to know about YAML](https://faun.pub/all-you-need-to-know-about-yaml-3dbfbf9f19a4)

  

 YAML requires colons and commas used as list separators followed by space with scalar values. Multiple documents with single streams are separated with 3 hyphens ( — -) Nodes should be labeled with an exclamation mark (!!), followed by a string that can be expanded into a URL or URL. Multi-line strings are stored using pipe the character ( | ) in the format of key-value pairs. The new line is preserved and end spaces are not preserved.

  

## [Fleet, a Lightweight IDE from JetBrains](https://blog.jetbrains.com/blog/2021/11/29/welcome-to-fleet/)

  

JetBrains is releasing a lightweight editor called Fleet. The lightweight editor is built from scratch with a new architecture and user interface. It is also a fully functional IDE bringing smart completion, refactorings, navigation, debugging, and everything else that you’re used to having in an IDE – all with a single button click. With its distributed architecture, Fleet doesn’t care if your project is local, in a container, or in another country thousands of miles away. By providing a virtualized file system, Fleet can work with local and remote projects.

  

## [Software Interviews Suck — Here is How to Fix Them](https://levelup.gitconnected.com/software-interviews-suck-here-is-how-to-fix-them-ea587f89db89)

  

 There are 7 easy steps to restore humanity to the software developer interview process. Rethink/remove one-on-one coding sessions and create a rubric to standardize, score and rank candidates. Instead, try Karat — the company that had the outrageous idea to (gasp) actually train engineers to interview. The interviewers are excellent; the questions are fair (ie. no riddles, start easy and get harder) and best of all, you get a one free redo option, no questions asked.

  

## [Re-using your Github Action Workflow](https://piyush-dubey.medium.com/re-using-your-github-action-workflow-888660df183c)

  

 Github beta feature allows you to reuse your workflows across files using workflows. Reusable workflows can be used to run and reuse any number of workflows in your project. To create a reusable workflow we need to attach a different dispatcher then regular onPush or onPR to trigger the workflows inside a workflow. To use a workflow you should follow the same process as regular workflow file but main area would be, inside jobs you can create a separate workflow file to run workflows within.

  

## [Measuring Software Complexity: What Metrics to Use?](https://thevaluable.dev/complexity-metrics-software/)

  

 This article is a broad introduction of the different complexity metrics you can use. Measuring complexity can bring the information we need to be sure we’re headed in the good direction. The goal is not to acquire absolute certainty about the modules which could bring horrible bugs, but to reduce this uncertainty. In the following articles, we'll see more concrete examples how to combine these metrics to get the data we want. The first article is also the first of a series about measuring complexity in a codebase.

  

## [The internet is held together with spit and baling wire](https://krebsonsecurity.com/2021/11/the-internet-is-held-together-with-spit-baling-wire/)

  

 Internet Routing Registry (IRR) is a distributed database of Internet routing instructions that helps connect a vast array of individual networks. Lumen Technologies Inc. (formerly CenturyLink) is one of more than two dozen entities that operate what’s known as an IRR. A key function of the BGP data maintained by IRRs is preventing rogue network operators from claiming another network's addresses and hijacking their traffic. Nearly all IRRs have disallowed the use of this method since at least 2012.

  

## [An Introduction to Circuit Breaker Pattern and Its Uses](https://aws.plainenglish.io/an-introduction-to-circuit-breaker-pattern-and-its-uses-a3e9c295e814)

  

 Circuit breaker pattern detects whether a failed operation is likely to succeed if tried again and if so it retries. Circuit breaker keeps track of the number of failures against different dependencies. When a dependency is down for a longer period, the circuit breaker is closed. It will instead spare requests to the failing dependency as they are likely to fail, and instead, throw exceptions and fail fast. The circuit breaker will open when the failure threshold is above a certain threshold. When this timer runs out it goes to the half-open state and tries again when it runs out. The failure threshold should be based on how the dependency typically acts.

  

## [Beginners Guide to Authentication Basics](https://levelup.gitconnected.com/beginners-guide-to-authentication-basics-ead786af0e77)

  

 There are different ways to implement an authentication system using modern technologies. This article is a more general explanation of how authentication systems work. Authentication and authorization are 2 different sections of a login system. Token-based or cookie-based approaches are mainly used to perform these scenarios. There are pros and cons to each approach. If you would like to support me as a writer consider signing up to become a Medium member. So that I can spend more time on sharing knowledge and creating more content. It’s just $5 a month and you get unlimited access to Medium.

  

## [Distributed Authorization and Wayfair’s Supply Chain](https://www.aboutwayfair.com/careers/tech-blog/distributed-authorization-and-wayfairs-supply-chain-of-the-future)

  

 IsC Engineering was a new department in Wayfair, replacing a monolithic codebase that housed the majority of the company’s engineering services. It quickly became apparent that this model was incapable of supporting an agile, fast-moving company. With that, Wayfair decided to split the monorepo into smaller microservices. We saw deployment times shrink from hours to minutes and began shipping to production at a dramatically increased rate. But the team wasn’t fully satisfied with the architecture, which brought us back to authorization and authentication.

  

## [JWT Ultimate: How-To Guide With Best Practices In JavaScript](https://betterprogramming.pub/jwt-ultimate-how-to-guide-with-best-practices-in-javascript-f7ba4c48dfbd?source=rss----d0b105d10f0a---4)

  

 JWT is a standard RFC 7519 for exchanging cryptographically signed JSON data. It is probably the most popular current standard of authorization on the web, especially when it comes to microservices and distributed architecture. Modern web solutions are often based on multiple servers or multiple services working together. With a growing distributed system, sharing a session can be quite challenging. The alternative to stateful session management is passing a stateless JSON Web Token which will represent an access token. It will hold claims that allow your services to authorize their users and it will use the magic of cryptography to ensure that the token is authentic.

  

## [The Perfect System Doesn't Exist](https://alexkondov.com/the-perfect-system-doesnt-exist/)

  

 The perfect system still remains a mythical creature - it doesn’t exist. What is considered a best practice for one domain may be an anti-pattern for another. We rarely do the same thing twice and change is much faster than anticipated. Even if we somehow managed to crystallize fundamental patterns that are applicable across all (or at least most) domains, the environment in which we work won't remain the same. We only have our previous experience and knowledge to rely on. We bring only the high-level abstract concepts and practices, but the details vary from business to business.

  

## [Automated Docker Deployments Using Watchtower](https://betterprogramming.pub/automated-docker-deployments-using-watchtower-1b7414a755e5?source=rss----d0b105d10f0a---4)

  

 Watchtower is a docker container that listens to changes that happen on deployed docker images. The watchtower listens to the Docker registry and deploys on changes that are published. In addition to watchtower by default check changes in 5-minute intervals, but with this setup I’m setting to check changes every 30 seconds using -i 30 while starting the watchtower. That’s why we mount /var/run/docker.sock as a volume. Because watchtower needs to have access to the docker instances in order to. capture changes from the origin docker registry.