---
layout: default
title: Security
---

[Overview](index.html) \| [Installation](installation.html) \| [Security](security.html) \| [Configuration](configuration.html) \| [Downloads](downloads.html)

---

# Security Model

Sparrowling's first security goal is minimalism: fewer default services, fewer default packages, and fewer moving parts to configure, patch, and audit.

## Initial principles

* Keep the base install small and understandable.
* Prefer explicit service enablement over broad defaults.
* Document verification steps for images and release artifacts.
* Make configuration readable for server and security-minded users.

## Verify downloads

Use published checksums before writing an image to removable media.

```bash
sha256sum -c SHA256SUMS --ignore-missing
```
