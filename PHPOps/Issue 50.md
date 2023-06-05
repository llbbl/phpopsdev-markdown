# DevOps / SRE - Top Links Last Week

## Week 43 Issue #50


## [HashiCorp Vault — Why should I use it for secrets management?](https://faun.pub/hashicorp-vault-why-should-i-use-it-for-secrets-management-4c3764683178)

HashiCorp Vault is an open-source secrets management platform. It provides full lifecycle management of static and dynamic secrets. Vault has the concept of ‘secrets engines’ making Vault extensible. Vault can interact with more unique environments like AWS IAM, dynamic SQL user creation, etc. It can also be used to augment configuration management systems like Puppet / Chef / Ansible. Vault is cloud-agnostic, hosting on a local machine is beneficial for developers, there is no internet connection, account, or cloud subscription required.

## [5 Soft Skills You Need To Succeed as a Developer](https://betterprogramming.pub/5-soft-skills-you-need-to-succeed-as-a-developer-357f7eac3372)

There are five key soft skills that truly make a software developer shine above the rest. The best developers care about the purpose they’re building for, and they seek to understand the people they're helping. Good communication between team members will result in poorly-designed products, as explained by Conway’s Law. Creativity is the true test of a developer's creativity, especially when it comes to problem-solving. Curiosity and curiosity are the best ways to learn, particularly in large groups.


---

## [Deploy a Set of EC2 Instances behind an ALB using Terraform](https://medium.com/@dasanirban834/deploy-a-set-of-ec2-instances-behind-an-alb-using-terraform-403fe584f09e)

Terraform is able to create infrastructures in multi cloud environment. It can be applied to AWS, Azure, GCP as well as On-Premises environment and cross cloud platform also. Terraform has been chosen by most of the clients just because of it’s benefits rather than others. It takes less time to provision and even to create any element as well. Deployment time has been reduced at a great extent by creating a single file for networking elements like VPC, subnets, Internet gateway and Route tables.

## [Deploy a GCloud instance with Gitlab CI | by Paul Brissaud](https://faun.pub/deploy-a-gcloud-instance-with-gitlab-ci-8bae98492682)

The Gitlab project is simple to deploy and provision a GCE Instance with Terraform and Ansible automatically from a simple Git commit. The project file will be structured as follows: an ansible folder with a playbook named main.yml. The main.tf file contains a fairly basic configuration for deploying a VM on Google Cloud. An Ansible Dockerfile allows to build an Ansible custom image with a Terraform state. An ansible playbook will display variables that Ansible will run during its harvest phase.

## [Automate Nginx Setup using Ansible](https://faun.pub/automate-nginx-setup-using-ansible-d2958e2b930c)

Ansible uses the push technique for configuration management. The push configuration management implies that configurations from the control node (master machine)are sent/pushed to the remote machine. The commands in the remaining parts of this article will be performed on the control nodes. The master key (ssh private key) stays with the owner (control node) while the other spare keys (ssh public key) can be given to the guests (managed nodes) Let’s set up an SSH connection between two machines.

## [From Cloud Run To Kubernetes: Why Internals Matter](https://anecdotes.dev/from-cloud-run-to-kubernetes-how-learning-the-internals-of-your-stack-empowers-you-as-a-developer-3d0cdf7cb7ec)

At anecdotes, we used Google’s Cloud Run as our serverless platform in our first year. However, our infrastructure rapidly grew to a point where this service was no longer feasible, so we started planning a move to Kubernetes. When we spun up the environment for the first time, the pods kept restarting. This was an absolute shocker. We couldn’t understand why. After eliminating the easiest suspect (lack of RAM/CPU), we understood that we needed to go deeper to understand what was happening.

## [A developer's guide to programatically overcome fear of failure](https://www.pagerduty.com/blog/engineers-guide-on-the-importance-of-failure/)

We need to get more comfortable with failing, and figure out why people fear it. He says there are lots of different ways to categorize failure, such as preventable and complex failures. We must normalize failure for us to be familiar with it in order to be comfortable with it, Kaur says. We also need to understand failure as a part of the growth process.

## [5 Pitfalls of the Online Code Review](https://levelup.gitconnected.com/5-pitfalls-of-the-online-code-review-d7a2e42556c8)

There are 5 Pitfalls of the Online Code Review feature on GitHub, GitLab, BitBucket. The review process can become a bottleneck to the development flow. The reviewer can see before and after code changes clearly highlighted in the code. The best reviewer you can get is someone whose interests are aligned with yours. The reviewers may insist on changes that reflect pet peeves rather than enhancements that would add true value. This scenario can degenerate into a dysfunctional or even toxic culture. Someone may intentionally delay the code review to avenge perceived personal wrongs you conducted for them.

## [Tao: Facebook’s distributed data store for the social graph](https://www.micahlerner.com/2021/10/13/tao-facebooks-distributed-data-store-for-the-social-graph.html)

This is the first in a two-part series on Facebook’s graph database. The first paper focuses on the original TAO paper, describing the motivation for building the system. The second part focuses on TAO-related research published at the VLDB - RAMP-TAO: Layering Atomic Transactions. The papers over the next few weeks will be from (or related to) research related to the research from the upcoming conference SOSP. As always, feel free to reach out on Twitter with feedback or suggestions about papers to read!

## [Goodbye Microsoft SQL Server, hello Babelfish](https://aws.amazon.com/blogs/aws/goodbye-microsoft-sql-server-hello-babelfish/)

Babelfish allows Amazon Aurora Postgres-Compatible Edition to understand the SQL Server wire protocol. It allows you to migrate your applications to Postgres cheaper, faster, and with less risks involved with such change. Amazon Aurora provides the security, availability, and reliability of commercial databases at 1/10th the cost. You can migrate your application in a fraction of the time that a traditional migration would require. You continue to use the existing queries and drivers your application uses today. You save on licensing costs of using SQL Server.

## [Power and Control at the Edge — The Beginning of a Long Battle](https://aws.plainenglish.io/power-and-control-at-the-edge-is-the-battle-only-just-beginning-c4f891c541bb)

As the balance in data infrastructure tilts from the core to the edge, a new battle is set to rage. What are the challenges and how might it play out? A major cloud computing battle is about to break out– Gioele Fazzeri, Pixabay. It is beginning to feel like the opening salvos of a battle for control, power, and ownership over the customer and their data. For edge deployments to be successful the laws of physics dictate that you need to place high performance, low latency infrastructure close to where the data is being created and used.


## [Infrastructure-as-Code: 6 Best Practices for Securing Applications](https://thenewstack.io/infrastructure-as-code-6-best-practices-for-securing-applications/)

Infrastructure-as-code (IaC) allows development teams to manage how applications are deployed and run on cloud infrastructure. With this practice comes changes in responsibility: IaC further extends developers’ responsibility to include securing their code and infrastructure. Gartner: 70% of attacks against containers will be from known vulnerabilities and misconfigurations that could have been remediated. Research from security platform provider Snyk reveals that many companies are only starting out on their IAC journey, with 63% just beginning to explore the technology.

## [How to Configure AWS Account and Set Up Billing Alarm](https://aws.plainenglish.io/how-to-configure-aws-account-and-set-up-billing-alarm-8b8c34929395)

How to configure an AWS account after creating an account and setting up a billing alarm to manage the bills. These are important steps for new AWS users as well as experienced users. By using these steps, a user can optimize and maintain their bills.Configure Account Alias, enable access to billing information and create an account ID that is hard to remember since it’s big numbers, so it's better to create account Alias. Check out AWS in Plain English for more AWS-related content.

## [How To Expose Your Local Host URL as a Public URL](https://www.realpythonproject.com/how-to-expose-your-local-host-url-as-a-public-url/)

There might be times when you wish to access your API or React project using a public URL but do not want to go through the hassle of deploying it. Exposing your localhost URL will let anyone with the URL access it. This can help you to share your server/react project with others for feedback or debugging. The first option will require you to download a software while the second will require an NPM package. The exposed URL will basically be in sync with your local host URL.

## [Are Your Unit Tests Getting Redundant? Here’s How To Write Them Effectively](https://betterprogramming.pub/are-your-unit-tests-getting-redundant-heres-how-to-write-them-effectively-a4d98234ec94)

An engineer’s responsibilities around unit tests are no exception to this rule. Redundantly redundant, these tests incur a greater maintenance responsibility and are more susceptible to unnecessary failure. The real virtue of good work comes when we can work smarter, not harder, says author of the test. The author of a unit test should know what goes on inside of a function, not the test, he says. The problem is quite subtle, yet it breaks the black box paradigm I mentioned up above. In this case, testing whether the function called getPhotos() on lines 48–50 doesn't fall into either category.

## [AWS SNS Events: SNS to Lambda vs SNS to SQS to Lambda](https://aws.plainenglish.io/aws-sns-to-lambda-vs-sns-to-sqs-to-lambda-788d4cc96f34)

SNS events can target multiple destinations such as Lambda, SNS, SQS. SNS invokes Lambda function asynchronously with an event that contains a message and metadata. Lambda can read messages in batches and invoke function once for each batch. When the function successfully processes a batch, it deletes the messages from the queue. This helps in cost saving on Lambda invocations. When the Lambda. process a batch of messages, Lambda automatically scales up and down based on the number of inflight messages in the queue.