---
title: "The Design and Implementation of the 5BSD Operating System"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 17:00 - 17:50"
where: "Balcones"
pretalx_code: "XQUDW7"
pretalx_link: "https://pretalx.com/txlf2026/talk/XQUDW7/"
pretalx_managed: true
track: "Distributions"

speakers:
  - name: "Kory Heard"
    image: "https://pretalx.com/media/avatars/8L7GLA_pDWbHt1.webp"
    link: "speakers/kory-heard/"
---

5BSD explores a different approach to operating system security. Rather than starting every process with broad ambient authority and then restricting it through layers such as namespaces, seccomp, LSMs, and cgroups, 5BSD begins with no ambient authority. Every privilege is represented by an explicit capability granted to a process, and no process can acquire authority it was not intentionally delegated.


Built on FreeBSD, 5BSD extends the operating system with a capability-oriented runtime while preserving compatibility with existing software, including Linux applications through the Linux ABI layer. Traditional UNIX applications continue to operate through familiar interfaces, while capability-aware applications can take advantage of new system calls and kernel services designed around explicit authority.


The system is bootstrapped by the Oracle, the privileged system initializer. Oracle launches workloads, constructs their initial capability sets, and delegates only the authority required for their intended function. After startup, workloads operate using the capabilities they possess rather than relying on ambient privileges. Services are discovered through Serviced, 5BSD’s capability-aware service registry, while kernel facilities such as Keyvault and mac_abac provide cryptographic services and attribute-based access control without exposing unnecessary privilege to applications.


This talk introduces the architecture behind 5BSD, including capability bootstrapping, authority delegation, capability-aware system calls, and compatibility with existing UNIX and Linux software. We will follow a workload from process creation through capability initialization, demonstrate how capabilities are transferred and enforced, and examine how the system behaves when software attempts operations outside its delegated authority.


Attendees will gain a practical understanding of capability-oriented operating system design, how 5BSD integrates capabilities into a BSD-derived kernel without abandoning compatibility, and how explicit authority provides a foundation for building systems with stronger isolation and more predictable security properties.
