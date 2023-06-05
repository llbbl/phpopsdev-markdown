# DevOps / SRE - Top Links Last Week

## Week 34 Issue #41

## [Ansible Techniques I Wish I’d Known Earlier](https://zwischenzugs.com/2021/08/27/five-ansible-techniques-i-wish-id-known-earlier/)

Ansible can be pretty tedious too debug and obscure to develop at times. So I went looking for ways to speed up the process, and make it easier to figure out what is going on. Eventually I found five tools or techniques that can help, so here they are. These tips go in order from easiest to hardest to implement/use, and are easy to follow.

## [This Week in Programming: When Linux Was ‘Just a Hobby’](https://thenewstack.io/this-week-in-programming-when-linux-was-just-a-hobby/)

This week, the open source Linux operating system turned 30, at least by one accepted standard of when it started. Linus Torvalds posted a message on Usenet, beginning the Linux OS. Almost all major websites — including Google, Facebook, and Wikipedia — run on Linux. All 500 of the world’s fastest 500 supercomputers run Linux, thanks to Android, Linux is also the most popular end-user operating system. The company now says it's doing it twice a year, to further increase its transparency.

---

## [Setup a CronJob to execute Kubectl or AWS commands](https://ksummersill.medium.com/setup-a-cronjob-to-execute-kubectl-or-aws-commands-c1c15dd4ff1f)

This article can help anyone pretty much do anything in Kubernetes when dealing with the Kubectl. The original intent of this article was to back up a Postgres Database. But the problem that I had was that an Elastic Block Storage (EBS) can only associate to one Node at a time in a particular Availability Zone. So using a Host path or a shared volume from another node was out of the equation. That is where I turned into using commands within an existing pod. This process is straightforward to do.

## [Role-based access control like it was meant to be](https://tailscale.com/blog/rbac-like-it-was-meant-to-be/)

The most common “RBAC” systems today have been stripped down in ways that make them considerably weaker than the original concept. By going back to the original, we can build a true RBAC/ABAC security model that’s both simpler and more powerful than what you’ve likely seen before, for both very small and very large networks. The original RBAC and ABAC concepts and terminology originated in the U.S. military, decades ago. With DAC, the owner of an object can grant permissions on it. With MAC, your ability to do something doesn’t let you share that ability with others.

## [Why is REST More Popular than RPC?](https://edward-huang.com/programming/system-thinking/architecture/2021/08/24/why-is-rest-more-popular-than-rpc/)

The primary goal of a microservice architecture is to deploy independent services so that product can create multiple fast iterations at different times. Microservice architecture, service and service communicate through network calls, and both services usually agreed on some contract - called API. RPC tries to make remote network calls like function calls or methods in your programming language. Integration with RPC can be seamless by using their favorite programming language - you don’t need to learn a new design philosophy by integrating with RPC equivalence. As RPC uses the binary format to send requests between networks, integrating with API is more efficient and compact than RESTful API.

## [5 reasons you should use FastAPI to get stuff done quickly](https://itnext.io/5-reasons-you-should-use-fastapi-to-get-stuff-done-quickly-6230ded3a8c6?source=rss----5b301f10ddcd---4)

FastAPI is the 4th fastest Python framework in the world, beating Flask. The framework generates documentation for you as you write the code. The documentation breaks down the framework feature by feature and then proceeds to explain each bit with an example. It’s possible to write a custom-built API for the application with your app with Mangum, but you can embed it with Amazon's API Gateway. It took me less than 10 minutes to create a simple CRUD with some simple endpoints.

## [Why Golang Is About To Take Over the Software Industry](https://betterprogramming.pub/why-golang-is-about-to-take-over-the-software-industry-fb48174a4cf)

Golang has been the most desired language to learn for three years in a row. Go is in the top ten of most loved languages to use and is the third most popular language on GitHub in terms of stars. Despite its flaws, there’s a lot to love about the language, Go is easy to pick up and start building. It's shallow learning curve is one of the biggest drivers for its rapid adoption. Money is another reason why developers are flocking to Go, all you need to do is follow the HackerRank.

## [Do You Know What It Really Means to Be Agile?](https://betterprogramming.pub/do-you-know-what-it-really-means-to-be-agile-38fd4c4b3c86?source=rss----d0b105d10f0a---4)

A group of 17 people met in Snowbird, Utah, to discuss the problems facing the software industry. They authored and co-signed a document that would change the way the world developed software. The Agile Manifesto is surprisingly short at only 68 words and consists of 4 values together with opening and closing statements. The manifesto says: We are uncovering better ways of developing software by doing it and helping others do it. We value individuals and interactions over processes and tools. We value working software over comprehensive documentation.

## [How To Write Manuals as a Developer](https://betterprogramming.pub/how-to-write-manuals-as-a-developer-83f481494ec8?source=rss----d0b105d10f0a---4)

Good user documentation should always focus on the user instead of just explaining the features of the product. An instructional chapter tells the user what to do step by step. Structure your instructional chapter in a numbered list. Structure your book in order to make it easier to follow. Structure a book of instructions in order the user will complete them. Structure an instructional chapter with a list of tasks per target group. Structure the book in the imperative form, i.e.i.e., i.u.

## [How to be a DevOps maestro: containers orchestration guide](https://itnext.io/how-to-be-a-devops-maestro-containers-orchestration-guide-b2cf884eaed1?source=rss----5b301f10ddcd---4)

The goal is to show what problems containers orchestration tries to solve. We will look at patterns and paradigms as well as tools that help address different areas of orchestration. Let’s assume that our application runs one container for each component, so 3 containers in total. Without orchestration doing so would mean setting up a connection to a remote docker host and issuing imperative commands like docker run etc. To enable smart provisioning we could take advantage of two patterns: Deployment should be fully automated.

## [Developers Are the Most Valuable Resource When Creating Software but Their Time Is Undervalued and…](https://itnext.io/developers-are-the-most-valuable-resource-when-creating-software-but-their-time-is-undervalued-and-85aab08d7af7?source=rss----5b301f10ddcd---4)

Developers are interrupted regularly, given tasks others could do and invited to endless meetings they don’t need to attend. Developers’ time is valued less because they are developers and not leaders or deciders. Managers who create nothing and whose job is to create the environment to enable effective development sacrifice developers. The real goal of most software projects is to deliver to deadlines and budget of the plan, but instead decisions focus on the meeting the plan not creating software. Developers are the slowest hiker; they are the bottleneck.

## [Improve the performance of Lambda applications with Amazon CodeGuru Profiler](https://aws.amazon.com/blogs/devops/improve-performance-of-lambda-applications-amazon-codeguru-profiler/)

Amazon CodeGuru Profiler helps developers improve their application speed by analyzing its runtime. The new automated onboarding process for AWS Lambda functions makes it even easier to use the tool with serverless applications built on Amazon Lambda. The tool generates recommendations to help developers understand the root cause of their slowest applications. The recommended recommendations can be found in the CodeGuru Profiler’s documentation and the code itself can be downloaded from GitHub. For more information, see the CodeGuru profiler's guide to creating Lambda applications.

## [The Sunk Cost Fallacy](https://thedecisionlab.com/biases/the-sunk-cost-fallacy/)

Richard Thaler first introduced the sunk cost fallacy, suggesting that paying for the right to use a good or service will increase the rate at which the good will be utilized. Hal Arkes and Catherine Blumer conducted several experiments to show that people were influenced by the fallacy in their decision-making. The researchers recorded how many shows each individual went to and found that individuals in the no-discount group went to an average of 4.11 shows, compared to 3.32 shows for the $2 discount group and 3.29 shows for those in the $7 discount group.

## [Conditionally setting your gitconfig](https://utf9k.net/blog/conditional-gitconfig/)

A lot of my custom work-related configuration has been deprecated (utilities for wrangling VPNs and proxies) and I basically don’t maintain anything more than what was already open sourced. With the advent of BeyondCorp-style zero trust, more internal services are thankfully available without a VPN required. This makes it easy to access tooling from your mobile device and other places but it can also mean the line between work and personal blurs a little bit. With conditional includes, you can dynamically switch instances of your.gitconfig on the fly.

## [Conductor: Why We Migrated from Kubernetes to Nomad](https://thenewstack.io/conductor-why-we-migrated-from-kubernetes-to-nomad/)

Conductor Technologies switched to HashiCorp Nomad for Kubernetes. Conductor is one of the largest cloud-based visual-effects rendering platforms. The Conductor rendering platform has been used to produce scenes for “Game of Thrones,” “Star Trek Beyond” and many other well-known movies, television shows and commercials. The key reasons we moved to Nomad include scalability, resource utilization, driver support and scheduling throughput. The company decided to adopt KuberNETes when the company started to transform its legacy system running on a cloud native platform.

## [Ultimate Cloud Pricing Comparison: AWS vs. Azure vs. Google Cloud in 2021](https://cast.ai/blog/ultimate-cloud-pricing-comparison-aws-vs-azure-vs-google-cloud-in-2021/)

AWS, Microsoft Azure, and Google Cloud offer flexible compute, storage, and networking combined with everything engineers love about the cloud: self-service, instant provisioning, and autoscaling. But cloud providers differ in key areas that have a massive impact on your cloud bill. How can you tell which cloud provider is the right one for your business? And which one isn’t going to break your wallet? Read this guide to learn which provider offers the most cost-effective services in 2021: Amazon, Microsoft, Google Cloud.