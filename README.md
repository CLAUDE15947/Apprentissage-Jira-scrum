Gestion du projet avec Jira — Méthodologie Scrum

Ce projet a été entièrement géré avec Jira Software en utilisant la méthodologie Scrum.
L’objectif était de structurer le développement d’une application de gestion de tickets (type HelpDesk) avec une organisation professionnelle.

 Épics (EPICS)

Voici les 4 grands blocs fonctionnels définis dans Jira :

 EPIC 1 — Gestion des utilisateurs (Auth & Roles)

Mise en place de la connexion

Séparation Admin / Utilisateur

Gestion des comptes (CRUD Users)

 EPIC 2 — Gestion des Tickets

Création de tickets

Tableau de bord utilisateur

Tableau de gestion admin

Mise à jour des statuts (Ouvert, En cours, Résolu)

 EPIC 3 — Dashboard Administrateur

Vue globale des tickets

Statistiques filtrées

Monitoring de l’activité

 EPIC 4 — Base de données & Connexion MySQL

Modélisation de la base

Connexion MySQL ↔ Streamlit

Requêtes SQL structurées

 Sprints (Scrum)

Le projet a été découpé en 3 sprints de 2 semaines.

Sprint 1 — Authentification + Base de données

Objectifs :

Structure du projet

Mise en place de MySQL

Authentification + gestion des rôles

User stories incluses :

US1 : En tant qu’utilisateur, je peux me connecter

US2 : En tant qu’admin, j’ai des accès supplémentaires

US3 : En tant que développeur, je crée la BDD et les tables

Tâches et sous-tâches principales :

Implémentation de la page de login

Hash des mots de passe

Création du schéma SQL

Tests de connexion

Sprint 2 — Gestion des tickets

Objectifs :

Interface utilisateur

Création/affichage des tickets

Interface admin

User stories incluses :

US4 : En tant qu’utilisateur, je peux créer un ticket

US5 : En tant qu’utilisateur, je peux consulter mes tickets

US6 : En tant qu’admin, je peux gérer les tickets

Tâches & sous-tâches :

Page “Créer un ticket”

Table des tickets

Page admin : liste, statut, détail

Ajout du champ catégorie / priorité

Sprint 3 — Dashboard + Optimisation

Objectifs :

Tableau de bord admin

Statistiques

Nettoyage final

User stories incluses :

US7 : En tant qu’admin, je vois les statistiques globales

US8 : En tant qu’utilisateur, je profite d’une interface optimisée

Tâches :

Graphiques (tickets par catégorie, statut…)

Optimisation UI/UX

Documentation (README, schémas…)

 Relations entre issues utilisées (Jira)

Pour montrer ta compréhension des liens Jira, les relations suivantes ont été appliquées :

 relates to

Lien général montrant que deux tâches sont connectées sans dépendance.

blocks / is blocked by

Utilisé pour exprimer une dépendance technique.
Exemple :

La création de tickets est bloquée par la mise en place de la base de données.

 duplicates / is duplicated by

Utilisé pour dédupliquer deux tickets ayant le même objectif.
