# DevOps / SRE - Top Links Last Week

## Week 28 - Issue #87

  

31 links

  

## [Storage Wars: AWS S3 vs Cloudflare R2](https://vantage.sh/blog/cloudflare-r2-aws-s3-comparison)

Cloudflare R2 is cheaper than S3 storing data, with no data egress fees. However, it has fewer features than S3 and is not compatible with all S3 API calls.

  

## [Why Linux Succeeded](https://riskmusings.substack.com/p/why-linux-succeeded-resilience-of)

Linux is a model for change that benefits most stakeholders. It is a worldwide, loosely organized, fluid collection of skilled volunteer programmers that is anti-fragile and resilient to risks.

  

## [Pitfalls of Multithreaded Programs and Achieving Thread-Safety Using Go](https://betterprogramming.pub/pitfalls-of-multithreaded-programs-and-achieving-thread-safety-using-go-1ac80c8d8106)

This article discusses the benefits and drawbacks of using multithreaded programs and how to achieve thread safety in Golang. Thread safety is a concept that means different threads can access the same resources without producing unpredictable results. There are several methods for avoiding race conditions to achieve thread safety, including locking and using the sync.Once library.

  

## [How to Provision VMs on DigitalOcean with Terraform?](https://faun.pub/how-to-provision-vms-on-digitalocean-with-terraform-898515a0dbbc)

This article will go through provisioning VM on DigitalOcean using terraform scripts. You will start with the basics and create a new project. Those are the files that every terraform project needs:

  

- main.tf: used to define infrastructure

- variables.tf: used to set variables

- .gitignore: used to ignore files

- README.md: used to document project

  

We are using those variables to make the Terraform scripts configurable. For instance, we want to define how many instances we need.

  

## [Introduction to Docker and Container based development](https://medium.com/@imilamaheshan30/introduction-to-docker-and-container-based-development-b30945428b92)

Docker is a way to run applications in isolated "containers" to run on any system, regardless of dependencies.

  

## [PHP isn’t that bad](https://medium.com/storyblocks-engineering/php-isnt-that-bad-68faa2bc5cca)

Don't let a monolith scare you away from working at Storyblocks. We've learned from our mistakes ( e.g., Videoblocks), and we're taking steps to modernize, but PHP is a part of us and will be for a while yet.

  

## [DevOps vs. SRE: The Differences Explained](https://faun.pub/devops-vs-sre-the-differences-explained-da462f1b2944)

DevOps improves collaboration between groups by breaking down silos, while SREs focus on automation and monitoring.

-Salaries for DevOps and SRE roles vary greatly based on the location of the job, experience, skills, and level of responsibility.

  

---

  

  

## [2022 Argo external security audit: Lessons learned](https://blog.argoproj.io/2022-argo-external-security-audit-lessons-learned-951f80e0450d)

Ada Logics identified 26 issues across the 4 Argo projects. 7 CVEs were issued as a result. All vulnerabilities have been patched.

  

  

## [Kubernetes Operators: 5 Things You Truly Need to Know](https://alexandre-vazquez.com/kubernetes-operators-the-basics/)

Kubernetes Operators are a way to extend Kubernetes to manage big workloads. They are based on the concept of custom Kubernetes objects, which are defined in YAML files. Therefore, operators must be coded in specific controllers that translate the changes to the YAML files into cluster status.

  

## [Why am I excited about WebAssembly?](https://blog.colinbreck.com/why-am-i-excited-about-webassembly/)

WebAssembly has a lot of potential for being a safe and efficient way to run code at the edge and in the cloud to support the IoT because it is portable and sandboxed.

  

## [Load-testing TensorFlow Serving and FastAPI on GKE](https://sayakpaul.medium.com/411bc14d96b2)

This post discusses the lessons learned from conducting load tests for a Deep Learning model across numerous deployment configurations. These configurations involve REST-based deployments with FastAPI and TensorFlow Serving. The goal is to provide a holistic understanding of the differences between the two.

Some critical considerations for the deployment experiments respective to FastAPI and TensorFlow Serving are framework choice, deployment infrastructure, the trade-off between more or fewer servers, options to benefit multi-core environments, dynamic batching, and initial model warm-up.

The load tests are conducted using Locust. 

  

  

## [The Journeyman's Guide to Lua Unit Testing](https://blog.insiderattack.net/the-journeymans-guide-to-lua-unit-testing-41642825314a)

This article discusses using the busted framework for Lua unit testing and stub dependencies using package.preload.

  

## [Boost your Kubernetes cluster's Autoscaler on AWS EKS with Karpenter](https://nivogt.medium.com/boost-your-kubernetes-clusters-autoscaler-on-aws-eks-with-karpenter-4d23955944f2)

Karpenter is a tool that helps you scale your Kubernetes cluster on AWS EKS. It is deployed inside an AWS EKS and intercepts requests passed to the Kubernetes admission controller. It then takes action when demand does not match the available resources. This allows the cluster to scale up or down as needed to prevent resource contention.

  

  

## [Technical Writing for Developers](https://css-tricks.com/technical-writing-for-developers/)

Technical writing is essential for developers because it can help them communicate better with people, make marketing part of their job, and improve the overall quality of their work.

  

## [Input validation for known values](https://medium.com/@frank.leitner/input-validation-for-known-values-b060e779ee5b)

To avoid all possible injection attacks, user input should never be used directly. Instead, an allowlist should be used to allow only known, safe values. This is especially important in languages where such attacks are more common.

  

  

## [Best Programming Language To Learn "DevOps"](https://faun.pub/what-then-is-the-best-programming-language-to-learn-for-devops-1f4a45e8f010)

This article discusses the best programming language to learn for those interested in pursuing a career in DevOps. It argues that Python is the best choice based on its difficulties, usefulness, and popularity.

  

## [AWS Cost Optimization: Your To-Do List](https://aws.plainenglish.io/aws-cost-optimization-your-to-do-list-c71d92d717e7)

Check for unused AWS EBS volumes and delete them to save on costs

-Use reserved instances and savings plans to minimize AWS costs

-Monitor estimated AWS charges using CloudWatch

-Consider using serverless technologies to reduce costs

  

## [API Gateway with Lambda and DynamoDB](https://medium.com/@melissgibson/api-gateway-with-lambda-and-dynamodb-d9fa1b0cc917)

In this article, the author walks through creating a Lambda function in the AWS console to get items using boto3 and Python. Then create an API using the API gateway in the AWS console. I will then invoke the API, and the API Gateway will route the request to the Lambda function, which will query items from the DynamoDB table. The response should then be routed back through the API Gateway to me. Thus creating a serverless API gateway using the AWS resources.

  

## [Red Hat CEO: Out | Blind Users: Revolt | ARM: Google Joins Party](https://devops.com/red-hat-ceo-out-blind-users-revolt-arm-google-joins-party/)

Matt Hicks is the new CEO of Red Hat; Paul Cormier is the new board chair

-There is a growing trend of blind users revolting against accessibility overlays that do more harm than good

-Google has joined the ARM party with their new Arm-based VMs

  

## [Devtron: Managing Kubernetes workflows, Logging, and more!](https://medium.com/@mrpunitsolanki/devtron-managing-kubernetes-workflows-logging-and-more-d113a800a63f)

The above blog discusses how to set up separate workflows for different environments using Devtron. It also highlights the importance of Logging and shows how easy it is to set up Logging using Devtron.

  

  

  

## [5 Tricky Container Security Challenges](https://containerjournal.com/features/5-tricky-container-security-challenges/)

Container environments can be challenging to secure because they are virtualized and hyper-dynamic. In addition, Kubernetes and other container management tools offer new attack surfaces for hackers. As a result, security must shift left, and DevOps teams must take on the challenge of protecting production environments.

  

## [Route Trino queries dynamically using Trino Gateway](https://itnext.io/route-trino-queries-dynamically-using-trino-gateway-9772d62b1630)

Trino is a popular query engine used to query data in data lakehouses. Trino Gateway can route Trino queries dynamically to downstream Trino clusters.

  

## [No more moats: Hardening cloud-native security](https://medium.com/mirantis/no-more-moats-hardening-cloud-native-security-3fab25ed04b9?source=rss------kubernetes-5)

Kubernetes is becoming increasingly popular but also becoming increasingly vulnerable to attack. Security practices must keep pace with adoption to keep clusters safe. Considering security in terms of a "moat" is no longer effective and can put systems at risk. A minimum viable cloud-native security strategy includes creating a secure software supply chain. This can be done by using private container registries with image signing and scanning capabilities, as well as enforcing role-based access control across a Kubernetes cluster.

  

## [Scanning Kubernetes YAML Files for Security](https://blog.devgenius.io/scanning-kubernetes-yaml-files-for-security-e302542b5407)

Kubesape is an open-source tool for scanning Kubernetes YAML files for security vulnerabilities and misconfigurations. It uses the OPA engine and scans the objects extracted from the API server using snippets.

  

## [Portainer vs Rancher vs OpenShift](https://www.portainer.io/blog/portainer-vs-rancher-vs-openshift)

Portainer is a multi-cluster manager that is extremely lightweight and can provide centralized access control and governance at scale.

  

## [The Real Cost of Open Source Software](https://betterprogramming.pub/the-real-cost-of-open-source-software-f87c29f68719)

Open source software is computer software that is released under a license in which the copyright holder grants users the rights to use, study, change, and distribute the software and its source code to anyone and for any purpose.

The Open Source Initiative was founded in February 1998 to evangelize open-source principles.

GitHub has played an essential role in being the defacto place for hosting open source projects.

Some of the critical challenges organizations face while trying to adopt OSS are that it is more susceptible to security breaches, upgrades require considerable effort, and there is no vendor.

  

## [Temporary Storage for Kubernetes Pods](https://itnext.io/temporary-storage-for-kubernetes-pods-f8330ad8db88)

Kubernetes pods can use EmptyDir volumes for temporary storage, which can be defined by size and type of storage medium.

  

## [7 Ways to Dramatically Reduce Your Time in Code Review](https://betterprogramming.pub/7-ways-to-dramatically-reduce-your-time-in-code-review-febe05e9f38c)

- keep your PRs small

- use a PR template

- set an SLA for review time

- teach your teammates about code review

- automate formatting and linting

- use a review app

- use a CodeSee Review Map

  

## [Pandas vs Dask vs Datatable: A Performance Comparison for processing CSV files](https://towardsdatascience.com/pandas-vs-dask-vs-datatable-a-performance-comparison-for-processing-csv-files-3b0e0e98215e)

Pandas is an excellent tool for data analysis, but it can be slow when working with large CSV files.

-Dask is a library that can improve pandas' performance by scaling it to multi-core machines and distributed clusters.

-Datatable is another library designed for speed and can be used in conjunction with pandas for large data processing tasks.

  

## [Experian, you have some explaining to do](https://krebsonsecurity.com/2022/07/experian-you-have-some-explaining-to-do/)

Experian allows users to sign up for new accounts using the victim's personal information and a different email address without confirming that the new email address can respond to messages or that the previous email address approved the change. This allows identity thieves to hijack the accounts and change the associated PIN and recovery questions.

  

  

## [The Laws of Software Development Explain Why Creating Software Always Takes Longer Than Expected](https://itnext.io/the-laws-of-software-development-explain-why-creating-software-always-takes-longer-than-expected-7b4fcbe35cea)

Software development is out to get you, so put your guard up and get ready to roll with the punches. The rules and principles below describe why creating software takes longer than expected, even when we know the rules and regulations of software development.