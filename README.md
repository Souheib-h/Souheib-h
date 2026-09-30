# 👋 Souheib Houssein

**Infrastructure Security Engineer (Junior) | Blue Team | Network Security**

Chez Hedal Consulting (Djibouti) : IAM Keycloak + Stalwart sur Proxmox, migration mail vers Infomaniak kSuite, cloud souverain.  
En parallèle, je construis des labs d'infrastructure sécurisée : cluster K3s en haute disponibilité, bastion, et une stack NOC/SOC complète et automatisée.

---

## 💼 Hedal Consulting : Production

| Projet | Stack | Description |
|--------|-------|-------------|
| [keycloak-stalwart-stack](https://github.com/Souheib-h/keycloak-stalwart-stack) | Keycloak · Stalwart · PostgreSQL · Proxmox | IAM + mail server, 4 serveurs prod |
| [stalwart-monitoring-stack](https://github.com/Souheib-h/stalwart-monitoring-stack) | Prometheus · Grafana · Docker | Monitoring stack production-ready |

Aussi en production : migration Microsoft 365 vers Infomaniak kSuite (DNS, DKIM/SPF/DMARC) et offre de cloud souverain (Nextcloud, OnlyOffice, Jitsi, ERPNext, n8n).

---

## 🔬 Labs personnels

| Projet | Stack | Statut |
|--------|-------|--------|
| [K3s-lab](https://github.com/Souheib-h/K3s-lab) | K3s HA (3 servers + 3 agents) · PostgreSQL · HAProxy · Alpine/Ubuntu | 📦 Archivé (lab d'apprentissage, remplacé par le cluster kubeadm) |
| [K3s-lab-monitoring](https://github.com/Souheib-h/K3s-lab-monitoring) | Zabbix · Wazuh · Prometheus · Grafana · Loki · Alloy · OPNsense · Ansible | ✅ Opérationnel (13 VMs) |
| [Bastion-lab](https://github.com/Souheib-h/Bastion-lab) | SSH · ProxyJump · fail2ban · OPNsense · Wazuh | ✅ Terminé |
| [Packet-Analysis-Lab](https://github.com/Souheib-h/Packet-Analysis-Lab) | PnetLab · Wireshark · tcpdump | ⏸️ En pause (phases 1 à 3 terminées, phase 4/6 à reprendre) |
| Cluster K8s HA | kubeadm · Calico · k9s · Kubernetes 1.35 | ✅ Opérationnel (terrain de préparation CKA) |
| Proxmox-cluster-lab | Proxmox VE · PBS · PDM · ZFS | 🗓️ Planifié après le CKA |

**Points forts de K3s-lab-monitoring** :
- Déploiement automatisé des agents Zabbix, Wazuh et Loki/Alloy sur les 13 VMs via Ansible
- Alerting enrichi VirusTotal avec envoi d'emails
- Détection de vulnérabilités Wazuh opérationnelle (diagnostic d'un bug upstream documenté)
- Dashboard Prometheus publié sur le marketplace officiel : [Grafana.com ID 25537](https://grafana.com/grafana/dashboards/25537) (40+ téléchargements)

---

## 🎯 En cours

- **CKA** : examen début octobre 2026
- **Detection engineering** : règles Sigma, mapping MITRE ATT&CK, Falco et audit logs Kubernetes (après le CKA)
- **Certifications visées** : RHCSA, CCNA, CySA+ puis BTL1 (CCST Cybersecurity obtenu en 2025)

---

## 🛠️ Stack

`Keycloak` `Proxmox` `KVM/libvirt` `Kubernetes (K3s, kubeadm)` `Ansible` `Wazuh` `Zabbix` `Prometheus` `Grafana` `Loki` `OPNsense` `HAProxy` `PostgreSQL` `Docker` `Wireshark` `tcpdump` `fail2ban` `Containerlab` `PNetLab` `Arch Linux`

---

## 📊 TryHackMe

[![TryHackMe](https://tryhackme-badges.s3.amazonaws.com/SkyCruzer.png)](https://tryhackme.com/p/SkyCruzer)

> Top 4% · 109 rooms · 16 badges
