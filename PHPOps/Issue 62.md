# DevOps / SRE - Top Links Last Week

## Week 3 - Issue #62

  

  

## [Solving Open Source Supply Chain Security for the PHP Ecosystem](https://paragonie.com/blog/2022/01/solving-open-source-supply-chain-security-for-php-ecosystem)

Gossamer is a proposal for securing the software supply chain for the PHP ecosystem. Code-signing and third-party attestations published to a transparency log prevent a partial censorship attack (i.e., allow updates to go through, but not crucial revocations or attestations). This approach largely mitigates the risk of extralegal government action. Developers remain in control of their signing keys and are mapped to a set of public keys. All changes show up in the transparency log.  

  

## [How to validate Kubernetes YAML files](https://itnext.io/how-to-validate-kubernetes-yaml-files-9a17b9a30f08)

This article is intended as a guide for validating Kubernetes YAML files. We will look at various tools and methods that shift the starting point of a validation process to a development workflow. The holy grail of shifting validation left is to make illegal states irrepresentable. The validation can be done using the right tools with a non-statically typed language, but it isn't easy to do without the right tools. These tools are more suited as a platform than a tool that fits neatly in a standard developer workflow.

  

## [Dude where's my coldstart?](https://www.openfaas.com/blog/what-serverless-coldstart/)

Alex takes a look at the architecture of OpenFaaS and why you can say goodbye to cold-starts. This article will cover why containers are slow to start - particularly on Kubernetes. Then take you through our research and development that ultimately led to not needing cold-starts or not needing to see them in the OpenFaaS. Finally, there are plenty of links and resources if you want to go deeper and a FAQ towards the end.

  

## [Deploying Argo CD and Sealed Secrets with Helm](https://faun.pub/deploying-argo-cd-and-sealed-secrets-with-helm-8de12f53051b)

The documentation for ArgoCD suggests creating a namespace for deploying services and applications. You need to provide a public and a private key for the target repository to do that. Without giving a private key for a git repository, ArgoCD won't be able to retrieve deployment manifests for your application. Repository details, such as the private key, are safely stored in the secrets tool.

  

## [How to tackle Kubernetes observability challenges with Pixie](https://piotrzan.medium.com/how-to-tackle-kubernetes-observability-challenges-with-pixie-4c6414ca913)

Decentralized systems observability has always been challenging. The more abstraction a decentralized system has, the more difficult it is to reason about it, debug and troubleshoot. The main reason that makes Kubernetes observability so tricky is the volatile nature of workloads and resources. Pixie uses eBPF (Extended Barkley Packet Filter) to capture telemetry data without the need for manual instrumentation automatically. Pixie is an open-source observability tool for Kubernetes applications.

  

## [We’ve Come a Long Way Since Healthcare.gov](https://thenewstack.io/weve-come-a-long-way-since-healthcare-gov/)

This week, the Biden administration made-at-home COVID tests available to the public through a couple of websites that allow each address to order four tests delivered by the United States Postal Service. For the most part, the entire affair appears to have been a success, at least when you compare it to the launch of Healthcare.gov eight years ago. But, of course, if you define success as "being able to order a COVID test from the same address as someone else in a multitenant complex," then, well…. well…. that's a cartoonish design flaw in this rollout.

  

## [Introduction to AWS Websockets](https://www.readysetcloud.io/blog/allen.helton/intro-to-aws-websockets/)

A WebSocket is a direct line of communication between a client and a server. It is two-way communication between the mobile app (or website) and the Twitter servers. One example is when a user wants to get updates when an entity they are working on has been modified. Postman is an application designed for everything around APIs, including connecting to WebSockets. To test your WebSocket, you can grab the WebsocketUri output from your SAM deployment and link to it in Postman.

  

## [Solving Four Kubernetes Networking Challenges](https://betterprogramming.pub/solving-four-kubernetes-networking-challenges-a5fb034db8bd)

Kubernetes networking is more complex than it seems. Deploying multiple clouds, maintaining various environments, and ensuring reliable and scalable network policies are significant challenges. Multi-Cloud systems are often divided into various environments, with different parts deployed to other cloud platforms. These heterogeneous environments need to communicate with one another. The volatility and elastic nature of the cloud require constant monitoring and rerouting in case of failures. With ephemeral Pods and continual dispatched resources, reliable service-to-service communication is not a given. We'll look at how to tackle those challenges.

  

## [The Definitive Guide To Building a New Service](https://betterprogramming.pub/the-definitive-guide-to-building-a-new-service-452867aac523)

The C4 model is a technique to model the architecture of a new system. It allows you to get a view of the architecture at different levels. It starts with the Context, which shows the new system, how users interact with it, and how it interacts with other systems in your enterprise. The next level is the Container level, which details the main components within each Container, such as controllers and key namespaces. One final level, code, goes very deep into individual classes, but this is usually an overkill and a nightmare to try and maintain.

  

## [WebAssembly: The New Kubernetes?](https://wingolog.org/archives/2021/12/13/webassembly-the-new-kubernetes)

Kubernetes promises a software virtualization substrate that allows you to solve several problems simultaneously. The "cloud of containers" architecture divides up building server-side applications. It cuts with the grain of Conway's law: the software looks like the org chart. WebAssembly gives you a sound abstraction barrier and (can provide) high-security isolation. Finally, it's even better in some ways because WebAssembly provides "allowlist" security -- it has no capabilities to start with, requiring that the "host" that runs the WebAssembly explicitly delegate some of its capabilities.

  

## [How to Keep Your Playbooks Secure With Ansible Vault](https://www.cloudbees.com/blog/how-to-keep-your-playbooks-secure-with-ansible-vault)

Ansible Vault provides a simple way of managing secrets with Ansible. It's easy to get started using an Ansible tool to create a Vault file from scratch. The password file is a file that contains the plain text of the Vault file, which can be used to edit in place or to store the password in your playbook. It's not sensible not to have plain text files in your development environment, especially when you have long and multi-line values. It gets more challenging to manage the Vault files if you have multiple files and if they are scattered.

  

## [Palo Alto Networks on the State of Cloud Native Security](https://thenewstack.io/palo-alto-networks-on-the-state-of-cloud-native-security/)

Palo Alto Networks has released its latest State of Cloud-Native Security Report. 69% of organizations host over half of their workloads in the cloud, up from 31% in 2020. Organizations expanded their use of the Clouds during the Covid-19 pandemic by more than 25% overall. Organizations also spent more on Platform-as-a-Service (PaaS) and Serverless. Despite this remarkable growth, companies are paying less on average. Those who did the best with their cloud moves tended to have the most robust security posture.

  

## [A Complete CDK for a Module-Federated Micro-Frontends AWS Architecture](https://aws.plainenglish.io/a-complete-cdk-for-a-module-federated-micro-frontends-aws-architecture-ce17e93f0d1c)

The complete CDK stack provides a mono-repo micro-frontend architecture on AWS. It is the most extensive follow-up to the "A complete AWS architecture for Module-federated MicroFrontends" article. By the end of this article, you will: Understand how to programmatically, Adapt the stack to your needs, and deploy it to your AWS account. It consists of 3 constructs that reflect three sub-architectures, in the following order: Foundational construct, to provide the building bucket and edge components for hosting. Finally, a MonoRepo triggers construct to receive GitHub pushes and trigger CodePipelines via Lambda@Edge.

  

## [Easy Node-Discovery with Consul](https://blog.devgenius.io/easy-node-discovery-with-consul-8b6f3c4b5116)

This article is only about an easy installation for Consul. We will skip setups for firewalls and more (but please still use it). Instead, we will use a simple Docker setup with the official Docker images. The encryption token is the password to access the data center. The UI, if used, is available with port 8500. We map port 80 to it to have a pleasant HTTP experience. Still, feel free to use HTTPS, NGINX proxies, or anything you need.

  

## [Load testing at scale and lessons learned](https://www.kevinlondon.com/2022/01/14/load-testing-guide)

We run load tests to ensure the service is ready for customer traffic at scale. Load testing helps us reduce ambiguity and avoid guessing if the service will meet our and our customers' expectations. We can then make assumptions about the high traffic event and model traffic on a per-service and even per-API basis. For example, we'll consider load testing a new service we're adding to a pre-existing food ordering website. This service provides menus to customers and allows them to browse items they can order from each restaurant.

  

## [How to Run Chaos Experiments on Your Physical Machine](https://faun.pub/how-to-run-chaos-experiments-on-your-physical-machine-e309bd1a848c)

Chaos Mesh is a cloud-native Chaos Engineering platform that orchestrates chaos in Kubernetes environments. With Chaos Mesh, you can simulate a variety of failures and use Chaos Dashboard, a web UI, to manage chaos experiments directly. At TiDB Hackathon 2020, we refactored "chaosd" to make it more than a command-line tool. You can simulate faults injected on physical machines at different levels, including process faults, network faults, Java Virtual Machine (JVM) application faults, stress scenarios, disk faults, and host faults.

  

## [Starting with microservices](https://arnoldgalovics.com/truth-about-microservices/)

This time I'll share my experience on the truth about microservices when starting a project from scratch. The promises are lovely, but often they are far from reality. The truth is, every environment/organization/project is different. You might make excellent use of microservices, and you might succeed in starting with microservices. But you can achieve an easily understandable system with a monolith too. How? Modularization. You structure the code in a way where you define similar boundaries you'd do for microservices, but instead of running those "services/ modules as different apps, they are part of the monolith.

  

## [Simplest way to add CI to iOS project](https://blog.devgenius.io/simplest-way-to-add-ci-to-ios-project-36f345ae3cb2)

CI stands for Continuous Integration and is the practice of safely and reliably merging all developers' work into a single branch (aka develop or master branch). CI is proven to increase developer experience and productivity. It will cost you nothing because it is free for Github public projects. You can easily set up your CI for your project using Github Actions. The easiest way to add CI to your iOS project is to use GitHub Actions. First, you need to create and push a new ci.yml file at the repository's root.

  

## [Understanding Firestore performance with Key Visualizer](https://cloud.google.com/blog/products/databases/understanding-firestore-performance-with-key-visualizer/)

Key Visualizer is an interactive performance monitoring tool for Firestore. Firestore is a serverless, scalable, No.SQL document database. It is ideal for fast and flexible web and mobile application development. The tool generates visual reports based on Firestore documents accessed over time that will help you understand and optimize the access patterns of your database, as well as troubleshoot performance issues. You can use key Visualizer with production databases, but it's best to identify performance issues before rolling out changes.

  

## [An Introduction to Terragrunt](https://blog.devgenius.io/an-introduction-to-terragrunt-dfe9921f5e48)

This Terraform tool keeps the backend configuration DRY. Terragrunt is defined on the root level, and the child modules inherit the configuration using the "terragrunt.hcl" file. Use the text editor of your choice, either vim or nano, to enter your secret and access keys inside. Export the keys and secret keys as environment variables to your machine.

  

## [Building with Open Policy Agent (OPA) for Better Policy as Code](https://dzone.com/articles/building-with-open-policy-agent-opa-for-better-pol)

Open Policy Agent (OPA) is an open-source project hosted by the CNCF (Cloud Native Computing Foundation) built for cloud-native systems. It combines an easy-to-learn, dev-readable language (Rego), along with a policy model and API, to provide a universal framework for applying policy across your stacks. OPA is essentially a flexible engine that not only enables you to enumerate and write policies but also has powerful search capabilities that don't require the learning of any new custom syntax.

  

## [HowTo: Deploy Serverless Function on Google Cloud using Terraform](https://faun.pub/howto-deploy-serverless-function-on-google-cloud-using-terraform-cbbb263571c1)

Terraform is an infrastructure as code solutions for various purposes. You can use it for Google Cloud as Azure, AWS, and many other cloud providers. It enables you to manage almost all resources in one tool/ language. Create a Source Repository and a Cloud Functions function to build from the source in the repository. Use Terraform first to create a source code repository and then trigger the build. Google's Cloud Functions service will use the function.

  

## [System Design Concepts Explained for Grandma](https://betterprogramming.pub/system-design-concepts-explained-for-grandma-313da71cae49)

The internet, in a nutshell, is a set of rules for a browser to send out a request. First, you need to fill up a designated form and submit it via the mailbox to order cookies. Then, to send a request to a server, your browser needs to specify the server's IP address — the IP address. DNS stores all the corresponding IP addresses and port numbers of websites. DNS is like a phone book, storing all the IP addresses, port numbers, and IP addresses.

  

## [My self-hosting infrastructure, fully automated](https://github.com/khuedoan/homelab)

Infrastructure-as-Code aims to automate provisioning, operating, and to update self-hosted services in Khue's Homelab. It can be used as a highly customizable framework to build your home lab and automated bare metal provisioning with PXE boot. You are installing and managing applications using GitOps. Expose services to the internet securely with Cloudflare Tunnel CI/CD platform. See roadmap and open issues for a list of proposed features and known issues.  

  

  

_Datree are sponsors of the phpops project_