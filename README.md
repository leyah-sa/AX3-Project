# AX3-PROJECT : Analyse des données d'activité physique par accélérométrie - Influence du tabagisme et du sexe

## Description

Ce projet à pour objectif d'analyser l'impact du tabagisme et du sexe sur les performances sportives. Les données traité proviennent de deux individus : 

- Un homme non-fumeur, sportif régulier.
- Une femme fumeuse, ayant une activité physique modérée.

Les données ont été collectées dans des conditions réelles, où chaque participant portait un accéléromètre AX3 au poignet dominant durant des activités physiques similaires, réalisées à la même heure et le même jour. Grâce à python, nous souhaitons explorer les différences physiologique et de performance entre ces deux profils.
---

## Objectifs

1. **Quantifier l'AP** : Mesurer la durée, intensité, cadence, et dépense énergétique des activités physiques.
2. **Analyser les données** : Étudier les corrélations et extraire des indicateurs clés (ENMO).
3. **Comparer les profils** : Identifier les différences entre un sujet fumeur et un sujet non-fumeur.
4. **Visualiser les résultats** : Présenter des graphiques et interprétations des données capturées.

---

## Structure du projet

- **`data/`** : Contient les données brutes d'accélérométrie au format CSV.
- **`notebooks/`** :
  - **`Non-smoker/`** : Analyse des données du participant non-fumeur :
    - Prétraitement et visualisation des données naturelles.
    - Étude des corrélations entre les variables (fréquence, intensité, ENMO, etc.).
    - Analyse des variations de cadence et des performances.
  - **`Smoker/`** : Analyse des données de la participante fumeuse :
    - Prétraitement et visualisation des données naturelles.
    - Étude des corrélations entre les variables (fréquence, intensité, ENMO, etc.).
    - Analyse des variations de cadence et des performances.
- **`results/`** : Contient les graphiques, tableaux et rapports issus des analyses.
- **`main.ipynb`** : Notebook principal pour l'exploration globale et la synthèse des résultats.
- **`.gitignore`** : Fichier pour exclure certains éléments du contrôle de version.
- **`README.md`** : Décrit le projet.

---

## Prérequis

- Python 3.9 ou plus récent.
- Bibliothèques nécessaires :
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scipy`

---
## Installation

- Clonez le dépôt sur votre machine locale.
  