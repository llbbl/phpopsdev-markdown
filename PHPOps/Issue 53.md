# DevOps / SRE - Top Links Last Week

Week 46 — Issue #53

  

  

## [Learning containers from the bottom up](https://iximiuz.com/en/posts/container-learning-path/)

Ivan Velichko started using containers back in 2015, and thought they were just lightweight virtual machines with a subsecond startup time. The "container is a VM" abstraction turned out to be quite leaky, so I had to start looking into the technology's internals to understand what containers really are. I tried tackling the domain from different angles, and over the years, I managed to come up with a learning path that finally worked out for me. Mastering containers is no simple task, so take your time, and don't skip the hands-on parts!

## [Fleet Management of Kubernetes Clusters at Scale — Rancher’s Fleet](https://itnext.io/fleet-management-of-kubernetes-clusters-at-scale-ranchers-fleet-de161cc52325)

Kubernetes Cluster Fleet Controller enables users to manage many clusters as easily as one. Rancher’s multi-cluster management already supports deploying and managing applications simultaneously on multiple clusters. Users can deploy bundles (collection of resources) across clusters. Bundles not only include application deployment manifests but anything that can be describes as a Kubernetes resource. The ability to import K3s. clusters into Rancher was added in v2.4.0, imported K3. clusters can be upgraded by editing the K3S cluster spec.

  

  

## [Improving the deployment experience of a ten-year old application](https://codeascraft.com/2021/06/15/improving-the-deployment-experience-of-a-ten-year-old-application/)

  

Etsy migrated its service infrastructure from self-managed data centers to cloud provisioning. The flexible scaling that comes with a cloud environment allowed us to completely reevaluate a somewhat cumbersome deployment process. Etsy’s Search team wrote a new custom tool to supplement our existing deployment infrastructure. The Canary (Lite) tool was a more scalable, more developer-friendly, and ultimately a more robust way to roll out changes to Search. It was inspired by the existing architectural pattern of canary rollouts.

  

  

## [Consul Service Mesh on Amazon ECS Now Generally Available](https://www.hashicorp.com/blog/consul-service-mesh-on-amazon-ecs-now-generally-available)

  

Consul service mesh on Amazon Elastic Container Service (ECS) is now general availability. Amazon ECS users can now run Consul in their production environments. Consul-native health checks can be layered on top of ECS checks to ensure that your service is not only running but that it is also ready to receive traffic. The GA release of Consul on ECS finely orchestrates the startup and shutdown of sidecar containers. This capability provides increased health granularity, similar to Kubernetes readiness probes.

  

## [SOLID Principles object oriented design](https://faun.pub/a-solid-guide-to-s-o-l-i-d-principles-77af3f3a52ba?source=rss----10d1a7495d39---4)

  

 SOLID design principles are long-standing principles used to manage most of the software design problems you encounter in your daily programming process. SOLID helps developers eliminate design smells and build the best designs for a set of features. The SOLID principles were first introduced by the famous Computer Scientist Robert C. Martin in his paper in 2000, its acronym was introduced later by Michael Feathers. The principles are used to help developers write code in the right way and maintain maintainability, readability or efficiency.

  

## [How To Effectively Scale Your Web Application](https://betterprogramming.pub/how-to-effectively-scale-your-web-application-7e3917bb98f?source=rss----d0b105d10f0a---4)

 Part 2 of a series of articles on how to scale your web applications. This article will focus on the basics of scaling a web application. Part 3 of the series will address the issue of scaling up and out. Part 4 will address how to use the resources of a single server to scale up. Part 5 will address this issue with the help of a load-balancing solution. Part 7 will cover the other side of the scaling process and how to manage the server. Part 10 will cover both sides of the scaling process.

  

## [PHP is worth learning and using](https://bulletproofphp.dev/yes-php-is-worth-using)

  

 PHP has gained some of the most significant features in the language since PHP 4 and 5. The spaceship operator is a little esoteric, but it's very useful for writing code. PHP 7 included a significantly expanded type system (scalar types and return types) and a built-in CSPRNG API. The release of PHP 7 in 2015 was the start of the "modern" PHP era, though, and this is true. PHP has become a significantly more ergonomic language over the last several years.

  

## [Introduction to Serverless Architecture](https://faun.pub/introduction-to-serverless-architecture-9e598d9f2862)

  

 Serverless is a way firms and developers outsource server management to cloud providers who manage the allocation and provision of servers. It’s an architectural style where application development is based on third-party services that manage server logic for businesses. Monoliths, Microservices & Serverless are the three most popular software architectures today. In this article, we are going to outline the different architectures, pros, shortcomings, and use cases for each of them. In the end, we will see how simple and straightforward it is to develop one with Fauna as the main database component.

  

## [An Introduction to SSL Security for Beginners](https://aws.plainenglish.io/ssl-security-introduction-encryption-sni-mitm-61f567a46f7)

  

 An Introduction to SSL Security for Beginners is a lecture about how SSL works and how to protect yourself against Man in the Middle attacks. Even if you know SSL, I will go over the basics, but trust me, there will be some new content for you. Don’t use public-facing HTTP, use HTTPS (meaning, use SSL/TLS certificates) Use a DNS that has DNSSEC to protect your domain name by configuring DNSSec for domain registration.

  

## [How To Deploy Your Kotlin Microservice on AWS Cloud — App Runner](https://betterprogramming.pub/how-to-deploy-your-kotlin-microservice-on-aws-cloud-app-runner-14f35185c6e7?source=rss----d0b105d10f0a---4)

  

 How To Deploy Your Kotlin Microservice on AWS Cloud — App Runner. This article continues a review of the different ways to use AWS stack to deploy your Java/Kotlin application to the cloud. App Runner is a fully managed service that makes it easy for developers to quickly deploy containerized web applications and APIs, at scale and with no prior infrastructure experience required. It's not free, you pay for storage, but it does include some free tier allowance, which might be enough for developer purposes.

  

## [IaC Cloud Misconfiguration Tools too Noisy without Context](https://thenewstack.io/iac-cloud-misconfiguration-tools-too-noisy-without-context/)

  

 Idan Plotnik is the co-founder and CEO of Apiiro. He is a serial entrepreneur and product strategist, with nearly 20 years of experience in cybersecurity. Plotnik: Cloud misconfigurations are one of the greatest risks when it comes to cloud computing. The risks of cloud infrastructure and the applications that run on it are inherently connected. An effective understanding of risk requires connecting the dots between the applications and their infrastructure, from design to code to cloud. It’s time to stop thinking about application security and infrastructure security separately.

  

## [Road Map to Chaos Engineering: Preparing for Major disruption](https://faun.pub/road-map-to-choas-engineering-preparing-for-major-disruption-e5dc01c73f2c)

  

 Chaos engineering is the discipline of experimenting on a software system in production in order to build confidence in the system’s capability to withstand turbulent and unexpected conditions (Principles of chaos engineering) Chaos engineering provides theories, best practices, and tools to get your company ready to face many types of disruption. I like to categorize disruptions into 4 categories and tackle them independently: network, infrastructure, application and infrastructure. The next task to be ready for a catastrophic event is to make your infrastructure configurable for a bit more configurable.

  

## [AWS App Runner and the Tale of Many Options](https://aws.plainenglish.io/aws-app-runner-and-the-tale-of-so-many-options-19978987b2de)

  

 AWS App Runner and the Tale of Many Options: Generic do almost anything services and opinionated services. Somewhat opinionated, still flexible services (think Lambda, ECS on EC2, Step Functions) Opinionated services (App Runner, Proton, Elasticache) On the opinionated end, you configure relatively little, but you don’t have to manage much. If you think to yourself, “But can I mount a volume into that container to...” then you probably need to look at Fargate/ECS/EKS.

  

## [New Linux malware preys on e-commerce websites in the run-up to Black Friday](https://blog.devgenius.io/new-linux-malware-preys-on-e-commerce-websites-in-the-run-up-to-black-friday-3af9038aa969)

  

 The malware, called “linux avp”, is built in Golang language and was found by Sansec experts after being contacted by a retailer who couldn’t seem to get spyware out of his business. The malware was discovered on the many US and EU-based servers, according to Sansec, though no other antivirus provider detected it as of the last check. The attackers use automated testing to scan e-commerce websites for lots of known flaws. It deploys a backdoor and downloads the “lion” server agent as soon as one is found.

  

## [How to Perform Incident Post-mortems: Identify Root Cause With “Five Whys”](https://www.buildingbettersoftware.com/blog/how-to-perform-incident-post-mortems-identify-root-cause-five-whys/?preview_id=2831&amp;preview_nonce=1863f02a11&amp;preview=true&amp;_thumbnail_id=2841)

  

 Kristian Erbou’s book, Build Better Software: How to Improve Digital Product Quality and Organizational Performance, takes a closer look at how to identify root cause and perform incident analysis by adopting the “Five Whys” The point is to keep asking until you reach the root cause of an incident. Only by gaining this knowledge will you be able to correct the problem that generated the whole incident. This is how you learn and truly improve incident management in your organization.

  

## [Safe schema updates - Near-zero downtime database deployments](https://octopus.com/blog/safe-schema-updates-7-near-zero-downtime-deployments)

  

 This blog post is part 7 of my safe Schema updates series. The Phoenix Project featured just such a disaster when a database update took longer than anticipated and critical systems could not be restored on time. Databases typically serve front-end applications/services, which means schema changes often need to be coordinated with changes to other systems. The more downtime is required for each deployment, the less frequently we’ll be able to do it. We need to ensure such deployments are executed small and often.

  

## [Five ways to step up software reliability](https://www.zdnet.com/article/five-ways-to-step-up-software-reliability/)

  

 Site reliability engineering (SRE) has become a must-have in an era when DevOps is a necessity. SREs connect operations and development, connecting IT operations with development. A recent study published by Constellation Research finds companies with high-functioning SRE organizations are one major incident away from a disaster. The study's author Andy Thurai says culture and mindset are everything to develop a SRE practice. Investing in the right tools is "key in enabling digitally efficient organizations to survive and thrive"

  

## [Slack moves to extend in-app workflow automation](https://www.computerworld.com/article/3640948/slack-moves-to-extend-in-app-workflow-automation.html)

  

 Slack is looking to make it easier for users to build workflows without needing developers or coding experience. The updates are aimed at extending existing capabilities that let developers customize apps and automate workflows within the app. Slack CEO Stewart Butterfield said automations can bridge the gap between systems of record and workers in business roles without requiring developers. The company said more than 400,000 users have created workflows since the introduction of the Workflow Builder, which was created after the acquisition of Missions, a startup specializing in this area.