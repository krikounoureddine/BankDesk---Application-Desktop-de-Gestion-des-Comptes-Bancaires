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

## 🔎 Aperçu

**BankDesk** est une application desktop (Java) dédiée à la gestion bancaire (comptes, dépôts, retraits, virements, historique), connectée à un backend **Java EE** exposant des **Web Services SOAP**. Un **middleware** orchestre la communication et assure la cohérence, la validation et la modularité entre le client desktop et les services bancaires.

**Démo / Page du projet :**  
https://krikounoureddine.github.io/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/

---

## 🏛️ Architecture (schéma)

```mermaid
flowchart LR
  A[Client Desktop - JavaFX/Swing] -->|SOAP/XML| B[Middleware (Adapter)]
  B -->|SOAP/XML| C[Java EE - Web Services (EJB)]
  C --> D[(Base de Données)]
  C --> E[Logique métier (EJB)]
  subgraph infra
    D
    E
  end
🧩 Fonctionnalités principales

🔐 Authentification sécurisée des utilisateurs

👤 Gestion des comptes utilisateurs (création, suppression, rôles)

💳 Consultation des comptes, soldes et détails

➕ Dépôts / ➖ Retraits / 🔄 Virements inter-comptes

🧾 Historique et export des transactions

🌐 Communication via Web Services SOAP (WSDL / XML)

🧱 Middleware pour orchestration, validation et transformation des messages

🛠️ Technologies & composants

Client (Desktop) : Java, JavaFX ou Swing, MVC

Middleware / Adapter : Java (JAX-WS client / logique de mapping)

Backend : Java EE (EJB, JPA), Servlets/JSP (optionnel), Web Services SOAP (JAX-WS)

Persistance : JPA (Hibernate) + base relationnelle (MySQL / PostgreSQL)

Messages : XML / SOAP / WSDL

Outils : Maven/Gradle, GlassFish/WildFly/Payara, Git

📁 Structure proposée du dépôt

/BankDesk
├─ /backend
│  ├─ pom.xml
│  ├─ src/main/java/...
│  ├─ src/main/resources/
│  └─ web/ (WSDL, xsd)
├─ /middleware
│  ├─ pom.xml
│  └─ src/main/java/...
├─ /desktop
│  ├─ pom.xml
│  └─ src/main/java/...
├─ docs/
│  └─ screenshots/
├─ sql/
│  └─ schema.sql
└─ README.md

🔁 Exemple de message SOAP (Requête dépôt)

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
                  xmlns:bank="http://services.bankdesk/">
   <soapenv:Header/>
   <soapenv:Body>
      <bank:depositRequest>
         <accountId>12345</accountId>
         <amount>500.00</amount>
         <currency>EUR</currency>
      </bank:depositRequest>
   </soapenv:Body>
</soapenv:Envelope>

Exemple de réponse SOAP

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
                  xmlns:bank="http://services.bankdesk/">
   <soapenv:Body>
      <bank:depositResponse>
         <status>SUCCESS</status>
         <transactionId>TX-20231101-0001</transactionId>
         <newBalance>1500.00</newBalance>
      </bank:depositResponse>
   </soapenv:Body>
</soapenv:Envelope>



⚙️ Installation & Déploiement (guide pas-à-pas)

Prérequis

JDK 11+

Maven 3.6+ (ou Gradle)

Serveur Java EE : WildFly / GlassFish / Payara

MySQL / PostgreSQL

Git

🖼️ Ajouter des captures et GIFs (recommandé)

Pour rendre la page GitHub plus attractive, ajoute dans docs/screenshots/ :

login.png — écran de connexion

dashboard.png — aperçu tableau de bord

transfer.gif — animation d’un virement
### Aperçu UI

![Login](docs/screenshots/login.png)
![Dashboard](docs/screenshots/dashboard.png)

✅ Bonnes pratiques & suggestions d'amélioration

Ajouter HTTPS & certificats pour sécuriser les services SOAP

Implémenter authentification JWT si tu exposes aussi REST

Ajouter tests unitaires (JUnit) et tests d’intégration (Arquillian ou équivalent)

Ajouter CI (GitHub Actions) pour build & déploy automatique

🧾 Licence & attribution

Ce projet est fourni à des fins pédagogiques. Pour toute réutilisation commerciale ou redistribution, merci de me contacter.

📬 Contact

Noureddine KRIKOU — Développeur Fullstack
GitHub: https://github.com/krikounoureddine

Page projet: https://krikounoureddine.github.io/BankDesk---Application-Desktop-de-Gestion-des-Comptes-Bancaires/

