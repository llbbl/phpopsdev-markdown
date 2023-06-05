# DevOps / SRE - Top Links Last Week

## Week 14 - Issue #73

  

28 articles

  

## [We use GitHub Actions to build GitHub](https://github.blog/2022-04-05-4-ways-we-use-github-actions-to-build-github/)

  

GitHub's Security Lab team uses GitHub Actions to automate processes related to reporting vulnerabilities to open source projects. They also use actions to use the CodeQL bug bounty program to test CodeQL's CodeQL code changes. GitHub has seen some great use of GitHub Actions from open source communities and enterprise companies alike, with more than 12,000 community-built actions in the GitHub Marketplace. The Security Lab uses the actions to track and report vulnerabilities to maintain maintainers and track the fix and the disclosure.

  

## [6 Reasons Why More Automation Means Secure Software](https://thenewstack.io/6-reasons-why-more-automation-means-more-secure-software/)

Software is being produced faster than ever, in smaller and smaller components. 57% of software development teams deploy at least once a week — and 20% deploy multiple times a day. The average organization performs 6,200 component migrations per year. When a developer updates a dependency, they have, on average, 21 versions. The most common type of vulnerability, CRLF injection, was detected in 65% of apps, according to a report by Sonatype and The New Stack.

  

## [An Open Letter from the CEO of Puppet: Puppet and Perforce](https://puppet.com/blog/an-open-letter-from-the-ceo-of-puppet//)

Puppet + Perforce will be joining forces with Perforce Software. Puppet founder Luke Kanies was one of the original creators of the DevOps movement. Perforce's mission is to help technology teams solve the most challenging problems in DevOps so nothing stalls innovation. Puppet and Perforce both have a deep focus on outstanding customer service, open and transformational leadership, and a people-first culture that empowers team members to do their best work as part of a community that cares, says Kanies.

  

## [Deploy a Full-Stack Application with Portainer](https://thenewstack.io/deploy-a-full-stack-application-with-portainer/)

  

Portainer allows you to manage registries, networks, networks and events, volumes, hosts, environments, logs, and even full-stack applications. With Portainer, you can create a single application and assign that stack to teams. This is a great way to learn how to work with everything from simple to complex deployments. The Portainer software is a must-have for container developers looking to enjoy the deployment and management of their containerized applications. To make this work, you'll need a running instance of Portainer, and that's it.

  

## [Open source data integration platform Airbyte launches its cloud service](https://techcrunch.com/2022/04/05/open-source-data-integration-platform-airbyte-launches-its-cloud-service/)

  

Airbyte is an open-source data integration platform for building ELT data pipelines. The company also details its new compensation plan for open source developers who write and maintain data connectors for the platform. The fast-growing company recently raised a $150 million Series B funding round. It now offers over 165 data connectors and expects to expand to 500 by the end of the year. Airbyte also plans to launch its new command-line interface later this week. In addition, it is working on making it possible for its cloud users to manage the data and control plane.

  

---

  

## [5 Tools and Techniques for Better Python Project Setups](https://betterprogramming.pub/tools-and-technics-for-better-project-setup-9909abca263f)

  

To write better code and avoid common mistakes, we write unit tests and run them every time. Pytest can help us run tests and configure how to run them and which files to run. Pytest has a configuration file pytest.ini where you can describe its configuration, for example, which version should be Pytest or which are test files like the following.# pytet.ini. The tools can help you define a code style for the whole application, and developers will keep it!

  

## [Introduction to CI/CD with GitHub Actions](https://faun.pub/introduction-to-ci-cd-with-github-actions-9808d8a960c9)

  

GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your… docs. Therefore, GitHub Actions can be considered a platform to automate developer workflows. For example, a developer can take the last two lines from the Syntax Checker tool in the Python Syntax marketplace.  

  

## [Software Development at the Edge of Chaos](https://itnext.io/software-development-at-the-edge-of-chaos-2934f536daf5)

  

The edge of chaos is where life has enough stability to sustain itself and enough creativity to deserve the name of life. Software development teams need to find an effective way to work with customers who have different technical and business knowledge levels. The more chaotic software development processes are, the lower the quality of software and the more problems occur. Good senior people step into problems, seek them out, solve them when they are minor issues, and give everyone plenty of time to get the work done.

  

## [Improving Query Performance by 10000x](https://betterprogramming.pub/improving-query-performance-by-10000x-79b84c80fbaf)

  

A simple query to retrieve time series data took 30 seconds to run in our staging environment. The problem happened when I created a demo for a client on the Sky Ledge platform. There are 7,000,000 rows in the asset\_metrics database. However, 84% of the data is associated with just ten assets in the staging environment. As a result, the dataset is very highly skewed. The 7 million rows are spread between 106 different assets. There are also 710 asset / metric pairs (speed, temperature, elevation, etc.)

  

## [5 Tips to Master the Serverless Framework](https://aws.plainenglish.io/5-tips-to-master-the-serverless-framework-1ecd97fc48d0)

  

The serverless framework deploys Lambda functions to API Gateway and assigns stages to each stage. Creating and managing API keys with the framework is also very easy. Working environment variables for various stages of an API on AWS are also quite simple to implement & secure. It also allows you to store your environment variables securely by encrypting them using KMS keys. You don't have to have to manage any.env files with this anymore. Instead, you can add all your environment. variables into AWS's Parameter store.

  

  

## [Stop Using JSON Web Tokens For Authentication. Use Stateful Sessions Instead](https://betterprogramming.pub/stop-using-json-web-tokens-for-authentication-use-stateful-sessions-instead-c0a803931a5d)

  

JWT is usually implemented (in tutorials) to authenticate users. The server creates and signs a JWT using a secret password and returns it in the response. The front-end code has free access to read and store the Token. This enables cross-site scripting attacks to steal users' identities and send requests on their behalf. The Token will be valid until it expires. The only way to revoke them is to change the signing secret, and this would essentially log out your whole user base since all tokens would be rendered invalid.

  

  

## [Policy-as-Code or Policy-as-Data? Why Choose?](https://thenewstack.io/policy-as-code-or-policy-as-data-why-choose/)

  

Omri Gazitt Omri is the co-founder/CEO of Aserto, an authorization startup. He's spent most of his 30-year career working on developer and infrastructure technology. The Open Policy Agent project has become the de-facto standard for expressing policy as code. Policy-as-code provides a powerful abstraction for lifting authorization logic out of an application and centralizing it in a different source code repository. The problem shifts from creating and evolving an authorization policy to defining a standard data format for feeding data tuples into the engine.

  

  

## [Using the right tool for the job](https://tech.loveholidays.com/using-the-right-tool-for-the-job-bd4e537c205f)

  

Nicolás Palumbo and Ben Douthwaite discuss how we simplified our content API architecture by using the right tool for the job: simplifying content API architecture. Content Repository, one of our core APIs, is responsible for providing static content to the rest of the business. The Elasticsearch cluster managed the complexity of wrapping all the data in a given index. This pattern relied on running Elasticsearch using Kubernetes Statefulsets. It led us to consider different alternatives for storing and retrieving the content data.

  

## [Cooking for Engineers: In Praise of Legendary Food Hacks](https://thenewstack.io/cooking-for-engineers-in-praise-of-legendary-food-hacks/)

Silicon Valley engineer Michael Chu started Cooking for Engineers in 2004. The site chronicles his enthusiastic explorations into the world of food. Chu's last post on the site was a 2016 review of a wireless thermometer for your meat smoker. Last month a link to "Cooking for Engineers" turned up on Hacker News, where it soon racked up 184 upvotes (and another 114 comments). Each page also has its bumper crop of comments left by grateful readers over the years.

  

## [Almost 1/3 of Top npm Accounts Aren't Protected with 2FA](https://thenewstack.io/almost-1-3-of-top-npm-accounts-arent-protected-with-2fa/)

32% of the top 35 npm packages are at risk of account takeover because their dependencies' owners haven't properly employed two-factor authentication (2FA). A study found that, on average, npm packages implicitly trust 79 third-party packages and 39 maintainers. Popular packages often influence over 100,000 other packages, making them prime attack targets. Npm finally adopted 2FA for its top 100 projects, but that's nothing like enough. If only one of those is compromised, criminals can transform thousands of applications into crypto miners.

  

  

## [A curated list of "top" based monitoring tools for use in Linux and Unix terminals.](https://faun.pub/a-curated-list-of-top-based-monitoring-tools-for-use-in-linux-and-unix-terminals-299154fd1394)

Here is a curated list of "Top" based monitoring tools used in Linux and Unix terminals. These tools follow a Top naming convention, and several have been developed, each with a unique look and utility. These are all built for use from the terminal and have been invaluable in our debugging endeavors. The list is a categorized list and links to their respective git repositories. Take a moment to star the repo and appreciate the people developing these tools. Then, if you want to install any of the top tools below, please google "How to install \<top monitoring tool\> in Linux."

  

## [Lambda vs. Step Functions: The Battle of Cost and Performance](https://www.readysetcloud.io/blog/allen.helton/lambda-vs-step-functions-breakdown/)

AWS has several ways to charge you with serverless services but is excellent about transparency and no hidden costs. With Lambda, the slowest times can be attributed to cold starts. You are not billed for cold start time with Step Functions, and it's not the execution time. Lambda is billed similarly to express workflows, but standard workflows are entirely different. Their billing is solely on several state transitions. To get an idea of how Lambda compares to Express Workflows, we must gauge performance.

  

## [It's Time for Data Reliability Engineering](https://thenewstack.io/its-time-for-data-reliability-engineering/)

Kyle Kirwan is the CEO and co-founder of Bigeye. Data Reliability Engineering (DRE) borrows from Site Reliability and DevOps principles. Data teams are starting to change that by borrowing from DevOps and DRE. As a result, data is being used in ever-higher impact applications, such as chatbots, product recommendations, inventory management, financial planning, and much more. DRE is a part of Data Operations (DataOps), but only a part. DataOps refers to the broader set of operational challenges that data platform owners will face.

  

## [Certificate Management for On-premises Cloud-Native Apps](https://itnext.io/certificate-management-for-on-premises-cloud-native-apps-dbca82e3c405)

Certificate Management for On-premises Cloud-Native Apps is traditionally centrally managed. This paper explores how the cert-manager can be used for the on-premise Kubernetes applications to manage their certificate lifecycles. The certificate can then be mounted to the pods for the application to consume. Certificate-manager watches the expiration of the cert and renews it before it expires. It's a root CA signed by the root CA and an intermediate CA. The installation is straightforward.

  

## [You're Never Done. By Definition.](https://betterprogramming.pub/youre-never-done-by-definition-c04ac77c616b)

How the 'definition of done' falls short of describing the required effort to bring a feature to maturity, says Goerp. Software development is not a one-and-done. We all need a 'defense' that we all need to be put in place in our developer's place to make the remaining tasks in business a part of the feature development process. Mining what is required to complete a feature for initial deployment is essential to ensure it is ready for production.

  

## [Garden Automates Kubernetes Building, Deploying, Testing](https://thenewstack.io/garden-automates-kubernetes-building-deploying-testing/)

Garden.io is a Kubernetes-based tool that lets developers create and test environments from scratch. Developers can spin up ephemeral testing and preview environments for integration tests, manual QA, and workflows. Garden scans for configuration files, even across multiple repositories, validates them, and compiles them into a graph that describes all the steps involved in building, deploying, and testing your application. Garden uses the Stack Graph, a directed acyclic graph (DAG)-based framework that allows you to codify a complete description of your stack.

  

## [The practical value of an SRE team](https://faun.pub/the-practical-value-of-a-sre-team-eb277664258)

Everyone must establish a Site Reliability Engineering culture before forming an SRE team. At its core, SRE will help an organization find a balance between the velocity of development features and the risk to reliability. Google advises that operation work(toil) should be under 50% of each SRE's time. Toil is work that is mundane and scales linearly as the service grows. SRE implementation depends on the organization's size and maturity, so hiring SREs looks for resilience and flexibility.

  

## [The One Quality That Sets Senior Engineers Apart From Everyone Else](https://betterprogramming.pub/the-one-quality-that-sets-senior-engineers-apart-from-everyone-else-b164a815da68)

The quality that sets senior engineers apart from mid-level and junior developers is the one quality they lack. Senior engineers are confident in their ability to yield results; their eyes only see one outcome of taking on new challenges: growth. When you're confident in what you have to give, don't worry about how you're perceived, you let your work do the talking for you. Senior developers know that asking questions is a quick way to close gaps in their knowledge and move ahead.

  

## [Hacking Your iTerm](https://betterprogramming.pub/hacking-your-iterm-5d2bdacdaccf)

Some developers cringe at the mere thought of opening a terminal window. It can be daunting, stressful, and downright annoying for the uninitiated. But devs who understand the command line would argue it's one of the best tools at your disposal. Hacking Your iTerm will allow you to customize your command line in many ways, but the actual commands you'll execute in the terminal will still be the same. In addition, the use of UI not only slows you down but also gives you the freedom to not remember many shortcuts that are there to make your work life easier.

  

## [TDD in Flutter - Special: Golden tests with Alchemist](https://itnext.io/tdd-in-flutter-special-golden-tests-with-alchemist-ea8c96ff4dfe)

The Alchemist package aims to simplify how golden tests are handled and improve consistency between generated snapshots. You will have a set of human-readable snapshots for you, as a developer, to confirm the rendering and golden files generated using the Ahem font for your CI, which should be constant no matter the OS. The package will generate two sets of snapshots, one specific to your platform (Linux, macOS, or Windows) and another one made specifically for you. This will allow your tests to be run against the golden.

  

## [The Multiple Facets of Leadership](https://betterprogramming.pub/the-multiple-facets-of-leadership-b8430c473b69)

The Multiple Facets of Leadership: How to balance multiple leadership roles to use them effectively and make us more successful as leaders. The success factor is being able to balance our activities so we can invest the right amount of time in both dimensions. We want our teams to feel empowered, innovative, motivated, focused, self-organizing, and ultimately achieve business objectives and results. The "leader as manager" role is essential. A leader as a coach is focused on helping to produce better results.

  

## [How JavaScript works: Recursion in JavaScript, What It Is, and How it is used.](https://blog.sessionstack.com/how-javascript-works-recursion-in-javascript-what-it-is-and-how-it-is-used-eef3d734f20d)

Post # 59 of the series is dedicated to exploring JavaScript and its building components. In this piece, we will be looking at what recursion is, why it is employed in software development, how recursion works in Javascript and when not to use recursion. First, we will consider some examples of recursion in JavaScript's use cases and then look at how it differs from the popular Loop functions. We also share some rules of thumb we use when building SessionStack, a JavaScript application that needs to be robust.

  

  

## [How to Set up CI/CD Pipelines & Monitoring for Google App Engine (GAE)](https://www.d3vtech.com/insights/how-to-set-up-cicd-pipelines-monitoring-for-google-app-engine-gae)

Cloud Build is a Google-managed Service Google Cloud Platform infrastructure that allows you to build, test, and deploy containers continuously. Cloud Build lets you create software quickly across all languages. CI/CD pipeline and monitoring for App Engine involves numerous steps - to make things easier to digest, we've broken down the entire process into different phases. We'll also explore how to utilize data better using Cloud Operations alongside App Engine. We use Cloud Build to perform this action when both are present.