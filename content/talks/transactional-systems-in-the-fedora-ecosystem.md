---
title: "Transactional Systems in the Fedora Ecosystem"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 15:00 - 15:50"
where: "Balcones"
pretalx_code: "PJLVGM"
pretalx_link: "https://pretalx.com/txlf2026/talk/PJLVGM/"
pretalx_managed: true
track: "Distributions"

speakers:
  - name: "Neal Gompa"
    image: "https://pretalx.com/media/avatars/GSJ7WA_vwcvc5B.webp"
    link: "speakers/neal-gompa/"
  - name: "Shawn W Dunn"
    image: "https://pretalx.com/media/avatars/RCVT7X_zO31Ksl.webp"
    link: "speakers/shawn-w-dunn/"
---

Transactional systems offer a middle ground between Fedora Atomics, and their image based updating, and read-only filesystems and Traditional Fedora, with it's read/write filesystems, as they can be configured to do either, offering great flexibility.


In a read-only context, transactional Fedora offers a minimal system, and workloads are handled through podman or docker containers, for server usage. On the desktop, toolbox, distrobox, flatpaks, and potentially other application delivery mechanisms can be used, while still providing the possibility of local modifications to the read-only filesystem, for things that just make sense to be delivered via RPM.


In a read-write context, Transactional systems offer Atomic updating, offering the possibility of more reliable updating, more stable systems over time, and the ability to "rollback" snapshots, in case of issues. or for troubleshooting purposes.


This talk will discuss the basic ideas behind Transactional Updates, how they're used in openSUSE, and what it takes to bring them to Fedora.
