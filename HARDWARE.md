
<div align="center">

# 🧰 Inventaire Matériel — Homelab de Jérémy

[⬅️ Retour au README](./README.md)

</div>

---

## Légende des statuts

| Statut | Signification |
|---|---|
| 🟢 | Actif / en production |
| 🟡 | En test / en cours de déploiement |
| 🔴 | Hors service / à remplacer |

---

## 💻 Poste de travail

| Appareil | Modèle | CPU | RAM | Stockage | GPU | OS | Usage | Statut |
|---|---|---|---|---|---|---|---|---|
| PC principal | Custom build | i7 / Ryzen 1800X | 2×8 Go DDR4 | — | NVIDIA GTX 1660 | Windows 10 | Bureautique, gaming, administration homelab | 🟢 |
| NUC | Dell D08U | — | — | — | — | — | À définir | 🟡 |

---

## 🖥️ Serveurs & compute

| Appareil | Modèle | CPU | RAM | Stockage | OS | Rôle | Statut |
|---|---|---|---|---|---|---|---|
| Raspberry Pi 5 | RPi 5 | ARM Cortex-A76 | 8 Go | NVMe 256 Go + NVMe 480 Go | Raspberry Pi OS | Docker host principal | 🟢 |
| Raspberry Pi 5 (distant) | RPi 5 | ARM Cortex-A76 | — | — | Raspberry Pi OS | Hébergement distant | 🟢 |
| Raspberry Pi 3 | RPi 3 | ARM Cortex-A53 | 1 Go | microSD | Raspberry Pi OS | Monitoring (Grafana/Prometheus) | 🟢 |
| Mac Mini | A1357 | Intel Core 2 Duo | 6 Go | SSD 250 Go | macOS / Linux | Build APK + serveur de génération d'application | 🟢 |
| CubieBoard | CubieBoard | ARM Cortex-A8 | 4 Go | microSD | Debian | Homelab / expérimentations | 🟡 |
| NAS | NAS-04 Mini-ITX | — | — | RAID 5 · 4×1 To | TrueNAS | Stockage fichiers / WebDAV | 🟢 |

### ☁️ Machines virtuelles (cloud)

| Hébergeur | Rôle | Statut |
|---|---|---|
| IONOS | VM cloud | 🟢 |
| Oracle Cloud | VM cloud (free tier) | 🟢 |

---

## 🌐 Réseau

| Équipement | Marque | Modèle | Fonction | Statut |
|---|---|---|---|---|
| Access Point | Ubiquiti | UniFi US 8 60W | Switch PoE 8 ports, alimentation AP/caméras | 🟢 |
| Gateway / Routeur | Ubiquiti | USG (UniFi Security Gateway) | Routage / pare-feu | 🟢 |
| Switch | TP-Link | *à compléter* | Switch réseau secondaire | 🟢 |
| Switch POE | D-Link | *à compléter* | Alimentation caméras / équipements PoE | 🟢 |

---

## 🗄️ Stockage

| Système | Détail | Usage | Statut |
|---|---|---|---|
| TrueNAS (NAS-04 Mini-ITX) | RAID 5 · 4×1 To | Partage de fichiers / WebDAV | 🟢 |
| MinIO | Hébergé sur Mac Mini | Stockage objet S3-compatible | 🟡 |

---

## 📹 Vidéosurveillance

| Équipement | Modèle | Détail | Statut |
|---|---|---|---|
| NVR | HIKVision 7600 | Enregistreur réseau | 🟢 |
| DVR | HIKVision (ancien modèle) | 16 canaux | 🟡 |

---

## 🏡 Domotique & contrôle

| Système | Détail | Usage | Statut |
|---|---|---|---|
| Home Assistant | Hébergé sur Raspberry Pi | Domotique, automatisations | 🟢 |
| iPad 1 | Mode kiosque | Wallpanel Home Assistant | 🟢 |

---

## 📱 Appareils mobiles & tablettes

| Appareil | Modèle | Usage | Statut |
|---|---|---|---|
| iPad | iPad Air 4 (Cellular) | Usage personnel / mobilité | 🟢 |
| iPad | iPad Air 7 | Usage personnel / mobilité | 🟢 |
| iPad | iPad 1 | Wallpanel Home Assistant (voir domotique) | 🟢 |
| Tablette | Samsung Tab A 10 (2018) | Usage secondaire | 🟢 |

---

## 🎮 Gaming & divers

| Appareil | Modèle | Usage | Statut |
|---|---|---|---|
| Nintendo Switch | V1 | Gaming | 🟢 |
| Nintendo Switch | OLED | Gaming | 🟢 |
| Console | PS4 | Gaming | 🟢 |
| Console | PS5 | Gaming | 🟢 |

---

## 📦 Services clés déployés

| Service | Usage |
|---|---|
| Jellyfin / Plex | Médiathèque |
| Pi-hole | DNS / blocage pub |
| Tailscale | VPN mesh / accès distant |
| Portainer | Gestion des conteneurs Docker |

---

<div align="center">

*Dernière mise à jour : octobre 2026 — inventaire évolutif, complété au fil des ajouts du homelab.*

</div>
