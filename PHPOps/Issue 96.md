# DevOps / SRE - Top Links Last Week

## Week 37 - Issue #96


28 links


## [GitOps your service orchestrations | Google Cloud Blog](https://cloud.google.com/blog/topics/developers-practitioners/gitsops-service-orchestration/)

In this approach, you have a staging branch where you make changes to a workflow. This change triggers a Cloud Build configuration that deploys a test staging workflow and runs some staging tests against it. If all tests pass, Cloud Build deploys the staging workflow. After more manual testing of the staging workflow, you merge changes from the staging branch to the main branch. This change triggers the same Cloud Build configuration to deploy a test production workflow, run more production tests, and deploy the production workflow if all tests pass.

This approach enables you to have an automated and staged rollout of workflow changes.

  

## [Kaniko — Building Container Images in a Kubernetes Cluster | by Ikram Khan | Medium](https://medium.com/@ikramkhan951/kaniko-building-container-images-in-a-kubernetes-cluster-a9381fe01976)

Kaniko is a daemon-less container image builder that allows users to build container images inside a container or Kubernetes cluster. It creates container images in the Kubernetes cluster in userspace without Docker Daemon.

  

## [Tyblog | 35 Million Hot Dogs: Benchmarking Caddy vs. Nginx](https://blog.tjll.net/reverse-proxy-hot-dog-eating-contest-caddy-vs-nginx/)

This blog post is about a benchmarking study on the performance metrics of Caddy vs. Nginx. The study found that Caddy is overall a faster reverse proxy than Nginx.

  

## [Observability is becoming mission critical, but who watches the watchmen? - Simon Aronsson](https://simme.dev/posts/who-watches-the-watchmen/)

Observability is becoming mission-critical for many organizations, but it is important to remember that the observability stack needs to be monitored to ensure it is functioning properly.

  

## [React App as a WordPress Plugin rendered with Shortcode | by Wesley Huber | Medium](https://wesleybaxterhuber.medium.com/react-app-as-a-wordpress-plugin-rendered-with-shortcode-f9ebf5f01234)

In this article, the author shows how to create a React App as a WordPress Plugin and pass data from PHP / WordPress to the React App.

  

## [Linux hardening: Systemd services | by SecSamDev | Towards Dev](https://towardsdev.com/linux-hardening-systemd-services-8742eaa1a645)

Systemd services can be sandboxed to improve security. This security review involves adding the "NoNewPrivileges" option to prevent processes from escalating privileges.

  

## [WunderBase - Serverless GraphQL Database on top of SQLite, Firecracker and Prisma - WunderGraph](https://wundergraph.com/blog/wunderbase_serverless_graphql_database_on_top_of_sqlite_firecracker_and_prisma)

WunderBase is an open-source, serverless database that runs on top of SQLite, Firecracker, and Prisma. It's simple to use and can be deployed in seconds.

  

---

  

## [Debugging Kubernetes Pods. I have spent a lot of time with botched… | by Matt Kornfield | Medium](https://mckornfield.medium.com/debugging-kubernetes-pods-7bc2aba66628)

To view a pod's information, run `kubectl describe pod $POD_NAME.` - To edit a pod's definition, run `kubectl edit pod $POD_NAME`. - To port-forward a pod, run `kubectl port-forward pod/$POD_NAME $LOCAL_PORT:$REMOTE_PORT`. - To port-forward a service, run `kubectl port-forward service/$SERVICE\_NAME $LOCAL\_PORT:$REMOTE\_PORT.`

  

## [Docker Image Testing With Container Structure Tests | by Aaron Berry | Level Up Coding](https://levelup.gitconnected.com/docker-image-testing-with-container-structure-tests-b2b2e5676060)

Container-structure-test is used to test if a container runtime meets its requirements. A specification file is created with YAML to include assertions such as commands that should run successfully, checking existing files with specified permissions, and checking for environment variables and labels in the built image. Then, the container structure test is run against the container image to see if it meets the specification. The container structure test will report the results if it does not meet specifications.

  

## [Docker security: Risks and Best Practices | by Abdullah Siddique | DevOps.dev](https://medium.com/@abdullah.siddique.010/docker-security-risks-and-best-practices-4f94bea451a5)

Docker is a container platform that is used by millions of users. Therefore, it is essential to prioritize security when using Docker, as containers lack a security dimension by default. There are seven scenarios in which Docker installation could become vulnerable, and ways to lessen the threat are discussed. Some best practices for security Docker installations are also discussed.

  

## [Journey Of A Microservice Application In The Kubernetes World | by Luc Juggery | ITNEXT](https://itnext.io/journey-of-a-microservice-application-in-the-kubernetes-world-876f72ce1681)

This article explains how to install and use the Loki stack from Grafana Labs to monitor a webhooks application in a Kubernetes cluster. We showed how easy it is to use Grafana to visualize logs and metrics stored in Loki and Prometheus. In the next article, we will use Acorn to deploy the webhooks application.

  

## [Securing the Supply Chain of Nothing | Kelly Shortridge](https://swagitda.com/blog/posts/securing-the-supply-chain-of-nothing/)

The document "Securing the Software Supply Chain" contains impractical, confusing, and dangerous recommendations.

  

## [K8s — Ingress Introduction Part One | by Tony | Medium](https://tonylixu.medium.com/k8s-ingress-introduction-part-one-696deeff6908)

In my last article, I introduced the K8s Service object. I will introduce the Ingress object in this article, a more complex load balancing mechanism.

  

## [Intelligently estimating your Kubernetes resource needs! | by Sanjit Mohanty | FAUN Publication](https://sanjimoh.medium.com/intelligently-estimating-your-kubernetes-resource-needs-c12a75ea3138)

The Kubernetes VPA recommender can help you develop a more realistic number for your workload resources. To use it, simulate the real user workload on your environment and let the recommender do the rest.

  

## [GitHub - surrealdb/surrealdb: A scalable, distributed, collaborative, document-graph database, for the realtime web](https://github.com/surrealdb/surrealdb)

SurrealDB is a scalable, distributed, collaborative document-graph database for the real-time web. It is designed to be simple to install and simple to run. SurrealDB can be used to manage and run SurrealDB database instances without the need to install any command-line tools.

  

## [Don't get burned licensing Oracle software in Kubernetes! | by Paul Dally | Medium](https://pauldally.medium.com/licensing-oracle-software-in-kubernetes-fc35e5528973)

Oracle's license management services are designed to help customers ensure they are making the most of their Oracle investments effectively and promptly. Still, many first-hand experiences with Oracle LMS audits would not describe LMS as effective or compliant. In addition, Oracle's licensing policies concerning workloads running on Kubernetes are onerous, and it is recommended that customers try to avoid running Oracle software on Kubernetes entirely.

  

## [Books to learn Kubernetes from beginner to advanced | by Quân Huỳnh | FAUN Publication](https://medium.com/@hmquan08011996/books-to-learn-Kubernetes-from-beginner-to-advanced-d8f099691a03)

This person recommends several books for learning Kubernetes, from beginners to advanced levels. The books are Kubernetes in Action, Kubernetes Best Practices, Managing Kubernetes, GitOps and Kubernetes, and Core Kubernetes.

  

## [What Will The Future of Laravel Development look like in 2022 and beyond? | by Emma Jhonson | Dev Genius](https://blog.devgenius.io/what-will-the-future-of-laravel-development-look-like-in-2022-and-beyond-a0148de33113)

Laravel is a popular PHP framework used by some of the biggest brands in the world. The future of Laravel development is looking bright, with new features and updates being released frequently. Some of the changes we can expect to see in the coming years include more focus on web socket support and HTTP/2 protocols, full PHP 7 support, and more laravel development companies taking advantage of React to provide top-notch user interfaces.

  

## [How We Improved the Response Time by 1000x After Migrating an API From MySQL to AWS OpenSearch | by Ankit Joinwal | Better Programming](https://betterprogramming.pub/migrating-an-api-from-mysql-to-aws-opensearch-for-1000x-speed-e46139dff652)

We migrated an API from MySQL to AWS OpenSearch and saw a 1000x improvement in response time. The main reason for the improvement was that OpenSearch uses text analyzers on String-type fields when documents are indexed, which makes searching text on a VARCHAR column much more efficient. Of course, the trade-off is that we now need to maintain a copy of the data in OpenSearch, but since the data is mostly static, the maintenance effort is very low.

  

## [Building the future of the command line · GitHub](https://github.com/readme/featured/future-of-the-command-line)

The command line is an intimidating but important part of many tech workers' day-to-day tasks. There is room for innovation in the command line experience, and many open source projects are tackling issues to take the command line into the future. The command line will probably still be with us decades from now, but it is evolving.

  

## [How to containerize Python application with Docker | by Abdullah Siddique | Dev Genius](https://blog.devgenius.io/how-to-containerize-python-application-with-docker-ce930b192c68)

This article taught us how to containerize a Python application using Docker.

  

## [Laying CICD Pipelines with Terraform | by Devin Moreland | Medium](https://medium.com/@Devin007/laying-cicd-pipelines-with-terraform-6c5b61e30f20)

In this article, the author walks readers through creating a CI/CD pipeline with CodePipeline from AWS using Terraform. First, the author describes how to set up the necessary resources, including an S3 bucket to store state, a CodeBuild project, and IAM roles. Next, the author also describes how to create the pipeline in the AWS console. Finally, the author describes how to destroy the infrastructure created by the pipeline.

  

  

## [A Quick Introduction to Top Metrics & Tools to Track the Kubernetes Observability | by Hardik Shah | Medium](https://hardiks.medium.com/a-quick-introduction-to-top-metrics-tools-to-track-the-kubernetes-observability-dc06896420c4)

Kubernetes is a container management platform that simplifies the management of your containerized cloud-native ecosystem. However, many components that need to be monitored continuously can also become complex in no time. To avoid this, you should keep an eye on a few Kubernetes metrics, such as node resource usage, the number of nodes, the total number of running pods per node, and memory & CPU requests. In addition, you can use monitoring tools, such as Jaeger and Prometheus, to help you gain complete visibility into the state of your Kubernetes cluster.

  

## [GKE with NGINX Service Mesh 1. Implement NGINX Service Mesh with… | by Joaquín Menchaca (智裕) | Medium](https://joachim8675309.medium.com/gke-with-nginx-service-mesh-8b1073af07bf)

This tutorial introduces NGINX Service Mesh and demonstrates how to use it with a real-world application (Dgraph). It also includes instructions on how to install o11y (Observability) tools and deploy them alongside NSM.

  

## [7 Common Kubernetes Pitfalls](http://www.qovery.com/blog/7-common-kubernetes-pitfalls/)

1. Don't use labels and selectors incorrectly in your configuration

2. Set up a proper monitoring and logging system

3. Be careful with the "latest" tag

4. Check your container port mappings

5. Troubleshoot the "crashloopbackoff" error

  

## [Kubernetes Ingress with NGINX Ingress Controller Example](https://spacelift.io/blog/kubernetes-ingress)

Ingress in K8S is an object that allows access to services within your cluster from outside your cluster. There are many Ingress controllers available. NGINX is a widely used one. Ingress is a robust way to expose services within your K8S cluster to the outside world.

  

## [Ansible vs. Terraform Demystified](https://www.ansible.com/blog/ansible-vs.-terraform-demystified)

Ansible and Terraform are two open-source tools that are often compared. Terraform is an infrastructure as a code tool, while Ansible is a multi-purpose automation tool. Both tools have products available with enterprise features. The primary difference between their community versions is that Ansible is an automation tool, whereas Terraform is an infrastructure as a code tool.

  

## [The maze of Python dependency management](https://blog.frankel.ch/maze-python-dependency-management/)

Python dependency management is a complex issue with no easy solutions.

- One way to manage dependencies is to use a tool like pip-compile, which allows for listing only direct dependencies.

- Another way to manage dependencies is to use a tool like Dependabot, which automatically fetches the latest versions of all dependencies.