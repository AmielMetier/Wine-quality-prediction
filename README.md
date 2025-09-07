# Wine Quality Prediction

Projet de modélisation visant à prédire la qualité de vins rouges à partir de leurs caractéristiques physico-chimiques. Réalisé dans le cadre du module “Introduction aux traitements de données” de la filière Mathématiques Appliquées et Modélisation à Polytech Nice Sophia.

## Objectif

Analyser un jeu de données de vins rouges, explorer les relations entre variables et construire un modèle de machine learning pour estimer la qualité d’un vin sur la base de ses propriétés mesurables.

## Structure du projet

- `Project_Wine_Quality_Prediction.ipynb` : Notebook principal. Contient le code, les analyses, les visualisations et les explications étape par étape.
- `Rapport_WIne_Quality_Prediction.pdf` : Rapport détaillé expliquant la démarche, les choix méthodologiques, les résultats et les limites.
- `winequality-red.csv` : Jeu de données utilisé (si présent).
- `Diapo_Wine_Quality_Prediction.pdf` : Diaporama de présentation.

## Démarche adoptée

1. **Exploration des données** : observation des caractéristiques, visualisations, recherche de corrélations et de valeurs aberrantes.
2. **Prétraitement** : nettoyage des données et sélection des variables pertinentes.
3. **Modélisation** : implémentation d’un modèle de machine learning (régression linéaire/forêt aléatoire).
4. **Évaluation** : analyse des résultats, interprétation des limites, discussion des pistes d’amélioration.

## Résultats

Le modèle de régression linéaire a permis de dégager les variables les plus influentes (telles que l’alcool et l’acidité volatile), mais la performance reste limitée (R² ajusté ≈ 0.40). La qualité subjective d’un vin ne se laisse pas modéliser uniquement par des critères physico-chimiques.

## Prérequis

- Python 3
- numpy, pandas, matplotlib, seaborn, scikit-learn

## Exécution

Ouvrir et exécuter le notebook `Project_Wine_Quality_Prediction.ipynb` depuis Jupyter ou Google Colab. Le rapport PDF fournit tous les détails techniques et méthodologiques.

## Auteurs

Yseult Canac–Pons, Amiel Metier, Lucas Fert  
Polytech Nice Sophia – Mathématiques Appliquées et Modélisation  
Année 2024-2025
