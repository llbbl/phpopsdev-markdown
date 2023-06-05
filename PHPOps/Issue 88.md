# DevOps / SRE - Top Links Last Week

## Week 29 - Issue #88

  

28 links

  

## [Hardcoded password in Confluence app has been leaked on Twitter](https://arstechnica.com/information-technology/2022/07/atlassian-warns-hardcoded-password-flaw-is-likely-to-be-exploited-in-the-wild/)

The hardcoded password for the Confluence app has been leaked on Twitter, potentially exposing users to danger.

-The company has advised users to take immediate action to fix the issue.

  

## [Fixing a Performance Anti-pattern With Amazon DynamoDB and Lessons Learned](https://betterprogramming.pub/fixing-a-performance-anti-pattern-with-amazon-dynamodb-and-lessons-learned-858b4e570b0d)

I made a mistake in my code when working with boto3 clients on AWS Lambda that Myles Loffler pointed out. This mistake led to bad code that was hard to read and caused delays in my application. I fixed the mistake by creating a new utility file to handle my database connections and moving my CRUD functions to use the new file. This change made my code better overall and was easier to read and maintain.

  

## [Deploy WordPress Self Managed on Amazon Lightsail](https://aws.plainenglish.io/deploy-wordpress-self-managed-on-amazon-lightsail-ebe615c3bc49)

In this blog post, the author explains how to provision and configure WordPress self-managed on Amazon Lightsail. They use Terraform with backend remote (Terraform Cloud) to configure the AWS resources. The child module for the template WordPress instance can be found in the Lightsail WordPress module directory, and the configuration for the Lightsail root module can be found in the Lightsail directory.

  

## [Four Great Alternatives to HashiCorp's Terraform Cloud](https://medium.com/@elliotgraebert/6e0a3a0a5482)

The top four Terraform CI tools are Spacelift, Env0, Scalr, and Cloudify.

  

## [3 Essential Steps for Scaling Any Application](https://betterprogramming.pub/3-essential-steps-for-scaling-any-application-337a1e0b4398)

1. Reduce latency by evaluating popular queries, adding indexing, and introducing read-only database replicas.

2. Consistency is key in design, so invest in a design library.

3. To scale BIG, look into using Kubernetes.

  

## [Kubernetes Story — Deep into Container Runtime](https://faun.pub/kubernetes-story-deep-into-container-runtime-db1a41ed2132)

Container runtime is a tool that helps manage all processes related to containers, including creating, deleting, and sharing them. Container runtime is divided into two types: low-level and high-level. Low-level container runtime is responsible for creating and deleting containers. In contrast, high-level container runtime focuses on managing multiple containers, transporting and managing container images, and loading and unpacking container images to the low-level container runtime. Docker is a tool that allows users to interact with containers through a container runtime.

  

  

---

  

## [Handling secrets in your Ansible playbooks](https://blog.omarelfarsaoui.me/handling-secrets-in-your-ansible-playbooks-6eeb29495633)

Ansible Vault is a feature that allows you to keep all your secrets safe. It can encrypt files, entire YAML playbooks, or even a few variables.

  

## [Provisioning Docker-based development instance with Ansible](https://medium.com/@oxyaction/provisioning-docker-based-development-instance-with-ansible-ecc1b5c82ae1)

Use docker and docker-compose to orchestrate services in your development environment

- Use Ansible to provision your instance and deploy your services

- Configure your services to start on boot with systemd

  

## [Implement Good Commit Message Conventions in Your Development Workflow](https://levelup.gitconnected.com/implement-good-commit-message-conventions-in-your-development-workflow-15dd78b7a86e)

Commit messages are important for developers to communicate changes to code bases. Writing good commit messages can help save time and effort for development teams. There is a general standard for committing messages that have been widely adopted. Conventional commit is a specification for adding human and machine-readable meaning to commit messages.

  

## [DevOps Security Checklist For Kubernetes](https://kumomind.medium.com/devops-security-checklist-for-kubernetes-3672b4ee8288)

The DevOps Security Checklist For Kubernetes is a list of best practices that should be followed to secure a Kubernetes cluster. The checklist covers topics such as network security, Admission Controllers, and scanning for vulnerabilities.

  

## [Hardening SSH](https://tech.marksblogg.com/hardening-ssh.html)

This post is about a service that allows you to connect to your servers using various two-factor authentication services. You can connect from anywhere without setting up VPNs or jump boxes. Connection auditing and SSH command logging are enabled by default.

  

## [How to run python code in your browser](https://blog.devgenius.io/how-to-run-python-code-in-your-browser-69b4044b803a)

Brython is a framework that can inject python code over HTML pages. Brython is capable of interacting with DOM, thus making it a promising framework on the scripting side. In addition, Brython can be used to write python code in the browser.

PyScript is a JavaScript framework that allows users to embed python codes inside the HTML page. It enables the users to use the power of python libraries such as NumPy, pandas, and scikit-learn on web apps.

  

## [Stages in DevOps and Tools used in Different Stages of an Application](https://yashguptaa.medium.com/stages-in-devops-and-tools-used-in-different-stages-of-an-application-da7a476ea02)

DevOps is a process that helps businesses develop, test, and distribute software more quickly and reliably. The process is customized to meet a project's or organization's unique requirements and is prone to change as new features and tests are added. The first stage of DevOps is writing code, fixing bugs, and adding new features. The code is then stored in a central repository and is thoroughly tested using unit tests. Static code analysis is also performed to look for any bugs or issues. After the code is pushed to the repository, it is tested and needs to pass all the necessary checks in

  

## [Do you know everything about Serverless Architecture?](https://dineshchandgr.medium.com/do-you-know-everything-about-serverless-architecture-f0cd06c81329)

FaaS is a way to deploy serverless applications with benefits and drawbacks.

  

## [Best practices for Cloud Migration](https://faun.pub/best-practices-for-cloud-migration-8efce9040876?source=rss----10d1a7495d39---4)

This post shares the best practices and key factors for the Cloud Migration strategy. Before you start, you must establish which strategy you will implement for your project that complies with such an objective. You must plan each step, determine everyone's role, its complexity, the required training and resources you will need, inventory of cloud assets currently at your disposal, the priority of the migration, tools for observability, etc.

  

  

## [The Top 7 DevOps Tools You Need to Grow Your Business](https://blog.devgenius.io/the-top-7-devops-tools-you-need-to-grow-your-business-2a6189c8c7ec)

There are many DevOps tools available, each with different features. Therefore, it's important to compare each tool's features with your project's requirements to find the best fit. Some popular DevOps tools include Selenium, Docker, Kubernetes, Puppet, Chef, Ansible, and GitHub.

  

  

## [Terraform — State Management](https://tonylixu.medium.com/terraform-state-management-85bc622f731c)

Terraform state management is the process of keeping track of the current state of your infrastructure and comparing it to the desired state described in your code. Terraform state is stored in a local file by default but can also be stored remotely. Backend is an abstract, remote storage interface. Different backends have different support for state locks.

  

## [Continuous Integration: GitHub](https://blog.devgenius.io/continuous-integration-github-1130217cc2e9)

Continuous Integration is the process of automating the development process. It processes the software development process through building, testing, and deployment phases.

GitHubCI or GitHub Workflow is one of the best CI tools because it is simple to use and encapsulates all the tools in one place.

  

## [Tired of Installing Databases? Use Docker Instead.](https://betterprogramming.pub/tired-of-installing-databases-use-docker-instead-7e193be458cf)

Docker can help you run databases without going through the lengthy installation and setup process. Instead, you can pull a database image from Docker Hub and run a container to get started. You can even create a script to automate setting up your database.

  

## [The Demise of the DevOps team — Status Report.](https://medium.com/@joelbelton/the-demise-of-the-devops-team-status-report-1edaecedbbe5)

Joel Belton believes that the future of DevOps is bleak, and the DevOps team as we know it will soon be disbanded. The reasons he gives are puppet's "The State of DevOps Report," which says that better communication and collaboration between Development and Operations is essential for success. Belton also argues that the traditional role of the DevOps team is becoming obsolete as more and more companies are blurring the lines between Development and Operations.

  

## [How to create Redis cluster in Kubernetes](https://faun.pub/how-to-create-redis-cluster-in-kubernetes-85041c20a7e6)

In this article, we'll learn how to set up a sharded Redis cluster in Kubernetes. First, we'll create two ConfigMaps - one for Redis configurations and one for ACL user permissions. We'll also create a StatefulSet of six Redis nodes and a headless service to connect them. Finally, we'll use the redis-cli tool to create the sharded cluster.

  

## [All the Things a Service Mesh Can Do](https://thenewstack.io/all-the-things-a-service-mesh-can-do/)

A service mesh is a cloud-agnostic tool that consolidates multiple existing tools to help reduce management toil and costs. It can span multiple runtimes, offer service discovery as a global shared service, and provide authentication, authorization, and encryption capabilities. A service mesh can also control traffic patterns and load balancing between service instances.

  

## [Istio Service Mesh 101 — Part (1/3)](https://pilotudesh.medium.com/istio-service-mesh-101-part-1-3-f07a8fedeea8)

Istio is a service mesh for managing microservices. It allows easy monitoring, security, and traffic management of complex deployments without changing application code:

Install Istio using istioctl and add a namespace label to instruct Istio to inject Envoy sidecar proxies when you deploy your application automatically.

Deploy the Bookinfo sample application and verify that it is accessible from outside the cluster using an Istio Ingress Gateway.

Install Kali to access a dashboard that shows an overview of your mesh and the relationships between services in the Bookinfo sample application.

  

## [16 Types of Software Testing I Use in Programming to Solve Problems](https://javascript.plainenglish.io/16-types-of-software-testing-i-use-in-programming-to-solve-problems-e7dbbcc2aa0)

Many different types of software testing can be used to solve problems. For example, unit tests, integration tests, system tests, acceptance tests, functional tests, and non-functional tests are all software testing used to solve problems.

  

## [Securing Containers At Scale](https://containerjournal.com/features/securing-containers-at-scale/)

To securely scale containers, organizations need to find ways to automatically detect and scan container images and proactively monitor the open source risks in their applications. This requires an automated security solution to orchestrate security and manage policy across a container cluster.

  

## [Terraform vs Ansible: DevOps tools Comparison](https://medium.com/@tanvis11105/terraform-vs-ansible-devops-tools-comparison-632641bdf8f7)

Terraform is an Orchestration tool, and Ansible is a configuration management tool. Terraform uses HCL, which is declarative, while Ansible uses YAML, which is procedural. In addition, Terraform supports lifecycle management, whereas Ansible doesn't support such kind of term.

  

## [7 Useful PHP Libraries You Should Use in Your Next Project](https://medium.com/codex/7-useful-php-libraries-you-should-use-in-your-next-project-258bd1cdd62e)

  

PHP is a server-side scripting language that is commonly used for web development. Here are seven PHP libraries that can assist you as you proceed with your development work. 

  

  

## [How to Cache API Requests With Redis and Node.js](https://betterprogramming.pub/how-to-cache-api-requests-with-redis-and-node-js-cba883385e7)

  

This tutorial explains how to use Redis to cache data in a Node.js application for improved performance.