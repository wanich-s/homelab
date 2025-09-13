# Claude-prompted homelab project

---

## Rules

### Global Rules
  - Do not hardcode, use environment variables and auto-detection instead.
  - Choose the best approach, and if any problems occur, solve them while maintaining the same quality.
  - Explain each step in detail, allow steps to be skipped or rolled back, and perform a verification check after completing every step.

---

## Hardware

### 1. Raspberry Pi
  - Raspberry Pi 5
  - 4GB of RAM
  - Boot from SSD 120GB via usb 3.0 port

---

## Software & Operating System

### 1. Operating System
  - Raspberry Pi OS Lite
  - System 64-bit
  - Kernel version 6.12
  - Debian version 12 (bookworm)
  - Memory Swap Optimization

---

## Services

### 1. Docker services
  - Pi-hole Lastest version
  - Nextcloud Lastest version
  - Joplin Lastest version
  - Gitea Lastest version
  - n8n Lastest version
  - Traefik reverse proxy Lastest version
  - Postgres Lastest version
  - SLMs Ollama Model `gemma3:270m-it-q8_0`
  - Rustdesk Lastest version
