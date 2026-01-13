# 🏨 Hotel Booking and Management — Compte Rendu de Projet

## 1. Informations générales

- Projet : Hotel Booking and Management  
- Type : Plateforme web de réservation et gestion hôtelière  
- Période : 2025–2026  
- Technologies principales : React, Tailwind CSS, Java Spring Boot, PostgreSQL  
- Type de document : Compte rendu  
- Support : Dépôt GitHub  

---

## 2. Contexte

Le projet *Hotel Booking and Management* a été réalisé dans le cadre d’un travail académique visant à concevoir une application web permettant la réservation de chambres d’hôtel et la gestion administrative associée.

Le projet repose sur une architecture client-serveur avec un frontend web et un backend exposant une API REST.

---

## 3. Déroulement du projet

### 3.1 Phase de conception

- Définition des besoins fonctionnels.
- Identification des rôles utilisateurs (Utilisateur, Administrateur).
- Élaboration des premières maquettes d’interface.
- Définition de l’architecture générale du système.

### 3.2 Phase de développement

- Mise en place du projet frontend avec React et Tailwind CSS.
- Mise en place du projet backend avec Spring Boot.
- Création des entités principales : Utilisateur, Hôtel, Chambre, Réservation.
- Implémentation des endpoints REST.
- Connexion à la base de données PostgreSQL.

### 3.3 Phase de tests

- Tests manuels des principales fonctionnalités.
- Vérification de la création de comptes utilisateurs.
- Vérification des réservations et annulations.
- Vérification des droits d’accès administrateur.

---

## 4. Fonctionnalités réalisées

### 4.1 Fonctionnalités utilisateur

- Inscription et authentification.
- Recherche d’hôtels selon la ville et la disponibilité.
- Consultation des détails des chambres.
- Création et annulation de réservations.
- Accès à l’historique personnel.

### 4.2 Fonctionnalités administrateur

- Création, modification et suppression d’hôtels.
- Gestion des chambres associées aux hôtels.
- Visualisation de la liste des réservations.
- Gestion des comptes utilisateurs.

---

## 5. Architecture mise en place

```text
Client Web (React)
        |
        v
API REST (Spring Boot)
        |
        v
Base de données (PostgreSQL)
