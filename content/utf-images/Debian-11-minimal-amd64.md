---
title: "Debian 11 Minimal AMD64"
thumbnail: thumbnail.png
images:
- thumbnail.png
- screenshot1.png
link_to_image: https://github.com/jamesmortensen/virtual-machine-releases/releases/download/debian-11-minimal-amd64-v1.0/Debian-11-minimal-amd64.utm.zip
link_to_website: https://github.com/jamesmortensen/virtual-machine-releases/releases/tag/debian-11-minimal-amd64-v1.0
spice_tools: false
username: debianx64
password: debian
tags: 
- debian
- x86_64
- amd64
- minimal
- console
- linux
description: "This is a Debian 11 minimal VGA/console image for the x86_64/amd64 architecture. This runs on arm64 Mac M1's and could be adapted to run on native x86_64 hardware or on Linux hosts."
---

<!--
Down here you can add further information a user might need for the image
-->

Architecture: x86_64 / amd64
Memory: 1024 MB
Disk: 1.91 GB
Display: VGA+Console
SPICE tools: unknown
Username: debianx64
Password: debian

Unzip the zip archive, and then import the utm VM into the UTM app by clicking the + button at the top, and then click "open", then navigate to the debian-11-minimUTM package.

If networking does not work using UTM, follow the steps in this UTM discussion, which involves renaming the network interface to the next number in the numerical series. For instance, if it was enp0s7, then rename it to enp0s8.
