# DevOps / SRE — Top Links Last Week

## Week 18 Issue #25

## [SRE fundamentals 2021: SLIs vs SLAs vs SLOs](https://cloud.google.com/blog/products/devops-sre/sre-fundamentals-sli-vs-slo-vs-sla/)

Site Reliability Engineering (SRE) team uses Service-Level Objective (SLO) and SLIS to monitor service-level metrics. SLOs, SLAs, SLIs and SLIs are used in SRE planning and practice. The more reliable the service, the more it costs to operate. Excessive availability has become the expectation, which can lead to problems. Don’t make your system overly reliable if the user experience doesn't necessitate it, and especially if you don't intend to commit to always reaching that level.

## [The Unconventional Guide To Serverless](https://betterprogramming.pub/serverless-bcc0d2b65b41)

Autoscaling is a cloud computing method that dynamically adjusts the amount of computational resources in a server farm, based on the load on the farm. It helps to reduce the number of active servers when activity is low and launch new servers when it is high. This practice is closely related to the idea of load balancing. It can mean lower bills if you use an infrastructure hosted in the cloud. That’s because most cloud providers charge based on total usage rather than maximum capacity. The short per-request lifecycle of a serverless architecture results in significant cost savings for some teams.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Top 10 GitHub Repos To Bookmark Right Now](https://towardsdatascience.com/top-10-github-repos-to-bookmark-right-now-b0bc62436ffc)

The Art of Command Line is essential to becoming a skilled and productive developer. The Book of Secret Knowledge contains a collection of resources to help Developers and DevOps Engineers to do their everyday work. These repos are very popular amongst other GitHub lists, but I have to include them too, as I fully respect the time effort and selfless devotion of their contributors to share knowledge in a digestible way. The Developer Roadmap certainly appears in other. GitHub lists but cannot be omitted from this article, due to the clever infographic.

## [Zero to Kubernetes in 5 Mins](https://dev.to/ahmednader10/zero-to-kubernetes-in-5-mins-2hbp)

Kubernetes(k8s) has become the de facto standard for not only container orchestration but also for cloud-native development. With the rise of microservices architecture, more and more organizations move to adopt it heavily. In this tutorial, we will: create a simple http server with golang and deploy a k8s cluster. We will use K3s (a lightweight KuberNETes distribution) and use a simple golang server on top of K8s. This tutorial assumes version 1.153 but older versions should work as well.

## [Seeing Like an SRE: Site Reliability Engineering as High Modernism](https://www.usenix.org/publications/loginonline/seeing-sre-site-reliability-engineering-high-modernism)

A list of things to monitor in software systems is vague and unsatisfying. The list includes Latency distribution and successful/unsuccessful request counts (plus error types) for all RPCs served. It also includes the count of leaders for a leader-elected system (expected to be one - you want to know if it isn’t) This is an OK list, but it’s a lot of things in software operations generally, and software operations are like this. We spend a lot trying to make our systems more legible by adding, monitoring, tracing, status and other tools.

## [GitLab's 2021 Survey uncovers a new DevOps maturity model](https://about.gitlab.com/blog/2021/05/04/gitlabs-2021-survey-uncovers-a-new-devops-maturity-model/)

GitLab’s just-released 2021 Global DevSecOps Survey found sharp increases in automation, release cadences, continuous deployments, and security postures, as well as a growing reliance on cutting edge technologies, including artificial intelligence and machine learning. Nearly 4300 people shared their struggles and successes, and demonstrated a commitment to DevOps maturity like we’ve never seen before. This year participants plan to invest in the cloud, followed by artificial intelligence. SCM, CI/CD, test automation, and a DevOps platform were the most popular additions to their DevOps practices.

## [Fluentd vs. Logstash: The Ultimate Log Agent Battle](https://logiq.ai/fluentd-vs-logstash-the-ultimate-log-battle/)

Logstash, Fluentd and Elasticsearch are the latest log collectors for DevOps teams and SREs. Log collectors pull, parses, normalizes, and enriches log data before forwarding them to a log management system, a monitoring tool, or a database. Logs are semi-structured, descriptive data about a system’s behavior and all the events occurring within it. Log stash is written in JRuby and runs on JVM and is naturally cross-platform.

## [What Is Mobile DevOps, and Why Should You Care?](https://betterprogramming.pub/what-is-mobile-devops-and-why-should-you-care-7e9094c8b034)

Mobile DevOps is a way of testing apps without the need for manual testing. Instead of using manual testing, the development team should try to adopt mobile DevOps. Automating the creation of environments for complicated apps would have many benefits, such as giving developers a guaranteed environment that is unaffected by environment drift (as it can be deleted and re-created at a moment’s notice). Automating testing for the full test suite on the app itself would have a lot of benefits, including making it easier to run the test suite.

## [Are You Securing Your Containers Properly?](https://aws.plainenglish.io/are-you-securing-your-containers-properly-9a4d66c2818b)

Images that are up to date have the latest security patches, which protect you from the latest vulnerabilities that they track. Signing an image will essentially create a digital fingerprint that you can use to cryptographically test and verify whoever it was trying to manipulate the image. You also want to make sure that the host server for the registry is secure so that you protect it from being compromised. The host OS is potentially one of the greatest vulnerabilities that you have in your container environment because it will give the attacker essentially access to your entire application environment.

## [Kubernetes: Apprentice Cookbook](https://aveuiller.medium.com/kubernetes-apprentice-cookbook-90d8c11ccfc3)

Kubernetes is a powerful orchestrator that will ease deployment and automatically manage your applications on a set of machines, called a Cluster. Mastering these concepts will ease your onboarding on other orchestrators, such as Docker Swarm. The aim of this article is to explain the most used concepts relying on basic system administration concepts, then use some of these to deploy a simple web server and showcase the interactions between the different resources. This article mainly focuses on the developer side, but I will leave some resources about cluster administration at the end.

## [odo, a tool to simplify development on Kubernetes](https://medium.com/@feloy/odo-a-tool-to-simplify-development-on-kubernetes-ce0df34313b7)

The odo tool is based on the deployment of pre-defined containers embedding all the environment to build and execute programs. This way, developers do not need to write any Dockerfile or Kubernetes manifests. Instead of building and running the API locally, developers can deploy the API into the cluster using specific odo commands. In this article, we will use quoted text, as for this paragraph, and a different narrative, to describe what happens in the cluster. This helps to clearly separate what are commands executed by developers on a daily basis, and what are the commands executed only to illustrate in the article.

## [Apache Airflow for containerized data-pipelines](https://towardsdatascience.com/apache-airflow-for-containerized-data-pipelines-4d7a3c385bd)

Apache Airflow allows you to install Python modules in there, so you can have all your preferred libraries on hand to do remarkable stuff. You just need to make sure that your code runs with the Python version of Airflow and your libraries are installed on the system. The more your workflow uses Python, the more you use the PythonOperator. You're happy because you’re able to use your Python knowledge for all your Data Science tasks. But this works well until you or someone on your team wants to use a new version of Python or a new library.

## [Spice up Your Kubernetes Environment with AWS Lambda](https://liavyona09.medium.com/spice-up-your-kubernetes-environment-with-aws-lambda-a07d81347607)

Kubernetes is a powerful container orchestration platform for automating applications’ deployment, scaling and management. It does not integrate well enough with Serverless tools too. In Serverless applications, events are the main communication mechanism. In this blog I will introduce a simple yet powerful effective and secure way we can integrate Lambda with existing KuberNETes environment without any codes changes at all. The following solution describes how to pass Lambda events as an HTTP request to the service without introducing any external endpoints.

## [Scares of Technical Debt (Part I)](https://medium.com/@yasas276/scares-of-technical-debt-part-i-33446af0e805)

An evolving business always grows in complexity and for an internet based one, the technical complexity of the application would naturally grow as well inevitably. This is the danger of unhandled “Technical Debt” - a large loan that you have taken from your Technologies. The application should be easily extensible to meet the demands quickly. If you as a team, can’t do that… then you might well be trying to repay a huge loan. Badly designed software products can go bankrupt “technically” they can find themselves no longer extensible after a certain point.

## [Devilbox for quick & flexible PHP stack development](https://blog.xendit.engineer/devilbox-for-quick-flexible-php-stack-development-76faef75cdc8)

Devilbox is a dockerized PHP stack that supports all major OS, requires no setup (as everything is pre-configured), and is highly customizable depending on your needs. The main objective of this tool is that it allows developers to setup many environments and quickly switch to different local server during development. Devilbox has developed many open source payment plugins that are compatible with WooCommerce and Easy Digital Downloads, as well as Magento, OpenCart, Joomla, and Sirclo. In this post, we will cover the basic ideas of Devilbox & a quick tutorial on how to setup WordPress in just few minutes.

## [New Auto Scaling Strategy with HashiCorp Nomad](https://www.hashicorp.com/blog/new-auto-scaling-strategy-with-hashicorp-nomad)

The Nomad Autoscaler has new plugins and capabilities to make it easier to achieve consistent autoscaling across cloud providers. APM plugins query and retrieve metrics from application performance monitoring systems. Strategy plugins calculate what changes the AutosCaler must do to meet the policy defined by operators. Target plugins apply the changes specified by the AutoCaler into infrastructure components. New strategy plugins are better suited for situations where the existing target-value strategy is not a good fit. The pass-through strategy is very simple in principle, but very powerful in practice.

## [Understanding the Kubernetes Attack Surface](https://rawcode7.medium.com/understanding-the-kubernetes-attack-surface-9a48ebcb6bc4)

The 4C’s of Cloud Native security are Cloud, Clusters, Containers, and Code. This layered approach augments the defense in depth computing approach to security, which is widely regarded as a best practice for securing software systems. It is absolutely important to cover the fundamentals: Your cluster is as secure as the system running it. Never expose a port, which doesn’t need exposure, which should be firewalled from public access. Use a private topology to avoid exposing anything critical to the public by mistake or lack of knowledge.

## [Dependabot Is GitHub Native Only](https://medium.com/geekculture/dependabot-is-github-native-only-6b62d048638)

Dependabot Preview is now part of the GitHub platform offering vulnerability scanning of public and private repositories. The migration path is top class and the integration in the Repository Dashboard just makes everything more cohesive and familiar. Auto-Merge option is gone and it does not look like it is coming back any time soon. The GitHub-native implementation does not offer the Live Updates which would create a PR a soon as a new dependency version is released. The new version is still caught within 24 hours (assuming a daily scan)

## [15 Point Kubernetes Security Checklist](https://containerjournal.com/editorial-calendar/rsa/15-point-kubernetes-security-checklist/)

Kubernetes has become an increasingly (and concerningly) frequent attack surface. Attackers exploit critical vulnerabilities to interfere with or infiltrate containers at every stage of the pipeline. Enterprises must be better about anticipating attacks, avoid deprioritizing security and implement protections across their entire infrastructure. The checklist offers a systematic approach to achieving defense-in-depth and addressing the range of threats your deployments may face. It also offers an automated security approach to succeed across containers and applications. The list includes: Harden your operating system, harden your containers by limiting their lifespans.

## [When To Use GraphQL and How It Compares to REST](https://medium.com/capital-one-tech/when-to-use-graphql-and-how-it-compares-to-rest-632afc621160)

GraphQL has been developed at Facebook in 2012 and a query language for APIs and a runtime for executing those queries. GraphQL is an alternative to REST that is faster and more flexible to handle changing client requirements. Backend for Frontend (BFF) is a separate backend for each UI interface which gets optimized for that front end, without worrying about affecting other frontend experiences. The single customized endpoint on the BFF aggregates data from multiple microservices, filters what is needed for the mobile channel, and then returns only necessary data.