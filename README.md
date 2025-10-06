# 💊 Pharmacy Management System

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Swing](https://img.shields.io/badge/Java_Swing-007396?style=for-the-badge&logo=java&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📌 Description

Le **Pharmacy Management System** est une application de bureau développée en **Java (Swing)** avec une base de données **MySQL**.  
Elle permet aux pharmacies de gérer efficacement leurs stocks de médicaments, les factures de vente et les utilisateurs grâce à un système d’authentification basé sur les rôles (pharmacien, administrateur).

Objectifs principaux :
- Réduire les **ruptures de stock**  
- Suivre les **dates de péremption**  
- Automatiser la **facturation et la gestion des utilisateurs**  
- Améliorer la **productivité et l’organisation** de la pharmacie  

---

## 🚀 Fonctionnalités

- 🔐 **Authentification et rôles**
  - Connexion sécurisée (Pharmacien / Administrateur)
  - Permissions adaptées selon le rôle

- 💊 **Gestion des médicaments**
  - Ajouter, modifier, supprimer des médicaments
  - Recherche et filtrage par stock, prix, date d’expiration
  - Alertes automatiques pour faibles stocks ou produits périmés

- 🧾 **Gestion des factures**
  - Génération et impression de factures
  - Consultation et recherche par date / montant
  - Historique des ventes

- 👥 **Gestion des utilisateurs (Admin)**
  - Création, modification et suppression de comptes
  - Attribution de rôles
  - Suivi des activités

---

## 🛠️ Technologies utilisées

- **Langage** : Java (OOP)  
- **Interface graphique** : Java Swing  
- **Base de données** : MySQL via JDBC  
- **IDE** : IntelliJ IDEA  
- **Serveur local** : WAMP / XAMPP  
- **Gestion de projet** : Maven  
- **Modélisation UML** : Cas d’utilisation, classes, séquences  

---

## 📂 Structure du projet

src/
 ├── dao/            # Accès aux données (MySQL via JDBC)
 ├── model/          # Classes métiers (Médicament, Facture, Utilisateur…)
 ├── service/        # Logique métier
 ├── ui/             # Interfaces Swing
 └── Main.java       # Point d’entrée


## ⚡ Installation et exécution

1️⃣ Cloner le projet
git clone https://github.com/username/Pharmacy-Manager.git
cd Pharmacy-Management-System

2️⃣ Configurer la base MySQL

Créer une base pharmacy_db

Importer /database/pharmacy_db.sql

3️⃣ Modifier la connexion JDBC

Dans DatabaseConnection.java :

String url = "jdbc:mysql://localhost:3306/pharmacy_db";
String user = "root";
String password = "your_password";

4️⃣ Lancer l’application

Ouvrir le projet avec IntelliJ IDEA

Exécuter Main.java
