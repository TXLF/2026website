---
title: "Enterprise Kubernetes at Home: A Homelabber's Guide to OKD"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 15:00 - 15:50"
where: "Lil Tex"
pretalx_code: "FQTX9Y"
pretalx_link: "https://pretalx.com/txlf2026/talk/FQTX9Y/"
pretalx_managed: true
track: "Cloud Native"

speakers:
  - name: "Thomas Cameron"
    image: "https://pretalx.com/media/avatars/BDYMQL_qLQBcrP.webp"
    link: "speakers/thomas-cameron/"
---

Running enterprise-grade Kubernetes platforms like OpenShift provides invaluable career skills, but translating that architecture into a home or departmental lab can feel like shoving a square peg into a round hole. Datacenter luxuries like hardware load balancers, enterprise storage arrays, and endless pools of RAM don't exist under your desk. Thankfully, the upstream OKD project brings that exact same cloud-native power to your local hardware—if you know how to navigate the infrastructure hurdles.


This presentation is a practical survival guide for successfully deploying OKD in resource-constrained environments. We will map out the architectural prerequisites that trip up most deployments, focusing heavily on configuring wildcard DNS subdomains and strict reverse DNS (PTR) records for node discovery. We will look at strategies for handling cluster ingress using lightweight open-source load balancers like HAProxy, and contrast persistent storage methods, comparing single-node local storage layout against multi-node NFS shared exports. Attendees will leave with a clear, realistic blueprint for spinning up a functional OKD cluster without melting their hardware or their power budget.


Key Takeaways:

- Sizing and Footprint: Navigating the trade-offs between traditional High Availability topologies, hyper-converged virtualized clusters, and Single Node OKD (SNO).

- The Networking Triad: Step-by-step logic for implementing the API load balancer, configuring wildcard application routes, and getting PTR records right.

- Storage Demystified: Configuring robust persistent volume backing using standard local LVM provisions or shared NFS storage mappings on Fedora CoreOS nodes.
