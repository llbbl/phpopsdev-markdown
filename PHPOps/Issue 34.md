# DevOps / SRE — Top Links Last Week

## Week 27 Issue #34

## [Kubernetes Essential Tools 2021](https://itnext.io/kubernetes-essential-tools-2021-def12e84c572)

In this article I will try to summarize my favorite tools for Kubernetes with special emphasis on the newest and lesser known tools which I think will become very popular. This is just my personal list based on my experience but, in order to avoid biases, I will also mention alternatives to each tool so you can compare and decide based on your needs. K9s is an excellent choice for those who prefer a lightweight terminal alternative. Helm is mature, has lots of pre defined charts, great support and it is easy to use.

## [Helm 101 for Developers](https://levelup.gitconnected.com/helm-101-for-developers-1c28e734937e)

Helm is a package manager for Kubernetes applications. Over 60% of CNCF survey respondents prefer Helm over alternative solutions. Helm packages applications into charts, which is a collection of YAML and helper templates. Helm charts are packaged as tar files and stored in repositories similar to Docker registries. For developers with little experience in DevOps, how do we get comfortable with Helm? In this post, we’ll break down the key concepts to understanding Helm structure and best practices to navigate the Helm world with ease.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [TechStrong Con](https://www.mediaopsevents.com/techstrongcon/home)

```
        Now in its second year, TechStrong Con continues to serve as a testament to the ways in which technology can improve human existence. Digital transformation, DevOps, cloud-native and cybersecurity all have played major roles in enabling organizations to move beyond survival mode and offer transformative and experiential services and environments that are shaping the new normal. This year’s TechStrong Con also will explore the future of hybrid, from events and workplaces to infrastructures. Join us as we continue to explore lessons learned from the pandemic and how tech can lead the way forward.
```

## [Cloud Native Software’s Technical Debt Is Growing](https://thenewstack.io/cloud-native-softwares-technical-debt-is-growing/)

Software development has undergone significant changes in the last decade. Software is no longer built completely in-house and instead, there is now what is known as the software supply chain. Modern applications are glue code and as much as 90% of software can be from third-party components. Modern software feels like a constant race to update the components to prevent the whole thing from breaking, with no control over the clock. Software maintenance typically takes 20-30% of the developer’s time.

## [Designing Our Serverless Engine: From Kubernetes to Nomad, Firecracker, and Kuma](https://www.koyeb.com/blog/the-koyeb-serverless-engine-from-kubernetes-to-nomad-firecracker-and-kuma)

At Koyeb, we are building a next-generation serverless platform that should be the fastest way to deploy applications globally. There are four core pillars we want to achieve: Fast, Global, Secure, Scalable, Fast and Secure. To be competitive on the market, we need to offer a scalable platform for our end-users. To better support our customers all around the world, we have a list of requirements, let's move to the technical level of abstraction. We considered all options to build a full-featured platform which would be able to support our mission and our own growth.

## [This Week in Programming: GitHub Copilot and the Generational Divide](https://thenewstack.io/this-week-in-programming-github-copilot-and-the-generational-divide/)

Last week, a lawsuit over the use of "GitHub Copilot" is in the works. The program uses all of the company's code, including that of Microsoft, to make software available for free. The legal battle is just now getting underway, with some saying it's illegal to use Copilot in how it was designed to just ignore software licenses. But others say it's a good idea even for open source software.

## [Infrastructure as Code: Pulumi challenges Terraform](https://faun.pub/infrastructure-as-code-pulumi-challenges-terraform-633658d51ad7)

Pulumi IaC is considered by many to be the biggest competitor to Terraform. Pulumi can be integrated with existing code and can be used alongside with known programming languages such as Node JS, C#, Python, Go, Go. The verdict: The competition will continue and both technologies will respond to the other fairly quick e.g. Terraform responded with TF CDK. For now, I will keep using Terraform as I am most familiar with, but I am open to use and learn Pulumi when it’s needed.

## [7 Kubernetes Scanners to Find Security Vulnerabilities and Misconfigurations](https://aws.plainenglish.io/8-kubernetes-scanner-to-find-security-vulnerability-and-misconfiguration-9d252266c8c1)

Kubernetes is used in some form or another by more than 80% of companies today. It basically optimizes container provisioning settings and administration. However, security is one of the most important aspects of any containerized program. There are several third-party open-source tools available to assist you in securing your Kubernees clusters. These tools include Kube Hunter, Kube Bench and Kubei, Checkov and Kubesecubesec. It's built-in Python and seeks to improve security adoption and compliance.

## [Multi-clustered architectures to scale big data systems](https://medium.com/creditorwatch/multi-clustered-architectures-to-scale-big-data-systems-922412c4550c)

In CreditorWatch, we use Hadoop clusters in combination with Spark and R to produce hundreds of billions of data points every month. Multi-clustered architectures to scale big data systems are one of the trickiest disciplines in software engineering and software architecture. This is the actual story of the alternatives that were considered and how our architecture evolved until reach a final multi-clusered architecture that we happily use in production to the day. The first approach was simple. We followed a simple design in which a data pipeline with several stages runs.

## [What is FindInMap in AWS CloudFormation?](https://aws.plainenglish.io/what-is-findinmap-in-aws-cloudformation-33fddb61ab07)

The mappings function in CloudFormation has a very practical use-case for EC2 Instance ImageId. The same image such as Amazon Linux 2 differs between regions. The above template could only be used in the Asia Pacific Southeast Singapore region. If you would like to deploy the same stack in US Ohio, you need to change the ImageId to the one in the US Ohio region. However, this causes the below disadvantages: Hard to maintain if your application is deployed to several regions.

## [Machine learning model serving for newbies with MLflow](https://medium.com/@maria.t.patterson/machine-learning-model-serving-for-newbies-with-mlflow-76f9f0ac3cb2)

A fully-reproducible, Dockerized, step-by-step tutorial for building an API for your sklearn model. A common problem in machine learning is the fumbling handoff between the data scientists building machine learning models and the engineers trying to integrate these models into working software. MLflow is an “open source platform to manage the ML lifecycle, including experimentation, reproducibility, deployment, and a central model registry” MLflow works with pretty much every programming language you might use for machine learning.

## [Fluvio: A programmable data platform](https://www.infinyon.com/blog/2021/06/introducing-fluvio/)

In the last few years, organizations started to adopt stream processing architectures to power a new generation of data-driven services that can detect events, predict behaviors, and respond to customer demand in real-time. Softbank estimates over 1 trillion devices connected on the Internet of things by 2025 driven by wearables, drones, self-driving cars, inter-connected devices, and more. The Data Mesh white paper explains how current data paradigms are ill-suited for modern organizations. We believe organizations that choose data streaming technology will enjoy an impactful, long-lasting competitive advantage.

## [Against SQL](https://scattered-thoughts.net/writing/against-sql/)

There is potentially a huge amount of value to be unlocked by replacing SQL, and more generally in rethinking where and how we draw the lines between databases, query languages and programming languages. The best we can do is add the use of json to the SQL spec and hope that all databases all implement all the databases are compatible in the same way in the way it does. The core message that I want people to take away is that there is potentially. a huge. amount of. value to. be unlocked. by replacing. SQL.

## [How DevSecOps Can Replace DevOps To Offer Better Security](https://betterprogramming.pub/how-devsecops-can-replace-devops-to-offer-better-security-3dedd413885b)

There is a high risk of security breaches due to a lack of visibility. The Limitations of DevOps have some limitations, but it is a viable approach for modern business. You have to tweak things a bit to implement a correct DevOps approach. A company or group of people must be ready to embrace new software and implement it according to its best practices. When it comes to security, people are reluctant to accept any responsibility until they can see the added value and organization. When you implement technology, technology won’t yield results if it’s not being used properly.

## [Integration static code analyzer to PHP projects.](https://legion112.medium.com/integration-static-code-analyzer-to-php-projects-614db13d0e65)

Using static analyzer (SA) tools, you can determine whether your code is correct or not without executing it. Precompiled languages such as Java, C, Go, etc., have built-in code analyzers, they look at your code before actually executing it and analyze whether it is valid or not from the perspective of rules of a particular language. Using such an analyzer, you could see it points out that the “thisFunctionNameIsNotExist” does not exist. PHP language does not have such functionality right out of the box.

## [Serverless Laravel Made Easy with Bref](https://aws.plainenglish.io/serverless-laravel-made-easy-with-bref-cdbeeed53ef4)

Serverless Laravel Made Easy with Bref package and AWS Lambda. Bref is an open-source composer package, that is used to deploy PHP (Laravel) applications to Lambda. Bref uses serverless framework to deploy and configure the serverless application. The serverless app will be hosted in us-east-1 region, if you want to change the region use can change region in serverless.yml file and the properties you can configure in it. The application is hosted in Lambda in the US-East region (34$045/month)

## [npm, yarn, pnpm — Which Node.js Package Manager Should You Use?](https://javascript.plainenglish.io/npm-yarn-pnpm-which-node-js-package-manager-should-you-use-a2a1378694f7)

Node.js is built around packages which you can install when you need them. Package managers take care of the installation, updating and removal of these packages. The Yarn workspaces aim to make working with monorepos easy, solving one of the main use cases for yarn link in a more declarative way. But which one is the fastest, most reliable, and offers the best developer experience? Let’s check out the specs and figure out which one can be the best.

## [Software Development Is Misunderstood ; Quality Is Fastest Way to Get Code Into Production](https://itnext.io/software-development-is-misunderstood-quality-is-fastest-way-to-get-code-into-production-f1f5a0792c69)

Software Development Is Misunderstood because the focus is on the short term creation but quality is fastest way to get software into production. Quality code makes maintenance easier and reduces code interaction times. Low quality code slowly creates more problems and slows down development. 66% of technology projects end in partial or total failure because software development is misunderstood. Software development is a creative process; an original masterpiece not a paint by numbers and why software estimates are wrong. Software requirements are not understood upfront and the right version of software is identified after using the software.

## [Building a data team at a mid-stage startup](https://erikbern.com/2021/07/07/the-data-team-a-short-story.html)

The story is a made up story based on n-th hand experiences (for n ≤ 3), and quite opinionated. It's a story about teams and organization, not the tech itself. The story could take place at many different types of companies, but it could take a different kind of company. The first few hours, you get access to all the major systems and discover some interesting code. You start to probe into the data practices of the marketing team. The real problem is that the growth team aren't converting all the traffic we're driving to the site.

## [Measuring security risks in open source software](https://security.googleblog.com/2021/07/measuring-security-risks-in-open-source.html)

With Branch-Protection check, developers can verify that the project enforces mandatory code review from another developer before code is committed. Malicious contributors with malicious intent or compromised accounts can introduce potential backdoors into code. Despite best efforts by developers and peer reviews, vulnerable code can enter source control and remain undetected. We have added checks to detect if a project uses Fuzzing and SAST tools as part of their CI/CD system. Scorecards checks for these anti-patterns with the new Frozen-Deps check for malicious dependency attacks.

## [Managing SSH Access at Scale with HashiCorp Vault](https://www.hashicorp.com/blog/managing-ssh-access-at-scale-with-hashicorp-vault)

Learn how to build scalable, role-based SSH access with SSH certificates and HashiCorp Vault. The likelihood of incidents due to SSH key mismanagement is growing, and so is the level of harm these incidents can cause. This architecture is designed to achieve the following outcomes: Enable and enforce identity-based security, where users and applications must authenticate first before being granted the ability to SSH into a host. It can be used in any environment: private, hybrid, or multi-cloud.

## [YouTube’s recommender AI still a horrorshow, finds major crowdsourced study](https://techcrunch.com/2021/07/07/youtubes-recommender-ai-still-a-horrorshow-finds-major-crowdsourced-study/)

YouTube’s video-recommending algorithm has been accused of fueling a grab bag of societal ills by feeding users an AI-amplified diet of hate speech, political extremism and/or conspiracy junk/disinformation for the profiteering motive of trying to keep billions of eyeballs stuck to its ad inventory. New research published today by Mozilla backs that notion up, suggesting YouTube's AI continues to puff up piles of “bottom-feeding”/low-grade/divisive/disinforming content. Google has been pretty successful at fuzzing criticism with superficial claims of reform.

