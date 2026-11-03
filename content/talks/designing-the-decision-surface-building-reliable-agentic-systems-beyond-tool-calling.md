---
title: "Designing the Decision Surface: Building Reliable Agentic Systems Beyond Tool Calling"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 11:00 - 11:50"
where: "Lil Tex"
pretalx_code: "M8H3K9"
pretalx_link: "https://pretalx.com/txlf2026/talk/M8H3K9/"
pretalx_managed: true
track: "Artificial Intelligence"

speakers:
  - name: "Pragya Keshap"
    image: "https://pretalx.com/media/avatars/S9VGN9_bBtpJAX.webp"
    link: "speakers/pragya-keshap/"
  - name: "Akhilesh Keshap"
    image: "https://pretalx.com/media/avatars/QVEBX3_V2OnbfN.webp"
    link: "speakers/akhilesh-keshap/"
---

AI agents are evolving from conversational assistants into systems that can execute shell commands, modify files, call APIs, start containers, and interact with production infrastructure. Giving an agent these capabilities can unlock powerful automation—but it can also turn a bad model decision, prompt-injection attack, or compromised tool response into a serious security incident.


This session explores how Linux security primitives can be used to contain agentic workloads before they are trusted with real systems.


We will build a practical threat model for an AI agent with access to the operating system and examine risks such as excessive privileges, unsafe command execution, credential exposure, unrestricted network access, resource exhaustion, and accidental modification of host files.


The session will then demonstrate how to reduce these risks using rootless containers, Linux namespaces, cgroups, capability dropping, seccomp profiles, read-only filesystems, AppArmor or SELinux policies, network restrictions, ephemeral credentials, and detailed audit logging.


A live demonstration will compare the same agent running in an overly permissive environment and in a hardened Linux sandbox. We will observe which dangerous operations succeed, which are blocked, and how the security controls affect the agent’s behavior.


Attendees will leave with a practical architecture and security checklist for running AI agents that can safely interact with Linux systems, containers, APIs, and infrastructure.
