---
title: "RamaLama + Podman Quadlets — Build Task-Specific AI Services with systemd"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Workshop"
when: "Friday, November 6, 13:30 - 14:50"
where: "Stadium"
pretalx_code: "88EDHE"
pretalx_link: "https://pretalx.com/txlf2026/talk/88EDHE/"
pretalx_managed: true
track: "Artificial Intelligence"

speakers:
  - name: "David Duncan"
    image: "https://pretalx.com/media/avatars/XHYHRX_Eb2EJor.webp"
    link: "speakers/david-duncan/"
---

Running a model locally is easy. Turning that model into multiple task-specific services — each with its own security boundary, system prompt, and restart policy — is where most guides stop. This workshop picks up where `ramalama run` leaves off.


RamaLama gives you container-native local AI inference with one command: pull a model from an OCI registry, detect your GPU, serve it. Podman quadlets turn that into a systemd-managed service that starts on boot, restarts on failure, and logs to journald, but one model can do many jobs! By placing lightweight agent containers in front of a single RamaLama model server you will build task-specific AI services that behave like any other daemon on your Linux box. No Kubernetes required.


Prerequisites: Laptop with a browser. Familiarity with Linux command line helpful but not required — we explain every unit file directive.
