---
title:  "What Startups Need to Know About Cloud Computing"
categories:
 - Cloud
author: Geoff Sullivan
excerpt: "Cloud Computing is just one of the services that have provided the
technical foundation for today’s fastest growing startups like Uber and AirBnB,
allowing these companies to bring their ideas to market and scale them globally
at an incredible rate. Far beyond the value of not having to run your own data
centre, cloud computing provides incredible flexibility and feature rich tool
sets that allow companies to gain a true competitive advantage in their market."
header:
  image: #"posts/coalmine.gif"
author_profile: true

---
There is no denying that the tech startups of today have a massive advantage
over their counterparts from just a decade ago. Cloud Computing is just one of
the services that have provided the technical foundation for today’s fastest
growing startups like Uber and AirBnB, allowing these companies to bring their
ideas to market and scale them globally at an incredible rate. Far beyond the
value of not having to run your own data centre, cloud computing provides
incredible flexibility and feature rich tool sets that allow companies to gain
a true competitive advantage in their market.

However, one still needs to know the best practices for choosing and working
with a cloud provider. Here are some things you should look for in a Cloud
service.

## Selecting your Cloud

There are several global leaders in the cloud infrastructure-as-a-service space,
led by giants like Amazon Web Services (AWS,) Microsoft Azure, IBM Softlayer
and Google Cloud. While all of these companies provide global footprints,
similar reliability and performance, and a robust suite of tools, there are
some important considerations to make when selecting a cloud infrastructure
provider for your company, product, or service.

## Startup Credits
Most of the major cloud infrastructure providers offer startup programs, where
they provide free cloud infrastructure and additional value-add services for a
period of time for qualified startups. The criteria for acceptance ranges from
provider to provider, but most are concerned with whether or not you’re a member
of a qualified incubator or accelerator, how much you have raised in investments
and your revenue.

## Regional Considerations

Depending on your target market and the type of data your application stores,
the global cloud leaders may not satisfy your customer’s requirements for
jurisdiction and data residency. Many verticals like healthcare, government,
banking as well as countries like Canada and Germany, have very strict data
residency regulations that require all personally identifiable information (PII)
to be stored in a specific country (usually outside of the USA.) In these cases,
there are hundreds of regional cloud providers that will satisfy this
requirement.

## Multicloud

Most of the major cloud providers allow you to deploy infrastructure in multiple
regions or zones around the world, helping mitigate the risk of data centre
outages. Though multi-region deployments are highly recommended to ensure that
your applications are on all of the time, putting all of your eggs in one
basket, or a single cloud provider still has associated risks. It is important
to design your stacks with portability in mind. One way to do this is to avoid
using any proprietary tools that “lock in” your deployments to one provider.
More on this later.

## Don't Forget Ops

Often times, startup CTOs are developers by trade. They are traditionally quite
good at bringing an idea to life through code. Furthermore, the advice they’ll
usually get from investors and mentors alike is to get MVP to market ASAP.
While this is sound advice, it focuses on the code itself and less about what
runs the code. Believe it or not, operations has a huge impact on the user
experience. If your app is down, you’ll have a hard time demoing it, it will be
impossible to onboard new customers, and investors may or may not kick you out
of their office mid-pitch (depending on how good your idea is.) Regardless of
whether or not you’re an “ops” person, ops is something that deserves attention
right out of the gate when building your product.

## Build a DevOps Culture

DevOps, or the cultural shift that promotes effective communication and
collaboration and between developers and operations staff, is the key to
building and managing highly available, highly performant cloud deployments.
While this may be simple to implement at a microscale, this can be difficult to
ingrain as your technical team begins to grow. A good starting point is to
include the right people at the table when planning the release of new
functionality or a new project. When ops understands what dev is trying to do,
the chances of getting something right the first time is greatly increased.

## Automate all Things
The secret sauce to many of today’s hottest tech companies is in the automation
of cloud infrastructure. Netflix, as an example, successfully operates a
tremendous amount of cloud infrastructure in AWS regions across the world, and
with millions of users daily. They are able to manage this infrastructure with
a small, highly skilled team who focuses on automating nearly every task
imaginable. This speaks to the strategic value of ops, where rather than
“keeping the lights on,” they are a critical element of Netflix’s success.
Netflix open sources much of their homegrown automation technology, so that
other companies can use and contribute back to the projects.

## Avoid Lock-in

The discussion around cloud vendor lock-in has often been described as the
“Hotel California effect,” where you can check in any time you’d like, but you
can never leave. This refers to the vast suites of extremely valuable but
proprietary tools that cloud vendors provide to more easily deploy applications
to their clouds. These tools are great at getting your stack up and running,
but can limit the ability to move your stack to another or an additional
provider should your business require it. Think of it as the cell phone
contracts as old, easy and enticing to get into and nearly impossible to get
out of.

## Go Open Source
There are thousands of well supported open source projects, used daily by the
world’s largest IT shops, that will provide similar functionality to the native,
proprietary tools that cloud vendors provide. Don’t limit yourself when you
don’t have to.

**Some popular third-party open source tools include:**

**Terraform** – Terraform allows you to define your entire infrastructure stack
in simple, human readable configuration templates that can be stored in version
control for simple and fast changes.  Terraform is similar to AWS Cloudformation
or OpenStack Heat, but with support for multiple cloud providers.

**Chef, Puppet, Ansible** – Chef, Puppet, and Ansible are considered
configuration management tools, allowing you to quickly deploy everything that
needs to live on your servers very quickly. These tools can be used in tandem
with Terraform, allowing you to automate everything from server orchestration
to configuration deployment.

**Gitlab** – Gitlab is a leading Git repository that enables code version control
and also provides wiki and issue tracking.

**Jenkins** – Jenkins is a continuous integration tool that allows developers to
integrate code multiple times per day, providing the ability to push new
features and bug fixes into production very quickly. Jenkins will monitor the
code repository, build the systems and run unit and integration tests.

## Conquering the Cloud

Though cloud computing might be a new learning curve for many startup founders,
it is important to understand the value that it brings your business early on.
Cloud computing allows startup founders to focus on building and bringing their
products to market without making massive capital investments in hardware and a
team of people to manage it. Therefore, today’s startups have an advantage over
many existing businesses, by using the available technologies, where everything
IT is greenfield. Instilling the concepts of cloud into a new organization is
much easier to do than doing the same in a mature IT shop.

By understanding and using the tools at their disposal, startups can potentially
save a lot of money and a lot of headaches getting their ideas from concept to
market.
