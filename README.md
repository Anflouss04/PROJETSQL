Rapport du Projet Bases de Données

Licence MIP - IAP S4 - 2025
Encadrant : Pr. J. Zahir
Introduction

Ce projet s’inscrit dans le cadre du cours de Bases de Données. Il est composé de deux parties complémentaires :

    Partie 1 : Modélisation, création et interrogation d’une base de données MySQL, réalisée par Mohamed.

    Partie 2 : Exploitation de la base via une interface web en Python/SQLite/Streamlit, réalisée par Yassine.

L’objectif est de manipuler une base de données représentant un système de réservation d’hôtels, puis de proposer une interface simple pour consulter et modifier ces données.
Partie 1 : Création et interrogation de la base MySQL

Réalisée par Mohamed
Modèle conceptuel des données (MCD)

Le MCD a été défini et corrigé pour représenter les entités suivantes : Hôtel, Client, Prestation, Type de Chambre, Chambre, Réservation, Évaluation.
Création de la base

    Utilisation de MySQL Workbench pour créer les tables selon le MCD.

    Respect des contraintes d’intégrité référentielle (clés primaires, clés étrangères).

    Scripts SQL de création fournis.

Insertion des données

    Données fournies en annexe (hôtels, clients, prestations, chambres, réservations, évaluations).

    Insertion via script SQL.

Requêtes réalisées

Les requêtes suivantes ont été développées en SQL et en algèbre relationnelle :

    Liste des réservations avec nom du client et ville de l’hôtel réservé.

    Clients résidant à Paris.

    Nombre de réservations par client.

    Nombre de chambres par type de chambre.

    Liste des chambres non réservées sur une période donnée.

Partie 2 : Exploitation via interface web Python/SQLite/Streamlit

Réalisée par Yassine
Création de la base SQLite

    La base SQLite a été créée à partir des mêmes données utilisées en MySQL.

    Cette base est autonome et utilisée par l’application Streamlit.

Fonctionnalités de l’interface

    Consultation de la liste des réservations et des clients.

    Affichage des chambres disponibles entre deux dates saisies par l’utilisateur.

    Ajout d’un nouveau client via formulaire.

    Ajout d’une réservation avec validation des disponibilités.

Technologies utilisées

    Python 3.x

    SQLite pour la base locale.

    Streamlit pour la création rapide de l’interface web.

Description technique

    Le code app.py contient les fonctions pour interagir avec la base SQLite.

    Utilisation de requêtes SQL préparées pour éviter les injections.

    Interface intuitive avec affichage clair des données.

Conclusion

Ce projet a permis de mettre en pratique les concepts fondamentaux des bases de données relationnelles, depuis la modélisation jusqu’à l’exploitation via une interface utilisateur. La séparation des deux parties a permis un travail en binôme efficace, Mohamed assurant la base SQL robuste, et Yassine développant l’interface web interactive.
Annexes

    Scripts SQL (création, insertion, requêtes)

    Requêtes en algèbre relationnelle (PDF)

    Code Python Streamlit (app.py)

    Données utilisées
