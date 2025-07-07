📘 SAE S104 : Création d'une base de données


🎯 Objectif
Ce projet a pour but de concevoir, créer et alimenter une base de données relationnelle à partir d’un fichier CSV contenant des données sur les libertés dans le monde.

🛠️ Étapes réalisées
Modélisation de la base de données

Utilisation d’un AGL (Atelier de Génie Logiciel) pour créer un MCD et un MPD.

Réalisation de relations fonctionnelles et maillées.

Script SQL de création

Rédaction manuelle du script SQL avec gestion des clés primaires, étrangères et des types appropriés (INTEGER, VARCHAR, BOOLEAN, SERIAL).

Génération automatique du script via l’AGL pour comparaison.

Peuplement de la base

Création d’une table temporaire change pour importer les données du fichier freedom.csv.

Transfert des données vers les tables définitives (region, status, country, freedom) via des requêtes INSERT ... SELECT DISTINCT.

Analyse comparative

Étude des différences entre le script manuel et celui généré par l’AGL.

Justification des choix de modélisation et d’implémentation.

💡 Compétences mobilisées
Modélisation conceptuelle et physique de base de données.

Écriture de requêtes SQL complexes.

Utilisation d’un AGL pour la conception de bases de données.

Chargement et traitement de données depuis un fichier CSV.

📁 Fichiers inclus
SAE BD.pdf : Rapport complet du projet.

freedom.csv : Données source (non fourni ici).

script_creation.sql : Script SQL de création manuel.

script_agl.sql : Script généré par l'AGL.
