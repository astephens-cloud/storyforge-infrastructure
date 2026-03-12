# 

# HAL — Docker Container Registry

A summary of all containerized services running on **HAL**, organized by function.

---

## Web & Networking

- **AdGuard Home** — Network-wide DNS-based ad and tracker blocking. Acts as a local DNS resolver for the homelab.

- **Newt** — Lightweight tunnel client, likely paired with Pangolin for secure reverse proxy connectivity.

- **Tor Relay** — Contributes bandwidth to the Tor anonymity network as a relay node.

---

## Monitoring & Uptime

- **Netdata** — Real-time performance monitoring and system metrics visualization with low overhead.

- **UptimeKuma** — Self-hosted uptime monitoring dashboard for tracking service availability and sending alerts.

---

## Databases & Storage

- **PostgreSQL 12.5** — Open-source relational database powering backend services that require structured SQL storage.

- **Redis** — In-memory key-value store used for caching, session management, and fast data retrieval.

- **MariaDB (Official)** — MySQL-compatible relational database serving additional web applications and services.

---

## Security & Secrets

- **Vaultwarden** — Lightweight, self-hosted Bitwarden-compatible password manager for secure credential storage.

- **MousehoLe** — Privacy-focused proxy or tunnel service for obfuscated network traffic routing.

---

## Automation & AI

- **Sure-Web / Sure-Worker** — Web frontend and background worker pair, likely handling job queuing and task processing.

- **CronMaster** — Scheduled task manager for automating recurring jobs across the homelab.

- **Paperless-AI** — AI-enhanced document management system for ingesting, tagging, and searching scanned documents.

---

## Home Automation

- **Home Assistant** — Central hub for smart home device control, automation, and integrations.

- **Music Assistant** — Self-hosted music library manager and player with smart home integration support.

- **Matter Server** — Implements the Matter smart home protocol, enabling cross-platform device compatibility with Home Assistant.

---

## Gaming & Media

- **All the Mods 10** — Dedicated Minecraft modpack server running the ATM10 kitchen-sink modpack.

- **Ripper** — Media ripping/processing service, likely for automated disc or audio content extraction.

- **binhex-DelugeVPN** — BitTorrent client (Deluge) bundled with VPN support for private, encrypted downloading.

---

## Content & Documents

- **Grav** — Flat-file CMS for lightweight web publishing without a database backend.

- **BentoPDF** — PDF utility service for document manipulation, merging, or conversion tasks.

---

## Crypto & Finance

- **Bitcoind** — Full Bitcoin node running the core daemon, contributing to network validation and enabling local wallet operations.

---

*Last updated: March 2026 · Server: HAL*
