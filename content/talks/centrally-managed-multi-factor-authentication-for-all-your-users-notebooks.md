---
title: "Centrally managed multi factor authentication for all your users' notebooks"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 17:00 - 17:50"
where: "Bevo"
pretalx_code: "JZGLEW"
pretalx_link: "https://pretalx.com/txlf2026/talk/JZGLEW/"
pretalx_managed: true
track: "Security"

speakers:
  - name: "Cornelius Kölbel"
    image: "https://pretalx.com/media/avatars/ZQGY8V_r0J1Y8e.webp"
    link: "speakers/cornelius-k-lbel/"
---

In enterprises or organizations users and their 2nd factors are managed centrally by you, the IT department. This works fine with logins to central services like web portals, the VPN or your SSH servers.


But when it comes to the login at notebooks it comes to some additional challenges you need to overcome. Even in 2026 - notebooks can go offline.


There are many different technical ways for multi factor authentication with different underlying cryptographic mechanisms. Symmetic keys or assymmetic keys. Some can work offline, some are hard to manage, some do not work offline in a sensible way.

In this talk we are looking into different authentication mechanism be it x509 certificates, OTP or FIDO2 to name a few with their pros and cons.


Then we check how the open source multi factor management system privacyIDEA implements different ways of authenticating offline at your user's notebooks - be it Linux or Windows - with OTP tokens or with FIDO2 devices. In 2019 I held a talk at TXLF about privacyIDEA in general as an on prem multi factor solution. We are now looking deeper into management of FIDO2 devices and management for local logins to Linux and Windows machines.


You will get in depth knowledge how you can secure your notebooks with reliable authentication hardware like Yubikeys or other FIDO2 devices centrally managed in your own on prem privacyIDEA system.
