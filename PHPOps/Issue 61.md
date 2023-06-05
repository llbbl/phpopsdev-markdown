# DevOps / SRE - Top Links Last Week

## Week 2 - Issue #61

  

## [Store Secrets in Repositories (Safely), and Deploy them with Terraform](https://mantux.medium.com/store-secrets-in-repositories-safely-and-deploy-them-with-terraform-aea79997d3a0)

SOPS is a tool developed and maintained by Mozilla that lets us encrypt YAML/JAML files using different types of keys, like AWS KMS, GCP, age, and PGP. It was designed with simplicity in mind, and it comes with a CLI that you can use to encrypt and decrypt files. We use the AWS SSM parameter store to share the secrets with apps. When we run "terraform apply" the provider decrypts the secrets during the deployment.

  

## [5 Best Practices for Infrastructure As Code](https://betterprogramming.pub/5-best-practices-for-infrastructure-as-code-82bd5ce12a79)

Infrastructure as Code allows IT resources and configuration parameters to be treated as programmable objects and to be able to control them via code. IaC has numerous benefits — it can boost the speed, efficiency, consistency, and security of IT operations while minimizing the risk of human error. DevOps professionals can implement infrastructure as a Code across various environments —  multi-cloud and hybrid cloud deployments to multiple pipelines. However, it's not something that should be approached lightly, with insufficient resources or a lack of guidance.

  

## [Large-scale, semi-automated Go GC tuning](https://eng.uber.com/how-we-saved-70k-cores-across-30-mission-critical-services/)

Uber engineering's tech stack comprises thousands of microservices, backed by a cloud-native, scheduler-based infrastructure. Uber engineering was focused on reducing the cost of Compute capacity by improving efficiency. This blog will share our experience with a highly effective, low-risk, large-scale, semi-automated Go GC tuning mechanism. The GOGCTuner library is a library that simplifies the process of tuning garbage collection for service owners and adds a reliability layer on top of it.

  

## [What NPM should do to stop a new colors attack](https://research.swtch.com/npm-colors)

A developer named Marak Squires intentionally sabotaged his popular NPM package colors and his less popular package faker. NPM's design means that as soon as the vandalized version of colors was published, fresh installs of command-line tools depending on colors started using it. When Marak updated colors, installs of aws-cdk and the other tools started breaking, and the bug reports started rolling in. The right path forward is to stop preferring the latest possible version of all dependencies when installing a new package.

  

## [BreakingFormation: AWS CloudFormation Vulnerability](https://orca.security/resources/blog/aws-cloudformation-vulnerability/)

Orca Security's vulnerability researcher, Tzah Pahima, discovered a vulnerability in AWS allowing file and credential disclosure of an AWS internal service. This zero-day, which AWS completely mitigated within six days of submission, was an XXE (XML External Entity) vulnerability found in the CloudFormation service. An attacker could have used the exposure to leak sensitive files found on the vulnerable service machine and make server-side requests (SSRF) susceptible to the unauthorized disclosure of credentials.

  

## [Real-world stories of how we’ve compromised CI/CD pipelines](https://research.nccgroup.com/2022/01/13/10-real-world-stories-of-how-weve-compromised-ci-cd-pipelines/)

Attackers and defenders increasingly understand that built pipelines are highly-privileged targets with a substantial attack surface. NCC Group has found many attack paths through different security assessments that could have led to a compromised CI/CD pipeline in enterprises large and small. In this post, we will share some of our war stories about what we have observed and been able to demonstrate on CI-CD pipeline security assessments, clearly showing why there is the saying, "they are execution engines." We hope to emphasize the criticality of securing this varied attack surface to better secure the software supply chain by offering many different flavors of attack on possible development pipelines.

  

## [PHP in 2022](https://stitcher.io/blog/php-in-2022)

PHP 8.1 was released just a little more than one month ago. PhpStorm added support for generic types, and PhpStan and psalm are only growing. Static analysis in PHP is significantly increasing. JetBrains has pledged $1 million to the PHP Foundation, a non-profit development initiative with the only goal to fund core development. The biggest news of 2021 is that a core PHP developer is stepping down to work on LLVM.

  

## [SSH Bastion Host Best Practices](https://goteleport.com/blog/security-hardening-ssh-bastion-best-practices/)

Bastion hosts are an indispensable security enforcement stack for secure infrastructure access. This blog post focuses on following best practices on building and deploying a secure SSH bastion server based on OpenSSH. The end capability of the bastion host depends on the use case of infrastructure access. For example, access requirements via bastion for a database server can differ from those for a Windows server. However, for managing ingress and egress traffic, nothing beats the power of the native Netfilter.

  

## [Practical Shell Patterns I Use](https://zwischenzugs.com/2022/01/04/practical-shell-patterns-i-actually-use/)

There are thousands of reusable patterns I've picked up from looking over others' shoulders and googling. Here, I list many of the patterns I use often enough to remember. If you want to get them under your fingers, your mileage may vary depending on your tastes and what you most commonly use the shell for. I'm acutely aware that there are better/faster/more elegant ways to achieve the same thing for most of these tips, but that's not the point here. The point is to reflect on why you are stuck to save time by learning. 

  

## [Setup Traefik routing in Kubernetes with Helm chart](https://faun.pub/setup-traefik-routing-in-kubernetes-with-helm-chart-34008100b88f)

Traefik provides an official Helm chart for deployment, and the source is on GitHub. There are several ways one can configure Traefik, according to how we deploy it and how the Configuration supports the config. Traefik is a Kubernetes cluster's ingress controller and has both static and dynamic compositions. To understand the networking, we can look at the documentation.

  

## [What is DevSecOps? Why does it Matter?](https://faun.pub/what-is-devsecops-why-does-it-matter-66d3d3242bed)

DevSecOps stands for Development+Security+Operations. It automates security integration at every stage of the software development lifecycle. Many big tech companies are already hiring more and more DevOps engineers as very few know all technologies like Kubernetes, Docker, and Cloud. In the west, many companies have already started putting out job positions for this role, and in the future, India will also start hiring people for these roles. Even though security is "everyone's responsibility," DevOps teams are uniquely positioned.

  

## [Terraform @ Scale](https://itnext.io/terraform-scale-ba31a4a6f3dc)

The cloud is simple to use but has an unspoken complexity that threatens many businesses and organizations. The challenge when it comes to the cloud is around governance and compliance. Since Terraform is so simple to understand and pick up, many have jumped on the bandwagon and found it becomes more challenging to manage and support as they scale its usage. As more and more product teams decide to develop microservices, Terraform will need to scale and grow.

  

## [VSCode Datree: Datree’s power now in your code editor](https://medium.com/@suyashsonawane/vscode-datree-datrees-power-now-in-your-code-editor-747c9cfee610?source=rss------kubernetes-5)

VSCode Datree needs to be installed for the extension to work. The extension incorporates different Datree features and provides added functionalities to the user. Highlighting K8s Schema Errors and Helm Charts are examples of Datree's new features. New features added to Datree CLI will be made available in the extension. In addition, Datree has 30 built-in battle-tested policy checks. If your Configuration has these errors, the CLI will link to the solution article with the error highlighted.

  

## [What Version of Your Code is Running, and Where ?](https://blog.devgenius.io/what-version-of-your-code-is-running-and-where-b200ec7353bc)

You are injecting the Latest Git Commit Hash into Dockerfile as an ARG. We can achieve this from the command line with an extra step in your Github Action for building your Docker image. We use the GIT_HASH environment flag to denote the current git commit hash of the code that I'm making and pushing. So, for example, to print GITHUB_SHA, my command could look like this within the action's step: Print Git Hash.

  

## [Monitor ArgoCD applications using Prometheus and AlertManager](https://faun.pub/monitor-argocd-applications-using-prometheus-and-alertmanager-f96d7f39b060)

AlertManager should trigger an alert if an application's sync status has not succeeded, is out of sync, or the application isn't found. The AlertManager handles signals sent by client applications such as the Prometheus server. Using ArgoCD's Prometheus metrics to sync status alerts is better than using "argocd-notification" because we have more configuration possibilities when building the alerting rule. In addition, we can manage the entire alert lifecycle with AlertManager. 

  

## [Getting your Vault Secrets into Kubernetes](https://yonahdissen.medium.com/getting-your-vault-secrets-into-kubernetes-82ec7ffcee6f)

Using a Secret means that you don't need to include confidential data in your application code. A vault is an object that contains a small amount of sensitive data, such as a password, a token, or a key. Vault was created by Hashicorp and is used to store secrets in Kubernetes. The next problem we'd encounter would be accessing the secrets as Kubernetes does not know how to read secrets from Vault. Its goal is to secure, store, and tightly control access to tokens, passwords, certificates, and encryption keys to protect secrets.

  

## [Deploy Your Static Web App to S3 Using AWS CodePipeline & CDK](https://faun.pub/deploy-your-static-web-app-to-s3-using-aws-codepipeline-cdk-3ad0808ee1b3)

In this post, I will show you how we can automate the deployment process of a static website using AWS CodePipleline and AWS CDK. I will deploy a simple React App using the CDK and its components. I mainly focus on the deployment part of the application, and you may have to set up the S3 bucket for hosting the static website. For example, I use GitHub as a third-party source provider. I have created a few helper classes to keep the main stack clean and straightforward.

  

## [An Introduction to Terragrunt](https://medium.com/@marcus.tse_70031/an-introduction-to-terragrunt-dfe9921f5e48?source=rss------devops-5)

Terragrunt is a Terraform tool that keeps the backend Configuration DRY. It is defined on the root level, and the child modules inherit the Configuration, using the "terragrunt.hcl" file. Use the text editor of your choice, either vim or nano, to enter your secret and access keys inside. Export the keys and secret keys as environment variables to your machine. The bucket name is globally unique. The state is stored in an S3 bucket called "medium-terragrunt-example."

  

## [What happened to Kubernetes in 2021?](https://medium.com/@jeremysolarz/what-happened-to-kubernetes-in-2021-f0de69634d30?source=rss------kubernetes-5)

Release Cadence Change blog post: Kubernetes 1.21/1.22/1: Credential providers graduate from Beta (since 1.8) to Stable. New field ownership and object merge algorithm running on API server running on Kubernetes API server. A New API field called dataSourceRef was introduced to copy any custom resources data as long as the controller implements the necessary logic (examples: existing PV, snapshots). New API fields for PersistentVolume Health Monitor (Alpha): Detect abnormal volume conditions (through CSI Driver) from underlying storage systems and report them as events on PVCs or Pods. New cgroups v2 API to control memory allocation and isolation.

  

## [Improve your productivity with Kubernetes using aliases](https://www.handsonarchitect.com/2022/01/improve-your-productivity-with.html)

Kubernetes is the de-facto standard for orchestrating containers. This post will look at how to give kubectl a huge productivity boost by using programmatically generated aliases. These aliases are like shortcuts that we can add to the terminal session to execute a command or piece of code. The Github repository contains the list of over 800 aliases that are programmatically generated. There is a set of conventions followed while naming or generating these aliases. We can persist the aliases across sessions and store them permanently.

  

## [Terraform+Ansible, Get Dynamic Inventory of EC2](https://faun.pub/terraform-ansible-get-dynamic-inventory-of-ec2-10f2868aae76)

This article assumes you know nothing about dynamic inventory but understand Ansible & AWS. We need to provide the AWS cloud servers and then get their dynamic inventory using boto3 (an object-oriented API built with Python). First, we need to set up the ".aws" folder, credentials, config and give it the necessary permissions. After that, we are responsible for getting the dynamic inventory from the AWS web services.

  

## [Building smaller docker images — the right way](https://blog.devgenius.io/building-smaller-docker-images-the-right-way-1b6c12c112e1)

Docker images are great; they are easy to work with — but they can get blown up to enormous sizes when not paying attention to building them right. This article will help you write smaller docker images that will lead to more efficient and secure Docker containers. First, we will be reducing the docker image size from a whopping 536MB to 263MB and then finally to 65.8MB. 

  

## [Getting Started: Atlantis with Terraform and GitHub](https://medium.com/@apoorva.murde/getting-started-atlantis-with-terraform-and-github-4e99ab190655?source=rss------devops-5)

Atlantis is an open-source technology that allows the engineer/approver to review the changes in the infrastructure. As well as evaluate that the proposed change is the actual change executed on your infrastructure. Atlantis helps you run commands using GitOps; when you create a Pull Request, get approvals and run the terraform commands so that your entire team knows what changes are being made to the infrastructure. To deploy Atlantis, you need to know the basics of Terraform, Kubernetes, Helm, GitHub, and Webhook Relay.

  

## [Unrecognized Simplicity of Writing Code and the Underestimated Complexity of Creating Software](https://itnext.io/unrecognized-simplicity-of-writing-code-and-the-underestimated-complexity-of-creating-software-cdf6c20ca68e)

Software development is full of project failures, late projects, and millions wasted. The biggest problems in software development are people, politics, and project plans. Software development takes a complex business with entities and relationships that few people in a company know or understand. The software development skill is not in the Tools but the developer and other team members creating software. The limitations of software are in mind, not the technical limitations. 

  

## [Is NPM Activism Now a Thing?](https://betterprogramming.pub/is-npm-activism-now-a-thing-63b322e8ec62)

Colors.js Author published a package to NPM that caused an infinite loop. Package maintainers can do whatever they want, including malicious code. MIT license explicitly protects the original creator from any action arising from a package they have authored. The age of NPM activism is upon us; we live in a world where if people feel very strongly about something, they will use the tools at their disposal to get their point across. If that person has access to a popular NPM package, they'll purposely break it to make a big enough fire to attract attention to their cause.

  

## [The Clean Architecture — Beginner’s Guide](https://betterprogramming.pub/the-clean-architecture-beginners-guide-e4b7058c1165)

The Clean Architecture is the system architecture guideline proposed by Robert C. Martin (Uncle Bob). It is one of the guidelines adhered to by software engineers to build scalable, testable, and maintainable software. The Dependency Rule states that the source code dependencies can only point inwards. It is hard to understand, so I'm going to break this rule at first to let you know what problems it brings and then explain and let's see how to keep up with this rule.

  

## [Designing Instagram](http://highscalability.com/blog/2022/1/11/designing-instagram.html)

Ankit Sirmorya is working as a Machine Learning Lead/Sr. Machine Learning Engineer at Amazon and has led several machine-learning initiatives across the Amazon ecosystem. He is applying machine learning to solve ambiguous business problems and improve customer experience. The application should support the following requirements: Uploading photos and following other users, generating machine learning-based personalized recommendations to discover new people, photos, videos, and stories relevant to one's interest. The system will comprise several micro-services performing a separate task.