---
title: "Recruit your friends into a backup cult!"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 11:00 - 11:50"
where: "Stadium"
pretalx_code: "U97UWX"
pretalx_link: "https://pretalx.com/txlf2026/talk/U97UWX/"
pretalx_managed: true
track: "Infrastructure"

speakers:
  - name: "Kevin Purdy"
    image: "https://pretalx.com/media/avatars/3PQDZT_rqvBkhh.webp"
    link: "speakers/kevin-purdy/"
---

Everyone knows 3-2-1 backups, but that "1 offsite copy" is the part that trips people up. Rather than pay for a storage subscription, why not enter a pact with a friend? You'll both grab your stuff from the cloud, store them on a big drive, and sync a copy to each other's big drives—fully encrypted and inaccessible to the public internet.


This is the true story of how I walked a friend through this experiment and became their Fireproof Backup Buddy. Their most important stuff is attached to my NAS; my stuff is on a drive attached to their computer. Flood, fire, ransomware, deeply stupid technical decision: we're both covered, and neither of us pays a grudging backup bill.


This talk will walk through setting up a system with:

- Restic encrypting for diff-based backups

- Tailscale (or just Wireguard) for reliable remote access

- rclone keeping your Google stuff up to date (reality check)


Will I be able to restore a real file from my friend's computer, during the talk? Maybe! Probably. Could be fun.
