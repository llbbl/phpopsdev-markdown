# DevOps / SRE — Top Links Last Week

## Week 13 Issue #20

## [PHP Supply Chain Attack Shows Open Source’s Virtues and Vices](https://thenewstack.io/php-supply-chain-attack-shows-open-sources-virtues-and-vices/)

Two malicious commits were pushed to the PHP language's master software code storage site. This would have enabled an attacker to run a remote program on anyone running software using this hacked version of PHP. Fortunately, because PHP is open source, the problem was spotted before it had a chance to screw anyone over. PHP has decided that maintaining its own git infrastructure is an unnecessary security risk. The Linux Foundation has been working on armoring the open source software chain with the Open Source Security Foundation (OpenSSF)

## [Node.js configuration in Kubernetes](https://luckylibora.medium.com/node-js-configuration-in-kubernetes-adbb032e9db7)

The principles and the requirements of configuration mechanism are the same everywhere. Storing constants in config makes your service more flexible and saves you from unnecessary code changes. Don't even think about adding configuration files to docker images! Configuration must be stored separately in Kubernetes. It's important to ensure that all necessary fields and values have correct fields and error messages have correct values. It must be a way to pass its configuration to service without adding additional files or environment variables without adding extra files without adding .

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [5 Awesome Years at Coinbase](https://maori.geek.nz/5-awesome-years-at-coinbase-fb2e0b4d808f)

New Zealander joined and worked in the infrastructure team for 5 years at Coinbase. The company has grown from 100 to over 1000 employees, growing from 3.5 million users to more than 40 million users. The team grew the team to 7 people in 18 months, with the exception of a wild Lianian. I think helping build that team was my greatest achievement at Coinbase. They are all wonderful talented people and I would work with any of them. I would probably be proud and proud of them .

## [How to backdoor curl](https://daniel.haxx.se/blog/2021/03/30/howto-backdoor-curl/)

An unknown project outsider managed to push a commit into the PHP master source code repository with a change (made to look as if done by two project regulars) that inserted a backdoor that could execute custom code when a client tickled a modified server the right way. The attack code would probably do something minor that would have a huge impact in a special context for which the attacker has planned to use it. The code needs to be included in a curl release that is used by the victim/target. It failed rather miserably at step 1, making the attack code look innocuous .

## [I Hosted My Valheim Dedicated Server with Docker on a Rock Pi X](https://ikarus.sg/valheim-server-rock-pi-x/)

Valheim is currently the hottest survival sandbox game on the market. Developer Iron Gate Studios developed by a team of just 5 people. Valheim's peak players statistics on Steam at one point were second only to Counter Strike: Global Offensive (CS:GO), which is very impressive given that it's only in Early Access and has only been released for slightly over a month. With a dedicated server, players can decouple their gaming schedules from each other, and play whenever they want and contribute to the collective progress of a shared world .

## [Serverless UI testing using Selenium, AWS Lambda, AWS Fargate, and AWS Developer Tools](https://aws.amazon.com/blogs/devops/serverless-ui-testing-using-selenium-aws-lambda-aws-fargate-and-aws-developer-tools/)

The goal of this post is to demonstrate how to use AWS Developer Tools to build a continuous delivery pipeline that automatically deploys a test environment and runs a UI test against it. We have a pipeline defined in AWS CodePipeline, with AWS CodeCommit as source stage which contains all the source code in a repository, changes to the source will automatically trigger the pipeline. After completion of test stage, it will send an email for approval with the link to the status website. When the approver accepts the results, the website will be deployed in production .

## [AWS CloudFormation Best Practices](https://www.stackery.io/blog/aws-cloudformation-templates-best-practices)

AWS CloudFormation lets you manage your AWS infrastructure and resources from a text file. It's easy to set up and manage your infrastructure with an AWS template. CloudFormations is the largest resource provider in the world. The benefits and potential drawbacks of Cloudformation are not without drawbacks. We'll also share CloudFormated template examples and how Stackery can make things even easier with templates. For example, we'll share examples of how to setup and modify your architecture with a template. We're happy to provide an overview of the benefits and how to use the template in this article .

## [Getting Started With Continuous Monitoring](https://devops.com/getting-started-with-continuous-monitoring/)

Every DevOps transformation requires a dedicated, continuous learning process and effective implementation to reach maturity. If a practice or pattern is passed over or ignored, it can put a damper on DevOps success. The practice of continuous monitoring helps to collect and analyze outcomes, statuses, exceptions and key metrics within each step of the DevOps process - from development to deployment and production. An effective continuous monitoring process collects enough data to gain sufficient understanding of both successes and failures of the organization's systems and processes .

## [Kubernetes Supports Nine Pillars of SRE](https://containerjournal.com/topics/container-ecosystems/kubernetes-supports-nine-pillars-of-sre/)

Site reliability engineering (SRE) is a discipline that incorporates aspects of software engineering and applies them to infrastructure and operations problems to create ultra-scalable and highly reliable distributed software systems. The DevOps Institute's SRE blueprint identifies Nine Pillars of engineering practices which are: site reliability leadership and culture, work sharing, monitoring, SLOs and SLIs, error budgets, toil reduction, deployments, performance management, incident management and anti-fragility. Kubernetes helps business leaders empower the organization to reach next-level performance, deliver innovative new software and features faster .

## [Debugging Go Microservices in Kubernetes with VScode](https://blog.getambassador.io/debugging-go-microservices-in-kubernetes-with-vscode-a36beb48ef1)

CNCF Telepresence allows you to connect your local development machine to a remote Kubernetes cluster. This article walks you through using the tool to use your favorite tools with all of your microservices running on your local machine. It gives you the ability to comfortably debug your remote apps with your existing skills. We're going to be working with the sample Edgey Corp application written in Go. We are going to use the Go extension made by the Google team with the Go debugger tool called Delve .

## [What Does a Software Architect Really Do?](https://betterprogramming.pub/what-does-a-software-architect-really-do-192d07aeda3d?source=rss----d0b105d10f0a---4)

The author explains his role as a point of contact for the high-level aspects of our solution. He divides his work into four different aspects: design, infrastructure, API, and integration. These four aspects are not only related to one another, but they more or less depend upon one another. The main thing, at least the one I personally spend most of my time on, is the design. This is the cornerstone that all other aspects of my work depend upon. This is also the part where all the blueprints and sketches come alive .

## [Should I consider the GitOps methodology?](https://kumomind.medium.com/should-i-consider-the-gitops-methodology-f49e042b8c22)

GitOps is a set of practices around the DevOps methodology to align development and operation teams into a shared work process. With a version control system at the center of the delivery pipelines, developers can submit pull requests to accelerate and simplify application deployments as well as operation tasks. The idea is to have one or multiple Git repositories with the current state of the infrastructure and create a pull request each time an update is required. The benefits of the GitOps methodology can be seen as a lot of benefits, meaning that everyone uses the same continuous deployment methodology .

## [Provisioning vs Configuration Management with Terraform](https://medium.com/dev-genius/provisioning-vs-configuration-management-with-terraform-4bf07b9c79db)

Configuration management vs Provisioning is a systems engineering process for establishing and maintaining computer systems, servers, and software in a desired, consistent performance - state. CloudFormation, Terraform, Ansible, Salt, Vagrant, Puppet, Docker, etc are tools that can be used for provisioning and configuration management. Most configuration management tools can do some degree of provisioning, vis versa. Some tools are going to be a better fit for certain tasks taking to account your IT organization setup and what you're trying to achieve .

## [Best practices for developing cloud applications with AWS CDK](https://aws.amazon.com/blogs/devops/best-practices-for-developing-cloud-applications-with-aws-cdk/)

AWS CDK allows developers and administrators to define their cloud applications using a familiar programming language, such as TypeScript, Python, Java, or C#. Applications are organized into stages, stacks, and constructs, which allows for modular design techniques in both runtime logic (such as AWS Lambda code) and infrastructure components such as Amazon Simple Storage Service (Amazon S3) buckets, databases, and network infrastructure. All your target deployment environments are fully configured in your source code, rather than parameterizing a deployment artifact to be configured later .

## [Deploy Quickly Everywhere: Beamery’s journey to CI/CD](https://medium.com/hacking-talent/deploy-quickly-everywhere-beamerys-journey-to-ci-cd-7d1ef5e255fe)

Beamery has 64 serverless functions across 61 repositories, and 10 storage buckets, all replicated over 7 environments. Each environment has its own manifest detailing what version of each function is deployed. This means when we merge our manifest changes into master, they are deployed through all of our environments, all the way to Production. With our environments in line, the risk of code changes being lost in a complex deployment are reduced to near-zero. Feature flags allow for quick visual validation and easy modification, both during development and hotfix scenarios .

## [Top 20 project management methodologies](https://www.cio.com/article/2950579/top-project-management-methodologies.html)

Project management offices (PMOs) can assist their organizations in improving business outcomes. With so many different - and in some cases, overlapping - approaches to managing complexities of any given project, how can you know which project management methodology is best? Here, we outline the most popular project management methodologies (PMMs) in practice today, comparing their focus and principles. There isn't always a single solution in all cases, even within the same organization, so there isn't a single project management solution .

## [Deploy An Application To App Engine Using Five-Finger Steps](https://awstip.com/deploy-an-application-to-app-engine-using-five-finger-steps-8a069f1b27cf)

Using the Google Cloud Platform, it is all about deploying applications and migrating products data to the cloud. This article addresses how to deploy a simple Hello World Python application. The major steps used in this process is shown below. The app engine helps to build apps; it is a serverless solution that takes care of the backend compute and gives the URL of the app and you do not care about many resources. The deploying could take a minimum of 7 minutes and more depending on the intensity of the application .

## [Pull Requests vs Pair Programming](https://chemaclass.medium.com/pull-requests-vs-pair-programming-77be022c10c3)

Pull Request (PR) is a way of showing suggested code changes such that they are easily comparable with the existing source code. This is part of a workflow that helps developers to share knowledge about the changes that are being done within the system. Pull Requests are an asynchronous way to share code changes, while Pair Programming is synchronous because it happens at the same time. The main problem with these topics above is that PR's are usually ready when the feature/bug is already being worked on and in the last stage of its development process. It's an "already change proposal to be merged into the current system"

## [The Hitchhiker’s Guide to Go](https://nkatirtzis.medium.com/the-hitchhikers-guide-to-go-53875d134368)

This blogpost introduces you to the Go programming language. Go is an open source programming language that makes it easy to build simple, reliable, and efficient software. The language has become very popular over the last years, especially in the platform and infrastructure space. The core components behind Docker, Kubernetes, and Istio are written in Go. The following table provides an overview of useful features but also limitations of the language. It is mostly a summary of "The Go Programming Language" book, by Alan A. Donovan, and Brian W. Kernighan .

## [CI/CD Pipeline Tools and AWS CodePipeline Tutorial](https://www.ordinarycoders.com/blog/article/deploying-django-aws-codepipeline)

CI/CD stands for continuous integration/continuous deployment and refers to creating a code pipeline where code changes are committed, tested, and then deployed without any manual interference. A pipeline will allow you to ship code faster and more effectively -- a crucial process for scalability. We'll go through the steps to deploy to ElasticBeanstalk first, and we're going to stick with AWS Codepipeline. The steps include creating a pipeline, specifying where your project's source code is hosted, adding a build stage to run tests in an isolated environment .

## [CI/CD pipeline with GitHub Actions](https://medium.com/nimbella/ci-cd-pipeline-with-github-actions-71abd144ddb4)

To run this application, you'll need to have Git, Node.js and NPM already installed. We are going to write our automated test with popular Jest Framework. The final step of configuring CI/CD pipeline on Nimbella using GitHub Action, is to modify the YAML file under./GitHub/workflows as per our deployment specifications as below. We can get a non-expiring token to deploy our app into nimbella by running below command on nimCL .

## [Interact with Kubernetes resources in PHP 8](https://alexrenoki.medium.com/interact-with-kubernetes-resources-in-php-8-1b865ca927d7)

PHP K8S is a PHP-based client that eases the use of writing controllers or managing a Kubernetes cluster from the outside in PHP, with minimal configuration and with an extensive API that makes customization a no-hassle job. Custom Resources can also be easily created for PHP K 8s. The Macros macro is stored and stored in the macro and can be stored and used to create callers and callers for specific callers to add custom callers .

## [Software Architecture Analysis](https://guelmisp.medium.com/software-architecture-analysis-25bd0274d837)

The main idea behind the software metric is to empower the developer with data in order to control and propose new designs. Using metrics helps us to see how the system is growing, places with higher complexity (related to best practices of object-oriented programming or architecture), and could give a hint of where maintainability will be chaos due to package relationships. This section is an overview of some tools available in the industry. The next section will be on some theory on metrics, tools, and the process of collecting quality design metrics .

## [Microservices in Golang and creating Docker image for easy deployment.](https://medium.com/@SarveshGulhane/microservices-in-golang-and-creating-docker-image-for-easy-deployment-b4af76e061b0)

The microservice will listen and serve on port 8082. It will listen to a network port and keep listening to the incoming requests. If someone makes GET request we will return a list of people as. JSON. If it is a GET request call function that will write existing data as. . If a request comes in, we want to redirect according to the request. As we will receive 'Get' and 'Post' requests, we will process accordingly. We will receive a. JSON of details of the person and add it to our data .

## [Shared Dependencies Between Multiple Application Instances on Kubernetes](https://faun.pub/shared-dependencies-between-multiple-application-instances-on-kubernetes-f69926fceda6)

Kubernetes HPA, when triggered, is going to scale out a specific deployment, meaning, increase the number of running instances of an application to handle a particular workload. The diagram below shows how HPA with KEDA will scale out our deployment to have multiple running pods. This job will be deployed for one time on the cluster and it has one main purpose: copying huge files from Azure to a persistent volume claim in our cluster. This claim has already been mounted to our pods. Then, those pods must wait until the job is finished successfully, and only then will they be able to start up .

## [Scaling monorepo — to infinity and beyond!](https://medium.com/productboard-engineering/scaling-monorepo-to-infinity-and-beyond-79bed3d302b2)

Frontend Platform has 400k lines of TypeScript in its frontend monorepo. Frontend platform uses Nx for every part of our codebase. Nx is feature-rich, open to the community, extensible, and based on battle-tested Angular CL. The team's mission is to empower engineers and enable productivity, especially at this scale. The frontend feature branch pipeline took us almost an hour to finish in darker days, says Productboard CEO .

## [Using Web Assembly Written in Rust on the Server-Side](https://thenewstack.io/using-web-assembly-written-in-rust-on-the-server-side/)

WebAssembly allows you to write code in a low-level programming language such as Rust that gets compiled into a transportable binary. That binary can then be run on the client-side in the WebAssembly virtual machine that is standard in today's web browsers. The real benefit of WebAssembly is using the technology to do computationally intensive work from within a browser. In this article, I'll show you how to install Rust and use it in a TypeScript-powered web server running under Deno .

## [Testing Machine Learning Pipelines](https://misbah-uddin.medium.com/testing-machine-learning-pipelines-22e59d7b5b56)

Machine Learning (ML) pipelines in production have to worry about backward compatibility of changes made to the pipeline. It may be tempting to increase test coverage, but a high test coverage cannot guarantee that your recent changes have not broken the pipeline. If you do not have the time to read the full article, consider reading the 30 seconds version of this week's blog post. In the comments below, please share your feedback about your work with us on Twitter @dailymailonline.com/newsquiz .

## [Let GitLab CI/CD work for you.](https://santukoley.medium.com/let-gitlab-ci-cd-work-for-you-85f5b560c2c0)

DevOps community has built GitLab CI/CD functionality in Version Control System itself. GitLab has two major components: GitLab Version Control and GitLab Runner. Pipeline is a set of jobs to perform with or without condition. Runner executes the following tasks/jobs: Build your application, Execute test cases, Allow/deny to accept merge requests based on condition. Deploy the changes to master branch in master branch then merge master branch. If master branch is merged, master branch will merge and master branch should be merged .