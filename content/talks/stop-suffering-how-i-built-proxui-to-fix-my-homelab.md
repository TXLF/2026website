---
title: "\"Stop Suffering: How I Built ProxUI to Fix My Homelab\""
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 10:00 - 10:50"
where: "Stadium"
pretalx_code: "SGK7R7"
pretalx_link: "https://pretalx.com/txlf2026/talk/SGK7R7/"
pretalx_managed: true
track: "Infrastructure"

speakers:
  - name: "Alexander Shut"
    image: "https://pretalx.com/media/avatars/KDTQRX_UVah4W5.webp"
    link: "speakers/alexander-shut/"
---

As a sysadmin, I spent years managing my Proxmox homelab the hard way - juggling browser tabs, editing config files by hand, running the same commands over and over. Every gap in my workflow was a small daily frustration. Then I stopped waiting for someone else to fix it and built ProxUI: a self-hosted Proxmox management UI built by a sysadmin, for sysadmins.


This talk is not about being a developer. It's about recognizing that the tool you need probably won't be built by a company - because your use case is too specific, too personal, and too real. Every feature in ProxUI exists because I needed it: a single-page cluster dashboard, multi-cluster switching, automated cloud-ready qcow2 image builds, LXC device passthrough without editing config files, and more. Each one started as something I was doing by hand.


I'll walk through the gap-driven development process: how frustration becomes a feature, how a sysadmin with minimal software engineering background ships a real tool and giving to the open source community. I'll also cover the infra around the project — how to build and store cloud images, how to run a live demo environment, and how to deploy ProxUI in your own homelab in minutes.


If you've ever thought "someone should build this" — this talk is for you.
