# 🏠 Hardware Inventory - Homelab

## 📋 Table of Contents

1. [Computing Infrastructure](#computing-infrastructure)
2. [Storage & NAS](#storage--nas)
3. [Network & Connectivity](#network--connectivity)
4. [Portable Devices & Consoles](#portable-devices--consoles)
5. [Remote Infrastructure](#remote-infrastructure)
6. [Technical Specifications](#technical-specifications)

---

## English

### 🖥️ Computing Infrastructure

| Device | Brand | Model | CPU | RAM | Storage | GPU | OS | Usage |
|--------|-------|-------|-----|-----|---------|-----|----|----|
| <img src="https://cdn.simpleicons.org/intel/0071C5" width="32" height="32" alt="Intel" /> Main PC | Intel | i7-1800X | i7-1800X | 2x 8 GB DDR4 | 480 GB NVMe | NVIDIA GTX 1660 | Windows 10 | Gaming & Development |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Raspberry Pi 5 | Raspberry Pi | RPi 5 | ARM Cortex-A72 | 8 GB RAM | 256 GB NVMe + 480 GB NVMe | Integrated | Linux | Docker Host & Primary Homelab |
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> Mac Mini | Apple | A1357 | Intel Core 2 Duo | 6 GB RAM | 250 GB SSD | N/A | macOS | APK Builder |
| <img src="https://cdn.simpleicons.org/cubie/000000" width="32" height="32" alt="CubieBoard" /> CubieBoard | Cubieboard | CB4 | ARM A20 | 4 GB RAM | 16 GB eMMC | N/A | Linux | Development & Testing |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Raspberry Pi 3 | Raspberry Pi | RPi 3B+ | ARM Cortex-A53 | 1 GB RAM | 32 GB microSD | N/A | Linux | Monitoring Stack |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Remote Raspberry Pi 5 | Raspberry Pi | RPi 5 | ARM Cortex-A72 | 8 GB RAM | microSD 128 GB | N/A | Linux | Distributed Infrastructure |
| <img src="https://cdn.simpleicons.org/dell/007DB8" width="32" height="32" alt="Dell" /> Dell NUC PC | Dell | D08U | Intel Core i5 | 8 GB RAM | 256 GB SSD | N/A | Linux | Distributed Computing |

### 💾 Storage & NAS

| Device | Brand | Model | RAID | Capacity | Usage | Specifications |
|--------|-------|-------|------|----------|-------|---|
| <img src="https://cdn.simpleicons.org/synology/000000" width="32" height="32" alt="Synology" /> Mini-ITX NAS | Synology | NAS-04 | RAID 5 | 4x 1TB (3.6 TB usable) | Primary Storage & Backup | Mini-ITX Form Factor |
| <img src="https://cdn.simpleicons.org/truenas/000000" width="32" height="32" alt="TrueNAS" /> TrueNAS | TrueNAS | System | RAID | To be configured | WebDAV & Distributed Storage | Self-Hosted |

### 🌐 Network & Connectivity

| Component | Brand | Model | Type | Specifications | Usage |
|-----------|-------|-------|------|---|---|
| <img src="https://cdn.simpleicons.org/ubiquiti/0099FF" width="32" height="32" alt="Ubiquiti" /> Network Switch | Ubiquiti | UniFi Switch 8 60W | PoE Switch | 8 ports + 60W PoE | Power & Data |
| <img src="https://cdn.simpleicons.org/ubiquiti/0099FF" width="32" height="32" alt="Ubiquiti" /> Router/Firewall | Ubiquiti | USG (UniFi Security Gateway) | Gateway | Centralized network management | Routing & Security |
| <img src="https://cdn.simpleicons.org/tplink/000000" width="32" height="32" alt="TP-Link" /> TP-Link Switch | TP-Link | To be determined | Managed Switch | - | Auxiliary Network |
| <img src="https://cdn.simpleicons.org/dlink/0000FF" width="32" height="32" alt="D-Link" /> D-Link PoE | D-Link | To be determined | PoE Injector | - | Device Power |
| <img src="https://cdn.simpleicons.org/tailscale/09F7FF" width="32" height="32" alt="Tailscale" /> VPN | Tailscale | Tailscale VPN | VPN Overlay | Mesh Network | Secure Remote Access |

### 📱 Portable Devices & Consoles

| Device | Brand | Model | Display | Usage | OS |
|--------|-------|-------|---------|-------|---|
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> iPad Air | Apple | iPad Air 4 Cellular | 10.9" | Homelab Interface | iPadOS |
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> iPad Air | Apple | iPad Air 7 | 11" | Mobile Dashboard | iPadOS |
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> iPad | Apple | iPad 1 | 9.7" | Wallpanel Legacy | iPadOS |
| <img src="https://cdn.simpleicons.org/samsung/1428A0" width="32" height="32" alt="Samsung" /> Samsung Tablet | Samsung | Galaxy Tab A 10 2018 | 10.1" | Home Automation Display | Android |
| <img src="https://cdn.simpleicons.org/nintendo/E60012" width="32" height="32" alt="Nintendo" /> Nintendo Console | Nintendo | Switch V1 | 6.2" (Handheld) | Entertainment | Nintendo Switch OS |
| <img src="https://cdn.simpleicons.org/nintendo/E60012" width="32" height="32" alt="Nintendo" /> Nintendo Console | Nintendo | Switch OLED | 7.0" (OLED) | Entertainment | Nintendo Switch OS |
| <img src="https://cdn.simpleicons.org/playstation/003087" width="32" height="32" alt="PlayStation" /> Sony Console | Sony | PlayStation 4 | 4K | Multimedia & Gaming | PS4 OS |
| <img src="https://cdn.simpleicons.org/playstation/003087" width="32" height="32" alt="PlayStation" /> Sony Console | Sony | PlayStation 5 | 4K | Gaming Performance | PS5 OS |

### ☁️ Remote Infrastructure

| Service | Provider | Type | Configuration | Usage |
|---------|----------|------|---|---|
| <img src="https://cdn.simpleicons.org/ionos/003D7A" width="32" height="32" alt="IONOS" /> Virtual Machine | IONOS | VPS | Linux VM | Cloud Services & Testing |
| <img src="https://cdn.simpleicons.org/oracle/F80000" width="32" height="32" alt="Oracle" /> Virtual Machine | Oracle Cloud | VM | Linux ARM | Free Distributed Infrastructure |

### 🔧 Technical Specifications

#### Network
- **Protocol** : Gigabit Ethernet + PoE
- **VPN** : Tailscale for secure remote access
- **DNS/Security** : Pi-hole on Raspberry Pi 3

#### Storage
- **Backup** : RAID 5 on Synology NAS
- **Object Storage** : MinIO for distributed storage
- **Synchronization** : WebDAV via TrueNAS

#### Monitoring
- **Stack** : Raspberry Pi 3 (Prometheus + Grafana + VictoriaMetrics)
- **Agent** : Netdata on all nodes

#### Virtualization
- **Proxmox** : Instances on main infrastructure
- **VMware ESXi** : Testing & development
- **Docker** : Deployment on Raspberry Pi 5

---

## 📝 Notes

- **TP-Link & D-Link** : To be completed with exact models
- **Capacities & Specs** : To be refined according to current needs
- **Remote Infrastructure** : Scalable and modular

---

**Last updated** : October 2026 | **Status** : Work in Progress ✏️
