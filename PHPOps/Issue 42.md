# DevOps / SRE - Top Links Last Week

## Week 35 Issue #42


## [Docker is Updating and Extending Our Product Subscriptions](https://www.docker.com/blog/updating-product-subscriptions/)

Docker is used by millions of developers to build, share, and run any app, anywhere. 55% of professional developers use Docker every day at work. Rapid global growth in developers – to an estimated 45 million by 2030 – pushes us to scale sustainably. New Docker Business subscription enables organization-wide management and security for businesses that use Docker for software development at scale. Docker Desktop remains free for small businesses (fewer than 250 employees AND less than $10 million in annual revenue), personal use, education, and non-commercial open source projects.

## [Kubescape – tool for testing if Kubernetes is deployed securely](https://github.com/armosec/kubescape)

Kubescape is the first tool for testing if Kubernetes is deployed securely. Kubescape can be used to test clusters or scan single YAML files and integrate it to your processes. It is based on [OPA engine](https://github.com/open-policy-agent/opa). The development (and the release process) is done with Go 1.16.

---

## [Docker Desktop no longer free for large companies](https://www.theregister.com/2021/08/31/docker_desktop_no_longer_free/)

Docker will restrict use of the free version of its Docker Desktop utility to individuals or small businesses. The company has renamed its Free plan to "Personal" and now requires that businesses with 250 or more employees with higher than $10m in annual revenue must use a paid subscription. A new $21/month Business subscription adds features including centralized management, single sign-on, and enhanced security. There are no changes to the command-line Docker Engine. Most Docker components are available for Windows, Mac and Linux, and despite the fact that most Docker containers run on Linux, Desktop is only available on Windows and Mac.

## [A curated list of actions to use on GitHub](https://github.com/sdras/awesome-actions)

With GitHub Actions you can automate your workflow from idea to production. Actions are triggered by GitHub platform events directly in a repo and run on-demand workflows either on Linux, Windows or macOS virtual machines or inside a container in response. A curated list of awesome things related to GitHub Actions includes a list of resources for creating your own workflows using GitHub Actions. The GitHub Toolkit is the GitHub ToolKit for developing GitHub Actions. The GitHub Actions toolkit is available for developers to use in their workflows.

## [Operations is not Developer IT](https://matduggan.com/operations-is-not-developer-it/)

Some developers have come to see Operations as their IT department. Operations is learned on the job, and there was a culture of training and patience with junior members of the team. Operations teams had to sit down and write something about the software, requiring someone at least vaguely familiar with how the software worked. The number of times I have sent a full-time Node developer a link to the Node.js docs is too high. It's not acceptable behavior among Operations teams. We treat software mostly like a black box, with instructions on how to deploy it and what to do if it wasn't working.

## [Automating quality checks for Kubernetes YAMLs](https://dev.to/wkrzywiec/automating-quality-checks-for-kubernetes-yamls-398)

In this blog post, I'll show how to create a simple, automated quality check of your K8s object definitions using Datree and Google Kubernetes Engine and Github Actions. The workflow will have two stages: analysis of missing configurations, and quality check, and testing an example application in a real cluster (GKE) Datree analysis will stop the workflow if it finds any problems. It's very important to have a safety net like this so you can feel confident that even if you make a mistake, or aren’t aware of best practices, an assistant will keep you on track.

## [How I re–over-engineered my home network for privacy and security](https://ben.balter.com/2021/09/01/how-i-re-over-engineered-my-home-network/)

A little less than a year ago, I wrote a now-popular post about how I over-engineered my home network for privacy and security. After having relied on, optimized, and upgraded what I described in that post for about eighteen months now, I’ve decided to build on what’s there by revisiting re-over-engineering how I setup, maintain, and manage the software and services that power and protected the network. The less I can trust to me “getting it right”, the better. I wanted to get out of the bespoke.sysadmin business, provisioning and then immediately walking away from “set it and forget it” systems.

## [Docker Says Some Users Must Pay: But Can It Make Money?](https://thenewstack.io/docker-says-some-users-must-pay-but-can-it-make-money/)

Docker’s decision to start charging corporate customers as part of a business revamp has raised eyebrows as the pioneer container orchestration provider struggles on its road to profit. Despite its popularity, Docker containers are required to run numerous applications on Kubernetes and other environments relied on by millions, including this writer. Analyst: "The Docker revenue model relies on these developers convincing their executives that they really need to use their own commercial DevOps toolchain when their company is already running a Kubernetes management platform.”

## [SUSE releases its first version of Rancher: Rancher 2.6](https://www.zdnet.com/article/suse-releases-its-first-version-of-rancher-rancher-2-6/)

Rancher 2.6 is the latest release of SUSE's Kubernetes management platform. The new release comes with major updates across all its supported clouds and platforms. New features include a redesigned platform experience with an improved user interface. SUSE also added integration with SUSE Linux Enterprise Base Container Images (SLE BCI) These include SLES 15 SP3 and SLES 12 SP5. The combination of SLES and Ranchers is a powerful one and with its ability to run across multiple cloud platforms, I can see it becoming a popular enterprise cloud stack.

## [An Overview of Docker Desktop Alternatives](https://matt-rickard.com/docker-desktop-alternatives/)

Minikube is the only tool that is a drop-in replacement for Docker Desktop. The other tools require a Linux distribution, which makes them a non-starter on Macs or Windows. Running any of these tools in a VM misses the point – you don't want to be managing the Kubernetes lifecycle and a virtual machine lifecycle. You have to choose between friction with VM networking (minikube) or friction with two layers of container networking. You can use podman as an alternative to Docker, but get mentioned as a replacement for the Docker component (not an alternative)

## [Cisco, Citrix, and Fortinet Among New Verified Terraform Providers](https://www.hashicorp.com/blog/cisco-citrix-fortinet-among-new-verified-terraform-providers)

This month, the total number of verified Terraform providers has surpassed 150. Verified providers have achieved a higher level of maturity and confidence by going through the partner onboarding process. This fast growth is good news for everyone hoping to use infrastructure as code to deploy and manage infrastructure across products in multi-cloud environments. Backblaze Cloud Storage store more than an exabyte of data for customers including American Public Television, PagerDuty, and Patagonia. 3DS Outscale focuses on trustworthiness in its operations as a multi-region IaaS cloud provider.

## [Amazon ECS vs EKS : The best AWS Container Service](https://faun.pub/amazon-ecs-vs-eks-the-best-aws-container-service-13cab094c541)

Amazon ECS is a container management service that is highly scalable and fast. Amazon also provides support for Kubernetes using its managed service EKS. EKS provides scalability and security to the applications. The difference between ECS and EKS is one of the most important points to understand when considering the difference between the two services and when to choose one. Amazon EKS allows up to a maximum 120 tasks per instance whereas ECS accommodates up to 750 pods per instance.

## [Computer Networking: What You Need To Know! Part 1](https://faun.pub/computer-networking-what-you-need-to-know-part-1-9e44d4b3dc40)

There are terms and concepts you need to have a proper understanding of when it comes to dealing with Computer Networks. Computer Networks are of different ranges and all depend on the purpose each one may be needed for. A VPN (Virtual Private Network) is a secure connection between two nodes or simply two computers. A Network Protocol can simply be defined as a set of rules that govern communication, transmission, and sharing of data between computers in a network. The range of reach of a Computer Network set up in your home is different from the range of access to a whole city.

## [Observability: The 5-Year Retrospective](https://thenewstack.io/observability-the-5-year-retrospective/)

"Observability" is starting to be used to mean anything to anyone, just a label you slap on the side of your product to fit in with the zeitgeist. The pain and suffering that people endure every day because they can’t understand their own damn systems is too real. We need specific, meaningful technical terms to help users navigate the future and find their way to those solutions. O'Reilly: Observability saw the greatest growth in the past year, while monitoring is only up 9%.

## [Web Apps and the White House Executive Order on Cybersecurity](https://thenewstack.io/web-apps-and-the-white-house-executive-order-on-cybersecurity/)

Mark Ralls is President and Chief Operating Officer of Invicti. He says 90% of data breaches originated in a web app in 2020. Ralls: Web apps represent a massive attack surface and are one of the dominant attack vectors for hackers. He asks why web apps are not getting the security hardening they need? Ralls says organizations must cover both the left and the right to adequately protect themselves from attacks on their web apps. He also says modern dynamic application security testing (DAST) is two examples of solutions that can bring security testing to production.

## [ZeroTier – Global Area Networking](https://github.com/zerotier/ZeroTierOne)

ZeroTier is a smart programmable Ethernet switch for planet Earth. It allows all networked devices, VMs, containers, and applications to communicate as if they all reside in the same physical data center or cloud region. ZeroTier traffic is encrypted end-to-end using secret keys that only you control. Apps for Android and iOS are available for free in the Google Play and Apple app stores. The goals and design principles of ZeroTier are inspired by among other things the original Google BeyondCorp paper and the Jericho Forum.

## [Best practices for developing on Kubernetes](https://itnext.io/best-practices-for-developing-on-kubernetes-8fbdbba12538)

In this blog, we look at what containers orchestration means and how we can improve our day-to-day operational activities with cloud-native patterns and tools. Today we are going to “shift left” and see how to empower developers to develop Cloud-native software from the start. We will examine the development, as well as building and shipping software, where container orchestration is the key to success. The development process would look something like this:Developing with Kubernetes in mind means developing Cloud Native applications.

## [Chaos Engineering with the AWS Fault Injection Service (FIS)](https://aws.plainenglish.io/chaos-engineering-with-the-aws-fault-injection-service-fis-a-terraform-project-83b77d2e8914)

Chaos Engineering with the AWS Fault Injection Service (FIS) deploys an application load balancer addressing an auto scaling group of EC2 instances. Terraform does not yet support the FIS service, so we deploy a CloudFormation template with FIS settings. The code gets the instance ID by querying the instance metadata and returning this in the default index. Then launch this index.html with the busybox httpd server. The use of the service is limited to the workstation IP from where the code is executed.

## [GitHub Copilot Generated Insecure Code in 40% of Circumstances During Experiment](https://www.theinsaneapp.com/2021/09/github-copilot-generated-40-percent-insecure-code.html)

A new academic paper examines the security of GitHub Copilot's code. The study found that 40 percent of the programs generated in 89 different code-completion scenarios were found to be vulnerable. Copilot is trained over open-source code available on GitHub. The Free Software Foundation called for more papers to be published to address philosophical and legal issues around the project. The project stirred up controversy along various aspects, with hints surrounding the quality of code, legal and ethical concerns, and the potential to advance security vulnerabilities.

## [The Complete GraphQL Security Guide](https://wundergraph.com/blog/the_complete_graphql_security_guide_fixing_the_13_most_common_graphql_vulnerabilities_to_make_your_api_production_ready)

The complete GraphQL Security Guide: Fixing the 13 most common GraphQL Vulnerabilities to make your API production ready. It's 2021, GraphQL is on its rise to become a big player in the API Ecosystem. One of the solutions will require some radical change in the way we're thinking about GraphQL, but it will come with a lot of benefits that go way beyond just security. You should not trust any GraphQL library without heavy testing, including fuzzing. Normalizing GraphQL Queries can potentially leak fields.

## [CacheLib, Facebook’s open source caching engine for web-scale services](https://engineering.fb.com/2021/09/02/open-source/cachelib/)

Facebook is releasing CacheLib, a pluggable in-process caching engine to build and scale high-performance services collaboratively. Facebook is working with Twitter on integrating CacheLib into Pelikanio to enable SSDs for caching objects within the Twitter infrastructure. Facebook says CacheLib and CacheBench have the potential to become an industry standard for caching innovations and benchmarking. We are open-sourcing this work in an effort to make building the future of caching a more collaborative and open space for sharing across the entire industry.

## [Terraform For Beginners](https://itnext.io/terraform-for-beginners-dd8701c1ebdd)

Terraform is an application that converts configuration files known as HCL (Hashicorp Configuration Language) into real world infrastructure. This concept of taking configuration files and converting them into real resources is known as IaC (Infrastructure as Code) and is the new hotness in the world of Software Engineering. The concept is not a new concept, in fact it has been around in different guises since the very early days of Cloud Platforms (AWS had CloudFormation and Azure had ARM Templates)

## [Database Change Management Tool: Liquibase with Snowflake Overview](https://faun.pub/database-change-management-tool-liquibase-with-snowflake-overview-90c65bdc589e)

Liquibase is an open-source database migration tool that provides organizations with an effortless way to track, version, and deploy database schemas changes. It is different from other database migration tools because the software understands the changes you are making based on how you specify those changes. The software is flexible enough to work with just about every tool in whatever variation that tool is provided. It also helps reuse the existing skill set of the team as it has all famous language support for Schema Change files.

## [A Quick Introduction to Istio](https://levelup.gitconnected.com/a-quick-introduction-to-istio-ffb486221f1f)

Service mesh is a way to control how different microservices will interact with one another. Istio is an open-source project co-founded by Google, IBM, and Lyft. It uses proxies to extract communication rules out of microservice. The data plane intercepts all packets on the network and is responsible for authentication, authorization, generation of observable signals, health checking, load balancing, and routing. The control plane manages and secures the data plane. The pilot is primarily responsible for traffic management, and also handles service discovery.

## [Secure Your Kubernetes Cluster With AppArmor](https://betterprogramming.pub/secure-your-kubernetes-cluster-with-apparmor-e4bb9fef37e1)

AppArmor is a standard Linux Security Module implementation that allows you to enforce fine-grained control over your Linux system. It helps restrict your programs to only the limited set of resources, files, and other permissions it needs to work. It enables you to implement the Principle of Least Privilege within your container applications. However, while AppArmor helps tremendously in reducing the attack surface, it has its limitations. Therefore, it should not be taken as a silver bullet and other ways to secure the containers should be considered.