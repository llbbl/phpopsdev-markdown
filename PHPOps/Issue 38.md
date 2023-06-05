# DevOps / SRE — Top Links Last Week

## Week 31 Issue #38

## [Less Is More with Kubernetes 1.22](https://thenewstack.io/less-is-more-with-kubernetes-1-22/)

Kubernetes version 1.22 has been released, and with the new features, some old features have been dropped. There are 56 enhancements to this new release, including 13 that have graduated to Stable. The new features include the Ingress API, Server-Side Apply and Server-side Apply. These are not deprecations but straight-up removals. The Deprecation Guide is available to help you migrate and find the replacement functionality for the old beta features.

## [Docker container security cheat sheet](https://blog.gitguardian.com/how-to-improve-your-docker-containers-security-cheat-sheet/)

Docker containers have been an essential part of the developer's toolbox for several years. Docker containers represent a standardized surface for attackers. They can easily exploit misconfigurations and escape from within containers to the host machine. The word “container” is often misunderstood, as many developers tend to associate the concept of isolation with a false sense of security, believing that this technology is inherently safe. We curated a set of the best recommendations regarding Docker containers configuration at build and runtime. Check out the one-page cheat sheet below.

---

_Please consider supporting the Weekly DevOps / SRE Report. Subscribe to our free [Newsletter](https://www.phpops.dev/subscribe/#/portal/signup) on our new website!_

---

## [The NSA Can Help Secure Your Kubernetes Clusters](https://thenewstack.io/the-nsa-can-help-you-secure-your-kubernetes-clusters/)

National Security Agency releases Kubernetes Hardening Guidance on how to protect your cluster. This includes guidance and a list of the most common vulnerabilities threat actors use to plant web shells on servers. The guide includes code examples to enable you to better secure your clusters. And, as many of you know, the NSA created SELinux. This is Linux’s optional mandatory mandatory access control (MAC) architecture. If you really want to secure Linux, SELinux is your first choice.

## [Cluster API Offers a Way to Manage Multiple Kubernetes Deployments](https://thenewstack.io/cluster-api-offers-a-way-to-manage-multiple-kubernetes-deployments/)

Cluster API project is a Kubernetes-style API for creating, configuring and managing cluster management. The real goal is “to make cluster lifecycle boring” Cluster API maintainer Vince Prignano told The New Stack. The cluster API project builds on kubeadm, a command-line tool to create, initialize, upgrade and administer clusters. It can be used in a bare-metal environment or in a virtual private cloud or in virtualized environments where there isn’t a provider like Azure or OpenStack.

## [Introduction to Kubernetes Clusters](https://faun.pub/introduction-to-kubernetes-clusters-c25cb425c2fc)

Kubernetes (K8s) cluster is a valuable tool because it abstracts away hardware infrastructure and enables the end-user to expose their infrastructure resources as a single computational resource. This computational resource can be used to run and manage microservices via container runtime solutions like Docker, containerd, rocket, etc. It is apt for most on-premise data centers and ideal for big cloud providers. The API server is the central component, which is used by all the other components and clients.

## [Developers, DevOps, or cybersecurity? This is the top tech talent employers are looking for now](https://www.zdnet.com/article/developers-devops-and-cybersecurity-the-top-tech-talent-employers-are-looking-for-now/)

Software developers were listed as the most in-demand occupation category, accounting for almost 250,000 job ads posted in Q1 2021. JavaScript, Java and Python were the most important programming languages for employers, with close to 60% of respondents citing high demand for JavaScript and Java in particular. The switch to remote working brought a sudden increase in demand for DevOps experts capable of managing organization's cloud infrastructure, and helping companies migrate their services to the cloud. 43% of survey respondents cited DevOps positions as their number one recruiting challenge in 2021.

## [Terraform Module for Kubernetes Cluster with Google Anthos](https://faun.pub/terraform-module-for-kubernetes-cluster-with-google-anthos-5f714ca3e6ff)

Infrastructure as Code (IaC) is a widespread terminology among DevOps professionals and a key DevOps practice in the industry. It is the process of managing and provisioning the complete IT infrastructure (comprises both physical and virtual machines) using machine-readable definition files. Terraform is an open-source infrastructure as code software tool. It helps in automating the complete data center by using programming scripts. Google Cloud Anthos is a hybrid, cloud-agnostic container environment. It enables us to run Kubernetes clusters anywhere, in both cloud and on-premises environments.

## [This Week in Programming: The ElasticSearch Saga Continues](https://thenewstack.io/this-week-in-programming-the-elasticsearch-saga-continues/)

Amazon Web Services and ElasticSearch have been at odds with each other for years. Elastic has tried to shut off access to ElasticSearch and shut out AWS. AWS says it is working on keeping clients of OpenSearch and Elasticsearch compatible with open source. Facebook's Winterfell, a STARK prover and verifier, has been released in Rust, Cratesio and an end-to-end tutorial. Facebook also released an open source tool that lets developers run a computation, get a result, and convince anyone that you did the computation correctly.

## [Kubecost vs. CAST AI: A Perfect Match for Cost Optimization — CAST AI](https://cast.ai/blog/kubecost-vs-cast-ai-a-perfect-match-for-end-to-end-cloud-cost-optimization/)

CAST AI is a full-service cloud automation platform providing powerful automation features for optimizing Kubernetes workloads. Kubecost is a robust cost reporting solution that teams can use to get insights into costs allocation, cost monitoring, and alerts – key tools for teams looking to gain visibility. Companies across industries such as e-commerce and adtech are using CASTAI to save from 50% to even 90% on their cloud bills. The tool provides detailed visibility, exhaustive reporting, and – in an ideal scenario – automated optimization can generate some serious cost savings.

## [Tools to Run Kubernetes Locally](https://yankee.dev/6-tools-to-run-kubernetes-locally)

There are multiple tools for running Kubernetes on your local machine, but it basically boils down to two approaches on how it is done. Running it from a single binary package running it as a container using Docker in Docker (DinD) running it inside of Docker is a popular way of bootstrapping it. The isolating nature of Docker makes running a multi-node cluster a breeze on a single machine, and also ensures the running instance does not affect the machine itself.

## [AWS X-Ray — Everything You Need to Know](https://aws.plainenglish.io/aws-x-ray-everything-you-need-to-know-8d7a79bd285c)

X-Ray is a tool that allows developers to analyze and debug distributed applications. It is available on Amazon’s Elastic Beanstalk, Elastic Load Balancer, SNS, DynamoDB, S3, and API Gateway. It can be used to analyze requests as they travel through the application. The tool can also be used for troubleshooting issues and errors. It will automatically catch metadata for API Calls made to AWS services made to these services. We will use this tool to help developers understand issues and troubleshoot issues.

## [We cut our AWS bill by 65% after moving to Lambda — Part 2: here’s how we did it](https://insights.project-a.com/we-cut-our-aws-bill-by-65-after-moving-to-lambda-part-2-heres-how-we-did-it-89ba52f4916f)

Fargate was too complex for our use case, but the project had a very simple microservice-based architecture but we were using a complex system to manage it. The main person responsible would be an all-round engineer with basic DevOps knowledge. He needed a deployment infrastructure that matched the simplicity of the application. The product data hub is the single source of truth about product information. Instead of connecting to the PIM directly, other systems like the ERP get their product data from the data hub’s architecture.

## [HTTP/2: The Sequel is Always Worse](https://portswigger.net/research/http2)

In this paper, I'll introduce multiple new classes of HTTP/2-exclusive threats caused by both implementation flaws and RFC imperfections. I'll start by showing how these flaws enable the.. these flaws. with case studies targeting high-profile websites powered by servers powered by. Amazon's Application Load Balancer to WAFs, CDNs, and bespoke stacks by big tech. These achieve critical impact by hijacking clients, poisoning caches, and stealing credentials to net multiple max-bounties. The paper is focused entirely on the technical details - if you'd like extra insight into the research journey, please check out the presentation:

## [How Airbnb and Twitter Cut Back on Microservice Complexities](https://thenewstack.io/how-airbnb-and-twitter-cut-back-on-microservice-complexities/)

Airbnb moved to a service-oriented architecture (SOA) to rid monolithic complexities, only to find this microservices-based approach led to its own tangle of complications. Airbnb created what its engineers call SOA v2, streamlined core functionalities into a simplified set of services to make it easier for developers to build out new features at the edges. Twitter has just rolled out a set of public APIs, as well as a multitenant microservice to cut down the sprawl of other microservices.

## [Kubernetes Security & Hardening Guidance](https://piotrzan.medium.com/kubernetes-security-hardening-guidance-cf5fc48a9b3e)

Hardening and securing Kubernetes requires expertise, experience and diligence not easy to find on the market. In the past, security might have been perceived as a hindrance too deliverables. In this article, we are going to look at patterns in cloud-native and Kubernetes security. These patterns are based on two interesting security-related publications, one from National Security Agency (NSA) and another from Cloud Native Computing Foundation (CNCF) The NSA Hardening Guidance and Cloud Native Security Whitepaper were released in November last year.

## [Why the New Firebase Web v9 Modular SDK is a Game-Changer](https://betterprogramming.pub/working-with-the-new-firebase-web-v9-modular-sdk-aad1c641640e)

Previously, the Firebase Javascript SDK incorporated what is known as side-effect imports. Each individual functionality of Firebase that your app requires is imported separately thanks to the introduction of modular packages. This drastically reduces the final bundle size of your app and will lead to much faster loading times. The new Firebase Web SDK is built into native Javascript ES modules, you can directly import only the features that your program needs: nothing more, nothing less. This is in stark contrast to the approach used with the old Firebase SDK.

## [How to Call a Serverless Function Or Web API Periodically With iOS Shortcuts](https://betterprogramming.pub/how-to-call-a-serverless-function-or-web-api-periodically-with-ios-shortcuts-24f3e696c105)

How To Automatically Call a Web API Periodically? How do you do it? Let’s open the Shortcuts app and tap the + sign to create a new shortcut. Tap on “Add Action” and search for “URL”, click it and add the API URL you want to call. To choose what type of request we want to do, we have to choose GET, POST, PUT, PATCH, and DELETE. If you want, you can send some headers when needed.

## [10 Easy Steps To Abandon Redux for the Remarkable React Hooks](https://betterprogramming.pub/10-easy-steps-to-abandon-redux-for-the-remarkable-react-hooks-124916fc634d)

A straightforward guide to using React Hooks for global state management Martin Novak explains how to leverage them to architecture your application. Using Hooks is the most simple way of managing your global state and access to your backend is through Hooks. We want React components in our application to be able to trigger actions, such as updating data, and we also want them to react to the results of these actions or any other change to the global state. This way we have access to all of our state and actions globally and we are following the separation of concerns principle.

## [How To Lead Meetings That Won’t Waste Time and Actually Drive Results](https://betterprogramming.pub/how-to-lead-meetings-that-wont-waste-time-and-actually-drive-results-d62f61fb5501)

14 Best Practices For Running Great Meetings include ground rules about acceptable and unacceptable behavior in the meeting. Every meeting should have a purpose, communicated to all attendees in advance. The majority of all business meetings take place with no pre-planned agenda. The more preparation required, the longer the lead time needed to distribute the agenda. If a meeting starts late, you disrespect the people who showed up on time, so be disciplined about starting and ending your meeting on time. If the meeting lasts more than an hour, people will need a break, so let them know that you will have scheduled breaks.

## [5 Signs of Highly Passionate Programmers](https://betterprogramming.pub/5-signs-of-highly-passionate-programmers-d0791217e064)

It is hard too have outstanding career growth in software development without a passion for it. 5 Signs of Highly Passionate Programmers can help you achieve extraordinary career growth and make you an inspiration for others. Learn the traits to set your software career on a high growth path. They are clear about their responsibilities and make every effort to excel in fulfilling their duties. They understand ‘We’re more powerful than ‘I’ and are perennially optimistic and confident in coping under pressure.

## [What Do Good Developers Need? Some Surprising Answers Here](https://thenewstack.io/what-do-good-developers-need-watch-some-surprising-answers/)

A European job site has recorded interviews with 12 different developers about the joys of programming. The videos are the work of Honeypot, a site that describes itself as a developer-focused job platform. Honeypot tries to match up employers with developers, data scientists, and DevOps, data and machine learning engineers (as well as engineering leaders) It's a reminder that not everyone has taken the traditional route into the programming field — not everyone’s experience is the same. Some common themes began to emerge, along with some challenges.

## [Introducing Variabless — JS & CSS A Match Made in Heaven](https://itnext.io/introducing-variabless-js-css-a-match-made-in-heaven-80d38c295f7b?source=rss----5b301f10ddcd---4)

Variabless allows you to easily create utility classes or any selector you wish referencing the variable’s value. It means you can leverage JavaScript to prevent repetitions and keep your config clean. It is all about sharing knowledge. Write for ITNEXT and share your ideas, knowledge, doubts and fears regarding technology to thousands. It provides a platform where developers and techies can share, learn & connect. Our audience ranges from very technical developers, enthusiasts, and IT managers willing to discuss new technologies. We are looking for content in areas like frontend and backend software development.

## [Evolution of search engines architecture - Algolia New Search Architecture Part 1](http://highscalability.com/blog/2021/8/2/evolution-of-search-engines-architecture-algolia-new-search.html)

Julien Lemoine, Co-founder & CTO of Algolia, to describe what the future of search will look like. He looks at some key milestones in the evolution of search engine architecture. The first big revolution was the use of inverted indexes in the early days of search engines. The introduction of sharding enabled search engines to treat large volumes of data. Lemoine: A totally new search engine will be built in August 2, 2021 at 9:11AM (GMT)

## [7 Git Commands That Saved My Life At least Once](https://betterprogramming.pub/7-git-commands-that-saved-my-life-once-or-forty-two-times-c76cc94244de)

There are three levels for configuration variables in git: local, global and system. The first (if defined) overrides the second and so on. This way we can have a global configuration in our computer but have a local configuration for a specific repository if we need to. If you want to learn something by yourself in your personal git account, you could set a specific. repository to use your personal configuration without messing up the configuration for all the other folders. There is more information on this StackOverflow answer or the official docs.