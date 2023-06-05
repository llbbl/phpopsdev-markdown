# DevOps / SRE - Top Links Last Week

## Week 49 - Issue #56

  

  

## [HashiCorp IPO today](https://www.hashicorp.com/blog/a-new-chapter-for-hashicorp)

  

 Nine years ago, HashiCorp started with a blank piece of paper and sketched out the plan for a portfolio of tools aimed at solving the many different challenges involved in building and managing modern cloud infrastructure. The company is now over 1,650 employees, with nearly 2,400 customers, and is committed to delivering a world-class experience with our HashiCorp Cloud Platform. The problems will change, the products will evolve, but the culture we’ve built will be the foundation for years to come.

  

## [Improving GitHub code search](https://github.blog/2021-12-08-improving-github-code-search/)

  

 GitHub is rolling out a technology preview for substantial improvements to searching code on GitHub. We want to give you an early look at our efforts and get your feedback as we iterate on helping you explore and discover code. The search index covers more than five million of the most popular public repositories. We’ll be growing the index until it covers every repository you can access on GitHub. We'll experiment with scoring and ranking heuristics to see what works best, and we'll explore what APIs and integrations would be most impactful.

  

  

## [You Can't Buy Integration](https://martinfowler.com/articles/cant-buy-integration.html#UseAGeneralPurposeLanguageToManageTheInterfaceEvolution)

  

 Brandon Byars is Head of Technology for Thoughtworks North America, where he helps organizations navigate their digital transformation journeys. He argues that "buy" decision mechanics have caused us to exaggerate the value proposition of integration tools. Integration tools thrive in a world that views integration as primarily about connecting systems, but that digital organizations have reimagined integration to be primarily about putting clean interfaces in front of digital capabilities, emphasizing capabilities over systems. He lists some of the key principles behind a modern view of integration and claim they are best managed with a general purpose language.

  

## [Code2flow: Pretty good call graphs for dynamic languages](https://github.com/scottrogowski/code2flow)

  

 Code2flow generates call graphs for dynamic programming language. It is not possible to generate a perfect call graph for a dynamic language - even less so if that language is duck-typed. The basic algorithm is simple: Translate your source files into ASTs. Find all function definitions and find where those functions are called. Trim orphaned nodes and groups to get a good estimate of your project's structure. Use the code2flow tool to help you understand the structure of your projects in dynamic languages.

  

## [Karpenter vs Cluster Autoscaler](https://ips-indersingh.medium.com/karpenter-vs-cluster-autoscaler-dd877b91629b)

  

 Cluster Autoscaler is an industry-adopted, open-source, and vendor-neutral tool. Elastic Kubernetes Service, aka EKS, is Amazon’s implementation of Kubernetes in the AWS cloud. In EKS we don’t really “own” the control plane, we pay a very little fee (almost nothing compared to your EC2 nodes) and AWS manages it for you. A “managed” node group means AWS creates the auto-scaling group and manages it. A self-managed node group is totally managed by yourself.

  

## [Scala at scale at Databricks](https://databricks.com/blog/2021/12/03/scala-at-scale-at-databricks.html)

  

 With hundreds of developers and millions of lines of code, Databricks is one of the largest Scala shops around. We use Scala everywhere: in distributed big-data processing, backend services, and even some CLI tooling and script/glue code. The most popular language is Scala, followed by Jsonnet (for configuration management), Python (scripts, ML, PySpark) and Typescript (Web) We also have high-performance `C++` code, some Jenkins Groovy, Lua running inside Nginx, Go and other things.

  

## [Stack Graphs at Github](https://github.blog/2021-12-09-introducing-stack-graphs/)

  

 Precise code navigation is powered by stack graphs, a new open source framework we’ve created that lets you define the name binding rules for a programming language using a declarative, domain-specific language. With stack graphs we can generate code navigation data for a repository without requiring any configuration from the repository owner, and without tapping into a build process or other CI job. This post is a condensed version of a talk that I gave at Strange Loop in October 2021. Please check out the video of that talk if you’d like to learn even more!

  

## [Moving from Jenkins Pipelines to DevOps Pipelines](https://faun.pub/moving-from-jenkins-pipelines-to-devops-pipelines-3bbbedd387c)

  

 80% of most development teams have multiple Jenkins and are struggling to find a path forward to an improved model/tool/architecture. Jenkins was a great start towards Continuous Integration (CI) over the past decade and has been a workhorse for development teams. Jenkins helped you achieve a Jenkins Pipeline. With well over 100,000 instances of Jenkins, there was a large community of developers who you could depend on. You could even take your skills and drive a mile further down the road and get a job.

  

## [DevSecOps for Databases: Data Masking, Cloud Backup, WAF and More](https://devops.com/devsecops-for-databases-data-masking-cloud-backup-waf-and-more/)

  

 DevSecOps promotes a ‘security-as-code’ approach via the partnership between release engineers and security teams. The traditional separation between DevOps and security is wasteful and dangerous. The goal of database security is to protect:Database management systems, applications that access database information. The more access you provide to the information retained in a database, the more vulnerable the information is. An overly secure database is neither practical nor functional. A good way to achieve a balance between security and usability is to create meaningful security protocols.

  

## [Rotating etcd Encryption Key In Kubernetes](https://faun.pub/rotating-etcd-encryption-key-in-kubernetes-11f28a4a0d01)

  

 Kubernetes stores all its configuration data in etcd, which is not encrypted. By default, the default data stored in etcD is unencrypted. In this post, we’ll see how we can encrypt our etcd data using etcd cli-client cliapt. I have a 2 node kubeadm cluster, running on Ubuntu instances on Google Compute Engine. I'll be executing all the commands on the master node. I’ve created a secret named db-user-pass in default namespace, we are querying etcd.

  

## [From YAML Engineer to YAML Herder](https://thenewstack.io/from-yaml-engineer-to-yaml-herder/)

  

 A common trope in the Kubernetes world is that you are not a DevOps engineer, but rather a YAML engineer. Ole Lensmar Ole is CTO of Kubeshop and Chief Architect at SmartBear. He is the Founder of SoapUI and was the Chairman of the OpenAPI Initiative. He says we need to find a way to translate the advantage of the cloud native developer experience (DevX) into better operations experience (OpX) Monokle: Bringing OpX to the Cloud Native.

  

## [Full CI/CD with Docker + GitHub Actions + DigitalOcean (Droplets + Container Registry)](https://faun.pub/full-ci-cd-with-docker-github-actions-digitalocean-droplets-container-registry-db2938db8246)

  

 GitHub Actions will build a Docker image in its runner and push that image to Container Registry. GitHub Actions then will connect to Droplets and deploy the image from Container Registry to that Droplets. We have 2 jobs here: run build_and_push then after it finishes, run deploy. We need a token that you have generated to access the DigitalOcean API. HOST: your host (Droplets ipv4) PASSPHRASE: to encrypt the private key, generated when you create ssh keys for Droplets. SSHKEY: the content of ssh private key. ex raw content of.

  

  

## [Solving Common Concurrency Problems](https://blog.professorbeekums.com/2021/solving-concurrency-problems/)

  

 Concurrency is basically having multiple separate pieces of code to function at the same time. This is to provide you a smooth experience of seeing suggestions as you type “i” and your notes/bookmarks/emails that start with ‘i’ The problem is the execution of API requests take approximately 100 ms each, not exactly 100ms each. This means you’ll make the API requests in order, but the return order will be different every time you execute the requests. You get a performance improvement with concurrency.

  

## [Denial of Service(DOS) Attack](https://faun.pub/denial-of-service-dos-attack-db0db0e99433)

  

 In computing, a denial-of-service attack (DoS attack) is a cyber-attack in which the perpetrator seeks to make a machine or network resource unavailable to its intended users by disrupting services of a host connected to the Internet. DoS attacks typically exploit security vulnerabilities present in network, software and hardware design. In reality, most DoS flood attacks can also be turned into DDoS attacks. In a DDoS attack, the incoming traffic flooding the victim originates from many different sources.

  

## [Amazon Wants Everybody on Its Cloud](https://thenewstack.io/amazon-wants-everybody-on-its-cloud/)

  

 Amazon Web Services pulled out many not-so-huge rabbits out of its hat during Re:Invent annual user’s conference. Announcements included no-code/low-code platforms to build quick-and-easy machine learning models (ML) and support developers, 5G infrastructure, to allow users to create their own private 5G networks, necessitating only AWS cloud access. Analyst Torsten Volk said that Amazon has mostly filled in portfolio gaps with new offerings that looked more exciting on stage at the keynote than they ultimately turned out to be.

  

## [Containerize and Deploy a Node app on GCP Kubernetes](https://faun.pub/containerize-and-deploy-a-node-app-on-gcp-kubernetes-f4eb3af54a42?source=rss----10d1a7495d39---4)

  

 Create a new project on Google Cloud Console and activate Cloud Shell. Use the official lightweight Node.js 16 image to containerize the sample app. Run the GKE containerizing an app with Cloud Build using Cloud Build. In this quickstart, you will store your container in Artifact Registry and deploy it to your cluster from the registry. In the next section, you'll create the cluster for your container image deployment in the same region as your cluster. The GKE cluster is a managed virtual GKE Engine that operate as a single GKE Compute.

  

## [Accessing Pods Outside Of The Cluster In Kubernetes](https://faun.pub/accessing-pods-outside-of-the-cluster-in-kubernetes-400be73db519)

  

 Kubernetes is designed in such a way that pods are only accessible inside the cluster through their IPs. If you want to access pods from outside then you have to use services such as NodePort. NodePort is basically a service that connects pods to the Node IP. It maps the IP of the pod, deployment, etc to a port on the Node. It is basically an outlet for the pods, deployments, etc because it maps. The pod is essentially what holds the docker containers running applications.

  

## [How and why to use Git Submodules](https://techsparx.com/software-development/git/submodules.html)

  

 With Git Submodules, we configure one or more other repositories to check out as child repositories. Submodules lets you construct a directory hierarchy containing data (source files) from multiple locations. Each sub module can be used by multiple parent projects. Each parent project has control over which release of each subsidiary project is being used, and each parent project can push changes to the subsidiary projects. Using Git submodules adds complexity, so it had better be worth your time. Make sure you understand what you need to use Git sub modules to make sure they're the correct solution for your problem.

  

## [The Projects and People that Shaped Open Source in 2021](https://thenewstack.io/the-projects-and-people-that-shaped-open-source-in-2021/)

  

 These are the top stories of the open source people and projects that shaped this year. According to Red Hat’s 2021 State of Enterprise Open Source Report, 90% of IT leaders are using enterprise open source. With most businesses using some form of open source, there is still varying maturity along the spectrum from consuming to producing and embracing open source. This year's top open source stories include Linus Torvalds on why open source solutions solve the biggest problems in the open software world.

  

## [How Do I Choose? API Gateway vs. Ingress Controller vs. Service Mesh](https://www.nginx.com/blog/how-do-i-choose-api-gateway-vs-ingress-controller-vs-service-mesh/)

  

 API gateways, Ingress controllers, service meshes are each a type of proxy, designed to get traffic into and around your environments. In this blog we tackle how these tools differ and which to use for Kubernetes‑specific API gateway use cases. An API gateway routes API requests from a client to the appropriate services. An Ingress controller (or service mesh) is a specialized Layer 4 and Layer 7 proxy that gets traffic into the services, and back out again (referred to as ingress‑egress or north‑south traffic)

  

## [How To Containerize And Scale Your Application For Unexpected Traffic Or Model Training](https://betterprogramming.pub/how-to-scale-your-application-for-unexpected-traffic-or-model-training-a8b0a0c44d80)

  

 We will be using containerization technology and docker software tool. The first step is to develop a web server listening at port 3000 and append a logline with the hostname.  Create a new directory at your home directory for simplicity sake. The same can be achieved with Python Django. We intentionally do not use python in order to learn how to Containerize an application on our own, since that’s what matters.