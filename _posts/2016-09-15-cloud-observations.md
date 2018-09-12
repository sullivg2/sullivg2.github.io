---
title:  "Observations from a Former Cloud Consultant"
categories:
 - Cloud
author: Geoff Sullivan
excerpt: "This month I embarked on a new journey, leaving the consulting world
behind and moving into a marketing capacity with a leading provider of
networking technology."
header:
  image: #"posts/coalmine.gif"
author_profile: true

---

**This post was originally featured on [Sweetcode](https://sweetcode.io)**
{: .notice--info}

This month I embarked on a new journey, leaving the consulting world behind and
moving into a marketing capacity with a leading provider of networking
technology. Although I am often a critic of the IT industry and its antiquated
ways, I am also a student of it, and I’ve made it my goal to better understand
all of the aspects of it, so that one day I can hopefully make a difference.

So as I make this transition, I want to leave a few notes behind from my own
experiences working with organizations who are moving their infrastructure to
the cloud.

## The cloud isn’t magic

The cloud isn’t something you should be scared of. The companies who have
figured it out (Amazon, Google, Microsoft, and many more) are providing you with
the opportunity to run your infrastructure in the same manner that they run
their own. It’s just servers, storage and networks managed by software in an
automated way that has proven to be much more efficient than the way you’re
currently running your traditional infrastructure.

I’ve come across several clients who assume that cloud is unattainable for their
organization. One of the biggest worries is that the learning curve is too
steep, but this is only a matter of perception. The beauty of the cloud is that
you can start off running your cloud servers similar to the way you run your
servers on-premises—then you can begin to implement cloud-specific optimizations
like automation and orchestration to make operations more intelligent and
efficient.

## Cloud infrastructure will bear fruit once operationalized

I’ve never been a fan of the cost-per-VM-based TCO. Yes, it is a component of
the overall cost, but there is so much more to cloud infrastructure than cheaper
VMs. It is critical to understand how the cloud will change your everyday
operational processes, where efficiencies will be gained, and where the gaps in
knowledge and process exist. Build a plan to address these elements, but DO NOT
write them in stone. Embrace change and an ever-improving approach to managing
cloud infrastructure.

I have worked with enterprise customers who have invested
millions of dollars in shiny new cloud technology (private cloud),
just to have it sit in the corner to collect dust. The reason? All of the
upfront planning was related to hard costs associated with the investment, and
little was put into understanding how teams would work together towards the
ultimate goal of more efficient software development and IT operations.

## Security and privacy concerns are lame excuses

I’m so tired of security and privacy excuses. Of course, not every application
(and associated data) is a candidate for the public cloud because of regulatory
or legal/privacy mandates in a given industry or jurisdiction, but chances are
not all of your applications are bound by the same restrictions. The public
cloud providers probably do a better job of securing their infrastructure than
you do, and at the end of the day you own root access to your public cloud VMs
and control over your VPC (Virtual Private Cloud), so you can introduce
(or re-write) your own internal security processes and policies in the public
cloud context.

If you are one of those organizations that stores sensitive
and/or private data, a good starting point that I’ve found effective is to put
effort into classifying your existing applications and data. Part of this is
understanding the restrictions that you are bound by as a host of such
data—which isn’t always an easy task.

## Start small and manage stakeholder expectations

Cloud projects shouldn’t be “Big Bang,” all-encompassing endeavors. Start with a
well-defined project with a business case and funding and measure everything.
This way you have a benchmark to work off of for future projects, and you should
aim to never stop making efforts to improve these cloud workloads once they
exist. This approach should arm you with everything you need to answer to your
stakeholders when they want progress reports.

## Partner with the right people

There are a lot of people out there that have gone down this road ahead of you,
with their own success and failure stories. Leverage these people. Be warned,
however, that there are a lot of systems integrators and consultants who are
very new to the cloud as well. Ask for references and case studies from cloud
consultants, and look for those who would prefer to partner with you on your
projects, rather than just doing the work for you.

The IT channel is being  disrupted, just as most other businesses, so there is a
scramble to build up cloud competencies in a short amount of time. The result is
a lot of people talking, and much less doing. Beware!

## Understand the Layers of Abstraction in Cloud

I feel that we are almost at the point where IaaS has become a normalized
utility. AWS, Azure, Google etc. all do a pretty good job of vending virtual
machines, storage and networks, but it is pretty utilitarian. Consider looking
at moving up the value chain into the PaaS world. PaaS allows you to build your
own tailored code management and deployment assembly line (Red Hat’s analogy,
not mine) for the cloud.

With PaaS, Devs understand how your apps interact with PaaS APIs, and Ops
understands how PaaS interacts with IaaS APIs. The Devs don’tcare which cloud
provider you are running on, because ideally they don’t interact with the
provider’s APIs directly, so embracing “hybrid mode” is afunction of
understanding how the PaaS layer interacts with the the differentIaaS utility
options.
