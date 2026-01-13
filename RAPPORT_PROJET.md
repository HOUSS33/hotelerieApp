# 🏨 Hotel Booking and Management — Rapport Technique

## 1. Introduction

Ce document présente le rapport technique du projet *Hotel Booking and Management*.  
Il décrit les objectifs, l’architecture, les choix technologiques, ainsi que les limites et perspectives du système.

---

## 2. Contexte et Objectifs

Le secteur hôtelier nécessite des solutions numériques fiables pour gérer efficacement les réservations et la relation client.  
Ce projet vise à proposer une plateforme centralisée permettant :
- La réservation en ligne de chambres.
- La gestion administrative des hôtels.
- La sécurisation et la centralisation des données.

---

## 3. Description fonctionnelle

### 3.1 Utilisateur
- Recherche d’hôtels selon des critères (ville, date, disponibilité).
- Consultation des informations des hôtels et chambres.
- Réservation et annulation.
- Accès à l’historique personnel.

### 3.2 Administrateur
- Création, modification et suppression d’hôtels et chambres.
- Gestion des utilisateurs.
- Suivi des réservations.
- Accès aux statistiques.

---

## 4. Architecture du système

text
[ Client Web (React) ]
            |
            v
[ API REST (Spring Boot) ]
            |
            v
[ Base de données PostgreSQL ]



## 5. Technologies utilisées

| Élément | Technologie |
|--------|-------------|
| Frontend | React, Tailwind CSS |
| Backend | Java, Spring Boot |
| Base de données | PostgreSQL |
| Sécurité | JWT |
| Versioning | Git, GitHub |

---

## 6. Sécurité

- Authentification basée sur JWT.  
- Hachage des mots de passe avec BCrypt.  
- Gestion des rôles (`USER` / `ADMIN`).  
- Protection des endpoints sensibles.

---

## 7. Déploiement

Le projet peut être déployé selon l’architecture suivante :

- Frontend hébergé sur Vercel ou Netlify.  
- Backend hébergé sur Render ou Railway.  
- Base de données PostgreSQL sur un service cloud.

---

## 8. Limites

- Absence de paiement en ligne.  
- Pas de support multilingue.  
- Pas d’application mobile native.  
- Scalabilité limitée sans conteneurisation.

---

## 9. Perspectives

- Ajout du paiement en ligne (Stripe).  
- Version mobile (React Native).  
- Recommandation intelligente basée sur l’historique.  
- Internationalisation (i18n).  
- Dockerisation pour une meilleure scalabilité.

---

## 10. Conclusion

Ce projet fournit une base solide pour une plateforme de gestion hôtelière moderne.  
Il peut être enrichi avec de nouvelles fonctionnalités selon les besoins métier.
