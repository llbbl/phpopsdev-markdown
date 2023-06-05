# DevOps / SRE - Top Links Last Week

## Week 33 - Issue #92

  

25 links

  

## [How to Find and Solve Engineering Bottlenecks – The New Stack](https://thenewstack.io/how-to-find-and-solve-engineering-bottlenecks/)

Due to dependencies on other teams, buggy CI/CD systems, or application complexity, engineering bottlenecks can arise. They can be identified relatively easily through qualitative data-gathering methods like retrospectives, and teams can use quantitative data to either support or debunk their assumptions about bottlenecks. Once a team has identified bottlenecks, they can create a status in their ticketing system (Jira, Azure, GitLab, etc.) that reflects that bottleneck, tracking the time that tickets sit in that state, blocked from moving forward.

  

## [Kubernetes Ephemeral Containers and kubectl debug Command](https://iximiuz.com/en/posts/kubernetes-ephemeral-containers/)

Kubernetes ephemeral containers are great and much needed. The fastest way to get started is the kubectl debug Command. However, this Command might be tricky to use if you're not container-savvy.

  

## [Introducing the PlanetScale serverless driver for JavaScript](https://planetscale.com/blog/introducing-the-planetscale-serverless-driver-for-javascript)

PlanetScale has introduced a new serverless driver for JavaScript that uses the Fetch API. The driver is compatible with Cloudflare Workers, Vercel Edge Functions, and Netlify Edge Functions. The driver also handles SQL sanitization to help prevent security issues like SQL injection.

  

## [Kubernetes The Easy Way. Kubernetes is the go-to solution for… | by Rumesh Bandara | devopsanswers | Medium](https://medium.com/devopsanswers/kubernetes-the-easy-way-19f69e57738d)

Kubernetes is an open-source container orchestration system trusted by the community and large web-scale companies. It is used to provision, schedule, and manage containers at a scalable level.

  

## [Boost your Laravel Application's performance with Octane | by Hooman Naghiee | Medium](https://medium.com/@hooman6445/boost-your-laravel-applications-performance-with-octane-4aae68769e38)

RoadRunner is a PHP application server that runs your application in workers instead of running it for every request. Laravel's official Octane package makes your app ready to use, RoadRunner.

  

## [Scanning for AWS Security Issues With Trivy | liamg](https://lia.mg/posts/trivy-aws/)

Trivy is an open-source security scanner that can find many different types of security issues in anything you point it at for free. It can now also scan AWS accounts for security issues.

  

—

  

  

## [Kubernetes from the ground up: the Kubelet | by Apoti Tech | Dev Genius](https://blog.devgenius.io/kubernetes-from-the-ground-up-the-kubelet-747e6d60c922)

Kubernetes is a container-focused cluster management system that was created by Google. The kubelet is the lowest level component in Kubernetes and is responsible for running containers on individual machines. Pods are defined by a JSON, or YAML file called a pod manifest and are a collection of containers that share some resources. To run a pod, you just put a manifest file in the watched directory, and the kubelet will check for changes in the directory every 20 seconds and launch or kill pods based on what it finds. The kubelet also has an

  

## [Observations and thoughts after building 3 Kubernetes platforms in Financial Services Industry — Part 3 — GitOps | by Patrick Picard | ITNEXT](https://itnext.io/observations-and-thoughts-after-building-3-kubernetes-platforms-in-financial-services-industry-7d6c60206717)

The market for GitOps tooling is relatively crowded, with a lot of options to choose from

-ArgoCD is a popular tool that is used to manage everything on a Kubernetes cluster

-Waves are used to instantiate components in a specific order where required

-ApplicationSets is another tool that is used to manage Kubernetes applications

  

  

## [How to optimize docker image size? | by Dwen | ITNEXT](https://itnext.io/how-to-optimize-docker-image-size-d6771225e0ec)

This article discusses how to optimize the size of a docker image. The author provides tips for multi-stage builds, avoiding creating unnecessary caches and documentation, and merging layers.

  

## [Grafana Loki And MinIO: A Perfect Match! - Alexandre Vazquez](https://alexandre-vazquez.com/how-to-configure-grafana-loki-to-use-minio/)

Grafana Loki is a log aggregation tool becoming increasingly popular for Kubernetes workloads. MinIO is an object storage solution that can be deployed on-premises or in the cloud. Grafana Loki can be used with MinIO to provide a more flexible and transparent solution for logging.

  

## [Let's Dockerize a Node.js Express App | by Aakash Jha | Bits and Pieces](https://blog.bitsrc.io/lets-dockerize-a-node-express-app-fdba1cf516b2)

Docker is a tool that helps you focus on your code by taking away the worry of deployment and distribution. You can use Dockerfile and docker-compose to configure your app and start a new container.

  

## [A basic React, Tailwind, and Firebase deployment | by Russell Eveleigh | Dev Genius](https://blog.devgenius.io/a-basic-react-tailwind-and-firebase-deployment-fc96fcf43b6)

Russell Eveleigh is teaching himself React, Tailwind and Firebase.

- He installed React using the terminal and created a new coin-toss app.

- He is using Tailwind CSS as an alternative to Bootstrap.

- He deployed his app to Firebase using the Firebase tools.

  

## [Amazon's Not So Secret Weapon. The magic of Working Backwards: a… | by Carlos Arguelles | ITNEXT](https://itnext.io/amazons-not-so-secret-weapon-54a089536dfb)

Amazon's success is due to the company's focus on the customer experience, which is made possible by the way its engineers work "backwards" from the customer announcement.

  

## [Standardizing RESTful APIs. Consistent, hierarchical, and modular… | by Jayanth Kumar | Technopreneurial Treatises](https://blog.jaykmr.com/standardizing-restful-apis-7f0b94d12d05)

This person suggests that RESTful APIs should be standardized to be consistent, hierarchical, and modular. This will make it easier for clients and customers to use the APIs and avoid chaos.

  

## [Create an ECS Cluster with Docker image using Terraform | by Revathijoshi | Towards AWS](https://towardsaws.com/create-an-ecs-cluster-with-docker-image-using-terraform-595fabbd9a65)

This article uses Terraform to deploy a Docker image from an ECS cluster. It outlines the main components of ECS and explains how to set up a cluster, create a container, and push an image.

  

## [PACKER. Packer is an open-source DevOps tool… | by Yash Hirulkar | FAUN Publication](https://faun.pub/what-is-packer-badf5a935641)

Packer is an open-source DevOps tool by HashiCorp to create automated, identical machine images for multiple platforms from a single source configuration.

Packer can be used on platforms like AWS, GCP, AZURE, etc.

Templates are written in JSON format.

We can use Terraform's infrastructure as a code tool to launch completely provisioned and configured machine instances with Packer images in seconds.

Identical images allow you to run dev, staging, and production environments across platforms.

By provisioning instances from stable images installed and configured by Packer,

  

## [How to manage multiple environments with Terraform | by Yevgeniy Brikman | Gruntwork](https://blog.gruntwork.io/how-to-manage-multiple-environments-with-terraform-32c7bc5d692)

If you're just looking for a quick recommendation of which option to use, here's a preview of the summary table from the very final blog post, which shows how the three options compare (more black squares = better):

  

| Option     | Ease of Use | Ease of Setup | Flexibility | Community Support |

| ---------- | ----------- | ------------- | ----------- | ----------------- |

| Workspaces | ★           | ★★★★          | ★★★         | ★★★               |

| Branches   | ★★★★        | ★★★           | ★★          | ★★★               |

| Terragrunt | ★★★★        | ★★            |             |                   |

  

  

## [Writing Automation Test Scripts With Python | by Ng Wai Foong | Better Programming](https://betterprogramming.pub/writing-automation-test-scripts-with-python-c00b924e0369)

Testing is important; pytest is a Python testing module, pytest is recommended for projects following the Agile or DevOps methodology, and pytest has a built-in parametrize marker.

  

## [AWS App Runner: Easy and Serverless Solution to Run Containerized Application | by Luthfi Anandra | AWS in Plain English](https://aws.plainenglish.io/aws-app-runner-easy-and-serverless-solution-to-run-containerized-application-74d7e4673fc2)

Aws App Runner is a serverless solution to easily run containerized applications, without the need to manage infrastructure or servers.

-Terraform can be used to provision and configure App Runner services regarding a child module containing a template configuration for an App Runner service using an ECR container image.

-DNS records need to be added on a DNS server for custom domain configuration of the App Runner service.

  

## [Terraform EC2 Module. In this project, I will take a resource… | by Melissa Gibson | Nerd For Tech | Medium](https://medium.com/@melissgibson/terraform-ec2-module-6483f49863df)

In this project, I will take an existing resource that creates an EC2 instance and restructure it into a custom Terraform module. The goal is to create repeatable infrastructure.

  

## [Using Terraform Modules to Deploy an EC2 Instance | by Devin Moreland | Medium](https://medium.com/@Devin007/using-terraform-modules-to-deploy-an-ec2-instance-6ab02f200f35)

In this article, we walked through how to use Terraform modules to deploy an EC2 instance with NGINX bootstrap script using Terraform. We also assigned an IAM instance profile to our instance so that we could list our S3 buckets.

  

## [WebOps: A DevOps for Websites, but the Tools Let It Down – The New Stack](https://thenewstack.io/webops-a-devops-for-websites-but-the-tools-let-it-down/)

WebOps is a term for the process of managing websites and web applications. It is similar to DevOps but includes managing content, which typically means marketing people are part of the process. WebOps can be used to manage CI/CD (continuous integration and delivery or deployment), but the term is also used more generally to refer to the process of website management.

  

## [Deploy Django Application on AWS with Terraform & Connect to Amazon S3 | by Yevhen Bondar | Python in Plain English](https://python.plainenglish.io/deploy-django-application-on-aws-with-terraform-connect-to-amazon-s3-307b1e60d188)

This is a tutorial on deploying a Django application on AWS with Terraform and connecting to Amazon S3.

  

## [With Additional Funding, Deno Sets out to Challenge Node.js – The New Stack](https://thenewstack.io/with-additional-funding-deno-sets-out-to-challenge-node-js/)

Deno is a new JavaScript runtime built on the Rust programming language and attempts to provide a standalone tool for quickly scripting complex functionality. However, it has yet to catch fire due to a lack of user-friendliness, documentation, and third-party packages. However, it has recently obtained $21 million in funding, which could help it overcome these obstacles.

  

## [5 Ideas for GitHub Actions. Bring more automation to your projects | by Dmytro Khmelenko | Better Programming](https://betterprogramming.pub/5-ideas-for-github-actions-4ad572c695df)

GitHub Actions is an automation tool used to improve development workflows

-IDEs can be used to automatically label changes made to code, generate changelogs, and enforce security policies

-GitHub Actions can be used to automate the publishing of mobile apps, Android and iOS projects

-The provided API enables anybody to create a GitHub Action