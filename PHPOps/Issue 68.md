# DevOps / SRE - Top Links Last Week

## Week 9 - Issue #68

  

20 links

  

## [How to secure anything](https://github.com/veeral-patel/how-to-secure-anything)

In this repo, I aim to document a process for securing anything, whether it's a medieval castle, an art museum, or a computer network. Security engineering isn't about adding a bunch of controls to something. It's about coming up with security properties you'd like a system to have, choosing mechanisms that enforce these properties, and assuring yourself that your security properties hold. The process I like for securing things: We follow as many best practices as possible. We write down our security policies or high-level security goals and develop a security model or spec we follow to satisfy our policies. We can then turn our policy into a more detailed specification.

  

## [Just say no to :latest](https://platformers.dev/log/2022-03-02-latest-literally-kills-puppies/)

It breaks one of the core requirements of continuous delivery: reproducible, idempotent builds. It can cause problems when trying to build your project, and at worst, in a production failure. Just say no to :latest in your Dockerfile! Or anywhere else! Do you want to live in a van down by the river? Don't specify latest in a Kubernetes Pod manifest. At least if you use the latest in your Dockerfile to create a versioned image, you could roll back to your previous versioned image if something happened.

  

## [Improve Your Pull Request Experience for AWS CDK Projects](https://betterprogramming.pub/improve-your-pull-request-experience-for-aws-cdk-projects-1fd5adb08bb3)

CDK-notifier is a small tool that helps you to improve the review process on GitHub pull requests. It gives more confidence to the changed resources of your AWS CDK stacks. It has been used for over five months successfully. We built the tool for CircleCI as this is our primary CI system. It will use the output of the CDK diff command to post the diff to pull a request as a comment. If there is no comment within one CDK stack, no comment will be sent.

  

## [Ballast: An adaptive load test framework](https://eng.uber.com/introducing-ballast-an-adaptive-load-test-framework/)

Uber's architecture has grown to encompass thousands of interdependent microservices. As a result, we need to test our mission-critical components at max load to preserve reliability. We developed Ballast, an adaptive load test framework that leverages traffic capture using Berkeley Packet Filter (BPF) and replays the traffic using a PID Controller mechanism to adjust the number of requests per second (RPS) to each service. Ballast removes the toil of writing, running, and supervising load tests improves coverage.

  

## [How to Run Docker in Rootless Mode](https://thenewstack.io/how-to-run-docker-in-rootless-mode/)

Rootless Docker takes advantage of user namespaces. This subsystem provides both privilege isolation and user identification segregation across processes. Rootless Docker will not have access to privileged ports, which is any port below 1024. The only limitation is that limiting resources with options such as –CPUs, –memory, and –pids-limit are only supported when running with cgroup v2 and systemd v2. Rootless Docker can be downloaded and installed with a single command.

  

---

  

## [How Kubernetes works under the hood with Docker Desktop](https://www.docker.com/blog/how-kubernetes-works-under-the-hood-with-docker-desktop/)

  

Docker Desktop makes developing applications for Kubernetes easy. It provides a smooth setup experience by hiding the complexity of the installation and wiring with the host. As a result, developers can focus entirely on their work rather than on the setup details. This blog post covers development use cases and what happens under the hood for each of them. The diagram below shows the interactions between the internal components of Docker Desktop for the cluster setup. The current-context, user, and cluster names are always set to docker-desktop while the global endpoint of the cluster is using the DNS name https://kubernetes.internal:6443.

  

## [Architecting Kubernetes Clusters for High-Traffic Websites](https://www.nginx.com/blog/microservices-march-architecting-kubernetes-clusters-for-high-traffic-websites/)

This blog is the second in our five‑part series about Kubernetes networking for Microservices March 2022: This week's Livestream provides a high‑level overview of the topic featuring subject matter experts from learnk8s and NGINX. So if you miss the live airing on March 7 – don't worry! You can catch it on demand! Next, read our four‑part blog series, A Guide to Choosing an Ingress Controller. Learn about risks you might introduce by selecting the wrong Ingress controller and how to future‑proof your selection.

  

## [We don't need runtime type checks](https://stitcher.io/blog/we-dont-need-runtime-type-checks)

Static analysis has the power to revolutionize the way we write PHP code much more than it already does today and how it can open doors to many new possibilities. First, we need a community-wide mind shift: there is a mountain of inertia around "The PHP Way," and it will take an equal and opposite mindset to alter the course. Most developers only want generics as a way to get better code insights while coding; does the "I want to know what items are in an array" argument ring a bell?

  

## [Pulumi Adds Business Critical Edition to Infrastructure Management Platform](https://devops.com/pulumi-adds-business-critical-edition-to-infrastructure-management-platform/)

Pulumi's Cloud Engineering Platform enables DevOps teams to use Pulumi Packages to create reusable components for automating IT infrastructure provisioning. Pulumi reported that adoption has accelerated across enterprises worldwide, with more than one million downloads per month. In addition, the company claimed it had seen 350% year-over-year growth of its enterprise customers, such as Mercedes-Benz, in the last 12 months. However, it's not clear whether development or IT operations teams will ultimately wind up managing infrastructure provisioning.

  

## [Why Encrypting Your CloudWatch Logs With KMS Is Easier Than You Think](https://aws.plainenglish.io/why-encrypting-your-cloudwatch-logs-with-kms-is-easier-than-you-think-364ad80bd281)

Why Encrypting your CloudWatch Logs With KMS is Easier Than You Think? This article shows how you can use KMS for encryption for the point of this article. It's easier to use KMS key policies to trust the CloudWatch service and a particular log group. The service needs key permissions, and it handles encrypting and decrypting transparently to the humans or apps using the logs. This way, you can assign the key least privilege permissions and tie them to the lifecycle of that logs group.

  

## [Knative becomes a CNCF project](https://techcrunch.com/2022/03/02/knative-becomes-a-cncf-project/)

The Cloud Native Computing Foundation (CNCF) has accepted Knative as a CNCF incubating project. Google will donate the Knative trademark, IP, and code to the foundation. The idea behind the project is to make it easier for its users to build, deploy and manage serverless and event-driven applications on top of Kubernetes. Bloomberg, Alibaba Cloud, Bloomberg, Bloomberg, and IBM already use it in production, while Google powers its serverless computing platform.

  

## [Security for package maintainers](https://sethmlarson.dev/blog/security-for-package-maintainers)

This article focuses on securing Accounts and Package Repositories: Configuring a project and deployment pipeline securely. I hope that some of the knowledge I've gained along the way can help you secure your packages and inspire some adversarial security-minded thinking. Email security is your top priority: Gmail or Outlook.com is your primary email account. NPM recently announced that all the complete 500 packages must use enforced 2FA as a requirement for publishing code to platforms. I sincerely hope that other ecosystems continue pushing to continue pushing for 2FA.

  

## [What the heck is Service Mesh?](https://levelup.gitconnected.com/what-the-heck-is-service-mesh-a2471ddc6f3b)

Service Mesh provides an infrastructure layer to handle inter-service communication. It makes communication secure and reliable. Other capabilities include load balancing, authentication, authorization, service discovery, container orchestration, and service discovery. The sidecar manages all inbound and outbound traffic, a proxy to securely communicate with other services. The service mesh can also authorize and authenticate requests from the web or between the services.

  

## [Kubernetes CRDs: What They Are and Why They Are Useful](https://thenewstack.io/kubernetes-crds-what-they-are-and-why-they-are-useful/)

Kubernetes is a container orchestrator, but it can do much more than that with custom resource definitions. Custom resource definitions, or CRDs, allow you to manage more than just containers. In this post, we learn what CRDs are and how to use them. Many companies don't even need to create any CRDs themselves, but many will install their own CRDs so many can be used to manage their cluster. If you're already using CRDs, you probably shouldn't jump into creating your own.

  

## [Are Blockchains Databases?](https://thenewstack.io/are-blockchains-databases/)

Tim Wagner is the inventor of AWS Lambda and a former general manager of Amazon Lambda. He has also served as VP of Engineering at Coinbase, where he managed design, security, and product management teams. With some databases now supporting versioning and checksums and blockchains storing more data types, are these technologies on a path to merge? In this article, we look at where these technologies have come from and where they're headed. You could say that keeping control of the data isolated to its owner is a defining characteristic of a modern cloud database.

  

## [Sprint Planning: Best Practices](https://betterprogramming.pub/sprint-planning-best-practices-1aad4103f6cb)

An approach for sprint planning that has proven to work well for my teams has been successful. I firmly believe that every team should experiment and find the best method for them. We break our planning meetings into the following parts: The goal represents users' value after the successful sprint. Next, the team breaks down the stories starting from the highest priority. At every step, the team defines the story's sub-tasks that need to be completed to meet the definition of done.

  

## [Lightweight and Efficient Database Alternatives For Python](https://betterprogramming.pub/lightweight-efficient-database-alternatives-for-python-bb990eee752)

Shelve is a simple way to store simple Python objects in a simple, efficient manner. TinyDB is a lightweight key-value store that is ultra-slim, relatively fast, and wildly simple to use. The Hierarchical Data Format (or HDF5) is a high-performance way of storing data from a disk. PickleDB is far from a full-blown database, but it's a great way to use Python without the administrative overhead of a traditional database. HDFF5 is a way to standardize distributing and sharing massive portions of scientific data.

  

## [Deploy Velero for Azure kubernetes cluster using ArgoCD](https://faun.pub/deploy-velero-for-azure-kubernetes-cluster-using-argocd-c1a28a643b32)

Velero is an open-source tool used for backup and restoring, disaster recovery, and migrating Kubernetes cluster resources. In addition, users can use Velero to replicate the production cluster to development and testing clusters. Velero consists of a server that runs on your cluster and a command-line client that runs locally. It is also possible to configure velero-credentials using the storage account access keys.

  

## [Sprint Planning: Should Velocity or Capacity Planning Be Used?](https://betterprogramming.pub/sprint-planning-should-velocity-or-capacity-planning-be-used-4fd2aa355d74)

Some say the best way is to rely on the team's velocity. Others say we should do capacity planning to be more accurate and do sprint planning correctly. In this article, we will look at the differences in velocity and capacity planning and discuss which type suits different teams. In another article, I will describe the approach I prefer to use for planning. Also, I will provide a tool (excel spreadsheet) for running the best planning meeting.

  

## [Building Blue/Green application deployment to Micro Focus Enterprise Server](https://aws.amazon.com/blogs/devops/building-blue-green-application-deployment-to-micro-focus-enterprise-server/)

This post is a continuation of our previous post, "Automate thousands of mainframe tests on AWS with the Micro Focus Enterprise Suite" We will explore the three crucial design "ingredients" to be implemented in the overall solution. Mainframe project teams use the first level of the pipeline to test project scope changes. The second level is used for system integration tests, where the pipeline will perform system tests for all of the project pipelines and perform extensive systems.

  

## [Multifactor Authentication Is Being Targeted by Hackers](https://thenewstack.io/multifactor-authentication-is-being-targeted-by-hackers/)

Proofpoint has found phishing kits adding MFA bypassing attacks to their features. These rely on a transparent reverse proxy. The same technology runs local man-in-the-middle (MitM) attacks to steal credentials and session cookies. The only exception is FIDO Universal 2nd Factor (U2F) protocol-based tokens. Zero trust will be tomorrow's personal authentication method of choice in the long run, but we're not there yet.