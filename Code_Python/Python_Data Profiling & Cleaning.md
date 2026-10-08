# 🐍 Python — Data Profiling & Cleaning

## 🎯 Objectif

Cette partie du projet utilise Python et Pandas pour analyser, contrôler et nettoyer les données commerciales.

Python intervient après le premier contrôle réalisé avec Excel/VBA afin d'effectuer des traitements plus poussés sur les données.

## 📄 Scripts

### `profiling.py`

Le script permet notamment de :

* vérifier la structure du dataset ;
* identifier les types de données ;
* détecter les valeurs manquantes ;
* rechercher les doublons ;
* analyser les valeurs atypiques ;
* produire un premier diagnostic de qualité des données.

### `cleaning.py`

Le script permet de :

* traiter les valeurs manquantes ;
* supprimer ou gérer les doublons ;
* corriger les types de données ;
* standardiser certaines valeurs ;
* préparer les données pour Power BI.

## 🔄 Workflow Python

```text
Données brutes
      ↓
profiling.py
      ↓
Diagnostic qualité
      ↓
cleaning.py
      ↓
Données nettoyées
      ↓
Power BI
```

## 🛠️ Technologies

* Python
* Pandas
* NumPy

## 🧠 Compétences démontrées

* Data Profiling
* Data Cleaning
* Data Quality
* Manipulation de DataFrames
* Analyse exploratoire
* Automatisation des traitements
