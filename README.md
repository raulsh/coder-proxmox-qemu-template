---
display_name: Proxmox Qemu VM
description: A minimal VM
icon: ../../../site/static/emojis/1f4e6.png
maintainer_github: raulsh
verified: true
tags: []
---

# Proxmox Qemu VM template

This repo contains a Terraform template for Coder https://github.com/coder/coder to setup a VM as dev environment with vscode.

This template will do the following:
- Creates a new VM on a Proxmox server based on a VM template

## Prerequisites

- A Proxmox server with a VM template to clone
- A Proxmox API URL, token ID, and token secret
- An SSH username and password for the Proxmox server (SSH must be enabled)
