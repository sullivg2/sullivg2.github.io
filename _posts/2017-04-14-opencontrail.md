---
title:  "OpenContrail – Enabling Advancements in Cloud Infrastructure Adoption"
categories:
 - Cloud
 - SDN
author: Geoff Sullivan
excerpt: "OpenContrail has solidified its position as the top SDN and network automation solution for OpenStack, and recently announced it’s integration into Kubernetes (K8s) and thus OpenShift (recent versions are powered by Kubernetes.) What does this mean for the organization mapping out their cloud infrastructure architecture?"
header:
  image: #"posts/coalmine.gif"
author_profile: true

---

**This post was originally featured on [tungten.io](https://tungsten.io/opencontrail-enabling-advancements-in-cloud-infrastructure-adoption/)**
{: .notice--info}

OpenContrail has solidified its position as the top SDN and network automation solution for OpenStack, and recently announced it’s integration into Kubernetes (K8s) and thus OpenShift (recent versions are powered by Kubernetes.) What does this mean for the organization mapping out their cloud infrastructure architecture?

## VMware -> OpenStack -> Kubernetes

At this juncture in cloud adoption, service providers and enterprises alike are defining their ever evolving stacks. The emergence of containers has changed the game – changing the conversation from “OpenStack or Kubernetes?” to “OpenStack and Kubernetes.” In many cases VMware is still in the mix somewhere. The combination of these platforms allows an organization to select the best hosting platform for each workload, based on it’s own unique characteristics:

- Aging monolithic application that will be deprecated in the next few years? Keep it where it is (VMware.)
- Distributed multi-tier web app? Perhaps OpenStack is a good candidate.
- Highly variable, net new microservices based application(s) – Kubernetes will allow the individual microservices to scale up and down independently of one another.

While all of this choice provides flexibility, it introduces complexity – especially on the network with each of the three platforms with three different networking stacks.

## How Contrail enables Successful Cloud Adoption
Introducing Contrail into a heterogeneous cloud/virtualization environment will help an organization move towards SDN adoption based on open standards. One SDN solution to manage them all! Furthermore, it isn’t realistic or likely for an organization to go from VMware to OpenStack to Kubernetes all at once – that is too much change to manage and it introduces risk. Because of it’s interoperability with all of these platforms, introducing Contrail will allow an organization to stitch together their virtualization/container platforms on their terms as their infrastructure evolves with the applications that sit atop it.

Check out how Contrail integrates with VMware, OpenStack, Kubernetes and OpenShift:

- [Integrating VMware ESXi with OpenStack, OpenContrail](http://www.opencontrail.org/integrating-vmware-esxi-with-openstack-opencontrail/)
- [Installing Contrail with VMware vCenter](http://www.juniper.net/techpubs/en_US/contrail2.2/topics/task/configuration/vcenter-integration-vnc.html)
- [OpenContrail Kubernetes Integration](http://www.opencontrail.org/opencontrail-kubernetes-integration/)
- [Video Demo: OpenContrail integration with OpenShift, Kubernetes](https://www.youtube.com/user/OpenContrail)

## 3 ways to get Getting Started with OpenContrail

- Try it yourself! – [OpenContrail Quick Start Guide](http://www.opencontrail.org/opencontrail-quick-start-guide/) (Software Installation guide for OpenContrail)
- Try OpenContrail Sandbox – [The Contrail Sandbox](http://www.opencontrail.org/sandbox/) is a cloud based testing environment that can help you evaluate Contrail Networking product on our infrastructure free of cost
- Let’s Chat – [Shoot me an email](mailto:geoffrsullivan@gmail.com)!