# DevOps / SRE — Top Links Last Week

## Week 25 Issue #32

## [Deploying AWS EKS Cluster With Terraform](https://faun.pub/deploying-aws-eks-cluster-with-terraform-97b5692d9f60)

Using Terraform modules to provision an EKS cluster with scalable, highly available, and fault-tolerant supporting architecture. The biggest issue in building modules and resources is dependability, compatibility & reliability of the code being used. We are going to use Terraform to build two AWS solutions with modules: A VPC with public and private subnets, both with autoscaling groups of EC2 instances, and a load balancer to work with the private subnet. We will set up a remote backend for the local copy of the Terraform files on AWS S3.

## [Running Laravel on Docker is really easy with Kool](https://dev.to/kooldev/running-laravel-on-docker-is-really-easy-with-kool-400h)

Kool is an open source dev tool that makes using Docker for local development a lot easier. In just 3 simple steps, you can use Kool's kool create command to start a new Laravel application running in a local Docker environment. Kool creates automatically runs the kool preset laravel command, which helps you set up your project's development environment using an interactive wizard. The latest version of Laravel will be installed and ready for you in your my-project folder, along with your new kool environment.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Upgrade Your SSH Key to Ed25519 (2018)](https://medium.com/risan/upgrade-your-ssh-key-to-ed25519-c6e8d60d3c54)

When is the last time you created or upgraded your SSH key? And did you use the latest recommended public-key algorithm? If it was more than five years ago and you generated your. SSH key with the default options, you probably ended up using RSA algorithm with key-size less than 2048 bits long. Ed25519 was introduced on OpenSSH version 6.5 using the Twisted Edwards curve. It’s using elliptic curve cryptography that offers a better security with faster performance compared to DSA or ECDSA.

## [GitLab 14.0 released with a celebration of GitLab 14](https://about.gitlab.com/releases/2021/06/22/gitlab-14-0-released/)

GitLab 14.0 is a complete DevOps platform with security embedded in its DNA, visibility and insights enabled by its single data store. The lead time for merge requests chart is now available at the Group level. Container scanning in GitLab now uses the Trivy engine by default. The editor preloads a template showing an example 3-stage pipeline to see it in action in your project. The pipeline editor is your one-stop shop when interacting with CI/CD pipelines. It is now much easier to get your first green pipeline!

## [Ultimate List of Web Development Podcasts](https://dev.to/tuckertriggs/ultimate-list-of-web-development-podcasts-4okf)

Ultimate List of Web Development Podcasts includes over 350 web development podcasts. This comprehensive list has over 350 podcasts covering website design, development, freelancing. Feel free to Contribute on Github. The list is a great way to stay informed about what's happening in web development.

## [Next.js 11: The ‘Kubernetes’ of Frontend Development](https://thenewstack.io/next-js-11-the-kubernetes-of-frontend-development/)

Next.js is the latest version of the React and JavaScript framework with new features to accelerate performance and developer collaboration. New features include real-time feedback, instantaneous live collaboration and significant image optimization enhancements. The new features include a preview of the framework's live version of Next.JS Live, which enables the framework to run entirely inside the web browser. Google is also working on technology to advance the framework, and has delivered Conformance for Next.js and the Next Script.js Script Component.

## [Rancher Desktop – An Open Source App for Desktop Kubernetes and Container Management](https://rancher.com/blog/2021/rancher-desktop-an-open-source-app-for-desktop-kubernetes-and-container-management/)

Rancher Desktop provides easy-to-use Kubernetes and container management for Mac and Windows. It’s important to be able to choose your version and test upgrading versions of the system. It also includes building and testing container images without the need to push or pull to a registry. It can speed up testing – especially with large images – especially on large images. It's a great way to test upgrading your application using the latest version of Kubernetes and keep your workloads around.

## [Ignore the Kingman at your own peril](https://taborsky.cz/posts/2021/kingman-formula/)

The Kingman formula originally appeared in an ancient math paper by J. F. C. Kingman in 1960 named “The single server queue in heavy traffic" The formula puts into relation the queue length with the queueing theory with the following variables: The mean service time, the mean arrival rate, the utilization rate and the number of tasks coming in steadily or in batches/peaks. But above 85% utilization the graph of queue length seems to explode exponentially. It becomes extremely sensitive to the two variabilities and above 95% the queue.

## [The Truth About Functional Testing](https://faun.pub/the-truth-about-functional-testing-66de92404c7f)

A recent discussion on functional testing got heated on LinkedIn over the weekend. The definition of functional testing should focus on validating the functionality of a software application. There shouldn’t be limits to the various functionalities under test. Testing should not just be limited to sanity, regression, and smoke testing. Instead of conflating terminology, testers should realize that each testing type has different tactics and goals. There are ways to combine these testing types constructively, whether it’s functional regression or API performance testing.

## [How To Use Pipeline on Google Cloud’s Vertex AI](https://betterprogramming.pub/how-to-use-pipeline-on-google-clouds-vertex-ai-863b429c811f)

How To Use Pipeline on Google Cloud’s Vertex AI is the foundation of Google Cloud's support of MLOps. We’ll walk through using Kubeflow to construct a simple pipeline to train an AutoML model. We want to create a schedule to repeat the training every hour of the pipeline. We will also show an example of a much more complex pipeline written in Tensorflow Extended. This is the sixth and last article of this series of articles by Eileen Pangu and Rodion Kutsaev.

## [Software Engineers Need To Know DevOps Too — And It Starts With CI/CD](https://betterprogramming.pub/software-engineers-need-to-know-devops-too-and-it-starts-with-ci-cd-ad0b5140da3e)

DevOps skills become increasingly important in the world of cross-functional teams and microservice architecture. In this article, we'll talk about best practices for CI/CD and how platforms like Armory can help manage some of the complexity involved. Some commonly used techniques are canary deployments, blue/green deployments, and rolling blue-green deployments. For CI, there are many good open source options like Travis CI or CircleCI. For CD, one of the most popular open source tools that helps automate deployments is Spinnaker.

## [Terraform: Deploying A Two-Tier Architecture Using Terraform Cloud CI/CD](https://troy-ingram.medium.com/terraform-deploy-a-two-tier-architecture-using-terraform-cloud-ci-cd-1e5d31327310)

Using Terraform Cloud as a CI/CD tool to check your build.com. The code uses modules for readability and re-usability. We will be deploying a two-tier architecture in AWS with public and private subnets. We want to ensure that our Web Servers are not able to be accessed directly from the internet. We added an Application Load Balancer that is internet-facing to direct traffic to our Web. Servers. are also in an Auto Scaling group to ensure high availability. We only included one NAT gateway to keep costs low.

## [How to Reduce Your Amazon EKS Costs by Half in 15 Minutes — CAST AI](https://cast.ai/blog/how-to-reduce-your-amazon-eks-costs-by-half-in-15-minutes/)

An e-commerce app was provisioned on an EKS cluster with six m5 nodes (2 vCPU, 8 GiB) on AWS EKS. I then deployed an AI engine to analyze my application and suggest some optimizations. I activated the engine and watched the system self-optimize. Within 15 minutes, the cluster cost went to $207 (a 50% reduction) by reducing six nodes to three. Then, 5 minutes later, the cost went down to $138 per month, using spot instances (a 66% reduction).

## [Red Hat Readies Major DevOps Upgrade for OpenShift Platform](https://containerjournal.com/features/red-hat-readies-major-devops-upgrade-for-openshift-platform/)

Red Hat will update the Red Hat OpenShift platform based on Kubernetes in July to add support for OpenShift Pipelines and an OpenShift Console that makes it possible to locally write and test code. Version 4.8 of Red Hat's OpenShift also adds support for both a IPv6/IPv4 dual stack and an IPv6 single stack. More than three quarters of respondents said they are deploying or plan to deploy a mix of both stateless and stateful workloads.

## [AWS has acquired encrypted messaging service Wickr](https://techcrunch.com/2021/06/25/aws-is-buying-encrypted-messaging-service-wickr/)

This is the first time we’ve been able to look at the world’s most famous and most dangerous animals. We’re looking at the first set of animals in a new wave of the world that could be seen in the next wave wave. We're looking at all the animals in the current wave wave wave, the first wave wave and the second wave wave of this wave wave. This wave wave will be the first of the wave wave in a wave wave over the world. The wave wave is a natural phenomenon in nature.

## [81% of developers admit to knowingly releasing vulnerable apps – research](https://www.theregister.com/2021/06/25/application_vulnerability_epidemic/)

81 per cent of developers admit to knowingly releasing vulnerable apps. Verizon Mobile Security Index found that 76 per cent experienced pressure to sacrifice mobile security for expediency. Dynatrace research found that 71 per cent are not fully confident that code isn’t free of vulns before going live in production. Osterman Research white paper identifies five key takeaways in exploring the human element as it contributes to cyber risk as far as the software development life-cycle (SDLC) is concerned. Not all vulnerabilities are high risk or exploitable in the production environment.

## [JWT Tokens are NOT safe](https://redislabs.com/blog/json-web-tokens-jwt-are-dangerous-for-user-sessions/)

There are many in-depth articles and videos from SMEs of companies like Okta talking about the potential dangers and inefficiencies of using JWT tokens[1]. These warnings are overshadowed by marketers, YouTubers, bloggers, bloggers and others who knowingly or unknowingly promote it. JWT is one such technology that could create unanticipated consequences. It's the perfect, buzzworthy, and friendly name that’s leading to its popularity. The use case is that the server sends you a session token to the front-end mobile or web application. This token is then stored in the cookie or in the local. application.

## [AuthZ: Scalable permissions system](https://medium.com/building-carta/authz-cartas-highly-scalable-permissions-system-782a7f2c840f)

Carta’s highly scalable permissions system is based on Google Zanzibar. It was built for distributed systems, so it scales well across a cluster. With millions of portfolios and securities on the platform, each user has permission to manage a large amount of roles. With each user’re scoped to access to their own portfolio assets, they can access to a set of shares of a fund that is invested in the company or invests in another fund. At Carta, user has individual permissions for a platform platform platform that has platform platform permissions system.

## [“Host” WordPress on Cloudflare for Free](https://blogabout.dev/how-to-get-static-wordpress-hosting-on-cloudflare-for-free/)

Static WordPress hosting on CloudFlare will give you the fastest possible page load speed for your site – and it’s completely free! It does really well with static content and will deliver your content quickly as there is no server side processing. If you have a simple WordPress site you use to just display content then this will be fine. WordPress is a server-side app that runs on PHP and MySql. In order to “host” your site, you need to run WordPress locally, write your posts and then export your site as a static set of content.

## [How to monitor Kubernetes costs with Kubecost and the Lens IDE](https://blog.kubecost.com/blog/lens-kubecost-extension/)

A Kubecost and Lens integration allows you to also visualize Kubernetes costs directly in the Lens UI. With Lens you can view costs and spend efficiency by namespace, pod, deployment and more. By default, pricing is pulled from public cloud providers, with AWS, Azure, and GCP being supported today. Future releases will be driven by the feedback we receive, so join the community (link below!) and let us know what features you’d like to see. Join the Kubecost Slack community or contact us if you want more!

## [AWS Identity and Access Management (IAM) Best Practices](https://aws.plainenglish.io/aws-identity-and-access-management-iam-best-practices-50a3c3ada02b)

Identity and Access Management frameworks let an organization control who has access to what and also keep track of what each user is doing inside the application. AWS IAM service is a fully-fledged service that allows admin users to control who is authenticated and who is authorized to use AWS resources. These principles are authenticated and authorized using IAM users or IAM roles. The principal should have required permission to perform any action on a resource. If there is at least a single policy denying an action then the whole request will be denied.

## [Testing Compliance with Coding Standards Through SAST](https://nbrites.medium.com/testing-compliance-with-coding-standards-through-sast-ff4f39184503)

Static Application Security Testing (SAST) can help mitigate the appearance of new vulnerabilities. This technique can be applied using tools that scan the code, searching for vulnerabilities while the code is being developed or in the pipeline before it’s deployed. SAST allows vulnerability detection to be an automated process. Integrating SAST in your IDE creates multiple scan possibilities before the code reaches production. It also provides a sense of security in the team, leading to more confidence and speed while developing the codebase.

## [Argo CD: A Tool for Kubernetes DevOps](https://kubesphere.medium.com/argo-cd-a-tool-for-kubernetes-devops-c46f2881edfe)

Argo CD is a GitOps tool on top of Kubernetes continuous delivery (CD) tool. It pulls application configurations from Git Repo and deploys applications in Kubernees clusters. It can process: AMQP, AWS SNS, AWS SQS, GCP PubSub, GitHub, GitLab, HDFS, K8s Resources, Slack, NetApp StorageGrid, Webhooks, Stripe, NSQ, Emitter, Redis, and Azure Events Hub.

## [What is Elastic Load Balancing on AWS?](https://aws.plainenglish.io/what-is-elastic-load-balancing-on-aws-461be2345885)

Elastic Load Balancing (ELB) is a way to automatically distribute incoming traffic to your apps. ELB helps us to handle the incoming load to ensure high availability, automatic scaling and ensure fault tolerance in our apps. There are 4 types of ELB that AWS offers: Application Load Balancer (ALB) NLB can handle millions of requests per second and offers low latency. The most common use case for ALB is for web apps built on the microservices framework can use ALB as the load balancer before incoming traffic reaches your EC2 instances.