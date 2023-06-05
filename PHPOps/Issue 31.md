# DevOps / SRE — Top Links Last Week

## Week 24 Issue #31

## [Are we there yet? Thoughts on assessing an SRE team’s maturity](https://cloud.google.com/blog/products/devops-sre/evaluating-where-your-team-lies-on-the-sre-spectrum/)

Customer Reliability Engineers (SREs) are working with Google Cloud customers to improve service reliability. We've noticed a recurring question: "Can we call ourselves SREs yet?" This question is asked in different ways, for a myriad of different reasons, and it can be quite hard to answer due to the wide range of different circumstances that our customers operate in. We hope to help answer this question by discussing some principles we consider fundamental to how an SRE team operates. The answer is partially dependent on how a team engages with the services it supports.

## [Crypto Mining is Killing All Free CI/CD Platforms](https://dev.to/n3wt0n/crypto-mining-is-killing-all-free-ci-cd-platforms-4chc)

This is why mining crypto currencies is killing every free CI / CD platform. Mining is negatively impacting many things in the world, and now it's ruining something else in a way no one has seen coming. Microsoft is not providing anymore free CI for their concurrent CI for new organizations. If the users want them, they need to request for them and provide additional information to verify they are eligible. If a user wants to keep using a paid plan, then they will have to buy a new account before adding account.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Six Deployment Strategies](https://medium.com/javarevisited/six-deployment-strategies-cf8f07c1a17)

Different organizations using different deployment strategies based on different factors such as cost savings, downtime management, risk.. etc. Let's explore in detail in detail here. Different deployment strategies are different to be used by different organizations. A ramped deployment strategy consists of slowly rolling out a version of an application by replacing instances one after the other until all the instances are rolled out. A canary deployment consists of gradually shifting production traffic from the current version to the new version. Shadow deployments consists of routing a subset of users to a new functionality under specific conditions. It is usually a technique for making business decisions based on statistics.

## [The “API Mandate” memo at Amazon](https://chrislaing.net/blog/the-memo/)

In 2002, Amazon’s Jeff Bezos issued a memo that has entered tech industry canon. The memo, known as the ‘API Mandate’, is generally perceived as being a statement about technology at Amazon, and is widely admired by technologists and wholly ignored by executives. The API Mandate completely transformed Amazon as a business and laid the foundation for its success. Unlike many things that global technology titans do, it is something that can be replicated and put to use by almost any business.

## [The Architectural Challenge of Authorization](https://thenewstack.io/the-architectural-challenge-of-authorization/)

Every B2B SaaS application requires an authorization system to enforce permissions that are granted to different tiers of users. But compared to authentication, authorization is a harder problem and is far from solved. Developers want a central control plane that manages all the artifacts that are involved in making an authorization decision. The decision logs that stream out of the authorization service should be aggregated and made available centrally. We can now use a set of open source building blocks, such as the Native Computing Foundation’s Open Policy Agent (OPA), instead of having to come up with custom languages and engines. And a new set of solutions is emerging that could fill this hole in the API economy.

## [Security Best Practices for Amazon S3](https://aws.plainenglish.io/security-best-practices-for-amazon-s3-f1983e40c29a)

Amazon S3 or Simple Storage is an object storage service and is one of the most used services in AWS. AWS follows a shared responsibility model which involves both AWS and the customer. Customers will be responsible for security in the cloud-based on the services which they select to use. The least privilege access control model can be implemented by starting with no permissions at all and then gradually allowing permission to perform the required actions. It is always best to use roles instead of using an IAM user when other AWS services have to access S3 buckets.

## [Metrics: reliably configuring Prometheus and Grafana with Docker.](https://joehonour.medium.com/metrics-reliably-configuring-prometheus-and-grafana-with-docker-2077541c8e6d)

This guide will take you through an overview of how Prometheus collects metrics, before moving on to visualizing them with Grafana. We will focus on how we store and version this config, so it can be deployed reliably with Docker. The first step to getting a reliable deployment of this architecture, is to simply get the images we need running locally. We need to:Configure the Prometheus scrape config, to tell it where our application is located and how often to get metrics from it. Store the metrics in a persisted volume, so we don’t lose them if the Prometheus Docker image is stopped. Store these dashboards with the queries/graphs we want to display.

## [We’ve All Been That HBOMax Intern at Some Point](https://betterprogramming.pub/weve-all-been-that-hbomax-intern-at-some-point-fabfbf39d088)

Integration Tests are meant to test how different parts of your platform work together. The code that you’re testing needs to be the code you want to deploy. This means you can’t hard-code an email address, run the test, remove that address, and deploy. The human factor is and always will be the main source of errors and problems in any situation. Instead, use an environment variable that is pre-configured by DevOps team inside each environment. This makes it so your code behaves differently depending on where it is deployed without having to touch a single line of code.

## [Terraform in AWS](https://billhegazy.medium.com/terraform-in-aws-9793e3c01173)

aws-vault is a must-use tool for Terraform in AWS. It stores IAM credentials in your Os’s secure Keystore and generates temporary credentials to be used in shell. Pre-commit framework will help your code to be kept clean, formated, updated document and checked for potential security issues before committing and pushing the code to git source. Using Terraform with Terraform to easily switch between AWS accounts and avoid hard-coding AWS profile in Terraform.

## [Continuous Deployment with AWS Amplify](https://aws.plainenglish.io/continuous-deployment-with-aws-amplify-f21250c1e36c)

With AWS Amplify, we can easily host different branches with subdomains. Within 5 small steps, you have successfully deployed your project into 3 different environments. This is an excellent approach to follow in small and medium scale projects, and I invite you to try this out and share your experience in the comments section of this article. You can find all the relevant details regarding the custom domain configuration in the below article: Using Route53, as I explained in my previous article, you will be able to connect your custom domain to the hosted application.

## [Low-code and no-code ready for sophisticated application development? It depends](https://www.zdnet.com/article/low-code-and-no-code-at-a-turning-point/)

Are business users ready and capable of building sophisticated applications? There is a lot of hope and hype associated with the low-code and no-code software movement. But that doesn't mean developers will be hanging up their IDEs anytime soon. We are nowhere near the point in which business users can build and deploy relatively sophisticated applications without the help of IT departments. The Covid-19 pandemic brought about demand for a range of applications that require relatively sophisticated workflows, logic and integrations.

## [CDN Providers Rival Hyperscale Clouds for Web Developers Deploying Jamstack](https://thenewstack.io/cdn-providers-rival-hyperscale-clouds-for-web-developers-deploying-jamstack/)

The State of the Jamstack 2021 report suggests that platforms aimed at web developers have actually gotten traction. Microsoft Azure was only cited by 29% as compared to 37% in the equivalent 2020 survey. Akamai, Digital Ocean and Netlify each were cited by 21% as where Jamstack projects are deployed and hosted. Gatsby Cloud, DigitalOcean and NetLify also market themselves as platforms for web developers, where devs can build their applications, deploy them to edge locations and then run them perhaps with the assistance of third parties that execute functions.

## [Top 10 HTTP Benchmarking and Load Testing Tools](https://thechief.io/c/editorial/top-10-http-benchmarking-and-load-testing-tools/)

Web server benchmarking is the process of testing a web server's performance to determine how well it can cope with high workloads. Benchmarking helps you understand which server, tech stacks, and configuration performs best for your application and gives you the benchmark performance when your application will become slow or break down. We have highlighted 10 of the most efficient and widely used HTTP benchmarking and load testing tools in this article. The list includes K6, Autocannon, Jmeter, Drillsung, SlowHTTPTest and Tsungsung.

## [Why Kubernetes Has Become So Popular in Data Engineering](https://www.gooddata.com/blog/why-kubernetes-has-become-so-popular-in-data-engineering/)

Containers have become the de facto standard for moving data projects to production. Data pipelines and ML models are finally reproducible and can run anywhere in the same fashion. With an ever-growing number of containerized data workloads, orchestration platforms are becoming increasingly important. With Kubernetes, especially when deployed to infinitely scalable cloud services, managing the execution of containers at scale has become considerably less painful. Containers facilitate collaboration between data engineers, data scientists, and analysts who can all work in a reproducible environment.

## [Kickstart your Laravel Web App using Laravel Sail](https://blog.devgenius.io/kickstart-your-laravel-web-app-using-laravel-sail-30276265e588)

Laravel Sail is a light-weight command-line interface for interacting with Laravel’s default Docker development environment. WSL stands for Windows Subsystem for Linux, it allows developers to run Linux environments directly on Windows without any “real” hosted VM. WSL 2 is a major overhaul and provides the benefits of WSL 1 with better file IO performance (20x faster). It is not like the traditional VM which may be slow to boot up, large resource overhead, and fully isolated.

## [Open source HIPAA compliance benchmark for AWS](https://github.com/turbot/steampipe-mod-aws-compliance)

300+ checks covering industry defined security best practices across all AWS regions. Includes full support for multiple best practice benchmarks including HIPAA, PCI DSS, Foundational Security Best Practices and CIS benchmarks. Includes support for the latest (v1.4.0) CIS benchmarks: v130_2_1_1; v140.cis_v140.2; v130. Use Steampipe introspection to view all current controls; run all benchmarks; run a specific control.

## [Kubeflow (is not) for Dummies](https://mtszkw.medium.com/kubeflow-is-not-for-dummies-414d8977158a)

Kubeflow is one of the hottest things in ML and MLOps area recently with around 30 actively developed repositories with almost 20,000 stars from GitHub users. It can be deployed both in local cluster as well as in the cloud. It took me a couple of attempts to finally setup Kubefl on AWS cloud (deploying it in Amazon EKS cluster) I am able to set up the infrastructure once and then tear it down with just a single command and I’m sure it will be cleaned up nicely.

## [What’s New in the Ansible Content Collection for Kubernetes - 2.0](https://www.ansible.com/blog/whats-new-in-the-ansible-content-collection-for-kubernetes-2.0)

The kubernetes.core Collection has been released for the 2.0 release of this Collection. This release introduces the. newest addition to the Collection, Ansible turbo mode. This. release also introduces the replacement of the. OpenShift client with the official Kubernetes Python client. This change enables us to more easily incorporate future improvements and new features into the Collection without the loss of any functionality with the new client. The k8s module has added the ability to. create an existing object to create an object that can’t be created and. continue to be changed by using the new.continue_on_error parameter.

## [Why Your DevOps Pipeline Should Include SAST](https://infosecwriteups.com/why-your-devops-pipeline-should-include-sast-87a0e06b8292)

Cybersecurity is one of the major concerns of the modern era. The risk of a potential hacker or virus invading our systems or personal data is at the highest point it has ever been. We need near-perfect security testing measures to prevent these from occurring. SAST is a white-box testing method that scans the working of an application even before the code is compiled. Integration of SAST and DevOps is a combination of effective practices and efficient tools to produce the best results in tackling any situational problems.

## [The 7 Struggles of a Tech Debt Management Team](https://betterprogramming.pub/the-7-struggles-of-a-tech-debt-management-team-ec8ef8316369)

The 7 Struggles of a Tech Debt Management Team. It’s the most crucial team for building scalable software software. The team is responsible for working on the core body of the application used, as shown in the example of a core coordinator / dependencies group in the diagram below. The work essentially is like managing tech debt management group. It is a team that is cleaning up other developers’ messes. No one would like to be in such a team, but we do have teams that are dedicated to fixing and addressing tech debt.

## [The Best DevOps Resources (Beginners & Advanced)](https://microtica.com/blog/great-devops-resources/)

The global DevOps market is expected to increase from $2.90 billion in 2017 to $10.31 billion by 2023. DevOps engineers are highly-paid, with Glassdoor estimating the average annual pay at around $100,000. If you’re looking for a career switch or upgrade, learning DevOps is a good idea. From books to podcasts, here are the best DevOps resources to start with: The Phoenix Project is an amazing novel about DevOps.