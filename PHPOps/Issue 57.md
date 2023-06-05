# DevOps / SRE - Top Links Last Week

## Week 50 - Issue #57

  

  

## [Log4Shell Log4j vulnerability (CVE-2021-44228) – cheat-sheet reference guide](https://www.techsolvency.com/story-so-far/cve-2021-44228-log4j-log4shell/)

  

CISA orders federal agencies to patch Log4Shell by December 24th. Vulnerability affects Java servers and clients that log anything using the log4j framework. Java 8+: upgrade to 2.16.0 or 2.12.2.0. Java 7: Upgrade to 2.12.0. If JMS Appender required, use Log4j 2.2. Users advised not to enable JNDI in Log4J 2.10 or greater. Removal of JndiManager will cause the J.ndiContextSelector and JMSAppender to no longer function.

  

## [The Light and Dark Side of the API Economy](https://www.swyx.io/api-economy/)

  

The 'API Economy' is a popular term for VC's and tech media, however Developers seem ironically out of the loop despite their central importance to the whole story. It is both a great opportunity for builders and a threat to people who cannot stay "Above the API" The most important implication of the API Economy is how it empowers developers to build full fledged products faster. In economics terms what we're really talking about here is turning fixed costs to variable costs which makes sense for a startup getting off the ground.

  

## [Power Loss Siren: Making Meta resilient to power loss events](https://engineering.fb.com/2021/12/16/data-center-engineering/power-loss-siren/)

  

Power Loss Siren (PLS) is a rack level, low latency, distributed power loss detection and alert system. It leverages existing in-rack batteries to notify services about impending power loss without requiring additional hardware. With PLS support, services can failover proactively, rather than reactively after servers go down. PLS has two major components: PLS Relay (detection) and PLS Handler (mitigation) Both daemons need to be simple to maintain, resource efficient and highly reliable in detecting power loss events.

  

## [A brief history of code search at GitHub](https://github.blog/2021-12-15-a-brief-history-of-code-search-at-github/)

  

GitHub hosts over 200 million repositories, with over 61 million repositories created in the past year. Many standard techniques (like stemming and tokenization) are at odds with the kind of searches we want to support for source code. We need to be able to match substrings, not just whole “words” Specialized queries can require wildcards or even regular expressions. We want p95 query times to be (well) under a second, or queries scoped to a set of repositories or organizations, should be much faster than that. We would like our index to reflect the updated state of a repository within a few minutes of a push event.

  

## [The Grace Period for the Docker Subscription Service Agreement Ends Soon – Here’s What You Need to Know](https://www.docker.com/blog/the-grace-period-for-the-docker-subscription-service-agreement-ends-soon-heres-what-you-need-to-know/)

  

Docker announced updated product subscription tiers — Docker Personal, Docker Pro, Docker Team and Docker Business. Docker Personal replaces Docker Free and it remains free for personal use, education, non-commercial open source projects, and small businesses. Docker Business is our newest subscription offering that enables commercial use of Docker Desktop, and includes additional enterprise-grade management and security features like Image Access Management, vulnerability scanning, SAML SSO, and more. The grace period for those who need to switch to a paid subscription under the new terms ends soon on January 31, 2022.

  

## [Understanding resource limits in kubernetes: memory](https://medium.com/@betz.mark/understanding-resource-limits-in-kubernetes-memory-6b41e9a955f9)

  

When I started working with Kubernetes at scale I began encountering something that didn’t happen when I was just running experiments on it. The real problem in many cases was not that the nodes were too small, but that we had not accurately specified resource limits for the pods. In this two-part series I’m going to first look closely at memory limits, and then follow up with a second post on cpu limits. The first is a critical input to the scheduler that enables it to choose the right node on which to run the pod.

  

## [3 lines of code shouldn't take all day](https://devtails.xyz/3-lines-of-code-shouldnt-take-all-day)

  

The goal of this post is to help remind you to reflect on your current development process. It would take an entire day to change 3 lines of code and know that it actually worked correctly. Testing changes here could mean progressing through several seasons of career mode in order to test out a change. It also allowed me to fix actual issues at a reasonable (by my standards) rate. The goal is to continually focus on a task that is not taking too long to compile (and run) Compile errors and logic errors are inevitable, but when I can re-compile it allows one to enter a state of state of work at work.

  

## [Using an ETL framework vs. writing yet another ETL script](https://airbyte.io/blog/etl-framework-vs-etl-script)

  

The first time your engineering team needs to pull data from an external source, you may be tempted to write an ETL script in your favourite programming language. In 2021, tooling has progressed such that this should be considered an antipattern. At Airbyte, we’ve built an open-source ETL framework (or should we say ELT) so you don’t have to code everything yourself. In this article, we share a common story of how this little ETL. script evolves as you need to add more features to make it production ready.

  

## [The Projects and People That Shaped Security in 2021](https://thenewstack.io/the-projects-and-people-that-shaped-security-in-2021/)

  

The latest exploitation of log4j logging library has sent developers in a scramble. The breach capitalizes on what has been another whirlwind of a year in cybersecurity. Kubernetes has exploded to 88% widespread adoption, yet more than half of respondents in Red Hat’s latest survey said they’ve delayed deploying Kubernetes applications into production due to security concerns. The U.S. presidential administration issued an executive order, requiring vendors who manufacture and distribute software to detail what is actually in their products.

  

## [Kubernetes Made Simple: The basics](https://faun.pub/kubernetes-made-simple-the-basics-1fedfe3a0e14)

  

Kubernetes is an open-source container orchestration tool or framework developed by Google in 2014. It helps you manage applications that are made up of hundreds or thousands of containers in different environment either Physical, Virtual or hybrid machines. It lets you deploy containers to clusters, meaning a network of virtual machines. A cluster is a set of node machines for running containerized applications. If you’re running Kubernetes, you‘re running a cluster. If you want to run a cluster, it’s a way of dividing the cluster resources between two or more users. It is an entry point for all types of administrative tasks. The Master Node is responsible for managing a cluster.

  

## [My EC2 Instance Was Breached. Now What?](https://betterprogramming.pub/my-ec2-instance-was-breached-now-what-6bb2b7277fb8)

  

An EC2 instance was hacked into a Jenkins CIK that ran build jobs for various node/ruby projects. The process was running a script that piped output to a random IP that turns out to be overseas. PagerDuty has a great security incident response plan that they have available. The company updated the security group attached to the compromised host with an “airgapped” group, meaning the host would not have any allowed network traffic inbound or outbound. It was an interesting clue to see all the other Jenkins agents and saw that they didn’t have anything funny running on them.

  

## [Linux Distros: Year in Review](https://thenewstack.io/linux-distros-year-in-review/)

  

2021 was a pretty exciting year for Linux distributions within the cloud native and developer world. AlmaLinux, Rocky Linux, and Ubuntu Server 21.10 were released. Red Hat released version 8.5 of Red Hat Enterprise Linux and AlmaLinux 8.4 of AlmaLinux. Rocky Linux was created by the originator of CentOS and it shows. If you didn’t know any better, without the branding in place you’d swear this was CentOS. And there were no new distributions released that were purpose-built for cloud, container, and edge use cases.

  

## [Fast Docker Builds With Caching  (Not Only) For Python](https://towardsdatascience.com/fast-docker-builds-with-caching-for-python-533ddc3b0057)

  

There are a couple of things that can make fast builds challenging. Docker can reuse locally cached layers, but external cache sources can help. BuildKit adds another feature that can help: build mounts. Multi-stage builds and virtual environments can help speed up builds. We also added a Python virtual environment to make the build process easier to do. The Challenge is to build and pull large images and pull them from a large registry. We use Docker with BuildKit with the DOCKER_BUILDKIT=1 environment variable.

  

## [5 Takeaways from SmartBear’s State of Software Quality Report](https://thenewstack.io/5-takeaways-from-smartbears-state-of-software-quality-report/)

  

Frank Kilcommins is API Technical Evangelist at SmartBear. He has over 15 years of experience in the technology industry, his roles spanning from software engineering to enterprise architecture. His mission is to inspire, engage with, and support the API community as well as SmartBear customers across the end-to-end API development lifecycle and management space. The State of Software Quality |API report continues to help SmartBear keep a finger on the pulse of API community. The majority of organizations operate in a multiprotocol landscape, with 81% of organizations using more than one protocol.

  

## [Inspection and the limits of trust](https://lethain.com/inspection/)

  

The most effective leaders start by understanding their new environment, but a surprising number of new leaders jump into the new environment somewhat recklessly. Leading effective and collaborative teams requires a nuanced approach to trust. When someone brings a problem or a concern to you, trust them that there is a problem, but give yourself space to independently verify their interpretation of the problem. Inspection is a gift: it’s taking it seriously enough to ensure we’re getting to the bottom of the actual problem at hand.

  

## [Log4j Is One Big ‘I Told You So’ for Open Source Communities](https://thenewstack.io/log4j-is-one-big-i-told-you-so-for-open-source-communities/)

  

Apache Log4j has a zero-day attack called Log4Shell, which allows attackers to “hit you with a Remote Code Execution (RCE) attack, which can be used to compromise your servers’s servers” The bug is so bad that it “is going to keep you up at night for weeks, possibly months, to come,” writes Steven J. Vaughan-Nichols. The response to the news has been a pile-on moment for open source developers and maintainers, with many offering their own version of an “I told you so” comic.

  

## [MongoDB Unit-testing in Node.js](https://itnext.io/mongodb-unit-testing-in-node-js-5686390a6689?source=rss----5b301f10ddcd---4)

  

The TL;DR section shows a JS code listing for a sample repository test. The tricky part that is left is creating a MongoDB instance. The feasibility and convenience of each of these ways depend on whether one needs to have a replica set or not. We will create a Docker-Compose configuration file that created 3 instances of MongoDB containers: a primary, a secondary, and an arbiter. Using the function initMongoConnectionWithDBName one can use a cloud-based or remote MongoDB deployment and randomize the DB name to avoid race conditions.

  

## [My pet peeves with Terraform](https://blog.runx.dev/my-pet-peeves-with-terraform-f9bb37d94950)

  

Terraform is one of the most popular open source infrastructure-as-code (IaC) solution. It makes it super easy to declaratively define your infrastructure with all the major public clouds. But no tool is perfect and there are a lot of annoyances with Terraform. Terraform uses state files to record the current infrastructure state. But the reality of the infrastructure could deviate from the state terraform expects due to multiple reasons. Terraform apply can fail mid way due to many reasons and ends up in a state where the resource is created but not recorded in the state.

  

## [Log4j is patched, but the exploits are just getting started](https://www.theverge.com/2021/12/16/22839624/log4j-vulnerability-patched-threat-mitigation)

  

The Log4j vulnerability was uncovered last week, but serious hacks making use of the exploit are all but certain. A list of affected software compiled by the Cybersecurity and Infrastructure Security Agency runs to more than 500 items long at time of press. Any one company could be using numerous programs containing the. vulnerable library containing the vulnerable library — in some cases, with multiple versions inside one application. Some names on the list will be familiar to the public (Amazon, IBM, Microsoft), but some of the most alarming issues have come with software that stays behind the scenes.

  

## [Scaling your Laravel applications](https://itnext.io/scaling-your-laravel-applications-3c59ad374ddf?source=rss----5b301f10ddcd---4)

  

Some practical scaling ideas and issues to be aware of in this section. In some cases, I’ll be advising of things to be mindful of. In others, I'll be dispelling some approaches that you probably shouldn’t be using. You probably don't need UUIDs, sharding, or other complex setups like Twitter’s Snowflake. Simple write queries will not usually lead to auto-incrementing deadlocking issues. Avoid using WHERE LIKE with a wildcard prefix.

  

## [HTTP/3 Is Fast](https://requestmetrics.com/web-performance/http3-is-fast)

  

The first official version of HTTP (Hypertext Transfer Protocol 1.0) was finalized in 1996. There were some practical issues and parts of the standard that needed updating, so HTTP/1.1 was released a year later in 1997. In 2015, RFC 7540 would standardize HTTP/2 as the next major version of the protocol. The major difference between the two is the use of a new protocol called QUIC instead of TCP, which is meant to address the head-of-line blocking issues with TCP/2. QUIC has the capability to improve the performance of a mapping of a series of state streams.

  

## [Log4Shell: We Are in So Much Trouble](https://thenewstack.io/log4shell-we-are-in-so-much-trouble/)

  

Apache Log4j has a zero-day vulnerability, CVE-2021-44228 – also known as Log4Shell – is easy to exploit and can be used to grab complete control of vulnerable servers. Amazon Web Services (AWS) developers have created a patching program that works on Amazon Corretto 8, its OpenJDK 8 implementation. There is a fixed version out now: Apache log4j 2.15.0.0. You should update this as soon as possible.

  

## [Yet Another Log4j Security Problem Appears](https://thenewstack.io/yet-another-log4j-security-problem-appears/)

  

A new security hole in Apache Log4j security hole has been discovered: CVE-2021-45105! Fortunately, there’s already a patch available: log4j 2.17.0.0. The problem this time, Apache explained, was that the new 2.16 version “does not always protect from infinite recursion in lookup evaluation,” which made it vulnerable to a denial of service attack. Triggering this problem is alarmingly simple. You simply feed the application a poisoned string, and ta-da, instant crash.

  

## [An Introduction to CAP Theorem in Distributed System Design](https://jinkanglow.medium.com/distributed-system-cap-theorem-3ca7d933f5e7)

  

In a distributed system, network partitions occur, the system needs to choose between availability and consistency according to the business requirements. The CAP principle is about the trade-offs in distributed system design. Industrial-level systems often choose weak consistency or eventual consistency within the range that the business can tolerate. For consistency, there can be strong consistency, weak consistency, final consistency, and other choices based on requirements. For usability, we need to consider how many system users request, the level of concurrency, the size of the data, and so on to define the usability of the system.

  

## [Designing Netflix](http://highscalability.com/blog/2021/12/13/designing-netflix.html)

  

Ankit Sirmorya is working as a Machine Learning Lead/Sr. Machine Learning Engineer at Amazon. He is developing machine-learning-based solutions to send personalized reorder hints to customers for improving their experience. Ankit has been working on applying machine learning to solve ambiguous business problems and improve customer experience. We need to design a video streaming platform similar to Netflix where content creators can upload their video content and viewers are able to play video on different devices. We should also be able to store user statistics such as number of views, video watched duration, and so forth.

  

## [Deploy a Python Visualization Panel App to Google Cloud](https://towardsdatascience.com/deploy-a-python-visualization-panel-app-to-google-cloud-cafe558fe787)

  

This article walks you through how to deploy a Python app to Google Cloud with only three short scripts. It is surprisingly simple using the Google Cloud App Engine. Set up your Google Cloud account to enable App Engine and set up a project to run locally. Use Github Actions for Automation to streamline your deployment process with the help of Github Actions. The code mentioned in this article is available at this [repo](https://github.com/sophiamyang/panel_gcp).