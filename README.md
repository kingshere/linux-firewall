# 🔥 Firewall for Linux

A lightweight firewall project for Linux that filters TCP and UDP packets at the kernel level using Netfilter. It supports adding, removing, and viewing firewall rules based on direction (inbound/outbound), IP addresses, ports, and protocol numbers.

---

## 📌 Features

- Filters TCP and UDP packets using custom rules.
- Command-line interface to:
  - Add rules
  - Remove rules
  - View all rules
- Packet filtering happens in the kernel space using a dynamically loaded kernel module.
- Communication between user-space and kernel-space via a character device file.
- Uses Netfilter hooks for inbound and outbound packet inspection.

---

