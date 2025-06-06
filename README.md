# Media Stack (Jellyfin)

This repository contains a simple Docker Compose setup for running [Jellyfin](https://jellyfin.org/) using the LinuxServer.io image.

## 🔧 Setup Instructions

📁 Default Volumes

/opt/docker-config/jellyfin → Jellyfin config

/mnt/jellyfin/Movies → Movie library

/mnt/jellyfin/TV Shows → TV library

🔒 Security Notes

The container runs as a non-root user (PUID=1000)

No passwords or tokens are hardcoded

Ports are open to LAN only by default

