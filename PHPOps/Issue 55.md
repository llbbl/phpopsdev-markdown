# DevOps / SRE - Top Links Last Week

## Week 48 - Issue #55

  

## [AWS Outposts](https://aws.amazon.com/blogs/aws/new-aws-outposts-servers-in-two-form-factors/)

  

AWS Outposts servers are on-premises compute and storage that is monitored and managed by AWS, and controlled by the same, familiar AWS APIs. The c6gd.16xlarge model supports six instance sizes, as follows: 2x 1.9 TB, 4x 4x 237 GB, 8 16 GiB 474 GB, 16 32 GiB 950 GB, 32 64 GiB 1.8 TB c6id.8xlarge supports all but the largest of the following instance sizes. Each Outposts server connects to the cloud via the public Internet or across a private AWS Direct Connect line.

  

## [Will JetBrains Fleet Be a VSCode Killer?](https://betterprogramming.pub/will-jetbrains-fleet-be-a-vscode-killer-89554d1096ae)

  

 JetBrains has re-built its VSCode editor from scratch to compete with IntelliJ IDEA and WebStorm. JetBrain's Fleet editor supports Java, Kotlin, Python, Go, Javascript, Typescript, Rust, and Json languages. Jetbrains has added two modes to its editor: Editor-light, Editor-smart and Editor-Smart. Editor-Light editor will launch quickly and with no delay. Editor now supports natively connecting to a remote machine where our code is located.

  

## [AWS Redshift Serverless](https://aws.amazon.com/blogs/aws/introducing-amazon-redshift-serverless-run-analytics-at-any-scale-without-having-to-manage-infrastructure/)

  

 Amazon Redshift Serverless is a new capability that makes it super easy to run analytics in the cloud with high performance at any scale. There is no need to set up and manage clusters, and you pay for the duration in seconds when your data warehouse is in use, for example, while you are querying or loading data. With the new serverless option, you can continue to query data in other AWS data stores, such as Amazon Simple Storage Service (Amazon S3) data lakes and Amazon Aurora and Amazon Relational Database Service.

  

## [Will Nix Overtake Docker?](https://blog.replit.com/nix-vs-docker)

  

 A reproducible environment is one that can be recreated from scratch in an identical way (ideally bit-for-bit) Practically, this means having the same tools, versions, and configuration between the environments. Nix provides a whole build system that allows for building packages in an isolated way. Docker doesn't have any guarantees that creating images is reproducible -- If you run docker build twice with the same Dockerfile you might get 2 images that behave in different ways. Nix takes a first-priniciples approach to reproducible builds and package management.

  

## [PHP Has Survived for 26 Years Because It Keeps Evolving](https://thenewstack.io/php-has-survived-for-26-years-because-it-keeps-evolving/)

  

 An influential developer in the open source PHP project, Nikita Popov, decided to move on, prompted the formation of a new foundation to run the project. The company JetBrains announced on its blog the creation of The PHP Foundation last week. The goal is to be “a non-profit organization whose mission is to ensure the long life and prosperity of the PHP language” Among the newly announced partners for the new foundation is Automattic, the company behind WordPress. Despite moving somewhat toward JavaScript technologies over the past several years, WordPress is still reliant on PHP.

  

## [Werner Vogel’s 6 Rules for Good API Design](https://thenewstack.io/werner-vogels-6-rules-for-good-api-design/)

  

 AWS Chief Technology Officer Werner Vogels spoke at the AWS re:Invent user conference in Las Vegas this week. He said the company is still learning how to best create manage APIs. Each API is managed by a team, and there is no central coordination of how they are designed. Vogels: API design is risky to think about designing a uniform format for APIs before understanding how they will be used would “stifle innovation” He said API calls should never be deleted, or changed, and that changing the API will basically break businesses.

  

## [Observability vs. monitoring debate: An irreverent view](https://ubuntu.com/blog/observability-vs-monitoring-debate-an-irreverent-view)

  

 In the past few years, the word “observability” has gained traction in the discussions around monitoring and cloud-native computing. There is significant confusion about the overlap or difference between observability and monitoring. In this post, I argue that the debate around observability vs. monitoring is, at best, poorly understood. Google Trends show that there is a clear spike in the interest in observability around 2019. Europe is split over it, with Germany and Spain searching predominantly for monitoring, and Italy and Great Britain.

  

## [Introducing Red Hat Ansible Automation Platform 2.1](https://www.ansible.com/blog/introducing-red-hat-ansible-automation-platform-2.1)

  

 Ansible Automation Platform 2.1 is the culmination of many years of reimagining how enterprise automators automate for today and tomorrow. Red Hat announced the general availability of the latest version of Ansible. This is the follow-on to Ansible 2.0 Early Access released this summer, and announced at AnsibleFest 2021. Every Ansible release will now have its own unique Red Hat Subscription Management repo, which requires a subscription. The execution plane is now resilient to network latency and connection interruptions and improves communications.

  

## [Anti-patterns when building container images](http://jpetazzo.github.io/2021/11/30/docker-build-container-images-antipatterns/)

  

 This is a list of recurring anti-patterns that I see when I help people with container build pipelines. When combined, they can easily compromise your productivity and waste time and resources. Smaller images will generally be faster to build, push and pull, use less disk space and network space. For microservices with relatively few dependencies, I don’t worry about images below 100 MB. For complex workloads (monoliths or, say, data science apps), it’s fine to have images up to 1 GB.

  

## [How to Evaluate the Maturity of DevOps Practices in your Company?](https://faun.pub/how-to-evaluate-the-maturity-of-devops-practices-in-your-company-58a1ff7246a2)

  

 SMART Maturity Assessment Method is my first success in repurposing a Lean Manufacturing methodology to the Software industry. This method is very versatile and applies every time you need to evaluate the maturity of your company during a transformation initiative. SMART also provides guidelines on how to create a roadmap to improve further and keep your transformation moving forward. Each letter represents one of 5 levels of maturity and each letter represents a maturity level. The first two phases of the evaluation lead to a spider diagram representing the current situation.

  

## [Understanding Agile vs Waterfall vs DevOps](https://faun.pub/understanding-agile-vs-waterfall-vs-devops-5eac10f7e1f9)

  

 DevOps is not just a collection of tools, but a methodology or system of methods used in software development and deployment. The waterfall system is a concept used to describe the stepwise process of the software development process. Agile is an Iterative team-based approach to development. The Agile method relies on a very high level of involvement from the developers, testers, and customers throughout the project but especially the reviews. The customer can be carried along the development process and he becomes also part of the process.

  

## [Docker Deep Dive — Part 1](https://faun.pub/docker-deep-dive-part-1-e7aee19ba445?source=rss----10d1a7495d39---4)

  

 In this article, we will be taking a look at the concept of containerization and a popular containerization tool in the DevOps world known as Docker. Containers are a form of operating system virtualization. They allow you to package your application and all its dependencies into a single executable that can be distributed among team members. Because of this, containers are more lightweight and are easier and faster to spin up leading to faster deployments. We will not be able to list them all out here.

  

## [Serve S3 Files via Cloudflare for Free](https://aws.plainenglish.io/serve-s3-files-via-cloudflare-for-free-1bbde103623d)

  

 Free version of the WP Offload Media Lite plugin is available in the paid version. Offloaded media is not routed through CDN and hence they won’t be cached or distributed among CDN servers. To avoid this, we need to proxy the traffic to https://aws-bucket.s3.amazonaws.com also via our CDN. All our images are getting loaded via https://s.us-west-2.amazon.com/s3. We need to make sure the image URLs seem to come from our domain.

  

## [How to review pull requests more quickly: practical tips](https://isamatov.com/review-pull-requests-faster/)

  

 As a developer, it’s one of your most important duties to review pull requests. Reviewing PRs quickly could slow you down a bit but that's okay since you’re boosting the productivity of your team as a whole. Read acceptance tests first to help you understand what the code is supposed to do and see the edge cases. Ask clarifying questions more often to speed up your review process. If you see that something big is incorrect, send comments immediately and do not wait to review the whole thing.

  

## [Introduction to Kubernetes Deployments and Services](https://itnext.io/kubernetes-for-dummies-deployments-and-services-7403f30d30ba)

  

Kubernetes for dummies: deployments and services. Let’s discover Service and Deployment objects. Deployment allows k8s to have desired state rules on a Pod or group of Pods. Service objects provide a way to expose an application running in one or more pods via a single IP. Services are one of the simple ways we can do it. An endpoint contains a simple object IP of a Pod. Endpoints are a simple collection of endpoints.

  

## [Karpenter: Open-Source, High-Performance Kubernetes Cluster Autoscaler](https://itnext.io/karpenter-open-source-high-performance-kubernetes-cluster-autoscaler-d56e3ab06aae)

  

 Kubernetes-native cluster autoscaler is now production-ready according to AWS. At re:Invent 2021, AWS announced the v0.5.0 release of Karpenter as production ready. The open-source tool is a version of GKE Autopilot’s dynamic node provisioning process, designed to work with any Kubernetes cluster. With Karpent, users can now dynamically provision underlying compute nodes based on pod specifications more efficiently than the existing Kubernetes cluster-autoscaler project.

  

## [How to Secure Serverless Architectures](https://aws.plainenglish.io/infographics-securing-serverless-architectures-bf2925a00ab0)

  

 Serverless reduces a lot of operational burdens, but a serverless architecture is still your responsibility. From web threats, over IAM principles to auditing & monitoring, learn more about securing serverless architectures in these two-parter infographics. Learn more about secure serverless security in these infographics: The Serverless Architectural Architectural Security Initiative is on the move to serverless-architecture, with the help of Google and Microsoft's IT experts in the U.S. It's a great way to keep your data secure.

  

## [5 Data Quality Tools You Should Know About](https://betterprogramming.pub/5-data-quality-tools-you-should-know-about-dacc38aa6ba8)

  

 The quality of the data dictates how useful it is to the enterprise. According to a recent Gartner data quality market survey, poor data quality costs enterprises an average of $15 million annually. In this post, we will consider five data quality tools and see how they can help you in your data journey. The tools you choose to mix and match will depend on your use case and budget. Great Expectations Spectacles is an open-source library used for validating, documenting, documenting and profiling data.

  

## [Terraform Resource Creation with Nested Data](https://itnext.io/terraform-resource-creation-with-nested-data-92af9a9f96ea)

  

 The ALB LB can only register HTTP based target groups, while NLB LB only registers TCP based targets. Each target could be by IP of the instance or by the EC2 instance itself (ignore the other type such as labmda or ALB) Therefore, I will have 2 protocols x 2 target types x 2 applications, 8 combinations for the target groups. The for_each loop seems like is a good fit to create those similar resources. However, it cannot perform nested looping in the resource definition block.

  

## [Amazon CloudWatch Gets Feature Flags, User-Based Monitoring](https://thenewstack.io/amazon-cloudwatch-gets-feature-flags-user-based-monitoring/)

  

 Amazon Web Services has augmented its Amazon CloudWatch monitoring service with feature flags and A/B testing. With feature flags, a developer can test new features of an application by only rolling them out to a select set of users. With these services, features can be tested through randomized experiments with multiple variations, allowing the developer to test which feature works best. The success of each variation can then be statistically analyzed. In addition, CloudWatch can now offer performance data (anonymously collected) based on actual usage.

  

## [PagerDuty Automates Incident Response with Rundeck](https://thenewstack.io/pagerduty-automates-incident-response-with-rundeck/)

  

 Digital operations management company PagerDuty has released a new version of its Operations Cloud that introduces a new level of automation to its platform. The company has added several features to connect everything, whether people to services or dependencies within an organization. The Dynamic Service Graph gives a snapshot of service health and application dependencies, as well as shows the teams or individuals responsible for those services. The automation comes in the form of Rundeck Actions, which brings automated diagnostics and response to the frontlines of incident response.