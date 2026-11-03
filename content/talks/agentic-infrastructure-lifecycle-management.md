---
title: "Agentic Infrastructure Lifecycle Management"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 16:00 - 16:50"
where: "Lil Tex"
pretalx_code: "SYKJDG"
pretalx_link: "https://pretalx.com/txlf2026/talk/SYKJDG/"
pretalx_managed: true
track: "Artificial Intelligence"

speakers:
  - name: "Cody Lee Cochran"
    image: "https://pretalx.com/media/avatars/7QZLDH_JFElwmI.webp"
    link: "speakers/cody-lee-cochran/"
---

AI assistants can generate infrastructure code quickly, but speed alone does not make infrastructure safe, repeatable, or maintainable. The interesting problem is not how to get an AI agent to write Terraform, Compose, Ansible, or Kubernetes manifests. It is how to design infrastructure projects where an agent can make useful changes without bypassing the engineering practices that make infrastructure-as-code reliable.


This talk presents a practical framework for using agentic tools across the infrastructure lifecycle: build, update, test, deploy, and destroy. Using Docker Compose-based applications as an approachable example, we'll examine how familiar IaC practices such as pinned dependencies, modular and DRY configuration, environment separation, secrets management, idempotency, automated testing, and reviewable changes become even more important when an AI agent is modifying the repository.


We'll also look at the agent-facing side of the problem: repository instructions, scoped context, validation commands, tests, and explicit guardrails that give an agent enough information to work effectively without giving it unrestricted authority over production-impacting decisions.


Although the examples use Docker Compose, the patterns apply broadly to Terraform/OpenTofu, Ansible, Kubernetes, Helm, Pulumi, CI/CD systems, and other infrastructure-as-code environments.


The goal is not better prompt engineering. It is better infrastructure engineering: building repositories where humans, automation, and AI agents can all make changes through the same predictable, testable, and reviewable lifecycle.
