# DevOps / SRE — Top Links Last Week

## Week 15 Issue #22

## [PHP in 2021](https://stitcher.io/blog/php-in-2021)

PHP 8.1 will be released somewhere by the end of 2021. Composer has had a new major major major release in October. PHP is getting coroutines and fibers in the next version of the language. The community is growing, and there's no end in sight in sight of everything that's been added to PHP in recent years. The number of packages available in PHP has doubled in the last year, and we're looking at ±60 million daily downloads. It's a fast and reliable language, used to build large applications at scale.

## [Introduction to Containers with AWS](https://dev.to/aws-builders/introduction-to-containers-with-aws-og4)

Containerization is changing the way businesses develop and deploy applications in cloud environments. Containers decompose applications into small, manageable packages containing everything the application needs to run: code, configuration files, interfaces, and dependencies. Amazon Elastic Container Service (ECS) with AWS Fargate is the only option to run Docker containers without running EC2 instances on AWS. K8s (Kubernetes) is an open-source container orchestration solution that runs Google Cloudises, or even on your local machine.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [1Password Secrets Automation](https://blog.1password.com/introducing-secrets-automation/)

1Password has been keeping secrets safe for humans like you and me: our passwords, our credit cards, our personal documents. With the addition of Secrets Automation, 1Password can now protect all of your company’s secrets in one place. The security of 1Password and infrastructure secrets are fully encrypted, using the same security that makes 1Password the most trusted enterprise password manager. With all of the secrets in a single place, you gain complete visibility and auditability in a way that you can’t when secrets are spread out across multiple services.

## [Docker for Local Development](https://medium.com/geekculture/docker-for-local-development-1caf04b84e94)

Docker is a very common thing and almost every vacancy has the requirement to have experience with Docker. In this article, we’ll walk through the basic use cases of Docker in the local development process. With Docker-compose you can run specific version of any service, it’s very useful feature, if for example one of your projects uses MongoDB version 3.6 and another uses version 4.2.6. There are several points which I want to emphasize:service versions must be specified explicitly in docker tags. Minor and patch versions matter!

## [The Decline of Heroku](https://www.infoworld.com/article/3614210/the-decline-of-heroku.html)

Heroku has long been held up as the gold-standard platform as a service (PaaS) for software developers to easily deploy their code without having to worry about the underlying infrastructure. Heroku’s architectural limitations and the high cost of running a business on the platform have historically hindered its ability to truly scale beyond a core set of web 2.0 customers, but there is still hope that Heroku is setting itself up for a glorious second act. “It had a good run and a huge influence, but nothing lasts forever” said James Governor, a founder of the developer-focused analyst firm RedMonk.

## [Leveling Up Container Security with Security-as-Code](https://containerjournal.com/features/leveling-up-container-security-with-security-as-code/)

As more organizations adopt microservices, they’re also adopting infrastructure-as-code (IaC) to streamline continuous delivery. Some believe security policies should be described and embedded within the CI/CD process. Tzury Bar Yochay, CTO and co-founder of Reblaze, and Curiefense maintainer, explores the security threats facing today’s container-based ecosystems. For containers, threats like insecure defaults, misconfigurations and over-permissive states are common existing vulnerabilities.

## [A CTO’s guide to modern tech stack](https://blog.runx.dev/a-ctos-guide-to-modern-tech-stack-a497d1b56de0)

With the advent of DevOps and “you build it, you own it”, the tech stack has evolved a lot for the modern startup. There are hundreds of dev tools launched in the last decade which have completely changed how developers manage their workloads. We evaluated this landscape very thoroughly at RunX and here is our opinionated guide. You can’t go wrong with any of the 3 big clouds (AWS, Azure, GCP). All of them have the full feature set needed by a company of any scale. Microservices require a more DevOps investment upfront to set all the right tooling and visibility.

## [Section, the Developer-Focused Content Delivery Network](https://thenewstack.io/section-the-developer-focused-content-delivery-network/)

Section is a developer-centric platform for moving parts of the application closer to the edge. The company provides what it calls a Point of Presence (POP) that lets developers see how code will work before it hits production. The global Content Delivery Network (CDN) market will grow from $14.4 billion in 2020 to $27.9 billion in 2025, says CIO Stewart McGrath. Section provides Docker-powered Kubernetes clusters that it calls edge modules, as long as developers can bring their own software into a container.

## [Building React Apps with Jenkins using npm, Snyk and Ansible](https://faun.pub/building-react-apps-with-jenkins-using-npm-snyk-and-ansible-80f666edf8d4?source=rss----10d1a7495d39---4)

This article takes you through building a simple react static app using Jenkins and Ansible. The Jenkins infrastructure is built inside the AKS cluster and all are stages inside the Jenkins pipelines are dynamically provisioned using containers. In the first stage, the source code will be scanned by Snyk tool which checks for any security vulnerability in the library used in the app. The second stage is to build the react app within a Node.js container and published binaries would be zipped and stored as an artifact within Jenkins. The last stage, ansible playbook will be executed inside a container with ansible installed and the deploys the react package to azure static apps.

## [How To Create a Universal Backend With Symfony](https://betterprogramming.pub/graphql-api-symphony-mongodb-c866a79fdf48)

Using Symfony and MongoDB, you can create a headless CMS from scratch. The output of this project is a working application that can be installed as a composer package. The resulting architecture is the following: the universal backend architecture. The CRUD service is responsible for reading and writing data to the collection databases. We will talk about the authentication layer and the validation layer in this article. The full source code is available at the end of this article, and you can use it as a base for implementing your applications.

## [The “never” Return Type for PHP](https://betterprogramming.pub/the-never-return-type-for-php-802fbe2fa303)

The new never keyword will allow you to mark a function as "never" returning. The function will stop the normal script execution by either throwing an exception, looping forever, or simply telling PHP to stop with die() PHP 8.1 is planned for the end of the year, and in addition to Fibers, the new never function will be added to the language's Fibers. The never keyword is not a big addition, but it's a welcome one. The new feature is called never.

## [Build a highly available Node.js application using Docker, NGINX and AWS ELB](https://faun.pub/build-a-highly-available-node-js-application-using-docker-nginx-and-aws-elb-d3c85f7e5e5f)

This is the architecture that we’re aiming for. Multi-level load balancers managed by AWS and NGINX. This will help us maintain multiple ports on each EC2 instance for our node apps. The ports are provided to the express app via the PORT environment variable. We will feed these port values via Docker. This is a very simple task thanks to docker-compose. We’ll launch the 2 instances separately, since we want these two instances in different availability zones.

## [Automating Endpoint Protection with Ansible](https://www.ansible.com/blog/automating-endpoint-protection-with-ansible)

The Red Hat Ansible Automation Platform caters to the growing importance of security with Ansible security automation. An endpoint protection platform (EPP) is a solution deployed on endpoint devices to prevent file-based malware attacks, detect malicious activity, and provide the investigation and remediation capabilities needed to respond to dynamic security incidents and alerts. The most recent addition to our security automation initiative was announced at AnsibleFest 2020: the extension to support endpoint protection use cases. Automated processes and workflows simplify and accelerate shared processes, like investigation & response.

## [A practical guide to writing secure Dockerfiles](https://medium.com/miro-engineering/a-practical-guide-to-writing-secure-dockerfiles-bf561224dd80)

A practical guide to writing secure Dockerfiles is based on a presentation at the recent Container Day conference. The talk is available online as a video recording. We are going to learn best practices to write Dockerfiles using BuildKit features, linters, and other tools. We’ll also touch on leveraging OPA (Open Policy Agent) to write custom policies. The Dockerfile is a text document that contains all the commands a user can call on the command line to assemble an image. The instructions to build a Dockerfile are stored in files called Dockerfile.

## [Terraform Best Practices — Testing your code](https://jackwesleyroper.medium.com/terraform-best-practices-testing-your-code-f25053b06c4c)

This is the last in the series which focuses on point 9 in the list, ‘Test your code’ This article aims to outline options for each type of testing. It’s hard to know what is considered ‘best practice’ in a number of areas. A combination of tools can be used to perform different types of testing to provide wider code coverage. I’ll aim to delve deeper into Terratest and TFLint and include examples in future articles.

## [Now reference latest AWS Systems Manager parameter values in AWS CloudFormation templates without specifying parameter versions](https://aws.amazon.com/about-aws/whats-new/2021/04/now-reference-latest-aws-systems-manager-parameter-values-in-aws-cloudformation-templates-without-specifying-parameter-versions/)

CloudFormation enables developers to model, provision, and manage their cloud environment in a safe, repeatable, and predictable way. Parameter Store allows developers to update parameter values, which creates new parameter versions. This new enhancement provides the convenience so that you do not have to specify parameter versions in the template whenever you update parameters in Parameter. This feature is available in all AWS regions where Cloudformation and Parameter store are available. To learn more, visit CloudFirmation documentation.

## [Languages and DevOps: Recommendations](https://devops.com/languages-and-devops-recommendations/)

"Use the right tool for the job" is a much more complex question in an existing IT environment than it is in woodworking. Assess the language with regard to how well it actually does the job you need to do. Does the tool do what you want, or will you be working around faults to get there? If you choose ASP.NET today, will it be a solid choice tomorrow? Is the developer base mentioned in the first point, above, to still be around?

## [Docker Desktop for Mac (Apple Silicon)](https://www.docker.com/blog/released-docker-desktop-for-mac-apple-silicon/)

Docker Desktop for Mac [Apple Silicon] is now available for general availability. It's the latest version of Docker Desktop to be available on Apple's new M1 chip. We are very grateful that we have such an active and supportive community, and that you have shared both your excitement and feedback with us. Join us for DockerCon LIVE 2021 on Thursday, May 27. Register today at [https://dockr.ly/2PSJ7vn](https://dockr.ly/2PSJ7vn). Register to learn about how to go from code to cloud fast.

## [Defend the Core: Kubernetes Security at Every Layer](https://thenewstack.io/defend-the-core-kubernetes-security-at-every-layer/)

Jimmy Mesta is currently the Head of Security Research at Fastly (formerly Signal Sciences), and a veteran application and infrastructure security leader with 15 years of experience. He has spent time on both the offensive and defensive side of the industry, working to build modern, developer-friendly security solutions. In this article, we’ll talk about security best practices for every layer of the container stack. At the kernel level, you can:Review allowed system calls and remove any that are unnecessary or unwanted. Use container sandboxing like gVisor or Kata Containers.

## [Observability Vs. Monitoring](https://somakesara.medium.com/observability-vs-monitoring-95a91646ff7c)

Monitoring is a reactive process that entails tracking standard metrics and resolving known issues. The process of Observability is proactive. It aids in the resolution of both known and unknown problems. Monitoring enables tracking system errors, usage, outages, and security attacks and alerting users as designed. It is essential because it provides detailed information about complex, distributed, and cloud-native applications. The cloud engineer's terms, Observability helps comprehend systems through the lens of the well-architected framework's pillars.

## [Why And How You Should Use Cloudflare Pages](https://medium.com/dev-genius/why-and-how-you-should-use-cloudflare-pages-4e3a6242bde6)

The first step is to sign up to Cloudflare Pages and connect to a GitHub account. The next step is setting up a custom domain to use for your first site. The process differs depending on where you bought your domain but is generally similar to Google Domains. Deployment will take a few minutes after which your site should be accessible through the “Visit site” link. For a bare-bones HTML page, you can pretty much leave everything empty. The build settings will differ based on your project based on what type of code you use.

## [Defense in Depth: The First Step to Security Certainty](https://thenewstack.io/defense-in-depth-the-first-step-to-security-certainty/)

Allen McNaughton Allen is the Director of Technical Sales, Public Sector at InfoBlox. He has over 20 years of experience in developing security solutions for service providers, public sector and enterprise customers. He says network security needs what’s known as “defense in depth” — a strategy that leverages different security solutions to provide robust and comprehensive security against unauthorized intruders. Without this kind of visibility, we have no idea how large the attack surface even is, he says.