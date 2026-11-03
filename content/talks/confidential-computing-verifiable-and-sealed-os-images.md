---
title: "Confidential Computing: Verifiable and Sealed OS Images"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Workshop"
when: "Friday, November 6, 13:30 - 16:20"
where: "Big Tex"
pretalx_code: "KBRFMJ"
pretalx_link: "https://pretalx.com/txlf2026/talk/KBRFMJ/"
pretalx_managed: true
track: "Cloud Native"

speakers:
  - name: "Sean Thrailkill"
    image: "https://pretalx.com/media/avatars/CYW7SD_KkD2Ypv.webp"
    link: "speakers/sean-thrailkill/"
---

Image based Linux OSes have become increasingly popular. From GnomeOS to Bazzite there are a lot of ways to build and maintain your images. This workshop will walk you through how to improve a standard transactional deployment to be hardened, sealed, and verifiable including hardware-rooted attesation by utilizing Unified Kernel Images (UKI), bootc, and composefs.


We will walk through the entire lifecycle of an OCI-native operating system:


1. Defining the image: Customizing a container image tailored for your needs.

2. Leveraging Composefs: Understanding how bootc ingests OCI containers and materializes them into a secure, verifiable, read-only filesystem.

3. Sealing the OS: Bundling your configuration into a Unified Kernel Image (UKI) to establish strict lifecycle and update guarantees rooted in hardware security. 

4. Booting and Verification: Deploying your newly minted image and validating its tamper-resistance and deployment integrity.


By the end of this lab, you will walk away with a fully functional, self-generated sealed image template and the practical confidence to implement container-like immutability across your infrastructure.


Prerequisites for Attendees:

- Familiarity with Podman and basic Linux command-line navigation.

- A Linux machine capable of running a virtual machine (KVM/QEMU, qemu-img, virtiofsd, openssh-clients)
