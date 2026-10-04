# 🏠 Inventaire Matériel - Homelab

## 📋 Table des matières

1. [Infrastructure de Calcul](#infrastructure-de-calcul)
2. [Stockage & NAS](#stockage--nas)
3. [Réseau & Connectivité](#réseau--connectivité)
4. [Appareils Portables & Consoles](#appareils-portables--consoles)
5. [Infrastructure Distante](#infrastructure-distante)
6. [Spécifications Techniques](#spécifications-techniques)

---

### 🖥️ Infrastructure de Calcul

| Appareil | Marque | Modèle | CPU | RAM | Stockage | GPU | OS | Utilisation |
|:----------:|:--------:|--------|-----|-----|----------|-----|----|----|
|  PC Gaming | <img src="https://cdn.simpleicons.org/intel/0071C5" width="32" height="32" alt="Intel" /> | DIY | Ryzen 7 - 1800X | 2x 8 Go DDR4 | 480 Go NVMe | NVIDIA GTX 1660 | Windows 10 | Gaming & Dev |
|  Raspberry Pi 5 | <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> | RPi 5 | ARM Cortex-A72 | 8 Go RAM | 256 Go NVMe + 480 Go NVMe | Intel Integré | Linux | Docker Host & Primary Homelab |
|  Mac Mini | <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> | A1357 | Intel Core 2 Duo | 6 Go RAM | 250 Go SSD | N/A | macOS | APK Builder |
|  CubieBoard | <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/shadow.png" width="32" height="32" alt="CubieBoard" /> | CB4 | ARM A20 | 4 Go RAM | 16 Go eMMC | N/A | Linux | Développement & Tests |
|  Raspberry Pi 3 |<img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> | RPi 3B+ | ARM Cortex-A53 | 1 Go RAM | 32 Go microSD | N/A | Linux | Monitoring Stack |
|  Raspberry Pi 5 Distant | <img src="https://cdn.simpleicons.org/raspberrypi/A22015" width="32" height="32" alt="Raspberry Pi" /> | RPi 5 | ARM Cortex-A72 | 8 Go RAM | microSD 128 GO | N/A | Linux | Infrastructure Distribuée |
|  PC NUC Dell | <img src="https://cdn.simpleicons.org/dell/007DB8" width="32" height="32" alt="Dell" /> | D08U | Intel Core i5 | 8 Go RAM | 256 Go SSD | N/A | Linux | Bureautique |

### 💾 Stockage & NAS

| Appareil | Marque | Modèle | RAID | Capacité | Utilisation | Spécifications |
|:----------:|:--------:|--------|------|----------|------------|---|
| NAS Mini-ITX | <img src="https://cdn.simpleicons.org/synology/000000" width="32" height="32" alt="Synology" /> | NAS-04 | RAID 5 | 4x 1To (3.6 To utile) | Stockage Principal & Backup | Mini-ITX Form Factor |
| TrueNAS | <img src="https://cdn.simpleicons.org/truenas/000000" width="32" height="32" alt="TrueNAS" /> | Système | RAID | À configurer | WebDAV & Stockage Distribué | Self-Hosted |

### 🌐 Réseau & Connectivité

| Composant | Marque | Modèle | Type | Spécifications | Utilisation |
|:-----------:|:--------:|--------|------|---|---|
| Entrée de site | <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/orange.png" width="32" height="32" alt="Orange" /> | LiveBox V6 | Firewall | Gestion réseau centralisée | Routage & Sécurité |
| Switch Réseau | <img src="https://cdn.simpleicons.org/ubiquiti/0099FF" width="32" height="32" alt="Ubiquiti" /> | UniFi Switch 8 60W | PoE Switch | 8 ports + PoE 60W | Alimentation & Données |
| Routeur/Firewall | <img src="https://cdn.simpleicons.org/ubiquiti/0099FF" width="32" height="32" alt="Ubiquiti" /> | USG (UniFi Security Gateway) | Gateway | Gestion réseau centralisée | Routage & Sécurité |
| Switch TP-Link | <img src="https://cdn.simpleicons.org/tplink/000000" width="32" height="32" alt="TP-Link" /> | -- | Switch Géré | - | Réseau Auxiliaire |
| Switch D-Link | <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/d-link.png" width="32" height="32" alt="D-Link" /> | -- | Injecteur PoE | - | Alimentation Appareils |
| VPN | <img src="https://cdn.jsdelivr.net/gh/selfhst/icons/png/tailscale.png" width="32" height="32" alt="Tailscale" /> | Tailscale VPN | VPN Overlay | Mesh Network | Accès Distant Sécurisé |

### 📱 Appareils Portables & Consoles

| Appareil | Marque | Modèle | Écran | Utilisation | OS |
|:----------:|:--------:|--------|-------|---|---|
| iPad Air | <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> | iPad Air 4 Cellular | 10.9" | Interface Homelab | iPadOS |
| iPad Air | <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> | iPad Air 7 | 11" | Dashboard Mobile | iPadOS |
| iPad | <img src="https://cdn.simpleicons.org/apple/000000" width="32" height="32" alt="Apple" /> | iPad 1 | 9.7" | Wallpanel Legacy | iPadOS |
| Tablette Samsung | <img src="https://cdn.simpleicons.org/samsung/1428A0" width="32" height="32" alt="Samsung" /> | Galaxy Tab A 10 2018 | 10.1" | Affichage Domotique | Android |
| Console Nintendo | <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/nintendo-switch.png" width="32" height="32" alt="Nintendo" /> | Switch V1 | 6.2" (Portable) | Loisir | Nintendo Switch OS |
| Console Nintendo | <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/nintendo-switch.png" width="32" height="32" alt="Nintendo" /> | Switch OLED | 7.0" (OLED) | Loisir | Nintendo Switch OS |
| Console Sony | <img src="https://dashboardicons.com/api/icons/external/simpleicons/playstation4/brand.png" width="32" height="32" alt="PlayStation" /> | PlayStation 4 | 4K | Multimédia & Gaming | PS4 OS |
| Console Sony | <img src="https://dashboardicons.com/api/icons/external/simpleicons/playstation5/brand.png" width="32" height="32" alt="PlayStation" />  | PlayStation 5 | 4K | Gaming Performance | PS5 OS |
| RecalBox |<img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/recalbox.png" width="32" height="32" alt="Raspberry Pi" /> | RPi 3B+ | N/A | Retro Gaming | GNU/Linux |

### ☁️ Infrastructure Distante

| Service | Fournisseur | Type | Configuration | Utilisation |
|:---------:|:------------:|------|---|---|
| Machine Virtuelle | <img src="https://cdn.simpleicons.org/ionos/003D7A" width="32" height="32" alt="IONOS" />  | VPS | VM Linux | Services Cloud & Tests |
| Machine Virtuelle | <img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/oracle-cloud.png" width="32" height="32" alt="Oracle" /> | VM | Linux ARM | Infrastructure Distribuée Gratuite |

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
