# DevOps / SRE - Top Links Last Week

## Week 16 - Issue #75

  

23 articles

  

## [Announcing new simple query options in Cloud Logging](https://cloud.google.com/blog/products/devops-sre/querying-logs-just-got-easier-in-cloud-logging/)

Logs Explorer adds a simple text search box for global text searches. Show/hide query toggle expands and closes Logging query language behind the query. Date/time display now respects date/time preferences set in Cloud Console settings. Dropdown selectors have also been improved to run the query each time a selection is made. This makes it easier to narrow logs quickly with each dropdown selection. For more complex queries, you can edit the query language directly.

  

## [Ubuntu 22.04 LTS](https://ubuntu.com/blog/ubuntu-22-04-lts-released)

Ubuntu 22.04 LTS features a real-time kernel for industrial applications, enterprise Active Directory, PCI-DSS, HIPAA, FIPS, and FedRAMP compliance – raising the bar for open source from cloud to cloud edge, IoT, and workstations. In addition, Ubuntu is deeply integrated into public clouds and optimized for performance, security, and ease of use. For example, confidential Computing is an essential new capability that significantly improves data protection and privacy in leading public clouds without requiring changes to existing application deployments.

  

## [Amazon Web Services fixes container escape in Log4Shell hotfix](https://www.bleepingcomputer.com/news/security/amazon-web-services-fixes-container-escape-in-log4shell-hotfix/)

Amazon Web Services (AWS) has fixed four security issues in its Log4Shell hot patch from December. Attackers could exploit the flaws through unprivileged processes to elevate privileges and execute code with root permissions. The vulnerabilities are currently tracked as high-severity risks with 8.8 out of 10. Amazon has also released a new advisory on the vulnerabilities above the official guidance to address the issues above. The fixes are not exclusive to Amazon resources and allow escaping a container in the environment and taking control of the host.

  

## [Laravel 9.9 Released](https://laravel-news.com/laravel-9-9-0)

The Laravel team released 9.9.0 with a configurable pluralizer, getAllTables() support for SQLite and SQLServer, an Eloquent Builder convenience method, and the ability to call throw() in a PendingRequest. You can see the complete list of new features and updates below and the diff between 9.0 and 9.8.0 on GitHub. The following release notes are directly from the changelog. The release notes follow Laravel's latest version of the Laravel software.

  

## [Memray: a memory profiler for Python](https://github.com/bloomberg/memray)

Memory is a memory profiler for Python. It can track memory allocations in Python code, native extension modules, and the Python interpreter itself. Traces every function call so it can accurately represent the call stack, unlike sampling profilers. It also handles native calls in "\`C/C++ "libraries, so the entire call stack is present in the results. Memory requires Python 3.7+ and can be easily installed using the most common Python packaging tools. Unfortunately, it only works on Linux and cannot be installed on other platforms.

  

—

  

  

## [These are the five most in-demand cloud computing jobs in 2022](https://thenextweb.com/news/5-most-in-demand-cloud-computing-jobs-2022)

Pippa is a content creator and writer for Amply by Jobbio. She's a work-from-home enthusiast who loves all things travel and tech. By 2030, Grand View Research predicts that the sector will make annual revenue of $1.6 trillion. So we've done the hard work for you and lined up the top five jobs in cloud computing — now, all you need to do is spruce up your CV. Then, you might future-proof your career.

  

## [Profile Layering for Helm Encourages Self Service for Kubernetes](https://www.weave.works/blog/profile-layering-for-helm-encourages-self-service-for-kubernetes)

Kubernetes is the de facto cloud-native platform for applications and operational teams. Weaveworks has helped many customers and users to declaratively provision and manage their clusters with tailored configurations and components that meet their business needs. Profiles offer the capability to define a Kubernetes cluster that is tailored to the needs of your platform and application team. In addition, they let you bootstrap essential components in areas such as observability (Prometheus, Grafana) and configure them as part of the cluster provisioning process through GitOps.

  

  

## [Securing #Container and #Kubernetes Ecosystems! ](https://twitter.com/bamitav/status/1517168765502382082)

Container security refers to tools, processes, and policies that aim to enhance the security competence of containers so that the applications they house may run free of incidents and vulnerabilities. A typical containerized architecture has three elements; the container engine, orchestrators, and managed Kubernetes services. A container contains an application and all the functions required to run it, making it specific to a single application. Therefore, a firm security boundary is critical with tasks such as hosting different applications on the same server or cluster.

  

## [The changing economics of open source](https://www.technologyreview.com/2022/04/21/1050788/the-changing-economics-of-open-source/)

Open-source software's early and explosive growth tested some of those original ideas to the breaking point. The diversity of projects today has challenged many of the initial principles of open source. For example, ElasticSearch changed its licensing terms in 2021 to include requiring cloud service providers who profit off its work to pay it forward by releasing the code for any management tools they build. Log4J was dubbed the "biggest bug on the internet" after a vulnerability was disclosed in December 2021. Amazon Web Services, which offered a managed service based on ElasticSearch until the change, created a new distribution for its OpenSearch product.

  

## [A Quick Performance Optimization Guide  Using PHP Generators](https://betterprogramming.pub/a-quick-performance-optimization-example-using-php-generators-9e71aac810e0)

PHP generators are an easy way to implement simple iterators without the overhead or complexity of implementing a class that implements the Iterator interface. Instead of returning once, a generator can yield as many times as it needs to provide the values to be iterated over. In addition, using generators, PHP only keeps track of the current state of the traversal (the value we're returning with yield) without needing to store the whole collection that's being traversed. This allows you to start working with the Nth item of the collection without worrying about the (N+1) item.

  

## [The Modern Software Supply Chain: How It's Evolved and What to Prepare For](https://www.darkreading.com/application-security/the-modern-software-supply-chain-how-it-s-evolved-and-what-to-prepare-for)

Software supply chain attacks are becoming more frequent and introducing more significant consequences. Modern software development has made the supply chain increasingly complex. In addition, current practices like agile development, CI/CD, and DevOps have accelerated the pace of product delivery. Any link in the software supply chain can be compromised, but current research highlights three main targets: dependencies, pipelines, and the combination of both — pipeline dependencies. These elements create complex software supply chains, which are attractive attack vectors and target malicious actors.

  

## [The Kubernetes to Nomad Cheat Sheet](https://www.hashicorp.com/blog/the-kubernetes-to-nomad-cheat-sheet)

For Kubernetes users looking to learn HashiCorp Nomad concepts and commands — or vice versa — we've designed a cheat sheet for quick reference and a fast onramp. This new, one-page reference PDF starts with a list of commands and their Nomad equivalents at the bottom. The community has also begun a GitHub page for collecting Nomad cheat sheets. It's now open for edits and additions by the community to add to the list of Nomad cheats sheets.

  

## [Whats New in PHP 8.2](https://stitcher.io/blog/new-in-php-82)

PHP 8.2 will probably be released at the end of 2022, but there's no date set yet. Null and false as standalone types could be considered valid types independently. Dynamic properties are deprecated in the new version of the language but will throw an ErrorException in PHP 9.0.0. Redact parameters in any code that sends traces to a service that keeps track of errors and will notify developers when something goes wrong when it goes wrong in the stack.

  

## [You probably don't need AWS and are better off without it](https://www.trickster.dev/post/you-probably-dont-need-aws-and-are-better-off-without-it/)

Amazon Web Services (AWS) is the most prominent large cloud provider globally. It is heavily marketed toward startups and big companies alike. An entire branch of the DevOps industry helps set up software systems on AWS. But is it that great? Is it suitable as a default choice to host a software system of any scale? Let us go through some arguments against going all-in with AWS and why many companies and individual side-project developers might be better off using something else.

  

## [Automation is the serialization of understanding](https://changelog.com/posts/automation-is-the-serialization-of-understanding)

This is a specified excerpt from Ship It! #44. Read the original transcript or listen to the entire conversation for more context. Kelsey: The fundamentals are very clear. For example, if you're thinking about application delivery, we know what the fundamentals are. These fundamentals can be applied using different tools. The tools are not the fundamentals. It's the ideas and concepts that we have been talking about today.

  

## [The Missing Kubernetes Type System](https://danielmangum.com/posts/the-missing-kubernetes-type-system/)

Crossplane and across the Kubernetes community, we lean in heavily to the idea that everything is "just an object" While this is true in some respects, it has led us to provide a weak separation between operations that define the cluster and those that are consuming the cluster. The degree of safety we get from a language is highly dependent on the type of system. For example, rust gives us some "unsafe" capabilities to provide the programmer with unfettered access to the machine's resources.

  

## [How to Optimize Images for Usage in Websites](https://betterprogramming.pub/how-to-optimize-images-for-usage-in-websites-9eaee88c2e6b)

Images are usually the most significant part of any application payload, and therefore it's a big area for optimization. In this article, we try to go along with all possible ways that help to make applications more efficient. We will focus on optimizing static images, which are included in our code base. All approaches are transferable for any other images stored in any 3d party service like Cloudinary, and we have a look at them more closely in the following articles. Lighthouse is an automated tool for improving the quality of web pages.

  

## [Tutorial: Manage Docker Swarm with Portainer](https://thenewstack.io/tutorial-manage-docker-swarm-with-portainer/)

The Docker Swarm container orchestration engine is a great way to utilize a cluster for your container deployments. Once you have your Docker Swarm up and running, you can deploy Portainer, and it will automatically pick up your controller and all of your nodes. You can deploy this setup on any Linux machine, but you'll need to modify the installation process to fit your distribution of choice. The Portainer container management system is an even easier way to manage Docker Swarm than Kubernetes.

  

## [Rancher K3s: Kubernetes on Proxmox Containers](https://betterprogramming.pub/rancher-k3s-kubernetes-on-proxmox-containers-2228100e2d13)

Rancher K3s: Kubernetes on Proxmox Containers: Using LXD containers to spin up a K8s cluster with NGINX Ingress Controller. The author has been re-learning Docker and the benefits of deploying applications using containers. He deploys the applications to a set of lightweight Linux VMs (read: lightweight VMs) on a free and open-source hypervisor with an excellent management interface. The current iteration of my setup relies on a series of Ansible playbooks that install all the various applications and configure them for use.

  

## [Cog: Containers for Machine Learning](https://github.com/replicate/cog)

A cog is an open-source tool that lets you package machine learning models in a standard, production-ready container. You define your environment with a simple configuration file, and it generates a Docker image with all the best practices. Cog knows which CUDA/cuDNN/PyTorch/Tensorflow/Python/Python combos are compatible and will set it up correctly for you. Then, you can deploy your packaged model to your infrastructure or Replicate it. Alternatively, you can run predictions on this model.

  

## [How to Write a Bash Script to Create and Update a Changelog](https://betterprogramming.pub/how-to-write-a-bash-script-to-create-and-update-a-changelog-de4df98985ab)

A changelog is a valuable tool to show other contributors and users what updates were made to your project, when, and what those updates entail. Our script allows the flexibility to decide what information is included and how it should look. In this post, we will generate a basic structure that looks like the basic structure. For more on these conventions, please see the Keep A Changelog initiative.

  

## [How we upgraded our 4TB Postgres database](https://retool.com/blog/how-we-upgraded-postgresql-database/)

Postgres 9.6 reached end-of-life on November 11, 2021, which meant it would no longer receive bug fixes or security updates. Postgres 13 was the highest released version of Postgres when we began preparing for the upgrade, with a support window through November 2025. With this approach, you run two copies of your database in parallel: the primary database you're upgrading and a secondary "follower's" database running at the target database. This effectively eliminates the need to wait to restore the primary state to the secondary database.

  

## [The SRE book turns 6!](https://cloud.google.com/blog/products/devops-sre/the-sre-book-turns-6/)

Site Reliability Engineering: How Google Runs Production Systems with O'Reilly Media has been six years since the book became a bestseller. Google SREs have also given dozens of talks at conferences about the topics covered in the SRE Book in the intervening years. All three books are available for free at //sre.google/books. To make this work more discoverable, we've put together a compendium of this material, mapped by topic to each chapter of the book.