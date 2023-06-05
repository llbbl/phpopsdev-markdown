# DevOps / SRE - Top Links Last Week

## Week 12 - Issue #71

  

27 articles

  

  

## [Hunt for Lapsus$ Hackers Leads to a British Teen](https://www.wired.com/story/russian-hackers-lapsus-north-korea/)

  

The Lapsus$ extortion gang hacked Okta and leaked source code for Microsoft's Bing search, Bing Maps, and Cortana voice assistant. The White House warned U.S. companies that Russia may be exploring options for cyberattacks. The U.S. Department of Justice unsealed two indictments on Thursday. According to unnamed U.S. officials, the Viasat satellite hack, which disrupted Ukrainian military communications, was whodunnit. We looked back at the most extensive hack since the Ukraine war began late February.

  

## [Diving Into Open Source](https://rsealfon.medium.com/78edc820048e)

  

People join open-source projects to connect with the community, to learn technical skills, to help create software they care about, and even, in the case of a few tasks, to earn swag. On your resume, you should list any project you significantly contributed to and the main contributions. This can help give employers a feel for the technologies you know and highlight your skills as a team player. Learn the project structure, including the documentation, release frequency, package format, and package format, and who accepts pull requests.

  

## [PHP filter\_var shenanigans](https://pwning.systems/posts/php_filter_var_shenanigans/)

  

We have likely all seen PHP filters that prevent us from encountering vulnerabilities. In this blog post, I'll walk you through my thought process for bypassing a filter by looking for a bug in the filter itself to reach a bug! The code that is generated will resemble something like the following.php $userinput = "YOUR\_USER\_INPUT" ; $command = "ping -c5 "; $retval = $user input.

  

## [Its Always Sunny in us-east-1: The gang does business continuity | cyclic.sh](https://www.cyclic.sh/posts/its-always-sunny-in-us-east-1)

The gang experiences an AWS outage; customers report SHOWSTOPPERs; the gang triages the issues and attempts to implement an elaborate disaster recovery plan. The goal here is efficiency and the mitigation of risk to lunchtime. As always, the secondary objective is to expose the truth about how the P.R. comment you left was ignored and best practices spitefully neglected. Large organizations have Recovery Time Objective (RTO) and Recovery Point Objective ( RPO) standards for disaster/outage scenarios. RTO/RPO can be internal standards or sometimes compliance requirements.

  

## [Understanding Load vs. Stress Tests](https://betterprogramming.pub/load-vs-stress-tests-ee49ae110b1d)

  

A load test shows how the application will behave under several simultaneous requests. A stress test shows the limits of the concurrent requests that an application can handle. This article will begin by explaining the differences and then showing how to implement straightforward tests using two simple tools. Many available tools allow us to create load and stress tests; some are paid, others aren't. Finally, I will show how to use two of them, K6 and loadtest.

  

—

  

  

## [Building Stateful Apps on K8s Takes a Village](https://containerjournal.com/features/building-stateful-apps-on-k8s-takes-a-village/)

  

Running stateful, often business-critical applications in Kubernetes is increasingly common. Getting those wrong can cost organizations dearly in unequivocal business terms. The CNCF Storage Landscape Whitepaper is intended to provide an overview of what can often seem like an impenetrable world of overlapping words, metrics, and considerations. Architects, platform engineers, and critical decision-makers must understand the implications of storage decisions in more detail, so we don't repeat mistakes that have been made in the past.

  

## [10GB Ephemeral Storage for AWS Lambda](https://itnext.io/10gb-ephemeral-storage-for-aws-lambda-788fad51c99b)

  

March 24, 2022, is a game-breaking day for Lambda consumers that needs ephemeral/temporary disk-based storage above the previous limitation (512MB). Before this update, provisioning storage requires a painful setup of either VPC + EFS or baking large function containers. The most common drawback of EFS integration with Lambdas is just the tip of the annoyances required to provide access to large disk spaces. EFS offers a multi-az persistent NFS storage.

  

  

## [How to Use SSH Config File to Boost Your Productivity](https://betterprogramming.pub/use-ssh-config-file-to-boost-your-productivity-b3867ce8cbfe)

  

Effortlessly keep track of your servers' I.P. addresses and credential locations. This is where the ssh config file comes to the rescue. The format for writing a remote host configuration inside a config file is as follows: Host \<server-alias\>Server-alias \<server I.P. or URL\> The space provided from the second line is not compulsory but helps in making the file more readable. A single SSH config file can have multiple ssh configurations. You can find the entire list of parameters here.

  

## [How to Deploy Kubernetes with Kubeadm and containerd](https://thenewstack.io/how-to-deploy-kubernetes-with-kubeadm-and-containerd/)

  

There's an almost endless path to getting the Kubernetes platform up and running. One method is with kubeadm (a tool that helps fast-track your Deployment) and containerd (a container runtime engine). Another approach is to deploy a cluster with a master and one node (for simplicity), but you can deploy as many nodes as needed. To do this, you'll need at least two machines (one for the master and the node). Each device should have at least 2 G.B. of RAM.

  

## [Simple React Application with Flask and Kubernetes Deployment](https://blog.devgenius.io/simple-react-application-with-flask-and-kubernetes-deployment-cb4dc240e8dc)

Python and Go (for Docker and Kubernetes) used frameworks: Flask and ReactJS. The front-end folder is called the front-end. The backend folder is our flask-server, including a./static,./templates folder, and the main.py file. The Kubernetes folder includes our deployment files for Deployment. After a successful launch, you can decide if some libraries should be added or changed. To serve the react app via the flask server, we need to run one command to change the build path of our application.

  

## [I built a receipt printer for GitHub issues](https://aschmelyun.com/blog/i-built-a-receipt-printer-for-github-issues/)

  

Andrew Schmelyun uses a thermal receipt printer to print out a ticket when anyone adds a new Github issue. The printer prints a ticket every time a new issue is added to one of the Repos on GitHub. He also used an old Raspberry Pi Zero W to send data to the printer from the internet to send it data. Next, he used an Epson thermal printer and an Ubuntu version of Composer to get the printer working with ESC/POS commands in PHP. Finally, he created a rule to let users from the dial-out group use the printer.

  

  

## [Build Docker Image In Kubernetes Pod —](https://devopscube.com/build-docker-image-kubernetes-pod/)

  

This beginner's guide focuses on step by step process of setting up Docker image build in Kubernetes pod using Kaniko image builder. Kaniko is an open-source container image-building tool created by Google. It does not require privileged access to the host for building container images. However, the Docker build containers run in select mode, which is a big security concern and opens the door to malicious attacks. Using Kaniko, I will use publicly available tools to build Docker images on Kubernetes.

  

## [A Simple Git Workflow: Releaseflow](https://hasnode.byrayray.dev/a-simple-git-workflow-releaseflow)

  

Release flow is much simpler than gitflow and has only four different types of branches. The long-life branch in the git release flow is the primary or master branch. You will merge these branches into the main branch with a pull request. At the end of each sprint, there will be a new release branch like this `release/{prefix}-{sprint-number}.` This branch is created from the main branch and deployed to production. It's good to introduce feature flags in your backend or front-end application.

  

  

## [Locking Down Kubernetes Containers with vcluster](https://thenewstack.io/locking-down-kubernetes-containers-with-vcluster/)

  

You can now use loft Labs' open-source cluster in an isolated mode for virtual clusters. This is news you can use. Loft Labs sees this as a default best practice for isolating virtual clusters. Vcluster follows in the footsteps of k3v, which was a proof-of-concept for virtualizing Kubernetes. Virtual clusters are often used as development environments when engineers build, test, and debug cloud-native software. It may be critical to the secure development environment you've been looking for.

  

## [Automation Is No Silver Bullet: 3 Keys for Scaling Success](https://thenewstack.io/automation-is-no-silver-bullet-3-keys-for-scaling-success/)

  

Automated testing makes for better products in smaller batches, so it should be the priority throughout the continuous delivery cycle. It's a must-have for agile, continuous integration, and continuous integration. However, the way to harness its real potential is a commitment to automated testing is commitment, says Ramiro Millan. The benefits of automated testing include reducing the number of bugs and security in the final products delivered, which increases the value of the products produced in the final products.

  

## [PlanetScale Rewind: An ‘Undo’ Button for Bad Schema Migrations](https://thenewstack.io/planetscale-rewind-an-undo-button-for-bad-schema-migrations/)

  

Rewind is an "undo" button that enables users to recover in seconds from schema changes that break production databases. It's, in effect, the equivalent of Control-Z, allowing you to roll back schema changes but without losing any data collected from that breakpoint. PlanetScale is a serverless database built atop Vitess, the open-source project developed at YouTube to scale its databases horizontally during YouTube's years of hypergrowth. The company announced the general availability of its zero-downtime Schema migration technology in November.

  

## [Top 10 Container Security Best Practices](https://faun.pub/top-10-container-security-best-practices-317d8070b9a9)

  

The cost of each data breach is USD 3.92 million as per this IBM report. 94% of organizations use one or more cloud platforms, and 45% of their computing is on containers or CaaS. The dominance of containers is increasing, and thus the security threats are growing. This article will go through some container security best practices we can follow and implement to reduce the security risks in containerized workloads. The top issues identified as a threat in these reports are Data exposure and malware, application vulnerabilities; weak authentication; weak or broken authentication.

  

  

## [How To Deploy Helm Charts With Terraform](https://getbetterdevops.io/terraform-with-helm/)

  

We will see how to deploy software components with Helm. This will allow you to manage applications on top of Kubernetes in the form of code. For example, we will use the Helm provider to deploy Helm charts in the following article. This provider needs Terraform and Helm binaries installed on your machine to work. You can find the complete code of this tutorial in this GitHub repository. You will use it to connect to the kubeconfig file, Grafana, and Prometheus.

  

  

## [Terraform Init — Command Overview with Quick Usage Examples](https://spacelift.io/blog/terraform-init)

  

The terraform init command is the first command you should use to run with Terraform. In this article, I will explore the options available and give an example of when to use it in automation using Azure DevOps. The example files I will use in this article will create a specified number of groups in Azure AD. These files are contained in a directory called az-ad-group. Within it, I have my Terraform configuration files, named main.tf, variables.tf and terraforms.tfvars, and a .gitignore file will specify which file extensions to not have in version control.

  

  

## [Problems with "graceful shutdown" in Kubernetes](https://philpearl.github.io/post/k8s_ingress/)

  

At Ravelin, we've migrated to Kubernetes (on GKE). We need to set up an Ingress so You can access the API from the outside world. At first, this seems straightforward. But we have begun to notice our integration tests are occasionally receiving 502 errors. And there begins a journey that I'll save you the pain of reading about by cutting directly to the conclusions. This Grace is not overrated. But you really shouldn't do it in.

  

  

## [Use Cloud Formation Templates to spin up MySQL instances on RDS](https://www.sqlshack.com/spinning-up-mysql-instances-on-rds-using-cloudformation-templates/)

  

Cloud Formation is a cloud service that enables AWS customers to write the desired state of any infrastructure as a code and then use it to deploy resources to Amazon. In this article, we will discuss how to set up a MySQL instance on AWS RDS using Cloud Formation templates. The components of a cloud formation template are as follows: A JSON or YAML file. The resources will be defined as a template, a. stack, which can be a combination of multiple resources that need to be set up as a part of the application. The templates support a wide range of resources on AWS.

  

  

## [NSA on How to Harden Kubernetes](https://thenewstack.io/nsa-on-how-to-harden-kubernetes/)

  

The National Security Agency has updated its Kubernetes Hardening Guide. The new guide explains how to harden the system against attackers. The focus has been updated and is more helpful today than the previous version. The NSA has also written guidelines on securing video conferencing, text chatting, and collaboration tools. It also advises developers to run containers and Pods with the least privileges possible, use firewalls to limit unneeded network connectivity, and use encryption to protect confidentiality. 

  

  

## [GitOps in Kubernetes with ArgoCD](https://blog.getambassador.io/gitops-in-kubernetes-with-argocd-c6ea0e510741)

  

This article will focus on ArgoCD: an open-source tool GitOps continuous delivery tool for Kubernetes. In GitOps, our infrastructure and application configuration are defined as code and stored centrally in a version control system like Git. This means it uses what is described in the Git repository to configure your infrastructure and applications. As a result, the entire system can be defined declaratively, where you can control access to the cluster. We will be using a tool called minikube to set up a local Kubernetes cluster for development.

  

## [Terraform Explained In Brief](https://thedeveloperstory.com/2022/03/21/terraform-in-a-nutshell/)

  

Terraform is an infrastructure as code (IaC) tool that can provision resources in the cloud from simple declarative code. Terraform enables you to securely and efficiently create, maintain, and version infrastructure by representing your infrastructure and settings with the HashiCorp configuration language (HCL) or even. The best part is that it is free and open-source. So the first step to getting started is to install the. CLI on your local system, then from your project, create a file ending in a.tf extension.

  

  

  

## [The Language Every Programmer Should Master](https://betterprogramming.pub/the-language-every-programmer-should-master-8d0dfc461284)

  

The Language Every Programmer should know is neither JavaScript nor Python nor `C++` nor Rust. Software development is not just coding; it's not just about writing code but rather about offering a service centered around the software. Good communication skills and the ability to express ideas compellingly are keys to success. Good documentation is one of the most critical steps in ensuring the service is usable. GitBook is a tool to quickly and neatly publish your docs from a git repository or export them as PDFs.

  

  

## [Okta and the Lapsus$ breach: 5 big questions](https://venturebeat.com/2022/03/23/okta-and-the-lapsus-breach-5-big-questions/)

  

In January, Lapsus$ accessed the account of a customer support engineer who worked for a third-party Okta provider; the identity security company acknowledged this on Tuesday. Okta has identified the breached third-party provider as Sitel, which provides Okta with contract workers for customer support. Sitel said the breach contained "parts of the Sykes network" - referring to Sykes Enterprises, which was acquired by Sitel last year. Forrester's Andras Cser: "If you have a security incident, maybe it's worth disclosing it to the public and getting it over with."