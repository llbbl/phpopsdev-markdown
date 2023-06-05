# DevOps / SRE — Top Links Last Week

## Week 12 Issue #19

## [A new Cloudflare Web Application Firewall](https://blog.cloudflare.com/new-cloudflare-waf/)

The Cloudflare Web Application Firewall (WAF) blocks more than 57 billion cyber threats per day. The new WAF blocks 650k blocked HTTP requests per second. The WAF has received many accolades including the highest score for ability to execute in the 2020 Gartner Magic Quadrant for WAF. New WAF brings better rule browsing and configuration - easy one click deploy without losing the power tools: advanced filtering, bulk editing, rule tags and more. A new matching engine - written in Rust and supporting the wirefilter syntax - the same syntax used by custom Firewall Rules. This engine will allow us to have faster managed rule deployments .

## [Should never happen. If it does, call the developers](https://stackoverflow.blog/2021/03/18/creating-a-good-feedback-loop-between-ops-and-devs-using-documentation/)

Running a successful website requires cooperation of operations (ops) and developers (devs) When there is a conflict, antagonisms, or disharmony, the website suffers. You can't force people to cooperate, but you can set up structures and glide-paths that create an environment for cooperation. Management needs to include runbook creation as part of the project. The goal of the feedback loop is to create a mechanism where subject matter experts create runbooks, but both devs and ops are empowered to improve them in ways that reduce the number of escalations .

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Stop losing sleep when developing Kubernetes applications](https://blog.getambassador.io/stop-losing-sleep-when-developing-kubernetes-applications-daf783f43dd0)

Ambassador Service Catalog provides a comprehensive view of all services deployed across your cluster. Telepresence 2 lets you quickly find the necessary information to respond to an incident. Edge Stack 1.12 with Argo Rollouts integration can now plug Edge Stack directly into your continuous integration workflow to do canary rollouts. Service Catalog leverages Kubernetes annotations to provide a simple, platform-neutral way to document this information. The Service Catalog also displays critical human-visible metadata such as the owner of the service .

## [Announcing HashiCorp Vault 1.7](https://www.hashicorp.com/blog/vault-1-7)

HashiCorp Vault 1.7 focuses on improving Vault's core workflows and making key features production-ready to better serve your use cases. Vault provides secrets management, data encryption, and identity management for any application on any infrastructure. In this release, we added an Autopilot feature to Integrated Storage for a more operator-friendly experience, promoted Tokenization via Transform and the Key Management Secret Engine to general availability. This release also includes many additional new features, workflow enhancements, general improvements, and bug fixes .

## [Open source Heroku Like Platform on premises](https://github.com/porter-dev/porter)

Porter is a Kubernetes-powered PaaS that runs in your own cloud provider. Get started on Porter without the overhead of DevOps and fully customize your infra later when you need to. Porter is built on top of a popular Kubernes package manager helm and is compatible with standard Kubernees management tools like kubectl. It is also possible to link up an existing cluster with Porter. Porter provides one-click provisioning of a cluster in a cloud console .

## [Kubernetes Enables DevOps-as-a-Service (DaaS)](https://containerjournal.com/features/kubernetes-enables-devops-as-a-service-daas/)

DaaS is DevOps capabilities made available to users through portals and APIs, on demand. Kubernetes can be used to create on-demand clusters on a container-capable CI worker node. The portability of application and orchestration management across private and public cloud platforms and operating system versions allows developers and DevOps teams to build applications and pipelines without worrying about the underlying infrastructure and operating systems that the applications need to run on. The ability to spin up multiple container instances with different scaling policies makes it a perfect fit for DevOps jobs and activities .

## [How To Use Kubernetes To Run Your Cron Jobs Effectively](https://geshan.com.np/blog/2021/02/kubernetes-cron-job/)

Kubernetes is an open-source container orchestration system for automating computer application deployment, scaling, and management. It is great at managing long-running workloads like web servers or queue consumers. In this post, we will focus on how to run optimally configured cron jobs on KuberNETes. We will also look at how to use Cron Jobs to run web applications and other web applications in the container era for deploying workloads such as web servers and queues .

## [Overcoming the Obstacles to Data Democratization and DataOps](https://thenewstack.io/overcoming-the-obstacles-to-data-democratization-and-dataops/)

The practice of DataOps has emerged with the notion of democratizing data, which has become increasingly popular over the last 10 years. This collaborative approach is supposed to bring people, data, and applications together to ensure a more business-driven focus. Done right, DataOps can accelerate business intelligence and the rate at which companies can extract maximum value from their data. However, well-entrenched siloed systems and risk-averse corporate culture prevent organizations from successfully implementing and realizing the benefits .

## [5 DevOps and Testing Videos to Binge Watch](https://thenewstack.io/5-devops-and-testing-videos-to-binge-watch/)

Software testing has too often been undervalued, left too late to deliver the fast feedback that DevOps demands. When quality testing is strategically woven into release cycles, you deliver better software faster and more frequently. In these Tricentis Virtual Summit videos, tech giants Microsoft and Dell walk us through their DevOps transformations. The videos give us a demonstration of AI-powered testing, and offer a lens into future transformative tools. The speakers are refreshingly human and openly transparent about their challenges, with some intriguing analogies (diving, cycling, magic carpets...) along the way .

## [Optimizing EKS networking for scale](https://engineering.salesforce.com/optimizing-eks-networking-for-scale-1325706c8f6d)

Elastic Kubernetes Service (EKS) is a service under the Amazon Web Services (AWS)umbrella. It significantly reduces the time to deploy, manage, and scale the infrastructure required to run production-scale KuberNetes clusters. With no network overlays, a container, or EC2 instance, can now talk to another without the need for Network Address Translation (NAT) plugin. The plugin consists of two primary components: IPAM, IPAM and CNI plugin, responsible for attaching ENIs to instances .

## [7 Rules for Faster Releases with Containerized CI/CD](https://containerjournal.com/features/7-rules-for-faster-releases-with-containerized-ci-cd/)

Containers are designed to bundle the correct tool, version and other execution assets in a package. This makes it easy to build applications using a given set of tools and scripts, because the package is already prepared and ready to run. Containers make it easier for software engineers to continuously build and deploy applications and, by orchestrating container deployment, software teams can achieve replicable, continuous clusters of containers. By following these best practice rules, teams can use containers to improve their software delivery environment .

## [DevOps for an Application Developer: CodeDeploy](https://havimaki.medium.com/devops-for-an-application-developer-codedeploy-f5ba608fa853)

This article will focus on the CI/CD pipeline, and how CodeDeploy as a service works. CodeDeploy is a service in AWS that automates deploying software applications. It's valuable to understand the services that are involved, even at a higher level. It can be easy for software application developers to focus solely on app development, without ever understanding the underlying infrastructure the application is actually built upon. Each row of data defines a deployment, each with a duration, a status, an error code (null if no errors), a start time and an end time .

## [How to Deploy Multiple Containers with Docker and Amazon Elastic Beanstalk](https://predictivehacks.com/how-to-deploy-multiple-containers-using-docker-compose-and-amazon-elastic-beanstalks-multi-container/)

An example of how you can work with multiple containers, how to share volumes and how to deploy multiple containers locally suing the docker-compose and the Amazon Elastic Beanstalk's multi container option. For this scenario, we assume that we are dealing with 2 APIs and we want to share data across APIs containers using anonymous volume. We will show how we can pre-seed a volume with data and share it. This can be accomplished by using externally created named volumes along with what we call a docker .compose file .

## [5 Minute DevOps: The Metrics are Lying](https://bdfinst.medium.com/5-minute-devops-the-metrics-are-lying-5a45446c916)

"DORA Metrics" are becoming very popular in the industry and for good reason; they are good indicators for the health of a delivery process. High-performing teams can deliver changes daily with pipeline cycle times of less than an hour. They have an MTTR measured in minutes and less than 15% of their changes require remediation. However, they are trailing indicators for poor health, not indicators everything is going well. Correlation is not causation. We can push teams to improve those metrics and get short-term wins that will get people promoted .

## [5 common pitfalls in Infrastructure as Code](https://piotrzan.medium.com/5-common-pitfalls-in-infrastructure-as-code-3637ab6b02e0)

Infrastructure as Code (IaC) is a common pattern where virtualized infrastructure and auxiliary services can be managed using configuration expressed in almost any language, usually hosted in a source code repository. IaC enables automated, repeatable and reliable creation and maintenance of any virtualized. infrastructure can be created and destroyed within minutes. It can be scaled up and down depending on load and usage patterns. There are also cloud vendor specific tools and standards to get you started with IAC .

## [Automate Static Site Deployment to AWS](https://yasaminkamali.medium.com/automate-static-site-deployment-to-aws-c6ea81e57824)

AWS offers a simple solution for this: CodePipeline. The goal is so that every time you push changes to your master branch, the S3 bucket from which the site is being hosted gets updated as well. If you're using CloudFront (to reduce latency, to Gzip, etc.) then you'll need to update that too. We need to set up an IAM role that will give permissions to Lambda to perform actions on S3, Cloudfront and CloudWatch .

## [Load Balancers: A deep dive](https://shreyasmn.medium.com/load-balancers-a-deep-dive-7d17067f5ff6)

Traditional load balancing solutions rely on proprietary hardware housed in a data center. Software‑based load balancers can deliver the performance and reliability benefits of hardware‑based solutions at a much lower cost. Layer 4 load balancing has become obsolete as CPU and memory have become cheap enough to overlook the small performance benefits in layer 4. Private Load Balancers have private IP assigned from local private network subnet. This type of load balancer is usually employed to handle traffic with in a private network(VCN, Private cloud), between private networks(between private networks) and the network traffic from on-premise cloud .

## [Helm & Kubernetes | Create Helm Charts and how to push them](https://manserpatrice.medium.com/helm-kubernetes-create-helm-charts-and-how-to-push-them-c741edf11f1e)

Helm is a package manager for Kubernetes that allows developers and operators to more easily package, configure, and deploy applications. Helm automatically applies every file that is in its "templates" directory. Helm has a Values.yaml file, in which you can store all your data required for defining your K8s. With Helm you can prevent copy pasting the exact same name 10 times in different resources. We will take a look at an example later on, so just keep reading .

## [Vercel Serverless Functions vs. Cloudflare Workers](https://moiva.io/blog/vercel-serverless-functions-vs-cloudflare-workers)

Vercel provides a good solid solution for Serverless Functions and makes the process of their creation seamless and hassle-free. Cloudflare Workers offer more functionality out-of-the-box (e.g. key-value data store, CRON) and look more mature and sophisticated. Vercel doesn't replicate Functions across their Network in Free and Pro accounts - Functions can be deployed to one particular region only. It's important to note that Functions are executed on every request, even if the response has been cached .

## [New Terraform Tutorial: Use Application Load Balancers for Blue-Green and Canary Deployments](https://www.hashicorp.com/blog/terraform-tutorial-application-load-balancers-for-blue-green-and-canary-d)

Use Application Load Balancers for Blue-Green and Canary Deployments. Use a combination of blue-green, canary, and rolling deployments to incrementally promote a new application version via HashiCorp Terraform feature toggles and an AWS application load balancer (ALB) ALB automatically distributes incoming traffic to the appropriate service at the application layer. ALBs are different from classic load balancers, which only route traffic to EC2 instances across multiple availability zones. You can define an ALB's listeners (rules) and target groups to dynamically route. These rules enable you to run canary tests on and incrementally. promote the green environment .