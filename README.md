# 🖥 Home Server

My personal home server infrastructure built and maintained by me.

This project is mainly used for self-hosting, networking experiments,
remote access and learning how server infrastructure works in practice.

---

## ⚙️ Stack

- 🐧 Linux
- 🐳 Docker
- 🔐 WireGuard
- 🎬 Jellyfin
- 🌐 Networking
- 🏠 Self-hosted services

---

## 🔧 What I did

### Server

Set up and configured my own server environment from scratch.

- Linux installation and configuration
- Server administration
- Storage and service management
- Network configuration
- Remote access

### Docker

Use Docker to deploy and manage self-hosted services.

- Container deployment
- Service configuration
- Port mapping
- Container management
- Troubleshooting

### WireGuard

Built my own VPN setup using WireGuard for secure remote access
to my home network and services.

- VPN server configuration
- Client configuration
- Key management
- Network routing
- Remote access

### Jellyfin

Self-hosted media server for managing and streaming my personal
media library across devices.


## 📸 Server

Screenshot of my server environment:
<img width="1280" height="653" alt="StagCloud" src="https://github.com/user-attachments/assets/d06b781c-e340-4c1e-a42b-73225d3d70e2" />

---

## 🌐 Network

Basic infrastructure:

```text
                    Internet
                       │
                       ▼
                   Home Router
                       │
              ┌────────┴────────┐
              │                 │
              ▼                 ▼
          Home Network      WireGuard VPN
              │                 │
              │                 ▼
              │           Remote Devices
              │
              ▼
          Home Server
              │
         ┌────┴────┐
         │         │
         ▼         ▼
      Docker    Other Services
         │
         ▼
      Jellyfin
