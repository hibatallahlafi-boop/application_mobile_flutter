# application_mobile_flutter# Rapport sur l’Application Mobile « MediMate »

## 1. Introduction

MediMate est une application mobile développée avec le framework Flutter. Cette application a pour objectif d’aider les utilisateurs à gérer leurs activités médicales quotidiennes de manière simple et pratique.

L’application propose plusieurs fonctionnalités importantes comme la gestion des médicaments, des rendez-vous médicaux, des tâches personnelles et des dossiers médicaux.

---

# 2. Objectif de l’Application

L’objectif principal de MediMate est de faciliter l’organisation médicale des utilisateurs grâce à une interface mobile intuitive.

L’application permet :

* Ajouter et suivre les médicaments.
* Organiser les rendez-vous médicaux.
* Gérer les tâches quotidiennes.
* Accéder aux dossiers médicaux.
* Préparer des notifications médicales.

---

# 3. Technologies Utilisées

## Framework

* Flutter

## Langage de programmation

* Dart

## Bibliothèque utilisée

* flutter_local_notifications

## IDE recommandé

* Android Studio ou Visual Studio Code

---

# 4. Structure Générale du Projet

Le projet est organisé en plusieurs dossiers :

## lib/

Contient les fichiers principaux de l’application.

### models/

Contient les modèles de données.

### screens/

Contient les différentes interfaces utilisateur.

### services/

Contient les services comme les notifications.

---

# 5. Analyse des Interfaces

## 5.1 Écran de Connexion

Fichier : `login_screen.dart`

### Fonction

Cet écran permet à l’utilisateur d’accéder à l’application.

### Éléments présents

* Champ Email
* Champ Mot de passe
* Bouton « Connexion »
* Icône médicale

### Fonctionnement

Lorsque l’utilisateur clique sur le bouton « Connexion », il est redirigé vers le tableau de bord principal.

---

## 5.2 Tableau de Bord (Dashboard)

Fichier : `dashboard_screen.dart`

### Fonction

Le tableau de bord représente le menu principal de l’application.

### Sections disponibles

* Médicaments
* Rendez-vous
* Tâches
* Dossier médical

### Particularité

Chaque section est représentée sous forme de carte avec une icône.

---

## 5.3 Gestion des Médicaments

Fichier : `medication_screen.dart`

### Fonction

Cette interface permet d’ajouter et consulter les médicaments.

### Données enregistrées

* Nom du médicament
* Dosage
* Heure de prise

### Fonctionnalités

* Ajouter un médicament
* Afficher la liste des médicaments
* Organisation simple des traitements

---

## 5.4 Gestion des Tâches

Fichier : `tasks_screen.dart`

### Fonction

Permet à l’utilisateur de créer des tâches personnelles.

### Fonctionnalités

* Ajouter une nouvelle tâche
* Cocher les tâches terminées
* Suivre les activités quotidiennes

---

## 5.5 Gestion des Notifications

Fichier : `notification_service.dart`

### Fonction

Ce service prépare l’utilisation des notifications locales.

### Bibliothèque utilisée

`flutter_local_notifications`

### Utilité

Les notifications permettront d’envoyer des rappels pour :

* Les médicaments
* Les rendez-vous
* Les tâches importantes

---

# 6. Points Forts de l’Application

* Interface simple et moderne.
* Navigation facile.
* Bonne organisation des fonctionnalités.
* Développement multiplateforme grâce à Flutter.
* Structure du code claire et modulaire.

---

# 7. Limites Actuelles

* Pas encore de base de données.
* Pas d’authentification réelle.
* Les données ne sont pas sauvegardées après fermeture.
* Notifications non encore complètes.
* Absence de synchronisation cloud.

---

# 8. Améliorations Futures

Pour améliorer MediMate, il serait possible d’ajouter :

* Firebase Authentication.
* Base de données SQLite ou Firebase.
* Notifications automatiques avancées.
* Historique médical.
* Interface plus professionnelle.
* Mode sombre et mode clair.
* Sécurité des données médicales.

---

# 9. Conclusion

MediMate est une application mobile médicale développée avec Flutter qui permet d’aider les utilisateurs à mieux organiser leurs activités de santé.

Malgré sa simplicité actuelle, l’application possède une bonne base de développement et peut évoluer vers une solution médicale complète grâce à l’ajout de nouvelles fonctionnalités et d’un système de sauvegarde des données.
