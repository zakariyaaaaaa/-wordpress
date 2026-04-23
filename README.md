# 🌐 WordPress Local Installation Project

## 📌 Description

Ce projet consiste à installer et configurer un site WordPress en local en utilisant XAMPP.
Il permet de comprendre le fonctionnement d’un CMS ainsi que la gestion d’un serveur local et d’une base de données.

---

## 🎯 Objectifs

* Installer un serveur local avec XAMPP
* Créer une base de données avec phpMyAdmin
* Installer WordPress en local
* Accéder au tableau de bord (wp-admin)

---

## 🛠 Technologies utilisées

* PHP
* MySQL
* Apache
* WordPress
* XAMPP

---

## 📁 Structure du projet

```
htdocs/
 └── mon_site/
     ├── wp-admin/
     ├── wp-content/
     └── wp-includes/
```

---

## ⚙️ Installation

### 1. Installer XAMPP

Télécharger et installer XAMPP puis lancer Apache et MySQL.

### 2. Créer la base de données

Accéder à http://localhost/phpmyadmin
Créer une base nommée `wordpress_test`

### 3. Installer WordPress

* Télécharger WordPress
* Copier les fichiers dans `htdocs/mon_site`

### 4. Lancer le projet

Ouvrir dans le navigateur :
http://localhost/mon_site

---

## 🔐 Accès admin

http://localhost/mon_site/wp-admin

---

## 💡 Notes

* Le projet fonctionne uniquement en local
* L'utilisateur par défaut MySQL est `root` sans mot de passe
* Ne pas oublier de lancer Apache et MySQL

---

## 👨‍💻 Auteur

Ton Nom Ici

---

## 📚 Projet réalisé dans le cadre de formation / PFE
