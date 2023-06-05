# DevOps / SRE -Top Links Last Week

## Week 40 Issue #47

## [Automated security and compliance remediation at HDI](https://aws.amazon.com/blogs/devops/automated-security-and-compliance-remediation-at-hdi/)

At HDI, one of the biggest European insurance group companies, we use AWS to build new services and capabilities and delight our customers. Having a secure and compliant cloud environment is a prerequisite for every new experiment and use case on our data platform. The continuous monitoring of AWS infrastructure and application changes complemented by the automated incident response of the security baseline helps us foster security best practices and allows for a high innovation pace. We also apply GDPR compliance on AWS recommendations and AWS Foundational Security Best Practices.

## [Stop Using Microservices. Build Monoliths Instead.](https://betterprogramming.pub/stop-using-microservices-build-monoliths-instead-9eac180ac908)

Most companies would be better off avoiding microservices, says GreekDataGuy. Building out a microservices architecture takes longer than rolling the same features into a monolith. Microservices work best for large teams, especially for large engineering departments. Building a microservice architecture is more complex than a comparable monolith, he says. Building microservices takes more work to configure, maintain and monitor multiple microservices compared to a single monolithic app. The right type of infrastructure for each service can drastically lower costs but it comes with its own challenges.

---

## [Automate Provisioning of Kubernetes Clusters on AWS with Terraform](https://faun.pub/automate-provisioning-of-kubernetes-clusters-on-aws-with-terraform-61ff6aaf8ead)

In this article, we are going to create an EKS cluster using terraform. In the previous article we created the cluster using an AWS management console. We will use Terraform to create a VPC with all the subnets and configurations inside the VPC. The VPC is a control plane that is managed by AWS. We need to create worker nodes and connect them to the master node. We also need to set the availability zone depending on the region using data in Terraform. We can then get all the availability zones from the region specified in the provider.

## [Is Web3 Really Decentralized? A Look at Alchemy and BitClout](https://thenewstack.io/web3-isnt-fully-decentralized-a-look-at-alchemy-bitclout/)

Many current “dapps” (distributed applications) are reliant on centralized web infrastructure. Despite all the highfalutin talk about Web3 being a decentralized version of the web, much of the infrastructure is exactly the same as Web 2.0. Alchemy is a VC-funded blockchain company that styles itself as “AWS for blockchains” The company that built the platform ultimately controls it. Alchemy’s platform is controlled by Alchemy, because at least some of its parts are centralized. If you build your dapp on top of Alchemy and the platform crashes (like Facebook did last week) then your app crashes too.

## [DevOps at the Crossroads: The Future of Software Delivery](https://thenewstack.io/devops-at-the-crossroads-the-future-of-software-delivery/)

Rajeev Madhavan: 90% of DevOps initiatives will fail to fully meet expectations. DevOps culture is becoming mainstream, organizations are struggling with the increasing tool sprawl, complexity and costs. Smaller companies lack the resources, expertise, and processes to do it themselves. The need for efficient DevOps has never been more evident but most companies have not been able to realize the benefits yet, he says. Kumar Chivukula is the co-founder and CTO of Opsera, driving the mission to help companies deliver software fast, safe, and secure.

## [Getting started with Otomi](https://itnext.io/getting-started-with-otomi-a82d361330a2)

Otomi is a single package for Kubernetes that includes projects like Istio, Knative, Prometheus, Harbor, Keycloak, Nginx ingress, External-DNS, Cert-manager, Hashicorp Vault, Gatekeeper, Drone, Gitea. Otomi ships Gatekeer with a complete set of policies, so there is no need to add the Azure policy add-on. In this example, I’ll be installing Otomi on AKS using the Helm Chart.

## [Attacking GitHub Organizations](https://github.com/ovotech/gitoops/blob/main/docs/blog.md)

GitOops is a tool to map CI/CD attack paths in a GitHub organization. Users can directly and indirectly run code in a variety of contexts by pushing changes to repositories. This can offer easy paths for lateral movement and privilege escalation within an organization. We're particularly interested in users/teams that can open a pull request against a user/team (allowing them to disable branch protections to disable them to enable an attack). We're welcome to check the code and the details for the details of the details.

## [Why every programmer should care about the quality of their code](https://imjosef.medium.com/32746362051e)

Why every programmer should care about the quality of their code? Why? Because everyone prefers to work with code that is easy to analyze, extend and modify. The high quality of the code means that we can focus on making changes instead of fighting what is already there. High-quality code also makes it easy to deploy new employees and use up-to-date technologies. The author says code quality also affects the possibility of using up to-date technology. He says code readability affects many aspects of your work.

## [SSH Tunneling Explained](https://goteleport.com/blog/ssh-tunneling-explained/)

OpenSSH is the most widely used open-source SSH server. It comes pre-installed by default with the vast majority of Linux distributions. It helps achieve security use cases such as remote web service access without exposing port on the internet, accessing server behind NAT, exposing local port to the internet. In this post, I’ll cover different tunneling features as supported by OpenSSh, which includes local port forwarding, dynamic port forwarding and TUN/TAP tunneling.

## [Deploying Laravel to CloudRun — SecretManager and LoadBalancer for Custom Domain Mapping](https://faun.pub/deploying-laravel-to-cloudrun-secretmanager-and-loadbalancer-for-custom-domain-mapping-780677aa4037?source=rss----10d1a7495d39---4)

CloudRun + Secret Manager can be used to deploy Laravel to CloudRun. This story is only a conceptual testing, there are many other configurationw need to be considered when deploying in production. CloudRun in asia-southeast2 does not have the custom domain mapping featuren for present time, so based on the documentation we can use the Google Cloud Load Balancer to later on map to our custom domain. This is why I am using the LB or. else we can directly use the custom. domain mapping in CloudRun. The concept is to create a flow to deploy my laravel app to cloudRun.

## [SOLID Principles—The ‘D’](https://faun.pub/solid-principles-the-d-6076c360362c?source=rss----10d1a7495d39---4)

SOLID Principles—The ‘Dependency Inversion Principle—SOLID Principles. In this post, we’ll discuss in detail this principle and understand the main advantage of following this principle that is the easy maintainability of code and very loosely coupled classes. The D in SOLID is the D in the SOLID Principle. DIP states that high level modules should not depend on low-level modules. Both should depend on abstractions, not details. Abstractions should not be dependent on details, not vice versa. We can avoid unnecessary works by simple using abstractions.

## [ETL Pipelines with Airflow: The Good, the Bad and the Ugly](https://airbyte.io/blog/airflow-etl-pipelines)

Airflow is a popular open-source workflow management platform. Many data teams also use Airflow for their ETL pipelines. With Airflow you can use operators to transform data locally (PythonOperator, BashOperator...), remotely (SparkSubmitOperator) and KubernetesPodOperator… With Airbyte and dbt, you can easily integrate Airflow with Airbyte. There is no Airflow operator to transfer data directly from Postgres to BigQuery. The suggested alternative is to keep using Airflow to schedule and monitor ELT pipelines.

## [GitHub Advisory Database now powers NPM audit](https://github.blog/2021-10-07-github-advisory-database-now-powers-npm-audit/)

The GitHub Advisory Database is a curated set of more than 5,000 security vulnerabilities that powers important security tools like Dependabot. Every developer gets the same, high-quality vulnerability information from the GitHub advisory Database, and we’ll stay focused on keeping developing on GitHub and Node.js secure. We’re redirecting the advisories on. npmjs.com to the GitHub Advisory. Database. This means you can view advisories and also search and sort advisories in a more advanced way.

## [How to use AWS Named Profiles](https://www.itscava.com/how-to-use-aws-named-profiles)

IAM (Identity & Access Management) is the gatekeeper of your Amazon Web Services accounts. It says who can access your account and what this person/service can and cannot do. With programmatic access, you can set a particular set of credentials in the .aws/ files to access your resources. A profile wraps a set of. credentials locally, so users can invoke different. AWS account by pointing to other profiles. The correct way to use this feature is to have multiple profiles for some specific use-cases. simultaneously. Other sets of credentials stored in a more secure place, like the System Vault.

## [Lessons learned from sharding Postgres at Notion](https://www.notion.so/blog/sharding-postgres-at-notion)

Sharding Notion’s Postgres monolith into a horizontally-partitioned database fleet. The shard nomenclature is thought to originate from the MMORPG Ultima Online, when the game developers needed an in-universe explanation for the existence of multiple servers running parallel copies of the world. Sharding represented a major milestone in our bid to improve application performance. The inflection point arrived when the Postgres VACUUM process began to stall consistently, preventing the database from reclaiming disk space from dead tuples.

## [Will Cloudflare R2 Win Customers from Amazon S3?](https://www.taloflow.ai/blog/will-cloudflare-r2-win-customers-from-amazon-s3)

Cloudflare R2 is a cloud object storage service with some incredible features. It promises to solve three main problems that make incumbent providers like Amazon S3 more complicated. It also offers a supposedly easy migration from S3-compatible storage buckets, and automatic replication of “blobs” across the world. R2 has cheaper and simpler pricing than several incumbent cloud services, but is still well behind others on raw storage cost. When comparing R2 to Backblaze B2, Wasabi or Storj DCS, it is about 3 times more expensive for storage.
