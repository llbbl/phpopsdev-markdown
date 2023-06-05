# DevOps / SRE - Top Links Last Week

## Week 7 - Issue #66

    

## [How to optimize the security, size and build speed of Docker images](https://www.augmentedmind.de/2022/02/20/optimize-docker-image-security/)

This article introduces 12 tips to optimize your Docker image security. Each tip explains the underlying attack vector and one or more mitigation approaches. Recommendations include avoiding leaking of build secrets, running as a non-root user, or how to use the most recent dependencies and updates. Multi-stage builds (official docs) have many different use cases, e.g., speeding up your image build or reducing the image size. The problem originates from the fact that Docker images are built layer by layer in a purely additive way.

  

## [On Demand CI/CD with Serverless Tekton](https://www.anadimisra.com/post/on-demand-ci-cd-with-serverless-tekton)

The reason behind Fargate is the ease of server-less managing our CI/CD pipelines without managing the infrastructure for it. I'llI'll share my experience of getting a Serverless infrastructure for Tekton up and running quickly via Terraform in this post. The following steps are to create a Terraform profile for running Tekton, Tekton Dashboard, and Tekton Triggers in the `tekton-pipelines` namespace. Then, declare a security group with Ingress rules for each subnet CIDR to restrict the VPC running EKS.

  

## [Joel Spolsky on Structuring the Web with the Block Protocol](https://thenewstack.io/joel-spolsky-on-structuring-the-web-with-the-block-protocol/)

Block Protocol is a proposed specification to combine data displayed on the Web with its structure and type. It aims to make it easier to create and share data across platforms and make that value more readily available to abstract and use in various ways. The Block Protocol has expressed interest in working with WordPress, which provides the content management system that powers a vast swath of the Web. The Block Protocol already works with the Project Gutenberg editor, used by WordPress, Notion, and other web editing tools.

  

## [The Triumph and Tragedy of .env Files](https://blog.doppler.com/the-triumph-and-tragedy-of-env-files)

Environment.env files were a good idea in theory but created more problems than solved. The security risks and impact on developer productivity are only fully realized. Environment variables are supported in every operating system and every programming language. A simple format (restricted to be valid Linux shell syntax) enabled.env (dotenv) file parsing libraries to be created for every primary programming language such as Python dotenv and Node dotenv.

  

## [How to Make the Most of Kubernetes Environment Variables](https://thenewstack.io/how-to-make-the-most-of-kubernetes-environment-variables/)

In traditional systems, environment variables play an essential role but are not always crucial. Some applications make more use of environment variables than others. However, when it comes to Kubernetes, environment variables are more important than you think. When developing microservices to provide configuration to your Docker containers as environment variables whenever possible, it's generally good practice. This way, you can make your Docker image more generic and possibly reuse the same image for different purposes. The most straightforward option is to specify environment variables directly in your deployment.

  

—

  

## [Deploy React App on GitHub Pages Automatically](https://betterprogramming.pub/deploy-react-app-on-github-pages-automatically-761090d266ba)

GitHub Pages is free to host static websites such as wikis, documentation sites, or resumes. It provides free hosting for static sites. In addition, GitHub Pages allows you to create a new react app with the npx create-react-app helloworld command and then install the jest package with the npm install jest command for running tests. After submitting your page, you will receive a subdomain URL such as username username.io/repository. You can change the URL to anything you like.

  

## [We Can Do Better Failure Detection in Serverless Applications](https://aws.plainenglish.io/we-can-do-better-failure-detection-in-serverless-applications-aaa6bb98c89)

There are many reasons why you shouldn't use classical error-reporting tools in AWS Lambda. Error-handling libraries in the code are blind to Lambda-specific failures, such as timeouts, wrongly configured packages, and out-of-memory failures. The ability to detect failures across all functions and connect them with specific invocations, view logs and pull X-ray traces significantly reduces the meantime to resolution in failure scenarios. Fortunately, the information-emitting aspect is well implemented in AWS, and serverless users have an opportunity to get visibility without specifically implementing extra stuff in their code.

  

## [How to create a dynamic launch script with Terraform](https://faun.pub/how-to-create-a-dynamic-launch-script-with-terraform-34c53f0fe2ba)

Terraform is a widely used open-source "Infrastructure as Code" automation tool. Terraform includes provider configuration for AWS, Azure, GCP, and Kubernetes clusters. This tutorial will demonstrate using variables to parameterize a configuration and build AWS EC2 instance launch scripts.

  

## [Change Encryption Type of All Objects in S3 Bucket](https://aws.plainenglish.io/change-encryption-type-of-all-objects-in-s3-bucket-4002070a1fb7)

AWS S3 provides no direct way to change the encryption type of all objects in a bucket. Changing the default bucket encryption only changes the encryption of new things uploaded. All existing objects remain with the old encryption setting. We assume versioning is switched off, and I recommend running first with an additional arg of --dryrun flag at the end of your command so you can see what will happen first before you do a real run. These can save a lot in cutting costs by cutting a lot by cutting costs in using SSE-KMS keys.

  

## [Why Do We Need GraphQL?](https://betterprogramming.pub/why-do-we-need-graphql-43ea26d0efc4)

GraphQL is a query language for APIs and a runtime for fulfilling those queries with existing data. It is transport-independent but is usually provided over HTTP. Facebook invented GraphQL in 2012 to improve how the server sent data to the client. GraphQL supports many different languages, including C#, Elixir, Erlang, and many other languages. The future of the internet has always been about delivering data quickly from the server to the client. Fast applications make users happy and bring more money to the providers.

  

## [How to manage software developers without micromanaging](https://www.infoworld.com/article/3649773/how-to-manage-software-developers-without-micromanaging.html)

Software developers bristle at the idea of being closely managed. But there's also the practical reality that organizations require methods to recognize whether agile teams and software developers meet or exceed performance, development, and business objectives. What follows are seven recommended practices that align with principles in agile, scrum, DevOps, and the software development lifecycle.  

  

## [Tools for Querying Logs with SQL](https://arctype.com/blog/logging-tools/)

Logging is vital for any software project, from development to ongoing management. Maintenance logs are crucial for determining the state of an application and monitoring and troubleshooting purposes. These days, logging is usually embedded throughout an application, from simple user access logs to database activity, error logs, and network flow logs. LogTail is a managed service that requires users to create an account on the platform. We will be querying system logs from an Nginx installation on an ubuntu server for the following examples.

  

  

## [A pentester gets root - step by step example](https://kaizoku.dev/htb-devoops)

DevOps is a Medium-rated retired machine on HackTheBox, and also appears on the TJ Null list for OSCP prep. We begin with a basic TCP/ UDP ports scan and service enumeration, version detection, and script scan on the open TCP ports. Next, we can search for any available exploits using searchsploit. Finally, we have a dump of new info.

  

## [Plaid is an evil nightmare product from Security Hell](https://drewdevault.com/2022/02/19/Plaid-is-an-evil-nightmare-product.html)

Plaid is a business that has built a widget that can be embedded in any of their customer's websites which allows their customers to configure integrations with a list of third-party service providers. To facilitate this, Plaid pops up a widget on their customer's domain that asks the end-user to type in their username and password for the service provider. This is done without the third party's permission, presumably through a browser emulator and a provider-specific munging shim.

  

## [The Two Things Seniors Look for When Assessing New Tech](https://betterprogramming.pub/the-two-things-seniors-look-for-when-assessing-new-tech-e88e951cb540?source=rss----d0b105d10f0a---4)

The Two Things Seniors Look for When Assessing New Tech: Do We Need This? Is this the best solution to our problem? Does your company already have the capability this new technology offers? Do you need this? Will it scale? Will it handle all of your production load if it's a new piece of infrastructure? Have any large companies used it? Are there any blog posts that aren't apparent marketing content? These are the hallmarks of senior engineering.

  

  

  

## [3 Tips To Become A Better DevOps Engineer in 2022](https://faun.pub/3-tips-to-become-a-better-devops-engineer-in-2022-6abfa75ebe4a)

To become a better DevOps, you need to have an in-depth knowledge of operating systems. You can solve problems and create bash scripts much more smartly if you can handle the system well. It would be best if you kept in touch with developers to debug what caused the deployment issues all the time. Get Certified Certified Kubernetes Administrator (CKA) and AWS Solution Architect also. It is also true to without skill certifications, but if you both, then there is a great chance you can land your dream job easily.

  

## [Inside Docker: One Nginx But Different PHP Versions Based on Your Hostname](https://betterprogramming.pub/inside-docker-one-nginx-but-different-php-versions-based-on-your-hostname-2d4aca6654bd)

Inside Docker: One Nginx But Different PHP Versions Based on Your Hostname. The goal is to keep both versions running simultaneously, not replacing the existing config. Because nginx is running inside Docker, we have to tell nginx which resolver nginx should use to get the correct IP from our mapping hostnames: PHP-fpm7 and PHP-Fpm8. Although with this setup, nginx knows which to use based on our domain name, we want to extend our docker-compose.yml.

  

## [Basics Of Consistency And Locking In Databases](https://recepinanc.com/Basics-of-Consistency-and-Locking-in-Databases/)

A database transaction is a unit of work performed in a database management system. Consistency ensures data integrity is intact at all times. Different isolation levels bring different levels of consistency. Locking is all about achieving the promised level of consistency. Each isolation level uses other locking methods based on their promise. Choosing an appropriate isolation level for our business is a critical decision. Let'sLet's learn about consistency, transaction isolation levels, and locking in InnoDB.

  

## [What is Protobuf and Why You Should Use It?](https://betterprogramming.pub/what-is-protobuf-and-why-you-should-use-it-14d52646f2a7)

Protoc (Proto Compiler) uses Protobuf to serialize and deserialize ProtoBuf objects. Proto files are independent of both the platform and languages you are using. The Protocol Compiler generates a user_pb2.py file in $DST_DIR. The content of the generated classes is barely human-readable, but that doesn't matter. All you need to care about is importing and applying these classes in your application. Protoc uses Protoc to seriality and serializes data, giving ProtoBuf a definite Scheme.

  

## [The End of Unix Time: What Will Happen?](https://betterprogramming.pub/the-end-of-unix-time-what-will-happen-1b1a25ec1c20)

Unix-like systems agree to have their epoch on 1 January 1970, at 0:00:00 UTC. This date has been chosen arbitrarily as the reference instant to count time. The most imminent overflow date is the 32-bit signed integer-based systems'', scheduled for 19 January 2038, at 03:14:07 UTC. One second later, computers will fall back to 13 December 1901, at 20:45:52 UTC. The behavior is due to an integer overflow.