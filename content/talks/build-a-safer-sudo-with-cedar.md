---
title: "Build a Safer sudo with Cedar"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Workshop (long)"
when: "Friday, November 6, 13:30 - 16:20"
where: "Bevo"
pretalx_code: "EF3G9A"
pretalx_link: "https://pretalx.com/txlf2026/talk/EF3G9A/"
pretalx_managed: true
track: "Other"

speakers:
  - name: "Michael Schwartz"
    image: "https://pretalx.com/media/avatars/UEWK8J_oAv3Dno.webp"
    link: "speakers/michael-schwartz/"
---

Cedar is an open-source authorization policy language and CNCF Sandbox project for expressing fine-grained permissions in policies that are human-readable and designed for automated analysis. In this hands-on workshop, attendees will use Cedar to authorize privileged Linux operations invoked through sudo. Using a local VM and the Tarp browser client, participants will test and modify policies controlling who may view logs, check service status, or restart a systemd service. The demo also shows context-aware rules—such as allowing local operations while denying SSH requests—and how root-owned fixed command mappings prevent argument injection, arbitrary commands, and unauthorized shell access.
