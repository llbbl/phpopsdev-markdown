# DevOps / SRE - Top Links Last Week

## Week 30 - Issue #89

  

32 links

  

## [Google’s in-house desktop Linux](https://www.computerworld.com/article/3668548/the-story-behind-google-s-in-house-desktop-linux.html)

Google has been using Linux for its desktop computers for over a decade and has created its own Linux distribution (gLinux) and workflow system (Sieve) to manage upgrades and patches. Google plans to contribute more to the upstream Debian project.

  

  

## [Monitoring MySQL using Prometheus, Grafana, and mysqld\_exporter in Kubernetes](https://kapilbk1996.medium.com/monitoring-mysql-using-prometheus-and-grafana-in-kubernetes-16e7ae3de5dd)

This guide covers monitoring a MySQL database in a Kubernetes environment using Prometheus and Grafana. It walks through creating a namespace, MySQL StatefulSet, configuring Prometheus to scrape metrics from mysqld\_exporter, and setting up Grafana to use Prometheus as a data source.\_

  

## [You Don't Need Microservices](https://itnext.io/you-dont-need-microservices-2ad8508b9e27)

Microservices are expensive, difficult to maintain, and not always necessary. However, you can achieve many of the benefits of microservices by simply increasing the size or number of boxes available across the board, routing traffic to independently scalable clusters of your app instance, or separating asynchronous tasks into background jobs with independently scalable queues.

  

  

## [Goodbye Sealed Secrets, hello SOPS](https://itnext.io/goodbye-sealed-secrets-hello-sops-3ee6a92662bb)

Sops is a binary that encrypts configuration files. It understands format (JSON, YAML, INI, etc.) and will only encrypt the values of each line (in a key/value pair).

  

Sops provides the following advantages:

  

-The private and public keys created by Age are stored inside the file key.txt. We moved this file inside a .sops directory inside the home folder.

  

-To tell Sops where everything is, add these ENV variables to your shell configuration (/.bashrc or /.zshrc)

  

## [Convert Pod to Deployment in Kubernetes](https://medium.com/@whaleberry/convert-pod-to-deployment-in-Kubernetes-b0f2fc362b21)

How to convert a pod to a deployment:

  

1. Get the current pod's YAML

2. Copy a deployment example YAML and put the pod's metadata and spec into the deployment's template section

3. Deploy the merged deployment manifest

  

## [Basics of Load Balancing](https://blog.devgenius.io/basics-of-load-balancing-f8a1abd97ece)

Load balancing is routing client requests to the best available server at a given time for the best utilization of available resources. This is done abstractly to clients, so they are unaware of the number of servers in the backend. Load balancing can be implemented by adding more machines and installing the service on them, then routing requests through a proxy. This strategy makes the system more reliable and resilient to handle high loads.

  

---

  

  

## [Running a Flask API Application on Openshift With Nginx As Reverse Proxy](https://betterprogramming.pub/running-a-flask-api-application-on-openshift-with-nginx-as-reverse-proxy-6f3797f7b4db)

Use quay.io to store images for a Flask app and an Nginx reverse proxy

- Configure the Nginx proxy to send traffic to the Flask app via its service name and port

- Launch the apps on Openshift and create a route for the Nginx proxy

  

## [Managing the Looker ecosystem at scale with SRE and DevOps practices](https://cloud.google.com/blog/products/devops-sre/using-devops-and-sre-principles-to-manage-looker/)

Looker is a platform that helps segmented teams in large organizations work with data more efficiently. The platform is central to a data-rich organization, and teams must start with aligned goals and commit to strong collaboration to succeed. While DevOps and SRE practices can guide teams through the complexities of managing large amounts of data, there is also the potential for teams to over-engineer their data management processes, which can lead to increased complexity and wasted effort.

  

## [Build your web framework](https://vercel.com/blog/build-your-own-web-framework)

This article explains how to build your web framework using the Vercel Build Output API. The framework should support static and server-rendered pages, image optimization, and edge caching.

  

## [Best 8 Automated Software Testing Tools to Consider](https://ajaykapoor1509.medium.com/4bf8452d4c1c)

Many automated software testing tools are available on the market, each with its own features. Postman, SoapUI, Eggplant Functional, Tricentis Tosca, Apache JMeter, Robot Framework, and Protractor are all worth considering for your next project.

  

## [Git from Scratch: Basic Git Terminologies](https://medium.com/@senevirathnehu/git-from-scratch-basic-git-terminologies-2b8c663ea592)

A Git repository is a database that stores information about revisions and the history of a project. A local repository is stored on your computer, while a remote repository is stored on the internet. A branch represents an independent line of development. A commit represents a change made to the repository. The index is a temporary file that describes the repository's directory structure. Cherry-picking is used to apply a commit from one branch to another. Stashing allows you to switch branches without committing the current branch. A fork is a copy of a repository. Finally, a pull request is a way for a developer to tell.

  

  

## [Kubernetes: Run NGINX Containers Using YAML File](https://medium.com/@kinseyparham/kubernetes-run-nginx-containers-using-yaml-file-a37c115caf7e)

This article covers creating a deployment that runs an NGINX container on a Kubernetes cluster. It also covers how to do the same thing using a YAML file.

  

## [S3 isn't getting cheaper](https://matt-rickard.com/10-years-and-s3-isnt-getting-cheaper/)

Matt Rickard argues that storage costs are not decreasing as rapidly as one might expect and that AWS has significant pricing power when it comes to storage due to the complexity of its S3 service. He cites Clayton Christensen's work on the Innovator's Dilemma to support his claim.

  

## [Fly.io wants to change the way companies deploy apps at the edge](https://techcrunch.com/2022/07/28/fly-io-wants-to-change-the-way-companies-deploy-apps-at-the-edge/)

Fly.io wants to change how companies deploy apps at the edge by eliminating the need for a CDN. The company has raised $37 million to date, and it is hiring.

  

## [6 Git Features Every Programmer Should Know](https://levelup.gitconnected.com/6-git-features-every-programmer-should-know-9e9fd1e5b9b1)

Create a pull request to submit changes to a public repository. Use ssh for Github for increased security. Git submodules are useful for projects with dependencies. The .gitignore file tells Git which files are not to track.

  

## [Codefresh launches its hosted GitOps solution](https://techcrunch.com/2022/07/27/codefresh-launches-its-hosted-gitops-solution/)

Codefresh has launched a hosted GitOps service based on the Kubernetes-centric Argo open source project. The new service is free for community projects, individuals, and small teams. The service aims to give DevOps teams access to a GitOps platform that encodes some of the industry's best practices while still giving those teams the flexibility to tweak it to their needs.

  

## [Mirantis moves into ZeroOps by acquiring amazee.io](https://www.zdnet.com/article/mirantis-moves-into-zeroops-by-acquiring-amazee-io/#ftag=RSSbaffb68)

Mirantis 🚀Amazee

  

## [How I Back Up My Ghost Blog to a Cloud Storage](https://betterprogramming.pub/how-i-back-up-my-ghost-blog-to-a-cloud-storage-387524e3b524)

This article discusses various methods of backing up a Ghost blog, a type of website. The article details how to write a Bash script to automate the backup process. The article also covers scheduling regular backups using Crontab and testing the backups using Docker.

  

## [Creating a Custom Module for an EC2 Instance with Terraform](https://helenccampbell.medium.com/creating-a-custom-module-for-an-ec2-instance-with-terraform-eb624776f3c9)

Follow the steps in the article to create a custom module for an EC2 Instance with Terraform.

  

## [LiteFS a FUSE-based file system for replicating SQLite](https://github.com/superfly/litefs)

LiteFS is a FUSE-based file system for replicating SQLite databases across a cluster of machines. It is currently in an alpha state and only works on Linux.

  

## [How to Remove Sensitive Data and Plaintext Secrets From GitHub](https://www.secjuice.com/github-complete-cleaning-sensitive-secrets/)

To clean your GitHub commit history of sensitive data, you must first remove all the secrets from each repository, then use BFG Repo-Cleaner to clean the commits. However, BFG Repo-Cleaner will only clean the checked-out git branch, so you must repeat the process for every branch. Additionally, since GitHub PRs are independent of the git repository, you must manually remove all the PRs and their commits. Finally, to help prevent sensitive data from being committed in the future, you can use a git pre-commit hook.

  

## [Snyk adds policy-based code security to its arsenal](https://techcrunch.com/2022/07/26/snyk-adds-policy-based-code-security-to-its-arsenal/)

Snyk, a Boston-based security company, has acquired Fugue, a developer-focused cloud security company, for an undisclosed amount. With this acquisition, Snyk adds a policy engine to its arsenal, enabling security teams to hardcode complex rules into the system to fix problems before they become an issue. The product is available to a limited group of customers starting today, with general availability expected later this year.

  

## [PhpStorm Plugins You Should Know](https://levelup.gitconnected.com/phpstorm-plugins-you-should-know-ea4e51aeee69)

This person discusses three plugins for the PhpStorm IDE that they find particularly useful. These are PHP Code Sniffer, GitLive, and Database Navigator. They also mention a plugin for Symfony development.

  

## [Getting Started with Ephemeral Containers](https://metalbear.co/blog/getting-started-with-ephemeral-containers/)

Ephemeral containers let us run a container with a specific image in the context of an already running container in a Pod. This comes in handy when debugging/troubleshooting distroless images or images that lack certain utilities, where kubectl exec won't be helpful.

  

## [How to Save and Move Docker Images](https://betterprogramming.pub/how-to-save-and-move-docker-images-9c43a3d47225)

This article covers two different ways to save and move Docker images: the "save/load" commands or the "export/import" commands. It explains the difference between the two methods and when to use each.

  

## [5 Qualities in Awesome Tech Managers](https://betterprogramming.pub/5-qualities-in-awesome-tech-managers-a36df418a84e)

Being a great tech manager requires empathy, understanding, the ability to learn, and time management skills.

  

## [3 Scenarios Where You Can Store JWT Token in Your DB](https://betterprogramming.pub/should-we-store-tokens-in-db-af30212b7f22)

JWT tokens can be stored in a database in scenarios such as when a user clicks on "resend verification email" or "forgot password."

- In these cases, the server needs to store all the tokens or only the latest one in the database

- After a user clicks on a link, the token in the API request payload is matched with the latest token in the database for that user, and all the tokens for that user must be deleted

  

## [A Detailed Guide To Understand How Git-Rebase Works](https://betterprogramming.pub/a-detailed-guide-to-understand-how-git-rebase-works-2848e980e5e4)

This blog covers the basics of how the Git rebase command works. It goes over when rebase is useful, how to use it in different scenarios, and some of the pros and cons of rebasing compared to other Git commands.

  

## [Headless CMS Strapi Plans a Platform-as-a-Service](https://thenewstack.io/headless-cms-strapi-to-offer-cloud-platform-as-a-service/)

Headless CMS Strapi is planning to launch a platform-as-a-service offering in 2023. The PaaS model will allow the company to target developers who don't want to manage application infrastructure. Strapi is Node. js-based and 100% JavaScript. It runs an HTTP server based on Koa, a backend JavaScript framework. A platform-as-a-service approach supports more customization and flexibility than a software-as-a-service approach. The CMS has 2,000 plugins developed by the community in its ecosystem.

  

## [Cybersecurity Apprenticeships Don't Address Core Issues](https://thenewstack.io/cybersecurity-apprenticeships-dont-address-core-issues/)

Apprenticeships are being promoted as an alternative to college to try and address the shortage of people working in cybersecurity. Still, they are more likely to lead to jobs that are entry points into the cybersecurity field rather than actual cybersecurity jobs. Cybersecurity jobs require highly skilled and experienced professionals, and a college degree is still seen as the best way to get one of these jobs.

  

## [Overview of Consistency Levels in Database Systems](http://dbmsmusings.blogspot.com/2019/07/overview-of-consistency-levels-in.html)

Dbms should support complex integrity constraints to ensure semantic consistency.

  

  

## [The Difference Between Validating and Mutating Webhooks](https://medium.com/nerd-for-tech/the-difference-between-validating-and-mutating-webhooks-167757f8db5f)

Webhooks can be used to modify the incoming request data before it is validated. For example, the mutation webhook is executed before the validation webhook. The mutation webhook can add missing data to the request so that the validation webhook will not reject it.