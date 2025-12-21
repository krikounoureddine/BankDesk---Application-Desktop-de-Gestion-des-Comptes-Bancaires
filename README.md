<!-- README.md - BankDesk -->
<body style="background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%); margin: 0; padding: 20px;">


<div style="max-width: 1200px; margin: 0 auto; background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 10px 30px rgba(0,0,0,0.1);">

<p style="font-size: 1.2rem; opacity: 0.9;">Application Desktop de Gestion des Comptes Bancaires — Java Desktop ↔ Java EE (SOAP) via Middleware</p>
</div>

<br>

<div align="center" style="
    background: linear-gradient(90deg, #0a192f 0%, #1a237e 100%);
    color: white;
    padding: 2rem;
    border-radius: 10px;
    position: relative;
    overflow: hidden;
">
    
<br>

<div style="position: absolute; top: 0; right: 0; padding: 1rem;">
    <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white">
    <img alt="Java EE" src="https://img.shields.io/badge/Java_EE-007396?style=for-the-badge&logo=java&logoColor=white">
    <img alt="MIT License" src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge">
    <img alt="Status" src="https://img.shields.io/badge/Status-Prototype-blue?style=for-the-badge" />
    <img alt="Platform" src="https://img.shields.io/badge/Platform-Desktop%20%7C%20Server-green?style=for-the-badge" />
</div>

<br>

<h1 style="margin-top: 2rem;">🏦 BankDesk</h1>
<p style="font-size: 1.2rem; opacity: 0.9;"> BankDesk est une application desktop Java connectée à un backend Java EE via des Web Services. Elle permet la gestion complète des comptes bancaires, des opérations financières et des utilisateurs, au sein d’une architecture distribuée orientée services (SOA).
</p>

</div>

</body>

---

<div style="
    background-color: #f8f9fa;
    border-left: 4px solid #1a237e;
    padding: 1.5rem;
    margin: 2rem 0;
    border-radius: 0 8px 8px 0;">

</div>

## 📖 Table des Matières

### 📚 Navigation Principale
- [📋 Présentation du Projet](#-présentation-du-projet)
- [🎨 Démonstration de l'Interface](#-Démonstration-de-l'Interface)
- [✨ Fonctionnalités](#-Fonctionnalités-principales)
- [🏗️ Architecture](#️-Architecture-&-concepts-techniques)

### 🔧 Développement
- [🛠️ Technologies](#️-technologies)
- [📦 Installation](#-installation)
- [▶️ Utilisation](#️-utilisation)
- [🤝 Contribution](#-contribution)



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
## 🎨 Démonstration de l'Interface

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Vue d'Ensemble</strong><br><img src="https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/dashboard-overview.png" width="280" height="180" alt="Dashboard" style="object-fit: cover; border-radius: 5px;"></td>
      <td align="center"><strong>Dashboard Admin</strong><br><img src="https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/dashboard2.png" width="280" height="180" alt="Dashboard Admin" style="object-fit: cover; border-radius: 5px;"></td>
      <td align="center"><strong>Barre de Navigation<</strong><br><img src="https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/sidebar-navigation.png" width="280" height="180" alt="Barre de Navigation<" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
        <td align="center"><strong>Statistiques</strong><br><img src="https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/financial-stats.png" width="280" height="180" alt="Statistiques" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
    </tr>
    <tr>
      <td align="center"><strong>Transactions</strong><br><img src="https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/recent-activity.png" width="280" height="180" alt="Transactions" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
      <td align="center"><strong>Panneau d'Actions</strong><br><img src="https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/quick-actions.png" width="280" height="180" alt="Panneau d'Actions" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
      <td align="center"><strong>Monitoring</strong><br><img src="https://raw.githubusercontent.com/krikounoureddine/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/main/screenshots/backend-status.png" width="280" height="180" alt="Monitoring" style="object-fit: contain; background: #f8f9fa; border-radius: 5px;"></td>
   </tr>
  </table>
</div>
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

