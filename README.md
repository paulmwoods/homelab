# homelab

This repository documents my self-hosted homelab - an evolving setup built on a custom Debian server using Docker, with a focus on understanding how storage, networking, and remote access actually work in practice.

The setup has been eight years in the making, starting with a hard drive plugged into a domestic router, through a Synology NAS, and eventually to a custom-built Debian serevr. It's a real system used daily by my wife and kids - not a hypothetical lab exerise - which means the decision geind it have been shapred as much be reliability and usability as by technical interest.

The aim isn't to show a polished system, but to document how it has been build, what has gone wrong along the way, and the thinking behind the current setup. There are always compromises in a homelab, and I'm more interested in explaining why I made the choices I did than in pretending every decision was optimal.

## coming soon

 - Full architecture overview
 - Docker Compose configurations for the current stack
 - Storage architecture notes (mergerfs + SnapRAID - and why I oved away from RAID)
 - Tailscale setup and access model (including how this works with my kids and extended family)
 - Migration notes from Synology to Debian
 - Write-ups on specfic decisions, what broke, and what I'd do differently
