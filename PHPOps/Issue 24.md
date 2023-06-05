# DevOps / SRE — Top Links Last Week

## Week 17 Issue #24

## [SRE at Google: Our complete list of CRE life lessons](https://cloud.google.com/blog/products/devops-sre/sre-at-google-our-complete-list-of-cre-life-lessons/)

Customer Reliability Engineering (CRCE) is an offshoot of Site Reliability engineering (SRE) Our goal with CRE was (and still is) to create a shared operational fate between Google and our Google Cloud customers. Since then, here on the Google Cloud blog, we've published a wealth of resources to help you take the best practices we've learned from SRE teams at Google and apply them in your own environments. We still have plenty more articles to come, so keep your eye on our DevOps & SRE channel.

## [Benchmark results of Kubernetes network plugins (CNI) over 10Gbit/s network (Updated: August 2020)](https://itnext.io/benchmark-results-of-kubernetes-network-plugins-cni-over-10gbit-s-network-updated-august-2020-6e1b757b9e49)

All the CNIs tested are able to encrypt inter-pod communication. Only one not fully supporting Network Policies is Flannel. Antrea played the game well by providing many features : auto-mtu, encryption option, and straightforward install. Calico encrypted perf is about 6x better than Cilium, that ranks second. Kube-OVN is also RAM and CPU-intensive, it is still a pretty young CNI that relies on Open vSwitch (so does Antrea, but Antrea is lighter and performs better)

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Introduction to Containers with AWS](https://dev.to/aws-builders/introduction-to-containers-with-aws-og4)

Containerization is changing the way businesses develop and deploy applications in cloud environments. Containers decompose applications into small, manageable packages containing everything the application needs to run: code, configuration files, interfaces, and dependencies. Amazon Elastic Container Service (ECS) with AWS Fargate is the only option to run Docker containers without running EC2 instances on AWS. K8s (Kubernetes) is an open-source container orchestration solution that runs Google Cloudises, or even on your local machine.

## [Space Cloud: Open-Source Firebase and Heroku on Kubernetes](https://github.com/spaceuptech/space-cloud)

Space Cloud is a Kubernetes based serverless platform that provides instant, realtime APIs on any database, with event triggers and unified APIs for your custom business logic. Space Cloud helps you build modern applications without having to write any backend code in most cases. It provides GraphQL and REST APIs which can be consumed directly by your frontend in a secure manner. It is written in Golang, it follows cloud-native practices and scales horizontally. The results are sent directly to the concerned client.

## [Nine Pillars of DevOps Best Practices](https://devops.com/nine-pillars-of-devops-best-practices/)

In a prior blog I explained my 27-factor DevOps assessment model which includes nine pillars of DevOps and three dimensions of people, process and technology. In this blog, I include examples of practices for each of the nine pillars. In a future blog I will explain how to use these practices to conduct a gap assessment for your DevOps practices. The nine pillars represent categories of practices, including leadership practices for leadership, collaboration, integration and collaborative culture. For example, leaders demonstrate a long-term vision for organizational direction and team direction.

## [10 Simple Hacks That Will Make You Super Productive When Using AWS](https://dashbird.io/blog/aws-hacks-productivity/)

Everything on AWS is an API call; hence everything can be automated. This article will discuss several tricks that will save you time when performing everyday tasks in the AWS cloud. Use –dryrun flag to ensure that your command line operation does what you expect. The most interesting one is listed at the very end. Use the –profile flag to manage multiple accounts. Quickly download many files from S3 to download all files from a specified S3 path. The last S3 command is aws s3 cp, which allows us to download files.

## [DevOps progress: spotty, siloed and sporadic, but still moving forward](https://www.zdnet.com/article/devops-progress-spotty-siloed-and-sporadic-but-still-moving-forward/)

DevOps and agile methodologies have never been more important than now, with the growing complexity and interconnectedness of information technology. Industry leaders and experts share their perspectives on how and whether DevOps are serving the needs of today's digital organizations. The one thing missed in a lot of DevOps efforts isn't so much missed, as skipped because it's hard, says Grant Fritchey, a DevOps advocate at Redgate Software, Raj Patnam, and Alyson Simkins, director of developer operations at Catalytic.

## [Launching an Web Application on AWS Cloud using Terraform , GitHub, EFS and CloudFront](https://amangoyaler.medium.com/launching-an-web-application-on-aws-cloud-using-terraform-github-efs-and-cloudfront-c1a450d8986e)

Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It provides a centralized storage and we can able to connect it to multiple instances which is not in case of EBS. We also have to use the cloudfront and amazon s3 for proxy, faster loading and image storage purpose respectively. All this will be done using infrastructure as a service terraform using Terraform, GitHub, EFS and CloudFront.

## [Never Should You Ever In Kubernetes: #1 Do K8S The Hard Way](https://www.fairwinds.com/blog/never-should-you-ever-in-kubernetes-1-do-k8s-the-hard-way)

There are some things that you should simply never, ever do in Kubernetes. Corey Quinn, founder of Screaming in the Cloud and Chief Cloud Economist at The Duckbill Group, joined Kendall Miller, President of Fairwinds, and Stevie Caldwell, Senior Site Reliability Engineer at Fairwind's to discuss what development and operations teams should never ever do. There are a few tips to get you started to get started with some of the basics in place, and get help and advice from the folks who've already learned how to build repeatable frameworks.

## [How to create a Kubernetes cluster using Amazon EKS](https://faun.pub/how-to-create-a-kubernetes-cluster-using-amazon-eks-da0911ea62e2?source=rss----10d1a7495d39---4)

Amazon EKS has simplified the Kubernetes cluster creation process and has provided several approaches including simple UI navigation flow. An existing VPC and a dedicated security group meet the requirements for an Amazon. EKS cluster IAM role is required to set up an Amazon E.KS cluster. The cluster can be created in two different approaches, as a managed node group or as a Self-managed group. In this approach, a Cloud formation script has to be used to create the node group.

## [Create an API Gateway Solution for your APIs and Deploy it in Kubernetes with Ingress Controller](https://chashikaweerathunga.medium.com/create-an-api-gateway-solution-for-your-apis-and-deploy-it-in-kubernetes-with-ingress-controller-c28b09065471)

Using WSO2 API Microgateway, we need to create an API gateway solution. We need to set authentication mechanism for the APIs and as well as check every API request on whether it has a X-API-KEY header and if it does not have, I’m not going to send that request to the back end. Let’s create a docker image for the project and deploy it in the Kubernetes easily with the help of Wso2 k8s operator. We can easily build and create the docker image using the below command.

## [DevSecOps Learning Path: Integrating Security with DevOps](https://blog.pentesteracademy.com/devsecops-learning-path-integrating-security-with-devops-1cc03670552f)

Automated Code Review weeds out security-related issues and mistakes of the developers on the code phase itself. Sensitive Information Scan (SAS) scans the code for sensitive information (e.g. hardcoded password, tokens, secret keys, etc) before pushing the code into code repositories. Dynamic Application Security Testing (DAST) is performed to identify possible run-time vulnerabilities or security issues in non-running source code using techniques like taint analysis and data flow analysis. Vulnerabilities and reported issues can be tracked efficiently and resolved in an automated manner.

## [Why GitOps trumps all modern CD Solutions](https://harsh-prateek-singh.medium.com/why-gitops-trumps-all-modern-cd-solutions-31bc2a710278)

Traditional code delivery mechanisms to Kubernetes needed some glue to keep them running. Jenkins pipeline mechanism required loading cluster contexts, some kind of master token to grant access to deploy across multiple namespaces. GitOps is based on the principle that code delivery should happen in cluster, not out of cluster. Since everything is now deployed via a git repo, its open up the familiar git tools like code reviews, pipeline checks etc that can help to detect problems before deployment, rather than fixing them post deployment.

## [Scaling monorepo maintenance](https://github.blog/2021-04-29-scaling-monorepo-maintenance/)

A new set of tools has been added to the world's largest repository repository. The tool is called "Git" and is designed to make it easier to pack and find objects in a single file. The new tool is being used to make the most efficient way to find the best objects in the world. The tools are designed to work with the client rather than the client, which can be used to look at all of the files in a new way. They can also be used by the client to find out what objects they need to be added to a new set.

## [Monolithic vs. Microservice: Which Architecture Should You Choose?](https://javascript.plainenglish.io/monolithic-vs-microservice-which-architecture-should-you-choose-75f1ef0c6556)

Every web developer is already familiar with monolithic and microservice. Developers debate a lot about these topics. We can build a beautiful, functional application with both of them. The main thing is to know both of them very closely and pick one as per your need. Let's discuss both monolithic and microservice.

## [Release: Limitless environments so developers never have to wait to ship code](https://medium.com/sequoia-capital/release-limitless-environments-so-developers-never-have-to-wait-to-ship-code-a7165fcc763c)

Release: Limitless environments so developers never have to wait to ship code. Bogomil Balkansky: Having easy access to pre-production environments is a must. Release lets developers easily replicate production environments on demand. Sequoia: We look forward to partnering with Tommy McClung, Erik Landerholm and David Giffin on the road ahead — as they bring better, faster software development to every Release customer’s customers, writes Balkomil Balkomili: "We are pleased to lead their seed"

## [Diving Deep on S3 Consistency](https://www.allthingsdistributed.com/2021/04/s3-strong-consistency.html)

Amazon launched Amazon S3 in 2006 as “storage for the internet” in a bid to store backups, videos, and images for applications like e-commerce web sites. Over the years, S3 has become the storage used for analytics and machine learning on massive data lakes. Customers put in place their own application code to track consistency outside of S3 for their S3 usage. Customers also use S3 to store petabytes of data to train machine learning models. S3's pay-as-you model for capacity and constant innovation for new capabilities has fundamentally changed how customers use storage.