# DevOps / SRE — Top Links Last Week

## Week 14 Issue #21

## [Ory Keto, open source authorization server based on Google Zanzibar](https://github.com/ory/keto)

Ory Keto is the first and only open source implementation of "Zanzibar: Google's Consistent, Global Authorization System" The ORY stack protects 16,000.000+ API requests every month with over 250,000+ active service nodes. It has maintained 95th-percentile latency of less than 10 milliseconds and availability of greater than 99.999% over 3 years of production use. Ory is an API-first Identity and User Management system that is built according to cloud best practices.

## [Modern CI is too complex and misdirected](https://gregoryszorc.com/blog/2021/04/07/modern-ci-is-too-complex-and-misdirected/)

The state of CI platforms is much stronger than it was just a few years ago. Centralized CI platforms like GitHub Actions, GitLab Pipelines, and Bitbucket provide benefits of scale, as the Internet serves as a collective information repository for how to use them. CI platforms typically throw in a bunch of value-add features to enable you to ship software more easily. The advancements in CI platforms have come at a cost: increased complexity. I'm coming around to the belief that modern CI systems are too complex.

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Okta Expands Free Identity Management Services, Cloud Native Deployment Options](https://thenewstack.io/okta-expands-free-identity-management-services-cloud-native-deployment-options/)

Okta has expanded its free tier of authentication, authorization and user management tools for developers. The Okta Starter Developer Edition can now accommodate up to 15,000 monthly active users, up from the previous iteration. The company has streamlined the interface for developers, adding support for many new web and cloud native technologies. Okta will reveal more details of all these new and refreshed offerings at its annual user conference, Oktane21, being held virtually this week. It includes enhanced documentation, sample applications, and new integrations to weave in continuous integration and continuous delivery systems.

## [Cloudflare Pages is now Generally Available](https://blog.cloudflare.com/cloudflare-pages-ga/)

In December, we announced the beta of Cloudflare Pages: a fast, secure, and free way for frontend developers to build, host, and collaborate on Jamstack sites. We’re also excited to show off some of the new features we’ve been working on over the course of the beta, including: web analytics, built in redirects, protected previews, live previews, and optimized images (oh, my!). In just a few months of beta, thousands of developers have deployed over ten thousand projects.

## [Ultimate VueJS Resources🛠 For Developers👨‍💻](https://dev.to/theme_selection/ultimate-vuejs-resources-for-developers-3bbk)

VueJS is a progressive JavaScript framework for building user interfaces. It is a combination of Vue.js and the world’s most popular front-end CSS library, Bootstrap.js. It makes all Bootstrap elements, such as rows, columns, cards, and cards, available as Vue components. Vuexy is based on bootstrap Vue. It offers basic templates for Simple HTML, Webpack, NUXT, PWA, Electron, A La Carte, Apache Cordova.

## [Strong Security Doesn’t Have to Equate to Slow Development](https://thenewstack.io/strong-security-doesnt-have-to-equate-to-slow-development/)

Rob Juncker is CTO of Code42, the Insider Risk Management leader. Juncker: Developers thrive on innovation, moving fast, experimenting and rebuilding. Security professionals are pragmatic, risk-averse and are often misrepresented as “policing” company activity. At Code42 we created an integrated security and developer culture that allows us to build software at the speed customers and developers expect while integrating security at every step of the software development process. It’s made a big difference in how our DevOps and SecOps teams work together.

## [The Software Engineer’s Complete Guide to Code Quality](https://betterprogramming.pub/the-engineers-complete-guide-to-code-quality-dfa8d490c05e)

There are several things that separate good quality code from poor quality code. Good code quality refers to the attributes and characteristics of your code. These may differ according to your organization's specific business focus and the needs of your team. A code review ensures code is efficient, efficient, well written and adheres to agreed-upon standards or a style guide. A style guide provides a company's standard conventions (such as naming conventions) and other best practices within one place. The earlier you find errors, the faster, easier, and cheaper they are to resolve.

## [Demystifying GitLab CI/CD Variables](https://about.gitlab.com/blog/2021/04/09/demystifying-ci-cd-variables/)

GitLab provides a lot of flexibility when it comes to defining and using variables. They are extremely useful for controlling your jobs and pipelines, and they help you avoid hard-coding values in your GitLab-ci.yml configuration file. In GitLab, variables can be used to customize your jobs by defining and storing values that they could make use of. When you use variables, you don't have to hard code values. Variables are useful for configuring third party services for different environments like testing, staging, production, etc.

## [Gitpod Revamps Dev Automation Tool](https://devops.com/gitpod-revamps-dev-automation-tool/)

Gitpod has made Microsoft VS Code its default tool for editing code. The company claims there are now more than 350,000 developers using its tool that creates a Kubernetes pod on each developer machine. The overall goal is to eliminate the time developers waste setting up application development environments so they can write code on their own machines. That approach also makes it simpler for developers to collaborate around the same application development environment regardless of where they happen to be physically located, says Gitpod CEO Sven Efftinge.

## [We scaled the GitHub API with a sharded, replicated rate limiter in Redis](https://github.blog/2021-04-05-how-we-scaled-github-api-sharded-replicated-rate-limiter-redis/)

A year ago, we migrated an old rate limiter in order to serve more traffic and accommodate a more resilient platform architecture. We adopted a replicated Redis backend with client-side sharding. In the end, it worked out great, but we learned some lessons along the way. We used a feature flag to gate access to the new backend, and the bug reports started flowing in. Some clients had their requests rejected for being over the limit, but the response headers said the X-Rate-Reset header “wobbled” – it might show 2020-01-01 10:00:00 for one request but the request was rejected.

## [How to Learn Complex Things Quickly: A Guide](https://product.hubspot.com/blog/how-to-learn-complex-things-quickly)

In his 20+ years as a software engineer, I’ve constantly been asked or expected to learn complex things. New languages and platforms are launched, projects get new requirements, libraries and frameworks release new versions. I'm a breadth first, experiential learner. I try stuff and when it doesn’t work, I try something else, moving on to the next step as soon as it ‘works’ This helps me create an ever clearer mental model with each iteration.

## [Orchestrating ETL pipelines on AWS with Glue, StepFunctions, and Cloudformation](https://faun.pub/orchestrating-etl-pipelines-on-aws-with-glue-stepfunctions-and-cloudformation-1910f74d4704?source=rss----10d1a7495d39---4)

Orchestrating ETL pipelines on AWS with Glue, StepFunctions, and Cloudformation beSharp. Big Data analytics is becoming increasingly important to draft major business choices in corporations of all sizes. AWS is the pack leader with the versatile Glue and S3 services which allow users to ingest transform, and normalize store datasets. Glue Catalog and Athena let users easily run Presto-based queries on normalized data in S3 data lakes, whose results can easily be stored and analyzed in business intelligence tools such as QuickSight.

## [How To Handle Worker Threads in Node.js](https://livecodestream.dev/post/how-to-work-with-worker-threads-in-nodejs/)

Node’s single-threaded nature makes Node applications easily scalable and resource-efficient. But it also makes Node an unsuitable choice for implementing CPU-intensive tasks. In v10.5.0 release, Node introduced the concept of worker threads as a workaround to this problem. In this tutorial, we are going to give you a simplified introduction to worker threads and how to use them. To understand why worker threads are important, we’ll first discuss why exactly Node performs poorly when handling CPU intensive tasks.

## [An Introduction to Web Server Provisioning: Configure and Set Up Your AWS VM Automatically Using…](https://salibas.medium.com/an-introduction-to-web-server-provisioning-configure-and-set-up-your-aws-vm-automatically-using-b0fe8e334424)

An Introduction to Web Server Provisioning: Configure and Set Up Your AWS VM Automatically Using Ansible. This is going to be especially useful for developers who wish to automate their deployment process in order to accelerate shipping high-quality software. In this article, we will use Ansible to automate the provisioning of an Nginx web server on an AWS Ubuntu Virtual Machine (EC2) We will also automate the deployment of a simple web page on the same VM. The process of setting up the server before deployment is called Provisioning.

## [Get Involved with Docker](https://www.docker.com/blog/get-involved-with-docker/)

Every day, hundreds of passionate Docker users around the world contribute to Docker. There are many ways to get involved and start contributing to Docker.com. The website is entirely built on top of GitHub, is editable by the community and organized into six distinct sections. You'll find lots of tools and resources that will be continuously updated, including event handbooks. These handbooks are specifically designed with step-by-step guidance on how to run a workshop with a full list of topics to cover.

## [Unraveling Service Meshes: When and why do you need them?](https://blog.runx.dev/unraveling-service-meshes-when-and-why-do-you-need-them-ceba38263af2)

The rise of Kubernetes and its affiliated projects is one of the most recognizable new terms being thrown around is “Service Meshes” Yet, despite its popularity, there remains considerable lack of clarity and mystique surrounding the term. We will begin by clarifying the meaning of a Service Mesh, and use our refined understanding to know its purpose and through that the correct time to use it. The new service mesh “products” are not new, independent networking stacks, but rather a successive new software layer put on top of the existing setup.

## [Automate Your Go Applications With Gradle & Docker](https://israel-miles.medium.com/automate-your-go-applications-with-gradle-docker-3c4aa4ddd9bb)

Gradle is a build automation tool that can be used to define processes that make your projects reproducible. While Docker already adds a layer of reproducibility and containerization, you still have to handle the configuration and deployment of your Docker images and containers. Gradle offers plugins that can extend the capabilities of your project in a reproducible format. You can then define Gradle tasks to put these plugins to work. The first plugin on line 2 takes care of building our Docker image, and the second plugin automates running the image as a container.

## [Announcing HCP Vault General Availability](https://www.hashicorp.com/blog/vault-on-the-hashicorp-cloud-platform-ga)

HashiCorp Vault is now generally available as a fully managed service for AWS environments. HCP Vault allows organizations to get Vault clusters up and running quickly, providing access to best-in-class secrets management and encryption capabilities with the platform providing resilience and operational excellence as a service. At launch, the service is generally available in U.S. (Oregon and Virginia) and Europe (Frankfurt, Ireland, and London) at launch, we are offering a free month to new users.

## [Redefining Threat Modeling: Security team goes on vacation](https://segment.com/blog/redefining-threat-modeling/)

At Segment, threat modeling is the process of systematically identifying assets within a system or feature, brainstorming ways to compromise those assets, and designing ways to defend them. Security teams can often become bottlenecks on threat modeling and reviews due to the ratio between Security Engineers and Engineers in an organization. Security can then pick and choose which sessions they attend based on interests, priorities, and size of attack surfaces. Segment has created a self-serve threat modeling Utopia for developers and Security engineers.

## [Our journey to Kubernetes: Container design principles is your back bag](https://medium.com/coccoc-engineering-blog/our-journey-to-kubernetes-container-design-principles-is-your-back-bag-9166fc4736d2)

VU Minh Quan: Container design principle is your back bag. He explains how to run a Kubernetes (K8s) platform using good container design principles. Each container addresses a single concern and does it well. That make your application flexible and maintainable. It’s the fundamental principle of container application that you need to keep in mind. It means that no matter how a container is deployed, the other ones must be present at the same time and same place.

## [Feature Flags: Happy Customers, Efficient Developers, Faster Processes](https://medium.com/rise-engineering/feature-flags-happy-customers-efficient-developers-faster-processes-74cdbd4c6e84)

Feature-flagging is a concept in software engineering that can be thought of as a giant on/off switch for some part of the code. We use feature flagging to get feedback from our clients before releasing the new feature to everyone. Feature toggling employs the concept of incremental rollouts which allows code to be deployed into production but not necessarily available to clients just yet. Split.io is a service that allows engineers to fine-tune how deep they want to feature-flag something.

## [Dealing With Code Smells and Metrics in Complex Software](https://betterprogramming.pub/dealing-with-code-smells-and-metrics-in-complex-software-879f9fc4a767)

When Is Software Considered Complex (Complexity Smells)? We have to ask ourselves: Is it clear enough that we can easily understand it after two years? The idea is not to fill our code with comments but to write an understandable code. There are two types of complexities: one related to code and the other related to design complexity. Complexity is the major constraint that dampens the evolution of software. If code is difficult to test, understandability is a means of technical control. Unit testing is the first level of complexity control.