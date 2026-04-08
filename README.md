# Analyse de données League of Legends via l'API Riot Games

## Description
Ce projet illustre l'interrogation et l'exploitation d'une API REST avec R,
appliquée à l'univers de l'esport. Il démontre qu'il est possible de réaliser
en R ce qui est traditionnellement fait en Python pour ce type de données.

## Compétences mobilisées
- **Connexion à une API REST** : authentification par clé, requêtes HTTP GET
avec le package `httr`
- **Traitement de données JSON** : parsing et structuration avec `jsonlite`
- **Manipulation de données** : nettoyage et transformation avec `dplyr`
- **Visualisation** : création de tableaux interactifs avec `kableExtra`

## Contenu
- Récupération du PUUID d'un joueur via son pseudonyme
- Extraction des identifiants de matchs
- Analyse détaillée d'une partie : kills, deaths, assists, gold, vision score,
items achetés, objectifs...
- Tableaux récapitulatifs par joueur et par équipe

## Technologies
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)

## Source des données
[Riot Games Developer Portal](https://developer.riotgames.com)
