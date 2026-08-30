---
layout: default
title: Configuration
---

[Overview](index.html) \| [Installation](installation.html) \| [Security](security.html) \| [Configuration](configuration.html) \| [Downloads](downloads.html)

---

# System Setup

Sparrowling uses systemd and keeps configuration direct. These starter notes outline the kinds of tasks users should expect after installation.

## Common first tasks

* Create or review local user accounts.
* Set hostname, timezone, locale, and keyboard layout.
* Configure networking for the target environment.
* Enable only the systemd services the machine needs.

## Service management

Use systemd to inspect, enable, disable, start, and stop services.

```bash
systemctl status
sudo systemctl enable --now example.service
```
