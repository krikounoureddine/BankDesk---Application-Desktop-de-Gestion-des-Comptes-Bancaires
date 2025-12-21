<!-- README.md - BankDesk -->

<p align="center">
  <h1 align="center">🏦 BankDesk</h1>
  <p align="center"><em>Application Desktop de Gestion des Comptes Bancaires — Java Desktop ↔ Java EE (SOAP) via Middleware</em></p>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/License-Educational-lightgrey?style=for-the-badge" />
  <img alt="Status" src="https://img.shields.io/badge/Status-Prototype-blue?style=for-the-badge" />
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Desktop%20%7C%20Server-green?style=for-the-badge" />
</p>

---

> **BankDesk** est une application **desktop Java** connectée à un **backend Java EE** via des **Web Services**.  
Elle permet la gestion complète des comptes bancaires, des opérations financières et des utilisateurs, au sein d’une **architecture distribuée orientée services (SOA)**.

---

## 🚀 Présentation du projet

**BankDesk** a été conçu pour illustrer la mise en œuvre d’une **application client–serveur robuste**, reposant sur un **middleware** assurant la communication entre :

- une **interface desktop Java** (JavaFX / Swing)
- un **backend Java EE** centralisé exposant des services métiers

L’objectif principal est de garantir :
- la **cohérence des données**
- la **sécurité des opérations**
- la **modularité et la scalabilité** du système bancaire

---

## 🎨 **Maquettes d'Interface**

### **Vue d'Ensemble du Dashboard**
![Dashboard complet BankDesk](screenshots/dashboard-overview.png)
*Interface principale avec sidebar, statistiques financières et monitoring système*

### **Dashboard Administrateur Détail**
![Dashboard détaillé](screenshots/dashboard2.png)
*Vue administrateur avec tableau d'activité, alertes et statut des services*

### **Éléments d'Interface Détachés**

<div align="center">

| Barre de Navigation | Statistiques Centrales | Tableau des Transactions |
| :-----------------: | :--------------------: | :----------------------: |
| ![Navigation](https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/sidebar-navigation.png) | ![Statistiques](screenshots/financial-stats.png) | ![Transactions](screenshots/recent-activity.png) |
| *Menu principal avec profil utilisateur* | *KPIs financiers et graphiques* | *Historique des opérations bancaires* |

<br>

| Panneau d'Actions | Monitoring Backend |
| :---------------: | :----------------: |
| ![Actions rapides](screenshots/quick-actions.png) | ![Services backend](screenshots/backend-status.png) |
| *Actions fréquentes et alertes système* | *État des services Java EE et SOAP* |

</div>

---

## 🎨 **Démonstration de l'Interface**

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Vue d'Ensemble</strong><br><img src="screenshots/dashboard-overview.png" width="300" height="200" alt="Dashboard BankDesk" style="object-fit: cover;"></td>
      <td align="center"><strong>Dashboard Administrateur</strong><br><img src="screenshots/dashboard2.png" width="300" height="200" alt="Dashboard détaillé" style="object-fit: cover;"></td>
    </tr>
    <tr>
      <td align="center"><strong>Barre de Navigation</strong><br><img src="screenshots/sidebar-navigation.png" width="300" height="150" alt="Navigation principale" style="object-fit: contain; background: #f5f5f5; padding: 5px;"></td>
      <td align="center"><strong>Statistiques Centrales</strong><br><img src="screenshots/financial-stats.png" width="300" height="150" alt="Statistiques financières" style="object-fit: contain; background: #f5f5f5; padding: 5px;"></td>
    </tr>
    <tr>
      <td align="center"><strong>Tableau des Transactions</strong><br><img src="screenshots/recent-activity.png" width="300" height="150" alt="Activité récente" style="object-fit: contain; background: #f5f5f5; padding: 5px;"></td>
      <td align="center"><strong>Panneau d'Actions</strong><br><img src="screenshots/quick-actions.png" width="300" height="150" alt="Actions rapides" style="object-fit: contain; background: #f5f5f5; padding: 5px;"></td>
    </tr>
  </table>
</div>

---


---
## 🎨 **Démonstration de l'Interface**  (2x3)

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Vue d'Ensemble</strong><br><img src="screenshots/dashboard-overview.png" width="280" height="180" alt="Dashboard" style="object-fit: cover; border-radius: 5px;"></td>
      <td align="center"><strong>Dashboard Admin</strong><br><img src="screenshots/dashboard2.png" width="280" height="180" alt="Dashboard Admin" style="object-fit: cover; border-radius: 5px;"></td>
      <td align="center"><strong>Navigation</strong><br><img src="screenshots/sidebar-navigation.png" width="280" height="180" alt="Navigation" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
    </tr>
    <tr>
      <td align="center"><strong>Statistiques</strong><br><img src="screenshots/financial-stats.png" width="280" height="180" alt="Statistiques" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
      <td align="center"><strong>Transactions</strong><br><img src="screenshots/recent-activity.png" width="280" height="180" alt="Transactions" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
      <td align="center"><strong>Monitoring</strong><br><img src="screenshots/backend-status.png" width="280" height="180" alt="Monitoring" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
    </tr>
  </table>
</div>

---
---
## 🎨 **Aperçu de l'Interface** (3x2) 

<div align="center">
  <table style="border-spacing: 10px;">
    <tr>
      <td align="center" style="padding: 5px;">
        <div style="font-size: 0.9em; margin-bottom: 5px; font-weight: bold;">Dashboard</div>
        <img src="screenshots/dashboard-overview.png" width="250" height="140" alt="Dashboard" style="object-fit: cover; border: 1px solid #ddd;">
      </td>
      <td align="center" style="padding: 5px;">
        <div style="font-size: 0.9em; margin-bottom: 5px; font-weight: bold;">Navigation</div>
        <img src="screenshots/sidebar-navigation.png" width="250" height="140" alt="Navigation" style="object-fit: contain; background: #f5f5f5;">
      </td>
      <td align="center" style="padding: 5px;">
        <div style="font-size: 0.9em; margin-bottom: 5px; font-weight: bold;">Statistiques</div>
        <img src="screenshots/financial-stats.png" width="250" height="140" alt="Statistiques" style="object-fit: contain; background: #f5f5f5;">
      </td>
    </tr>
    <tr>
      <td align="center" style="padding: 5px;">
        <div style="font-size: 0.9em; margin-bottom: 5px; font-weight: bold;">Transactions</div>
        <img src="screenshots/recent-activity.png" width="250" height="140" alt="Transactions" style="object-fit: contain; background: #f5f5f5;">
      </td>
      <td align="center" style="padding: 5px;">
        <div style="font-size: 0.9em; margin-bottom: 5px; font-weight: bold;">Actions</div>
        <img src="screenshots/quick-actions.png" width="250" height="140" alt="Actions" style="object-fit: contain; background: #f5f5f5;">
      </td>
      <td align="center" style="padding: 5px;">
        <div style="font-size: 0.9em; margin-bottom: 5px; font-weight: bold;">Backend</div>
        <img src="screenshots/backend-status.png" width="250" height="140" alt="Backend" style="object-fit: contain; background: #f5f5f5;">
      </td>
    </tr>
  </table>
</div>

---
---

## ✨ Fonctionnalités principales

### 👤 Gestion des utilisateurs
- Création de comptes utilisateurs
- Authentification sécurisée
- Gestion des rôles et accès

### 💳 Gestion des comptes bancaires
- Consultation des comptes
- Création et mise à jour des comptes
- Visualisation des soldes et historiques

### 💸 Opérations financières
- Dépôts
- Retraits
- Virements entre comptes
- Validation côté serveur via services métiers

### 🔗 Communication client–serveur
- Appels via **Web Services (SOAP / REST)**
- Middleware assurant l’interopérabilité
- Backend orienté services (**SOA**)

---

## 🧠 Architecture & concepts techniques

- Architecture **distribuée**
- Séparation **Frontend / Backend**
- Middleware pour la communication
- Backend **Java EE** orienté services
- Design **modulaire et scalable**

---

## 🛠️ Technologies & outils

- **Java SE**
- **Application Desktop Java (JavaFX / Swing)**
- **Java EE**
  - EJB
  - Servlets
  - JSP
- **Web Services**
  - SOAP
  - REST
- **Middleware**
- **Architecture SOA**
- **Sécurité & authentification**
- **Communication client–serveur**

---

## 📦 Installation

### Prérequis
- Java JDK **8 ou supérieur**
- Serveur d’applications Java EE (GlassFish / WildFly / Tomcat selon configuration)
- IDE Java (**Eclipse recommandé**)

### Étapes
```bash
# Cloner le dépôt
git clone https://github.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires.git

1. Importer le projet dans Eclipse  
2. Configurer le serveur Java EE  
3. Déployer le backend (Web Services)  
4. Lancer l’application desktop  
```

---

## ▶️ Utilisation

1. Lancer le backend Java EE  
2. Démarrer l’application desktop **BankDesk**  
3. S’authentifier avec un compte utilisateur  
4. Accéder aux comptes bancaires  
5. Effectuer des opérations financières en temps réel  

> Toutes les opérations sont validées côté serveur afin de garantir la **cohérence** et la **sécurité** des données.

---

## 🤝 Contribution

Les contributions sont les bienvenues :

1. Forker le projet  
2. Créer une branche (`feature/amelioration`)  
3. Committer vos changements  
4. Ouvrir une Pull Request  

---

## 📜 Licence

Ce projet est sous licence **MIT**.  
Vous êtes libre de l’utiliser, le modifier et le distribuer.

---

## 📫 Contact

👤 **Noureddine Krikou**  
💼 Développeur Java / Full Stack  
🌐 GitHub : https://github.com/krikounoureddine  

---

## ⭐ Pourquoi BankDesk ?

✔ Mise en œuvre concrète de **Java EE et Web Services**  
✔ Maîtrise des **architectures distribuées et middleware**  
✔ Gestion sécurisée des **opérations financières**  
✔ Projet orienté **backend, services et systèmes d’information**

> ⭐ *N’hésitez pas à laisser une étoile si le projet vous plaît !*
