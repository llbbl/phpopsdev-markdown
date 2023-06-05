# DevOps / SRE - Top Links Last Week

## Week 2 Issue #9

## [Maximizing Developer Effectiveness](https://martinfowler.com/articles/developer-effectiveness.html)

Technology is constantly becoming smarter and more powerful. I often observe that as these technologies are introduced an organization’s productivity instead of improving has reduced. This is because the technology has increased complexities and cognitive overhead to the developer, reducing their effectiveness. In this article, the first of a series, I introduce a framework for maximizing developer effectiveness. Through research I have identified key developer feedback loops, including micro-feedback loops that developers do 200 times a day. These should be optimized so they are quick, simple and impactful for developers. I will examine how some organizations have used these feedback loops to improve overall effectiveness and productivity.

## [Why Parler Can’t Rebuild a Scalable Cloud Service from Scratch](https://thenewstack.io/why-parler-cant-rebuild-a-scalable-cloud-service-from-scratch/)

Parler hasn’t published specific details of its architecture, although it initially said it doesn’t use any AWS-specific services that would tie it to one cloud. “We prepared for events like this by never relying on amazons [sic] proprietary infrastructure and building bare metal products.”

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [The Secret Power of CloudFormation](https://rhyno-vds.medium.com/the-secret-power-of-cloudformation-78c93ed9e5ec)

Terraform vs CloudFormation articles are everywhere. Most seem to highlight Terraforms dominance over CloudFormation. It’s easy to see why. Terraform has a far superior syntax and is much more versatile. However, CloudFormation has features that are not mentioned in any of these articles which in some cases dwarves the advantages that you get from Terraform. Depending on your circumstance, these secret powers could actually sway you to use CloudFormation over Terraform.

## [5 Simple Ansible Tweaks for Better Playbooks](https://medium.com/swlh/5-simple-ansible-tweaks-for-better-playbooks-fd9b789d5bca)

Ansible is fast, efficient and easy to use. On it’s own it can handle deployments of just about any size and let’s you build out large-scale infrastructure with nothing more than a simple YAML interface. Sometimes, Ansible playbooks, roles and modules can grow to become inefficient and unweildy over time. The more complicated a role becomes and the more moving parts, cause that once elegant YAML to look and perform like a nightmare.

## [Building DigitalOcean's API Gateway](https://mauricio.github.io/2021/01/14/building-digitaloceans-api-gateway.html)

DigitalOcean had 3 monoliths back in 2016 when we started (all 3 are still alive today, albeit much smaller than they were before). Why were there 3? There is a shared library that contains most of the logic that all 3 applications use, so in reality we had one “monolith library” that was reused at all 3, most logic changes were made into this library and then it would be upgraded at every single app separately. The library still exists today and continues to be updated every once in a while.

## [How To Deploy a Static Site(Gatsby) to Kubernetes With Cloud Foundry](https://medium.com/cloud-foundry-foundation/how-to-deploy-a-static-site-gatsby-to-kubernetes-with-cloud-foundry-ee31b5131c5f)

A lot of our application tech stack these days has to have some form of static content being served on the client side of our application, these could be just HTML, CSS and Javascript or it could be some javascript framework (React, Vue) or maybe a static site generator (Gatsby, Hugo, Jekyll). Cloud Foundry caters for this part of our system and we can easily deploy the static content to kubernetes with Cloud Foundry.

## [Helping to secure internet routing](https://aws.amazon.com/blogs/networking-and-content-delivery/how-aws-is-helping-to-secure-internet-routing/)

The internet works reliably, in large part, on the basis of a key technology called Border Gateway Protocol (BGP). BGP is a means by which all junction points on the internet (routers) communicate with each other to dynamically establish the correct (and correctly weighted) paths that network packets should follow to traverse the global networking system and reach their intended destination. Historically, however, BGP did not have built-in security. Routers simply trusted adjacent routers to send correct information. In the modern internet, this simple trust model is no longer adequate.

## [What the Ops are you talking about?](https://towardsdatascience.com/what-the-ops-are-you-talking-about-518b1b1a2694)

How to choose between DataOps vs. MLOps vs. AIOps? What are the right Ops for your big data team?

## [Kubernetes Patterns in a nutshell](https://florian-kromer.medium.com/kubernetes-patterns-in-a-nutshell-87c5a395e1a3)

Microservice architecture “arranges an application as a collection of loosely coupled services.” Microservice based applications can be run using lightweight container runtimes but usually they are cloud-native as well. Cloud-native means that the applications “(are scalable and run) in modern, dynamic environments such as public, private, and hybrid clouds.” The majority of cloud-native applications are developed to run on cloud provider infrastrcuture (e.g. compute resources) and using cloud provider specific technologies (e.g. blob storage, messaging brokers, etc.). The most common platforms are Amazon AWS, Google Cloud Platform (GCP) and Microsoft Azure.

## [Announcing CDK for Terraform 0.1](https://www.hashicorp.com/blog/announcing-cdk-for-terraform-0-1)

CDK for Terraform now supports Java and C# and has new collaboration features on Terraform Cloud.

## [Announcing Driftctl](https://driftctl.com/2020/12/22/announcing-driftctl/)

We recently released the first versions of driftctl, a new open-source project for infrastructure developers, DevOps, SRE, and cloud practitioners, with the goal of helping manage all kinds of drifts.