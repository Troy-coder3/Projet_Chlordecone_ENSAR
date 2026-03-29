---
title: "Analyse et Modélisation de la Chlordécone aux Antilles Françaises"
author: "Tao ROY - ENSAR"
date: "Mars 2026"
output: github_document
---

#  Projet : Pollution à la Chlordécone (ENSAR)

Ce dépôt contient l'intégralité des travaux réalisés dans le cadre du module **Analyse et Modélisation de données**. Ce projet vise à traiter la problématique de la pollution au chlordécone aux Antilles via un pipeline complet de Data Science (R).

---

##  Accès aux Livrables (GitHub Pages)

Le projet est structuré en deux phases majeures consultables en ligne :

1.  **[Volet 1 : Préparation & Cleaning](https://troy-coder3.github.io/Projet_Chlordecone_ENSAR/preparation_chlordecone.html)** *Nettoyage, gestion des valeurs manquantes, structuration et ingénierie des données.*
2.  **[Volet 2 : Analyse Statistique & ML](https://troy-coder3.github.io/Projet_Chlordecone_ENSAR/analyse_chlordecone.html)** *Exploration, Analyses multivariées (ACP/AFC), Clustering (K-means/CAH) et Aide à la décision.*

---

##  Présentation du Projet

La **chlordécone** est un insecticide persistant dont l'usage historique aux Antilles a créé une crise sanitaire et environnementale majeure. Ce travail utilise des jeux de données réels pour :
- **Identifier** les zones géographiques les plus contaminées.
- **Caractériser** les profils de sols ou de populations via des méthodes de clustering.
- **Aide à la Décision** recommandations basées sur les données pour l'orientation des politiques publiques.

##  Plan des livrables

### 1. Préparation des Données
-   import et inspection initiale des données
-   rennomage des colonnes
-   nettoyage du contenu des variables qualitatives
-   nettoyage du contenu des variables quantitatives
-   Conversion des dates et tests de cohérences
-   Détections et suppression des doublons
-   analyse et traitement des valeurs manquantes
-   imputation de variables critiques
-   validation de la cohérence spatiale

### 2. Analyse des données
-   Analyse Exploratoire des Données (AED)
-   Tests Statistiques
-   Analyse en Composantes Principales (ACP)
-   Analyse Factorielle des Correspondances (AFC)
-   Clustering – Segmentation des communes
-   Aide à la Décision
-   Conclusion générale – Synthèse et liens entre analyses
---

##  Structure du Dépôt

```text
├── preparation_chlordecone.Rmd  # Code R de nettoyage (Volet 1)
├── analyse_chlordecone.Rmd      # Code R d'analyse et ML (Volet 2)
├── README.Rmd                  # Ce fichier
├── data/                       # Données brutes et transformées
└── docs/                       # Rendu HTML pour GitHub Pages
