  

# DevOps / SRE - Top Links Last Week

## Week 18 - Issue #77


20 links
  

## [Kubernetes Adopts Sigstore for Supply Chain Security](https://thenewstack.io/kubernetes-adopts-sigstore-for-supply-chain-security/)

With the release of Kubernetes 1.24 on May 4, for the first time, over five million developers can verify that the distributions they're using are what they claim to be. The Sigstore is a free software signing service. It improves software supply chain security by making it easy to sign release files, container images, and binaries cryptographically. Once signed, the signing record is kept in a tamper-proof public log. Sigstore will be free to use by all developers and software providers.

  

## [Post-Quantum Cryptography Set to Replace RSA, ECC](https://www.darkreading.com/tech-trends/post-quantum-cryptography-set-to-replace-rsa-aes-ecc)

Post-quantum computing will be available in the cloud by 2026, with the global market projected to grow from $472 million in 2021 to $1.765 billion. Criminals could use the new technology to defeat current encryption methods. The U.S. government has issued a brief to prepare for the latest technology. It says the sooner we get started, the sooner than we think, and the sooner it will be possible to use the new tools to break into the world of quantum computing systems.

  

## [Introducing Terramate — An Orchestrator and Code Generator for Terraform](https://medium.com/mineiros/introducing-terramate-an-orchestrator-and-code-generator-for-terraform-5e538c9ee055)

Mineiros Terramate is an Orchestrator and Code Generator for the open-source and Terraform community. The tool is designed to help users and customers implement workloads in public clouds with Infrastructure as Code (IaC). It's designed to reduce code duplication by sharing data between stacks and generating HCL (Hashicorp Configuration Language) code inside each stack. We are currently building a VEsode extension for supporting native HCL. We hope to use this tool to help our clients and customers.

  

  

## [Introducing ArcticDB: A Database for Observability](https://www.polarsignals.com/blog/posts/2022/05/04/introducing-arcticdb/)

ArcticDB is an embedded columnar database written in Go built on top of Apache Parquet and Apache Arrow. This blog post describes why we made it and what drove specific features and requirements. The data model of Parquet is highly inspired by Prometheus' data model. It produces a vast amount of data to store and query efficiently, but the data model needs a columnar. In addition, the database is designed to handle unbound cardinality data, which conflicts with the desire to buffer samples per unique series.

  

  

## [Docker Under Siege: Cybercriminals Compromise Honeypots to Ramp Up Attacks](https://www.darkreading.com/application-security/docker-becomes-target-tool-for-attackers)

Cybercriminals are ramping up their attacks on the Docker Engine, the software foundation of the container infrastructure used by many cloud-native companies. For example, cloud-management platform Uptycs has detected 10 to 20 attempts to compromise its Docker-based infrastructure every day. In addition, cybersecurity services firm CrowdStrike says hackers compromised its honeypots through the open Docker API and installed two malicious container images used to attack Russian and Belarusian sites. Compromised infrastructure has far-reaching consequences for organizations unwittingly participating in hostile activity against the Russian government, military, and civilian targets.

  

---

  

  

## [Create a CI pipeline for dockerized PHP Apps with Github and Gitlab](https://www.pascallandau.com/blog/ci-pipeline-docker-php-gitlab-github/)

In the seventh part of this tutorial series on developing PHP on Docker, we will set up a CI (Continuous Integration) pipeline to run code quality tools and tests on Github Actions and Gitlab Pipelines. This is particularly important when working in a team because the CI system acts as the final gatekeeper before features or bug fixes are merged into the main branch. The general process will look very similar to the one for local development: build the docker setup and run the CI pipeline locally. The necessary changes are explained after the concrete CI setup instructions.

  

## [Forrester: 96% of Businesses Have Had Cloud Security Probs](https://thenewstack.io/forrester-96-of-businesses-have-had-cloud-security-probs/)

Forrester Consulting surveyed 154 cloud security decision-makers for Amazon Web Services (AWS) and Sonrai Security, a public cloud security company. Of those, 98% of attacks involved identity-related security challenges. These problems aren't with people's identities but with all the systems and service identities used to run cloud applications. Over half, 56%, said identities not attached to individuals are out of control in the cloud. In addition, 82% said they expect to have invested in new identity access management (IAM) tools to address this issue by 2023.

  

## [Tailscale Authentication for Nginx](https://tailscale.com/blog/tailscale-auth-nginx/)

Tailscale authentication works with Tailscale for Grafana and even for Minecraft. You can use this to authenticate every request to your internal services and decorate requests to them with the correct HTTP headers. This works in the server block, meaning that you can set up separate authentication logic for services listening over Tailscale vs. services listening to the internet. You don't need internal tools to maintain your accounts with their passwords. People connect to Tailscale servers over the server and use Tailscale to connect to their servers.

  

## [Notion app review: Why (and how) I rely on this powerful productivity tool](https://www.zdnet.com/article/notion-app-review/)

Notion is a cloud-based application that's quite a challenge to describe. It has the feel of a wiki, the organizational capability of a database, and the note-taking and data archiving ability of a networked notepad. Once you understand it, it's easy to set up, but people sometimes have a bit of a challenge getting their arms around it. Notion comes with a free tier, but my wife and I have a paying account because it's essential to business and household management.

  

## [AWS is only as safe as the weakest credentials setup for your developers.](https://faun.pub/aws-is-only-as-safe-as-the-weakest-credentials-setup-for-your-developers-efc56b74182d)

AWS is only as safe as the weakest credentials setup for your developers. Anyone can find credentials in environment variables and shared configuration files. If you're not implementing an application and need access to AWS API from the command line, the AWS CLI is the way to go. If the login is not expired, the malicious person (or software) can steal critical AWS credentials. For example, an attacker could find AWS credentials in your application's codebases or your password manager.

  

## [Demystifying FedRAMP Container Scanning Requirements](https://itnext.io/demystifying-fedramp-container-scanning-requirements-dbf7c6848a8)

Containers make up a growing proportion of production workloads. The FedRAMP PMO issued its initial container security guidance in March 2021. Containers are just a mechanism for running an application. Still, scanning requirements must cover the physical infrastructure of the hosting environment, the host OS, the container runtime environment, and the containerized modules/applications themselves. CSPs are NOT precluded from adhering to host-based security guidelines and FIPS 140–2 (soon 140–3) encryption requirements.

  

## [Linux Server Monitoring Tools Overview](https://faun.pub/monitoring-tools-5b3852a4c7fd)

Server monitoring is essential for server success and is on par with server security and backup access. A system administrator typically runs system monitoring tools to find out the system's state at a time. Network monitoring tools, unlike system systems, allow you to monitor almost the entire server environment, from detecting the availability of a host for the ICMP protocol to tracking the status of a RAID array. Icinga and Nagios are written in C and Perl, and Oracle and Post DBMS can be used as source code.

  

## [Cloudflare heads effort to make JavaScript environments interoperable](https://techcrunch.com/2022/05/09/cloudflare-heads-effort-to-make-javascript-environments-interoperable/)

Cloudflare collaborates with Deno and Node.js to create standards that enable developers to write code between JavaScript and serverless apps. The effort will allow the transfer of apps between Deno, Node.JS, and Workers without a rewrite. The company also announced today that it's open-sourcing the Workers runtime under the Apache V2 license. The move is a way to increase the number of developers migrating to the serverless app platform, which charges for batches of server-side tasks.

  

## [Building Apps in Kubernetes? Think Security Everywhere](https://containerjournal.com/features/building-apps-in-kubernetes-think-security-everywhere/)

More than 6.5 million cloud-native developers and 5.6 million of them use Kubernetes. Traditional tools that rely on static IP address-based enforcement rules and waterfall development models aren't sufficient. Cybercrime continues to wreak havoc on organizations in every industry and sector. Cybercriminals are continually finding new ways to infiltrate systems and infrastructure, and, eventually, they'll find a vulnerability to exploit. Without proper security measures in place, organizations will be sitting ducks.

  

## [How to profile your PHP applications with Xdebug](https://www.vincentbroute.fr/blog/how-to-profile-your-php-applications-with-xdebug/)

The primary purpose of this kind of practice is to ease the finding of performance bottlenecks in your code. In the PHP ecosystem, several tools are available to perform code profiling. We will focus on Xdebug in this post, and I may release a second post about Blackfire later. The basic setup is available in this GitHub repository, and you are free to clone it to do your experiments. The PHP 8.1-fpm service is built from a custom image defined in a Dockerfile that we will see right after.

  

## [How to Prevent Kubernetes Configuration Errors](https://builtin.com/software-engineering-perspectives/how-to-prevent-kubernetes-configuration-errors)

The team spent the entire sleepless weekend digging into a major production failure. The problem rests with the power of the tool. Developers are still struggling their way through the Kubernetes patterns. As too much configuration goes into the system, it becomes easy for errors to creep in. The root cause of the problem is that developers don't understand these configurations well enough. We need to identify these APIs becoming more and remove them before they begin failing in production. The world is going through development across the globe, improving the system.

  

## [Traces vs. Snapshots: Print Statements and Debuggers](https://www.scott-a-s.com/traces-vs-snapshots/)

Some programmers consider using print statements instead of debuggers as inferior means of debugging. But the issue is not really "print statements" versus "bugs" It traces versus snapshots, and snapshots show all of the data from a moment in time. Traces provide a long-term view over a small set of data, while snapshots give a snapshot of the entire program state. When a program crashes or hangs, I reach for a debugger. In those instances, sometimes, I want to be able to inspect the entire system state.

  

## [Fclones – an efficient duplicate file finder and remover](https://github.com/pkolaczk/fclones)

clones is a command-line utility that identifies groups of identical files and removes the file copies you no longer need. It has been implemented in Rust with a strong focus on high performance on modern hardware. It employs several optimization techniques not present in many other programs. It adapts to the type of the hard drive, orders file operations by physical data placement on HDDs, scans directory trees in parallel, and uses prefix compression of paths to reduce memory consumption. It is available on various operating systems, but it works best on Linux.

  

## [5 Ways to Know You Need a DevOps Engineer at Your Startup](https://blog.runx.dev/5-ways-to-know-you-need-a-devops-engineer-at-your-startup-fea89d0b3ece)

Getting a DevOps Engineer can help your startup maximize efficiency and short product life cycles. It reduces operating costs and helps you in future scaling. We will discuss why your startup needs a Dev Ops Engineer and How it can help give you an advantage in the market. DevOps combines both the development and operations teams, making the application ready for deployment faster. It accelerates the ability for applications and services to be delivered quickly and efficiently without breaking the bank or increasing the number of developers on your team.

  

## [Tutorial: Building a Golang application Docker image](https://blog.devgenius.io/tutorial-building-a-golang-application-docker-image-78e36d437c70)

We should first go over the Golang project structure. The code content of the hello.go is necessary to review. The hello application is a simple example of a Golang application written in Golang. We use Docker to compile the code and build the Dockerfile.