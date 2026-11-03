---
title: "From Log Files to Live Signals: Rethinking HPC Operations on Linux Bare Metal"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 14:00 - 14:50"
where: "Bevo"
pretalx_code: "D9AYRJ"
pretalx_link: "https://pretalx.com/txlf2026/talk/D9AYRJ/"
pretalx_managed: true
track: "Automation"

speakers:
  - name: "Borislav Sabotinov"
    image: "https://pretalx.com/media/avatars/U8NXHC_Yr059I2.webp"
    link: "speakers/borislav-sabotinov/"
---

A large share of High-Performance Compute (HPC) work runs on Linux: the schedulers, bare metal nodes, job queues, and MPI processes. The operating model is usually reactive. An engineer submits a job, waits hours or days, and reads a log file after the damage is done. By then the compute is spent, the data is stale, and the decisions that depended on it are late.


This talk is a real enterprise case study in flipping that model from reactive to proactive. We built a Linux-native automation layer that connects a chat-based control plane to underlying bare metal HPC infrastructure, serving several thousand internal engineering users running millions of simulations per year. Shell scripts and system-level integration drive event-driven pipelines and feed data into a control plane that gives engineers timely, actionable signals before compute time is wasted.


We combined pre-submit validation, to catch the failures that never needed to run, with runtime inspection of solver state to identify stalled or diverging jobs while they are still cheap to kill. Near real-time alerts moved job status out of log files and into chat where users already work. The result is hundreds of thousands of compute hours saved per year, tens of thousands of engineer hours reclaimed, and millions of dollars in cost savings. 


This talk shows that proactive HPC operations at scale are an automation problem you can already solve on the Linux stack you have.
