# DevOps / SRE - Top Links Last Week

## Week 39 Issue #46

## [Partitioning GitHub’s relational databases to handle scale](https://github.blog/2021-09-27-partitioning-githubs-relational-databases-scale/)

GitHub.com started out with a single database that housed a large portion of the data used by core GitHub features, like user profiles, repositories, issues, and pull requests. GitHub’s growth and resiliency requirements led to challenges. In 2019, GitHub set a plan in motion to improve our tooling and our ability to partition relational databases. The result, we see in 2021, is a 50% load reduction on database hosts housing the data that once was onmys1. This contributed significantly to reducing the number of database-related incidents.

## [Linus Torvalds on Community, Rust and Linux’s Longevity](https://thenewstack.io/linus-torvalds-on-community-rust-and-linuxs-longevity/)

Linux creator Linus Torvalds checked in with Dirk Hohndel at the Open Source Summit North America in Seattle. Hohndel, an early Linux contributor, gave a 30th-year-old birthday cake to celebrate Linux’s 30th anniversary. The theme of community seemed to keep coming up — notably about what that community has ultimately taught Linux creator has ultimately told him. Linux creator: "Every single feature ever since has been about things other people needed or wanted or were interested in"

---

## [Build Machine Images with Packer on Google Cloud Platform](https://blog.searce.com/build-machine-images-with-packer-on-google-cloud-platform-b43f77f1acd)

In September month blog, I’m taking everyone through Packer where we’ll be building Google Compute Engine Instance Custom Machine Image aka Golden Image. Packer is an open-source, lightweight, highly performant tool created by Hashicorp. With packer, you can use configuration management tools like chef, ansible, puppet etc to install software, libraries within your image. All software installation and configuration for a machine is done by Packer at the time of image building.

## [AWS ECS Blue/Green Deployment Setup Using Terraform](https://faun.pub/aws-ecs-blue-green-deployment-setup-using-terraform-b56bb4f656ea)

In this post, we’ll deploy a simple ECS application with Blue/Green deployment, using Terraform. We’re going to use the setup created in Gerd Koenig and Stephane Maarek’s awesome Udemy course, Amazon ECS & Fargate Master Class — Docker on AWS. We'll use the Dockerfile given at gkoenig/go-simplehttp to create an image and push it in to the registry. Terraform will create a private/public VPC with subnets, subnets and subnets.

## [Web3 Architecture and How It Compares to Traditional Web Apps](https://thenewstack.io/web3-architecture-and-how-it-compares-to-traditional-web-apps/)

The next wave of computing innovation will be driven by crypto, says venture capitalist Chris Dixon. Dixon: Web3 is “the internet owned by the builders and users, orchestrated with tokens” He positions Web3 as a kind of antidote to Web 2.0 (2005-2020), which became dominated by centralized platforms like Facebook, Google and Amazon. Dixon didn’t go into detail about what Web3 will look like from a web architecture perspective — other than saying it’ll all be built on blockchains.

## [FoundationDB: A distributed unbundled transactional key value store](https://www.micahlerner.com/2021/06/12/foundationdb-a-distributed-unbundled-transactional-key-value-store.html)

FoundationDB: A Distributed Unbundled Transactional Key Value Store, 2021, by Zhou, et al., Zhou. The paper discusses a distributed key value store that Apple, Snowflake, and VMWare (among others) run core services on at immense scale. Apple’s CloudKit is built on FoundationDB, in addition to other services (as described in their SIGMOD’21 announcement).

## [UI for Apache Kafka](https://github.com/provectus/kafka-ui)

UI for Apache Kafka is a free, open-source web UI to monitor and manage Apache Kafka clusters. Its lightweight dashboard makes it easy to track key metrics of your Kafka clusters - Brokers, Topics, Partitions, Production, and Consumption. The tool makes your data flows observable, helps find and troubleshoot issues faster and deliver optimal performance. You can run the tool locally or in the cloud using a pre-built Docker image or build it locally. The official Docker image for UI for UI is hosted here: hub.docker.com/r/provectuslabs/kafka-ui.

## [SpiceDB Is Open Source](https://authzed.com/blog/spicedb-is-open-source/)

Zanzibar is a distributed relationship-based authorization system that Google uses to manage permissions for most of their core cloud products (Docs, YouTube, Calendar, Maps, etc) It is an incredibly flexible, robust, and performant service, with 99.999% uptime and 20ms 99th %ile latency for permissions checks. SpiceDB is scalable, has support for globally replicated backends, and is available under the permissive Apache2 license. Unlike other implementations, SpiceDB also lets you compute inverse permissions, you can ask the question: “which resources can user access?

## [Cloudflare's Disruption](https://stratechery.com/2021/cloudflares-disruption/)

Cloudflare is launching a new cloud object storage service that promises to be cheaper than the established alternatives. The service will be called R2 — “one less than S3,” quipped CloudFlare CEO Matthew Prince in an interview with Protocol ahead of the announcement. R2 will be compatible with S3’s API, which makes it much easier to move applications already written for S3 in mind. The company will not charge data-egress fees for customers using R2, taking aim at the fees AWS charges developers to move data out of its widely popular S3 storage service.

## [Stupid Simple Service Mesh — What, When, Why](https://community.suse.com/posts/stupid-simple-service-mesh-what-when-why)

Service Mesh is an abstraction layer hiding away from business logic. Ingress Controller, API Gateway, Service Mesh and API Gateway work on different levels and solve different problems. In the first article, we will talk about the basic building blocks of a Service Mesh. We will implement a sample application to have a practical example of each theoretical concept. The next articles, based on this sample app, will touch more advanced topics, like Service Mesh in Kubernetes, and some more advanced Service Mesh implementations.

## [Migrating from App Engine to Google Kubernetes Engine](https://ipinfo.io/blog/app-engine-to-google-kubernetes-engine/)

IPinfo's data breadth and depth empower companies and initiatives of all sizes to implement various use cases. More than 40 billion requests are served every month for customers with various plans, from Free to Premium to Enterprise. Google AppEngine provides easy ways to configure and deploy new services, sparing teams from maintaining server infrastructure. Kubernetes is a popular open-source container orchestrator that works by spreading workloads across a number of virtualized computers (nodes) and managing the resources they need to run, to meet desired cluster size.

## [Wonk is a tool for combining a set of AWS policy files into smaller sets](https://github.com/aminohealth/wonk)

Wonk is a tool for combining a set of AWS policy files into smaller compiled policy sets. Amazon has helpfully created several hundred policies like AmazonRDSReadOnlyAccess and AmazonS3FullAccess that you can assign to users, groups, or roles. You can combine them into one big policy with a command line like: wonk combine -p MyPolicy AWSPolicy1.json and AWSPPolicy2.json. You could also use the wonk fetch command to fetch policy from Amazon instead of maintaining policy from the ARN.

## [Need of TLS](https://faun.pub/need-of-tls-cf3de74099d8)

Transport Layer Security (TLS) is a cryptographic protocol designed to provide communications security over a computer network. It runs in the application layer of the Internet and is composed of two layers: the TLS record and the TLS handshake protocols. The most common example for TLS can be seen while accessing web pages that are being served on HTTPS. Without any secure connection, all your inputs are sent as simple text which can be easily snooped by a hacker by just looking into network packets. With HTTPS, all the data is encrypted and can only be decrypted by the server.

## [Monitoring Production from A to Z, this is your CrashPlan](https://soufianebouchaa.medium.com/monitoring-your-production-from-a-to-z-this-is-your-crashplan-3e727d6ec04c)

Monitoring Production from A to Z, this is your CrashPlan. Observability, Monitoring, and Analysis combine to provide actionable intelligence. Monitoring with Monit is a utility for managing and monitoring processes, programs, files, directories, and filesystems on a Unix system. Monit rules: Load avg (15min) > vCPU x for 12 cycles, memory usage > 75% for 12. Memory usage: Memory usage, Disk usage > 80% for 90 days. Disk usage: 80%; vCPU usage: 90%; memory usage: 75%.

## [Bash vs. Python vs. JavaScript: Which Is Better for Automation?](https://betterprogramming.pub/bash-vs-python-vs-javascript-which-is-better-for-automation-92a277ef49e)

Programmers often write Shell scripts to boost productivity by automating tasks they do repetitively. Bash, Python, and JavaScript-based Shell scripts have various pros and cons. Python is a popular alternative for Bash to write environment setup, build, and release scripts. JavaScript is a great alternative to write automation scripts quickly, thanks to the Nodejs runtime. Bash performs very slow compared to other languages that we can use to write scripts. Python doesn’t support process execution as well as Bash.

## [Donald Knuth on Machine Learning and the Meaning of Life](https://thenewstack.io/donald-knuth-on-machine-learning-and-the-meaning-of-life/)

Donald Knuth appeared on the podcast of Lex Fridman, an AI researcher at the Massachusetts Institute of Technology. The 83-year-old programming legend appeared for a wide-ranging conversation. Knuth is a renowned computer scientist, Turing award winner, author of The Art of Computer Programming, creator of TeX. The two men discussed some overlooked milestones throughout Knuth’s career, including his early attraction to the open source movement. The interview was the second time the two men had met in the same way and revealed the personality and character behind Knuth.

## [Best Python Code Snippets to Save Time](https://betterprogramming.pub/3-how-to-python-code-snippets-for-data-analysts-6a9b850c254d)

Python code snippets are handy in data science projects. In the next three minutes, you will learn three code snippets using Python. You can simply copy and paste these code blocks into your project to keep it simple and boost analysis speed. In doing so, you can utilize your valuable time to interpret the analysis findings. Let’s get started using these code snippets: How To Convert Strings With Numerical Values to Numbers, How To Extract Day, Month, Year From Datetime Column in Pandas DataFrame and How To Visualize the Data Using Seaborn.

## [SOLID Principles — The ‘L’](https://faun.pub/solid-principles-the-l-6eec477e3cf7)

The Liskov Substitution Principle is the next principle in SOLID. It is named after Barbara Liskova who introduced this principle. The principle states that objects can be replaced with the objects of their subclasses without breaking the application. The LSP principle is broken by breaking the hierarchy of inheritance. We’ve seen about the Single Responsibility Principle (S) and Open Closed Principle (‘O’) Now it’s time we learn the next one, the LSP Principle.