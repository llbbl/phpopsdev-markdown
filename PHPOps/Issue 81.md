# DevOps / SRE - Top Links Last Week

## Week 22 - Issue #81

  

26 links

  

## [Airbnb Moves from Webpack to Metro, Enjoys Shorter Build Times](https://thenewstack.io/airbnb-moves-from-webpack-to-metro-enjoys-shorter-build-times/)

Airbnb migrated its JavaScript code bundler from Webpack to Metro in 2018. Even the slowest production build, one compiling 49,000 modules (JavaScript files), is now 55% faster — down to 13.8 minutes from 30.5 minutes with Webpack. Airbnb's own Page Performance Scores also improved (~1%) with those pages built with Metro. The migration took place in two phases: the Metro development server as the slow Webpack development server was the source of significant development productivity costs. Airbnb engineers created a Metro server with custom endpoints to handle building dependency graphs.

  

  

## [Portainer, a GUI for Docker Management](https://thenewstack.io/an-introduction-to-portainer-a-gui-for-docker-management/)

Portainer is a universal container management tool that can work with both Docker and Kubernetes to make the deployment and management of containerized applications and services easier and more efficient. Portainer enjoys over 650,000 users and 21,700 GitHub stars, so it's widely used and popular. It makes it an obvious management platform for admins and developers of all skill levels. Instead of having to build a complex manifest to include every aspect of the container, Portainer makes it easier to use the command line.

  

## [DevOps: The Many Facets of Infrastructure](https://faun.pub/devops-the-many-facets-of-infrastructure-5664e433934e)

The Many Facets of Infrastructure are the many different services, processes, or considerations that go into running a single service in a thorough manner. Failing to understand the big picture and future direction of these facets can put availability, security, and velocity at risk. The goal of this blog post is to capture this exhaustive list of software infrastructure facets in order to help people identify gaps in their knowledge or infrastructure and make improvements. If you are in any field that is DevOps/SRE/Security/Developer adjacent, there is content in this post that is meant for you.

  

## [The Linux cheat command](https://opensource.com/article/22/6/linux-cheat-command)

The Linux cheat command is a utility to search for and display example tasks you might do with a Linux command. Cheatsheets are just plain text files containing common commands. The main collection of cheat sheets is available at Github.com/cheat/cheatsheet. The Bash version of cheat downloads cheats sheets for you when you first run the command. The Go version uses a Yconfig file to define where each collection is located. The bash version uses the --fetch option to download the Bash version and install the Go version.

  

## [Contrast Security Adds Free Code-Scanning Tool](https://devops.com/contrast-security-adds-free-code-scanning-tool/)

Contrast Security has made available a free security tool that enables developers to scan their code using the same core engine used by the cybersecurity team within their organization. Contrast Security's CodeSec is not just another freemium offering for developers that is a hobbled version of a commercial offering. It provides access to a command-line interface that makes it easier to integrate within the context of a DevOps workflow. Every vulnerability discovered by an application development team is one less for cybersecurity teams to ask developers to fix in a production environment.

  

—

  

  

## [IAM Roles and DynamoDB Basics](https://aws.plainenglish.io/iam-roles-and-dynamodb-basics-1db7c097f813)

DynamoDB is a serverless and easy-to-use AWS database system that supports data structures and key-valued cloud services. It can auto-scale, has in-memory caching, offers built-in security, and back up and restore options. It can handle more than 10 trillion requests per day and support peaks of more than 20 million requests per second. The first thing we'll do is create a DynamoDB table. Next, we will make an IAM role to give our EC2 instance read access to our table.

  

## [What is Service Discovery in Microservices?](https://dineshchandgr.medium.com/what-is-service-discovery-in-microservices-15a2333bc1db)

Service Discovery is a design pattern by which the Client or the API Gateways discover the network info (IP address and port) of the Server through an important component called Service Registry or Discovery Server. The Service Registry keeps track of the entire individual microservices in the architecture and stores the IP address/port of those in its database. Every time a service scales up or down, it will send a heartbeat to the discovery service and update its database accordingly. The discovery server / Registry also groups the instances of each service accordingly.

  

## [Ingress in Kubernetes](https://blog.devgenius.io/ingress-in-kubernetes-67a4b843ea4e)

Ingress is an abstraction over nginx/haproxy/traefik/Istio, basically, load balancing solutions. This is not created by default, though, when a cluster is created. It is a combination of four K8s objects: Deployment, Deployment, a LoadBalancer service, if required, a separate DB pod, etc. The Ingress controller has additional intelligence to detect any new Ingress resource, pick their configurations and apply them on the nginx.conf file.

  

## [Gitlab CI for Node Testing and Coverage](https://betterprogramming.pub/gitlab-ci-for-node-testing-and-coverage-d8f8c82f8c1e)

Gitlab is a popular open-source version control system that is free to use and can be built on an intranet. Gitlab has been integrating CI/CD pipelines into Gitlab for a long time. This article will focus on how to make Node testing reports more presentable in Gitlab. We often use NYC and mocha together to build testing reports for Node, but such a combination needs a little twist. The key to all of this is in the npm run test, i.junit-spec.

  

## [Dashy – A self-hosted homepage for your homelab](https://github.com/Lissy93/dashy)

Dashy helps you organize your self-hosted services by making them accessible from a single place. Real-time status monitoring for each of your apps/links. Instant search by name, domain, or tags + customizable hotkeys & keyboard shortcuts. Multi-language support, with 10+ human-translated languages and more on the way. Easy to set up with Docker, on bare metal, or with 1-Click cloud deployment. 100% free and open-source software.

  

## [AWS CDK + Github actions CICD + Lambda backend](https://aws.plainenglish.io/aws-cdk-github-actions-cicd-lambda-backend-bbf369dc1638)

AWS CDK + Github actions CICD + Lambda backend are easy to set up. The code will be managed separately using Git/Git and CDK. Backend development with a Lambda function (I am using Fastify API code) and infrastructure on AWS for the above services. Manage the whole code (function + infrastructure ) using Git and Github actions for CICCD. Use CDK to configure infrastructure. AWS. CDK can be used globally or globally using npx to run CDK locally.

  

## [Building a Terraform Provider-Part-III— Resource Setup](https://allanjohn909.medium.com/building-a-terraform-provider-part-iii-resource-creation-db5b6eeb559e)

Building a Terraform Provider-Part-III— Resource Creation. This is a continuation of Part II. We have prepared a client and configured a Provider. We are looking only at Resources and how to create a resource. To add Import, we need to first fix the Read function. We will come back to it later. We have a boilerplate for a Resource. This resource is returned with a Context-based on what the context is. And each context has its own functions.

  

## [I wrote my first CI pipeline with dagger](https://benoitgoujon.com/post/dagger/)

Dagger is a new way to create CI/CD pipelines. It provides the following benefits: unifying dev and CI environments. In reusable packages, the aim is to favor the developer's velocity. CUE is a configuration language that is a superset of YAML and JSON. The code stays the same whether you are running your CI or CD pipelines with GitHub Actions, GitLab CI, or any other CI runner. Dagger leverages a language called CUE to configure the actions.

  

## [Fallacies of distributed systems](https://architecturenotes.co/fallacies-of-distributed-systems/)

Fallacies of distributed systems are a set of assertions made by L Peter Deutsch and others at Sun Microsystems describing false assumptions that programmers new to distributed applications invariably make. These eight fallacies are generally ignored or downplayed when discussing system design. We are hoping to build the largest system design community on the internet! We would love for you to join us. You can find us here on Twitter. We would like to see us on the site. We hope to be the largest design community.

  

## [Fully Automated NextJS Builds/Deployments (GitHub, AWS ECR, Fargate Service, ECS)- Part 3/4](https://blog.ricofritzsche.de/fully-automated-nextjs-builds-deployments-github-aws-ecr-fargate-service-ecs-part-3-4-1b200b961502)

Terraform is an "Infrastructure as Code" (IAC for short) tool. Terraform allows you to define, deploy and update infrastructure with code. Fargate provides the ability to run containers serverless on AWS. In essence, we are effectively at the container level and don't have to set up or configure anything further down the infrastructure stack. We are now ready to get our app running on AWS as a container. We will use Terraform for automated resource provisioning.

  

## [Create a Simple Kubernetes Custom Resource and CRD with kubectl](https://able8.medium.com/create-a-simple-kubernetes-custom-resource-and-crd-with-kubectl-f2a73e166f5d)

A Custom Resource is an object that extends the Kubernetes API or allows you to introduce your own API into a cluster. CRDs allows users to create new types of custom resources without adding another API server. Custom resources can appear and disappear in a running cluster through dynamic registration. Users can create and access custom resources using kubectl just as they do for built-in resources like Pods. The CRD defines the name and structure of your custom resource that you want to add to the cluster.

  

## [Architecture Of Kubernetes](https://medium.com/@jaydeepvpatil225/architecture-of-kubernetes-d17afd3428db)

Kubernetes is the Container Management Orchestration Tool which is developed by Google for managing their own microservices across the different clusters. Google developed an internal system called Borg and later on, named Omega, which they use to Orchestrate the Data Center. In 2014, Google introduced the tool as an Open Source, and it is written in Golang language. It is a tool that automates container deployment, load balancing, and auto-scaling. It will manage all the containers which are running in different environments.

  

  

  

## [Kubernetes – An Introduction to Sidecars](https://pauldally.medium.com/kubernetes-an-introduction-to-sidecars-21d99fbd7de3)

A sidecar container is a container that is co-located with and tightly coupled to your primary application container. The sidecar can also share resources (like network and storage) with the primary container(s). The functionality of a sidecar should be inter-dependent with the application containers — if it isn't, you would probably be better served to simply deploy the container in a different Pod. The Dockerfile is built as follows: Docker builds --progress=plain --no-cache -t HelloWorld-webserver:1.0.

  

## [Streamlining Dockerfile configuration in PHP](https://medium.com/@gvytenis/streamlining-dockerfile-configuration-in-php-90c2bd763556)

A simple Dockerfile configuration in Symfony/Laravel project can streamline Dockerfile development and maintainability. This simple configuration also works for plain PHP projects as well as Laravel. Publishing the image to DockerHub and pulling it via docker-compose.yml directly from it is as simple as a few commands. You can simply ignore building the image locally, and it will be pulled from DockerHub. This way, you avoid the Dockerfile duplication across projects and make it easy to maintain.

  

## [Dockerizing Your FastAPI Project](https://betterprogramming.pub/dockerizing-your-fastapi-project-d8bb13ad6335)

In this post, I briefly break down the Dockerization of a FastAPI project and how to upload it to Docker Hub. The concepts outlined here are expanded upon in a book I recently published, "Building Serverless Python Apps Using FastAPI and AWS" We will be using the Python 3.9-slim base image to help in our definition and installing uvicorn wheel, and poetry, along with a few other dependencies. We will need to essentially copy the minimum files required to run your application to avoid adding extra scripts, the tests folder, etc.

  

## [Why it isn't easy to throw cloud spending on the cutting block](https://techcrunch.com/2022/06/02/why-it-isnt-easy-to-throw-cloud-spending-on-the-cutting-block/)

Businesses may try to rein in cloud infrastructure spending to reduce the substantial bills they have from AWS, Azure, Google Cloud, and others. But simply wanting to cut costs and actually being able to do it are two entirely different matters. Tech companies built atop public clouds from birth see their infrastructure spending expand with time, making them lucrative customers of AWS and Microsoft Cloud. As investors put more weight on profitability, reducing spending in non-human expense categories becomes critical. Layoffs are far harder to execute than cuts to public cloud spending regarding the internal message, external branding, and morale.

  

## [Loading Large JSON Files](https://blog.devgenius.io/loading-large-json-files-bbd27b01f740)

ChesslabLab is a chess data science and machine learning machine with ML learning with Rubix MLix. I'm still using one single t2micro instance to run all the services required, which costs about $14 a month. I guess it's fair to say a flat-file database has been put in place instead of using a database. The DevOps side of things is kept minimal as well. It is pretty much the same thing as the AWS setup described in the previous post below. All chess games are currently being dumped into a large JSON file for further processing by the PHP chess server.

  

## [The Effective Way To Write Bash Scripts](https://betterprogramming.pub/effective-bash-scripts-108d976026bc)

The Effective Way To Write Bash Scripts: Use the Bashy library for better input parsing and script management. The Bashy interpreter wraps the scripts by parsing the argument with the information in the YAML manifest, serving the values to your script, and injecting them as regular variables. In addition, you can embed the bash code inside the bash script for short scripts directly. This article will discover Bashy, a tool written in Go that aims to solve all these issues by empowering BASH scripts to parse arguments.

  

## [Securing the Software Supply Chain For Policy-as-Code](https://containerjournal.com/features/securing-the-software-supply-chain-for-policy-as-code/)

The Open Policy Agent (OPA) project has been adopted in a wide variety of scenarios. OPA policies are powerful, but the default packaging format (a tarball) is not. Tarballs don't have many of the benefits we've come to expect from modern artifacts such as OCI containers. OCI images can be signed with Sigstore/cosign, ensuring a secure software supply chain for policies. The OPCR project provides actions for building, tagging, pushing, and pulling policy images.

  

## [Using Database Transactions in Laravel](https://betterprogramming.pub/using-database-transactions-in-laravel-8b62cd2f06a5)

Database Transactions help us never have situations where records are half-inserted into your database. A database transaction is a set of operations or queries you make to the database that it combines and treats as one container of work. Database transactions are available in most SQL databases, although it varies in how robust it is and how it is implemented. Using database transactions in Laravel is extremely easy and takes a few lines of code to use. There are two ways to use transactions: Closures and transactions.

  

  

## [Scaling Web Service](https://betterprogramming.pub/scaling-web-service-b391557a1134)

  

Analyzing How to Scale Web Services From Various Perspectives. Scaling web services is divided into several different levels. Another level of scale is not explained in detail in this article, but I will describe the concept of feature scaling a little bit at the end of the article. This article is an internal training for my team to explain to newcomers what are the best practices to consider when scaling a web service. The scaling mentioned in the article is divided between different levels. The upgrade of hardware specifications is called. Vertical scaling, a.k.a. scale-up. Vertical scaling is called 'scale-up.'