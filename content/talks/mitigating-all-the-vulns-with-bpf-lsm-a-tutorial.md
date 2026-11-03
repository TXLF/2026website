---
title: "Mitigating All The Vulns with BPF-LSM: A Tutorial"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Workshop"
when: "Friday, November 6, 15:00 - 16:20"
where: "Stadium"
pretalx_code: "J3DRGC"
pretalx_link: "https://pretalx.com/txlf2026/talk/J3DRGC/"
pretalx_managed: true
track: "Security"

speakers:
  - name: "Chris Arges"
    image: "https://pretalx.com/media/avatars/VWZBAH_in0V5pw.webp"
    link: "speakers/chris-arges/"
---

When yet another Linux kernel vulnerability lands on the front page, what are your options?

If you are lucky, it was patched months ago and is already in your distro kernel or latest stable LTS release. Worst-case, the patch doesn't exist yet and you're going to be exposed until one exists and you can reboot your fleet.


What if I told you... there is another way to mitigate these vulnerabilites and you don't even need to reboot your machine! To do this at Cloudflare we reached for BPF-LSM. In this hands-on workshop, you'll build your very own defensive BPF LSM program that can be used to disarm some of these attacks.


Starting from a "hello world" LSM program, you'll write and load your own BPF-LSM code on your laptop and watch it deny an operation in real time: blocking a syscall path the same way a live vulnerability mitigation would.


We'll cover how the Linux Security Module framework and BPF fit together, how LSM hooks differ from raw syscalls, how to return "permission denied" from your own policy, and how to verify it actually works.


Prerequisites: A laptop capable of running the provided VM image (setup instructions TBD). Comfort with C and the Linux command line is helpful.
