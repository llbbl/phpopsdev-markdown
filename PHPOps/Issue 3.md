# DevOps / SRE - Top Links Last Week

## Week 49 Issue #3

## [AWS brings ECS, EKS services to the data center, open sources EKS](https://techcrunch.com/2020/12/01/aws-brings-ecs-eks-services-to-the-data-center-open-sources-eks/)

Today at AWS re:Invent, Andy Jassy talked a lot about how companies are making a big push to the cloud, but today’s container-focused announcements gave a big nod to the data center as the company announced ECS Anywhere and EKS Anywhere, both designed to let you run these services on premises, as well as in the cloud.

These two services, ECS for generalized container orchestration and EKS for what’s focused on Kubernetes, will let customers use these popular AWS services on premises. Jassy said that some customers still want the same tools they use in the cloud on prem and this is designed to give it to them.

## [New for AWS Lambda – Container Image Support](https://aws.amazon.com/blogs/aws/new-for-aws-lambda-container-image-support/)

With AWS Lambda, you upload your code and run it without thinking about servers. Many customers enjoy the way this works, but if you’ve invested in container tooling for your development workflows, it’s not easy to use the same approach to build applications using Lambda.

To help you with that, you can now package and deploy Lambda functions as container images of up to 10 GB in size. In this way, you can also easily build and deploy larger workloads that rely on sizable dependencies, such as machine learning or data intensive workloads. ...

---

_Please consider supporting the Weekly DevOps / SRE Report. [Subscribe](https://www.phpops.dev/subscribe/#/portal/signup) to the phpops Newsletter on our website!_

---

## [Announcing HashiCorp Terraform 0.14 General Availability](https://www.hashicorp.com/blog/announcing-hashicorp-terraform-0-14-general-availability)

... Terraform 0.14 is all about workflow. We know that practitioners love the Terraform workflow. Our job is to continue to improve it. Terraform 0.14 takes steps to help every practitioner be better able to make critical decisions about their infrastructure with the addition of a concise diff, sensitive input variables, and a provider dependency lockfile. These improvements are designed to help better control Terraform’s behavior in both interactive use and when used in automation. This release is one of the final stepping stones to a 1.0 release of Terraform

## [AWS just went multi-cloud](https://acloudguru.com/blog/business/aws-just-went-multi-cloud-and-its-only-the-beginning)

AWS, you sneaky devils.

Look at the FAQ for EKS Anywhere, announced yesterday for a 2021 launch, and you’ll find plenty of references to “on-premises”, bare metal compute, and VSphere. AWS’s stated rationale for expanding access to their managed Kubernetes service is all about hybrid cloud, which traditionally has meant “your old busted servers plus AWS’s shiny goodness.”

But wait … EKS Anywhere? Does that really mean anywhere?

## [AWS announces DevOps Guru to find operational issues automatically](https://techcrunch.com/2020/12/01/aws-announces-devops-guru-to-find-operational-issues/)

At AWS re:Invent today, Andy Jassy announced DevOps Guru, a new tool for DevOps teams to help the operations side find issues that could be having an impact on an application performance. Consider it like the sibling of CodeGuru, the service the company announced last year to find issues in your code before you deploy.

## [Kubernetes Best Practices in Production](https://containerjournal.com/topics/container-management/kubernetes-best-practices-in-production/)

Kubernetes has excellent features that support scaling, zero-downtime deployments, service discovery, automatic rollout and rollback capabilities, to name a few. To manage your container deployment at scale, Kubernetes is a must, as it enables the flexible distribution of resources and workloads. Kubernetes in production is a great solution, but it takes some time to set up and become familiar with it. Since many companies want to use Kubernetes in production these days, it is essential to prioritize some best practices. In this article, we will look at some Kubernetes best practices in production.

## [KubeCon+CloudNativeCon: Service Mesh Battle Stories and Fixes](https://thenewstack.io/kubeconcloudnativecon-service-mesh-battle-stories-and-fixes/)

As more organizations implement service meshes, they are finding what works and what needs more work, and they are creating new management practices around this knowledge. A few tried-and-tested best practices were detailed last month during KubeCon+CloudNativeCon.

## [AWS Proton, a Shared Services Library for Cloud Native Resources](https://thenewstack.io/aws-proton-a-shared-services-library-for-cloud-native-resources/)

Amazon Web Services has launched a new shared service platform, called Proton, designed to integrate containers, AWS Lambda serverless jobs and other cloud resources into one catalog, making it easier for developers to assemble a standardized stack of components to run their applications.

## [How Fidelity Investments Enables a Pipeline As Code Capability for 12,000 Developers](https://cd.foundation/blog/2020/12/04/how-fidelity-investments-enables-a-pipeline-as-code-capability-for-12000-developers/)

Fidelity Investments speakers Jimmy McNamara and Aoife Fitzmaurice explain how they manage their internal “pipeline-as-code” platform in an organization with 12,000 developers. They present the reference architecture the teams use and also speak about the cultural problems of such a large transformation.

## [Using NetBox for Ansible Source of Truth](https://www.ansible.com/blog/using-netbox-for-ansible-source-of-truth)

Here you will learn about NetBox at a high level, how it works to become a Source of Truth (SoT), and look into the use of the Ansible Content Collection, which is available on Ansible Galaxy. The goal is to show some of the capabilities that make NetBox a terrific tool and why you will want to use NetBox as your network Source of Truth for automation!

## [What developers need to know about Docker, Docker Engine, and Kubernetes v1.20](https://www.docker.com/blog/what-developers-need-to-know-about-docker-docker-engine-and-kubernetes-v1-20/)

The latest version of Kubernetes Kubernetes v1.20.0-rc.0 is now available. The Kubernetes project plans to deprecate Docker Engine support in the kubelet and support for dockershim will be removed in a future release, probably late next year. The net/net is support for your container images built with Docker tools is not being deprecated and will still work as before.

## [Choose Boring Technology](https://panelbear.com/blog/boring-tech/)

Over the years I have observed that many engineers tend to attribute much of the success or failure of a company to the technical choices made. I know I’m often guilty of this too. And while it is often justified, I would argue that for the vast majority of startups out there, the choice of programming language, framework, or even database doesn’t matter that much. This seems especially true during the early stages.