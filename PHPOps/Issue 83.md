# DevOps / SRE - Top Links Last Week

## Week 24 - Issue #83

25 links


## [How we built daily.dev, the 150k+ developer community](https://levelup.gitconnected.com/how-we-built-daily-dev-the-150k-developer-community-27877e468bad)

Daily.dev is a top news resource for programmers with 150k+ active developers. It was created as a side project but quickly gained traction due to the organic community that developed around it. The company is devoted to helping developers grow professionally and providing quality information.


## [Kubernetes is Your Platform: Design Patterns For Extensible Controllers-My KubeCon Notes](https://sinemmerveyilmaz.medium.com/kubernetes-is-your-platform-design-patterns-for-extensible-controllers-my-kubecon-notes-276bb9662d1b)

Controller: A single reconcile loop (such as the ReplicaSet controller)

 -Manager/Operator: A component that runs one or more controllers, like the Kube-controller-manager

 -Custom Resource: an instance of a Kubernetes type defined by using Custom Resource Definitions. A custom resource is formed by metadata, spec, and status.

 -Owner: Controller responsible for driving a custom resource from the observed state to the desired state. (Such as ReplicaSetController owns the ReplicaSet resources.)

 -Watch: Action of a controller that looks

  

## [Multi-Stage Docker Layer Caching using Kaniko + Cloud Build](https://mr-pascal.medium.com/7e46395fb2c2)

Pascal Zwikirsch created a GitHub repository detailing using Kaniko on Cloud Build to cache multi-stage Docker images. He walks us through the file structure and commands needed to get this up and to run. You can check out the repo here.

  

## [A Beginner-Friendly Introduction to Kubernetes](https://davidcjw.medium.com/a-beginner-friendly-introduction-to-kubernetes-540b5d63b3d7)

Kubernetes is a container orchestration framework that helps manage the lifecycle of containerized applications. It comprises a Master node that manages a group of worker nodes. A typical application has a web server with a backend service to persist data. To deploy an application on Kubernetes, you need to create a Dockerfile, set up a Cloud SQL instance, create a Google Cloud Storage bucket, and create a ConfigMap and Secret on your local minikube cluster. Finally, you can deploy your application using a Deployment and Service.

  

## [Don't use Kubernetes yet](https://matt-rickard.com/dont-use-kubernetes-yet/)

There are many ways to run containers on the cloud, so it's especially tough to pick the right abstraction at the right time. Early-stage startups shouldn't run on Kubernetes yet, but eventually, growth-stage and large companies should be running on it in some form. A guide to choosing the right container abstractions is broken down by engineering teams 1e0, 1e1, and 1e2+ engineers. Of course, for any team building anything other than a simple web service, you'll run into a wall quickly with those services.

  

---

  

## [How to create a Pipeline in GitHub Workflow to deploy your app on Azure](https://medium.com/@jomaajob/how-to-create-a-pipeline-in-GitHub-workflow-to-deploy-your-app-on-azure-a6e14a184d26)

Continuous Integration and Continuous Delivery (CI-CD) is the core of DevOps that allows teams to plan work, collaborate on code development, and build & deploy applications.

- In this article, we create a pipeline in Github workflow actions to build, test and deploy the NodeJS app on the Azure web app service. 

- The complete file will be as below:

- So, let's now test our first workflow by Creating a pull request and labeling it "spin up environment "as below:

- After finishing the workflow, you can notice

  

  

## [Monitor Ansible Playbook Executions](https://levelup.gitconnected.com/monitor-ansible-playbook-executions-bf92ce16d100)

Ansible can write playbook output to a host file, which can be parsed and monitored for failures.

  

  

## [Complex coding concepts explained through visual diagrams](https://betterprogramming.pub/complex-coding-concepts-explained-through-visual-diagrams-4a9b543cc323)

This article discusses how diagrams can be helpful in understanding complex coding concepts. In addition, it includes a roundup of selected posts that explain concepts through visual introductions.

  

## [Data Interchange Techniques for Web Applications](https://betterprogramming.pub/data-interchange-techniques-for-web-applications-c64ec600a1fc?source=rss----d0b105d10f0a---4)

Data interchange techniques for web applications include using files (such as CSV or tab-delimited files) or JSON-based REST APIs.

-Each has its benefits and drawbacks, so the best option may depend on the specific use case.

-In general, files are better for large data sets, and REST APIs are better for real-time data.

-A hybrid approach may be the best of both worlds, using both files and REST APIs.

  

## [What Is Zero Trust Architecture?](https://thenewstack.io/what-is-zero-trust-architecture/)

NIST recommends focusing on users, assets, and resources rather than traditional network boundary defenses. The concept of least privilege security assigns access credentials to key network resources at the least privilege level required to accomplish the desired task. Privileged Access Management (PAM), also known as Privileged Identity Management, can be implemented using corporate directory products such as Microsoft's Active Directory. In addition, Microsoft has recently introduced a product named Microsoft Entra to address identity and access issues in a multi-cloud environment.

  

## [Use GitHub Actions and Terraform to provision EC2 instance](https://faun.pub/use-github-actions-and-terraform-to-provision-ec2-instance-5b51636e4e54)

Following the tutorial in this Medium post, you can provision an EC2 instance on AWS using Terraform and GitHub Actions.

  

## [How A Vulnerability Scanner Works](https://faun.pub/how-a-vulnerability-scanner-works-c0ff255a41c0)

A vulnerability scanner is a tool that automatically tests for misconfigurations or coding flaws that could create security vulnerabilities. Vulnerability scanners can be network-based, web-based, or open-source code scanners. The best way to manage web vulnerabilities is to use a shift-left DevSecOps approach and deploy scanners throughout the software development life cycle.

  

## [ReadySet Core: next-generation SQL caching, freely available](https://readyset.io/blog/readyset-core)

ReadySet connects to an upstream Postgres or MySQL instance, automatically maintaining a cache for specific queries. Source code for ReadySet Core (written entirely in Rust!) is now available under the BSL license, converting to a fully open-source Apache license after four years. ReadySet is under active, heavy development. Sign up for our fully-managed cloud product, ReadySet Cloud, on as many nodes as you need. Check out our community Slack channel for more information about ReadySet and ReadySet.

  

## [How to Securely Manage Secrets Within Jenkins](https://devops.com/how-to-securely-manage-secrets-within-jenkins/)

Secrets management is an important part of any CI/CD pipeline and is critical for maintaining a strong security posture. Securing secrets helps mitigate the risk of compromised credentials falling into the wrong hands. Additionally, exposing secrets in plaintext credentials represents a critical security risk. This post discusses how to secure secrets within Jenkins CI/CD pipelines.

  

## [Kubernetes Architecture.](https://aws.plainenglish.io/kubernetes-architecture-c93cb9c798d8)

Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services that facilitates declarative configuration and automation. It consists of a control plane and a set of worker machines called nodes. The key component of the Control Plane is the Kube API Server, which exposes an HTTP API that lets end-users, various parts of our cluster, and external components communicate with each other.

  

## [Simplifying CI/CD With Devtron](https://betterprogramming.pub/simplifying-ci-cd-with-devtron-a4e1eae80779)

Devtron is an open-source software delivery workflow orchestrator for Kubernetes that simplifies setting up a CI/CD pipeline. It includes a CI/CD builder that makes it easy to configure common CI/CD steps and provides built-in integrations with popular open-source tools for additional convenience.

  

## [How to Manage GitOps Environments at Scale](https://betterprogramming.pub/how-to-manage-gitops-environments-at-scale-a-technical-guide-86e62bbdb12e?source=rss----d0b105d10f0a---4)

Differentiate your codebase and GitOps configuration between applications to optimize for better stability, fewer repositories, and more uniformity.

  

## [How To Protect Your Microservices](https://betterprogramming.pub/how-to-protect-your-microservices-8d74045061c1)

In this microservices lab01, the author shows us how to configure a basic to-do application, configure a microservices architecture where a user logs in and adds to-do in their list, and looks at their tasks, etc. But only if authorized!

  

## [Terraform : Production grade IaC coding](https://medium.com/@anshuman2121/terraform-production-grade-iac-coding-9e22a43b2f96)

Once you have your Terraform code written, the next step is to configure these resources. This is where the fun starts! Now you have to upload the state file and ensure that the Terraform configuration is defined as per your expectations. Once you have pushed the updated configuration to the remote state, you will find that your infrastructure has been updated. But, first, don't forget to check the logs to confirm that everything you have set up is working as expected.

  

  

## [Here's a Pragmatic Approach to Technical Decision Making](https://betterprogramming.pub/heres-a-pragmatic-approach-to-technical-decision-making-9154d262f5d3)

Technical decisions are simply a matter of scale, scope, and resources. Some choices will be better than others for certain situations, but all are viable. To make the right choice in your tech decisions, use data-based evaluations, and focus on the easily measurable aspects. Lastly, take a cold hard look at your products. If they are outdated, poorly maintained, or too reliant on the single person who came up with the solution, switch to a more scalable & maintainable solution.

  

  

## [How to create Github Actions for Vercel Deployment](https://arctype.com/blog/github-vercel/)

GitHub Actions allows you to automate your CI/CD processes using GitHub pull requests. Using a simple text file, you can build and test your code every time you make a change to your repo. Once your code passes, you can even deploy your code to a variety of environments or domains.

  

## [What are the Six Thinking Hats?](https://faun.pub/what-are-the-six-thinking-hats-7cbdd2ac48b6)

The Six Hats method of problem-solving can help us in many ways. It can help us evaluate a situation, simplify complex problems, and improve our decision-making. It can also help us make better choices in life and give us the tools to make the best of every situation.

  

## [Build Your Python Script Into a Command-line Tool](https://betterprogramming.pub/build-your-python-script-into-a-command-line-tool-f0817e7cebda)

The code you wrote has now been packaged into a real Python module, available in any Python 3 environment (on Linux or macOS). So now you can use it as a tool in your scripts and distribute it to your colleagues and the greater community.

  

## [Increasing the Lowest Common Denominator for Web Performance](https://betterprogramming.pub/increasing-the-lowest-common-denominator-for-web-performance-2f0f782955c4)

The performance insights UI that Chrome made available in the new tab is a step in the right direction and helps non-technical people have a conversation about performance. However, while developing tools like this is very important, we also need to remember that they will not be enough.

  

## [A Complete Guide to the API-First Approach](https://itnext.io/a-complete-guide-to-the-api-first-approach-ecd796dd0f10)

The API-First Approach is a development methodology focused on designing and developing APIs before writing any code. This approach has many benefits, including improved team collaboration, reduced meeting time, and the ability to work on the project parallel. However, before implementing this approach, it is important to build a culture within the team that understands and supports the approach and has proper infrastructure in place for communication and documentation.