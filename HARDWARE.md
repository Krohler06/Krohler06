# 🏠 Inventaire Matériel - Homelab

[🇫🇷 Français](#français) | [🇬🇧 English](#english)

---

## 📋 Table des matières

1. [Infrastructure de Calcul](#infrastructure-de-calcul)
2. [Stockage & NAS](#stockage--nas)
3. [Réseau & Connectivité](#réseau--connectivité)
4. [Appareils Portables & Consoles](#appareils-portables--consoles)
5. [Infrastructure Distante](#infrastructure-distante)
6. [Spécifications Techniques](#spécifications-techniques)

---

## Français

### 🖥️ Infrastructure de Calcul

| Appareil | Marque | Modèle | CPU | RAM | Stockage | GPU | OS | Utilisation |
|----------|--------|--------|-----|-----|----------|-----|----|----|
| <img src="https://cdn.simpleicons.org/intel/0071C5" width="32" height="32" alt="Intel" /> PC Gaming | Intel | i7-1800X | i7-1800X | 2x 8 Go DDR4 | 480 Go NVMe | NVIDIA GTX 1660 | Windows 10 | Gaming & Dev |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Raspberry Pi 5 | Raspberry Pi | RPi 5 | ARM Cortex-A72 | 8 Go RAM | 256 Go NVMe + 480 Go NVMe | Intel Integré | Linux | Docker Host & Primary Homelab |
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> Mac Mini | Apple | A1357 | Intel Core 2 Duo | 6 Go RAM | 250 Go SSD | N/A | macOS | APK Builder |
| <img src="https://cdn.simpleicons.org/cubie/000000" width="32" height="32" alt="CubieBoard" /> CubieBoard | Cubieboard | CB4 | ARM A20 | 4 Go RAM | 16 Go eMMC | N/A | Linux | Développement & Tests |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Raspberry Pi 3 | Raspberry Pi | RPi 3B+ | ARM Cortex-A53 | 1 Go RAM | 32 Go microSD | N/A | Linux | Monitoring Stack |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Raspberry Pi 5 Distant | Raspberry Pi | RPi 5 | ARM Cortex-A72 | 8 Go RAM | microSD 128 GO | N/A | Linux | Infrastructure Distribuée |
| <img src="https://cdn.simpleicons.org/dell/007DB8" width="32" height="32" alt="Dell" /> PC NUC Dell | Dell | D08U | Intel Core i5 | 8 Go RAM | 256 Go SSD | N/A | Linux | Calcul Distribué |

### 💾 Stockage & NAS

| Appareil | Marque | Modèle | RAID | Capacité | Utilisation | Spécifications |
|----------|--------|--------|------|----------|------------|---|
| <img src="https://cdn.simpleicons.org/synology/000000" width="32" height="32" alt="Synology" /> NAS Mini-ITX | Synology | NAS-04 | RAID 5 | 4x 1To (3.6 To utile) | Stockage Principal & Backup | Mini-ITX Form Factor |
| <img src="https://cdn.simpleicons.org/truenas/000000" width="32" height="32" alt="TrueNAS" /> TrueNAS | TrueNAS | Système | RAID | À configurer | WebDAV & Stockage Distribué | Self-Hosted |

### 🌐 Réseau & Connectivité

| Composant | Marque | Modèle | Type | Spécifications | Utilisation |
|-----------|--------|--------|------|---|---|
| <img src="https://cdn.simpleicons.org/ubiquiti/0099FF" width="32" height="32" alt="Ubiquiti" /> Switch Réseau | Ubiquiti | UniFi Switch 8 60W | PoE Switch | 8 ports + PoE 60W | Alimentation & Données |
| <img src="https://cdn.simpleicons.org/ubiquiti/0099FF" width="32" height="32" alt="Ubiquiti" /> Routeur/Firewall | Ubiquiti | USG (UniFi Security Gateway) | Gateway | Gestion réseau centralisée | Routage & Sécurité |
| <img src="https://cdn.simpleicons.org/tplink/000000" width="32" height="32" alt="TP-Link" /> Switch TP-Link | TP-Link | À déterminer | Switch Géré | - | Réseau Auxiliaire |
| <img src="https://cdn.simpleicons.org/dlink/0000FF" width="32" height="32" alt="D-Link" /> PoE D-Link | D-Link | À déterminer | Injecteur PoE | - | Alimentation Appareils |
| <img src="https://cdn.simpleicons.org/tailscale/09F7FF" width="32" height="32" alt="Tailscale" /> VPN | Tailscale | Tailscale VPN | VPN Overlay | Mesh Network | Accès Distant Sécurisé |

### 📱 Appareils Portables & Consoles

| Appareil | Marque | Modèle | Écran | Utilisation | OS |
|----------|--------|--------|-------|---|---|
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> iPad Air | Apple | iPad Air 4 Cellular | 10.9" | Interface Homelab | iPadOS |
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> iPad Air | Apple | iPad Air 7 | 11" | Dashboard Mobile | iPadOS |
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> iPad | Apple | iPad 1 | 9.7" | Wallpanel Legacy | iPadOS |
| <img src="https://cdn.simpleicons.org/samsung/1428A0" width="32" height="32" alt="Samsung" /> Tablette Samsung | Samsung | Galaxy Tab A 10 2018 | 10.1" | Affichage Domotique | Android |
| <img src="https://cdn.simpleicons.org/nintendo/E60012" width="32" height="32" alt="Nintendo" /> Console Nintendo | Nintendo | Switch V1 | 6.2" (Portable) | Loisir | Nintendo Switch OS |
| <img src="https://cdn.simpleicons.org/nintendo/E60012" width="32" height="32" alt="Nintendo" /> Console Nintendo | Nintendo | Switch OLED | 7.0" (OLED) | Loisir | Nintendo Switch OS |
| <img src="https://cdn.simpleicons.org/playstation/003087" width="32" height="32" alt="PlayStation" /> Console Sony | Sony | PlayStation 4 | 4K | Multimédia & Gaming | PS4 OS |
| <img src="https://cdn.simpleicons.org/playstation/003087" width="32" height="32" alt="PlayStation" /> Console Sony | Sony | PlayStation 5 | 4K | Gaming Performance | PS5 OS |

### ☁️ Infrastructure Distante

| Service | Fournisseur | Type | Configuration | Utilisation |
|---------|------------|------|---|---|
| <img src="https://cdn.simpleicons.org/ionos/003D7A" width="32" height="32" alt="IONOS" /> Machine Virtuelle | IONOS | VPS | VM Linux | Services Cloud & Tests |
| <img src="https://cdn.simpleicons.org/oracle/F80000" width="32" height="32" alt="Oracle" /> Machine Virtuelle | Oracle Cloud | VM | Linux ARM | Infrastructure Distribuée Gratuite |

### 🔧 Spécifications Techniques

#### Réseau
- **Protocole** : Ethernet Gigabit + PoE
- **VPN** : Tailscale pour accès distant sécurisé
- **DNS/Sécurité** : Pi-hole sur Raspberry Pi 3

#### Stockage
- **Sauvegarde** : RAID 5 sur NAS Synology
- **Objet** : MinIO pour stockage distribué
- **Synchronisation** : WebDAV via TrueNAS

#### Monitoring
- **Stack** : Raspberry Pi 3 (Prometheus + Grafana + VictoriaMetrics)
- **Agent** : Netdata sur tous les nœuds

#### Virtualisation
- **Proxmox** : Instances sur infrastructure principale
- **VMware ESXi** : Tests & développement
- **Docker** : Déploiement sur Raspberry Pi 5

---

## English

### 🖥️ Computing Infrastructure

| Device | Brand | Model | CPU | RAM | Storage | GPU | OS | Usage |
|--------|-------|-------|-----|-----|---------|-----|----|----|
| <img src="https://cdn.simpleicons.org/intel/0071C5" width="32" height="32" alt="Intel" /> Main PC | Intel | i7-1800X | i7-1800X | 2x 8 Go DDR4 | - | NVIDIA GTX 1660 | Windows 10 | Gaming & Development |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Raspberry Pi 5 | Raspberry Pi | RPi 5 | ARM Cortex-A72 | 8 GB RAM | 256 GB NVMe + 480 GB NVMe | - | Linux | Docker Host & Primary Homelab |
| <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> Mac Mini | Apple | A1357 | Intel Core 2 Duo | 6 GB RAM | 250 GB SSD | - | macOS | APK Builder |
| <img src="https://cdn.simpleicons.org/cubie/000000" width="32" height="32" alt="CubieBoard" /> CubieBoard | Cubieboard | CB4 | ARM A20 | 4 GB RAM | 16 GB eMMC | - | Linux | Development & Testing |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Raspberry Pi 3 | Raspberry Pi | RPi 3B+ | ARM Cortex-A53 | 1 GB RAM | 32 GB microSD | - | Linux | Monitoring Stack |
| <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> Remote Raspberry Pi 5 | Raspberry Pi | RPi 5 | ARM Cortex-A72 | 8 GB RAM | microSD | - | Linux | Distributed Infrastructure |
| <img src="https://cdn.simpleicons.org/dell/007DB8" width="32" height="32" alt="Dell" /> Dell NUC PC | Dell | D08U | Intel Core i5 | 8 GB RAM | 256 GB SSD | - | Linux | Distributed Computing |

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

- **TP-Link & D-Link** : À compléter avec modèles exacts
- **Capacités & Specs** : À affiner selon besoins actuels
- **Infrastructure distante** : Évolutive et modulable

---

**Last updated** : October 2026 | **Status** : Work in Progress ✏️
