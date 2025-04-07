# 💻 Compte-Rendus de Travaux Pratiques Réseau – Ynov B2 Informatique

Bienvenue sur ce dépôt GitHub regroupant plusieurs comptes-rendus de travaux pratiques (TP) réalisés dans le cadre de la formation B2 Informatique à Ynov Campus.  
Ces TP ont été réalisés en binôme par **Arthur Chessé** & **Damien Mougenot** et mettent en pratique la configuration réseau sur des équipements Cisco.

## 📂 Sommaire

- [🧠 TP 1 – Prise en main d’un switch Cisco Catalyst 2960-C](#-tp-1--prise-en-main-dun-switch-cisco-catalyst-2960-c)
- [🔁 TD – Spanning Tree Protocol & Câblage](#-td--spanning-tree-protocol--câblage)
- [🌐 TP VLAN – Segmentation réseau & DHCP](#-tp-vlan--segmentation-réseau--dhcp)

---

## 🧠 TP 1 – Prise en main d’un switch Cisco Catalyst 2960-C

**Objectif :**  
Apprendre à réinitialiser, configurer et sécuriser un switch Cisco.

**Contenu :**

- Connexion au switch via port console (MobaXterm)
- Réinitialisation usine du switch
- Mise à jour du firmware via un serveur TFTP
- Configuration réseau de base
- Sécurisation (mot de passe, utilisateur, activation SSH)

📄 Voir le rapport : [`Compte Rendu TP Partie 1`](./Compte%20Rendu%20TP%20Partie%201%20Groupe%203%20(2).pdf)

---

## 🔁 TD – Spanning Tree Protocol & Câblage

**Objectif :**  
Mettre en place une topologie multi-switchs et configurer le STP (Spanning Tree Protocol) pour éviter les boucles réseau.

**Contenu :**

- Câblage d’une salle avec plusieurs switches
- Élection d’un Root Bridge et configuration de ses priorités
- Analyse des coûts de lien (Ethernet, Gigabit, fibre)
- Comportement du STP lors de la cicatrisation réseau
- Configuration des ports sécurisés (PortFast, BPDU Guard)

📄 Voir le rapport : [`TD Switch Cisco et STP`](./TD%20Switch%20Cisco%20et%20STP.pdf)

---

## 🌐 TP VLAN – Segmentation réseau & DHCP

**Objectif :**  
Créer plusieurs VLANs sur un switch, configurer le DHCP et effectuer des tests de connectivité.

**Contenu :**

- Configuration d’un port miroir (Wireshark)
- Analyse des échanges DHCP
- Création de VLANs (COMPTA, STAFF, GUEST, etc.)
- Mise en place de trunks entre switches
- Configuration d’un serveur DHCP par VLAN
- Stratégies de répartition de la charge réseau

📄 Voir le rapport : [`TP VLAN`](./TP%20VLAN.pdf)

---

## 🛠️ Technologies utilisées

- Cisco Packet Tracer / Switch Cisco Catalyst 2960
- MobaXterm
- Wireshark
- TFTPD64 (serveur TFTP)
- Protocole STP, VLAN, DHCP, SSH

---

## 📬 Contact

Pour toute question, vous pouvez me contacter via mon portfolio ou GitHub.  
Merci pour votre visite !

