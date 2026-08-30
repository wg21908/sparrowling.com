---
layout: default
title: Installation
---

[Overview](index.html) \| [Installation](installation.html) \| [Security](security.html) \| [Configuration](configuration.html) \| [Downloads](downloads.html)

---

# Install Sparrowling

These notes are starter guidance for early Sparrowling images. Replace placeholder commands as the installer, release process, and supported platforms become final.

## Before you begin

* Back up any data on the target system.
* Confirm the machine is a supported 64-bit x86 system.
* Download the current Sparrowling image from the project site.
* Verify the image checksum before writing it to USB media.

## Write the image

On an existing Linux system, identify the USB device carefully, then write the image.

```bash
lsblk
sudo dd if=sparrowling-base-x86_64.iso of=/dev/sdX bs=4M status=progress conv=fsync
```

> **Warning:** The `dd` command overwrites the target device. Replace `/dev/sdX` with the correct USB device, not a partition such as `/dev/sdX1`.
