# Projet Python

## Projet Python - Calcul du VWAP Horaires du Bitcoin

### Objectif

Ce projet vise à calculer le Priw Moyen Pondéré par le Volume (VWAP) horaire du Bitcoin pour différents exchanges de cryptomonnaies. Le VWAP est une mesure essentielle pour comprendre l'impact des transactions sur le prix du marché.

### Données

Les données utilisées proviennent de fichiers CSV contenant les trades de Bitcoin réalisés sur divers exhanges. Ces fichiers sont traités pour extraire, nettoyer et préparer les données nécessaires aux calculs.

### Manipulation des données

Le projet implique plusieurs étapes de manipulations des données :
- Importation des données depuis des fichiers CSV.
- Modification de la structure des données pour répondre aux besoins du calcul.
- Jointures des données issues de différennts fichiers pour un traitement homogène.

### Calculs

Les calculs réalisés incluent :
- Le VWAP pour chaque tranche d'une heure et pour chaque exchange.
- Le VWAP global, couvrant tous les exchanges.
- D'autres mesures comme le Volume Weighted Median Price, l'écart-type, et les mesures OHLC à divers intervalles de temps.

### Rendu 
Le projet est présenté sous la forme d'un Jupyter Notebook qui contient trois parties principales :
1. *Input* : Code pour l'importation des données.
2. *Manipulation des données* : Code pour la préparation et la transformation des données.
3. *Calcul* : Code pour les calculs des différentes métriques et l'exportation des résultats sous forme de DataFrames Pandas.

Chaque partie du notebook inclut des explications via des cellules de texte et des commentaires dans le code pour faciliter la compréhension et l'utilisation du projet par d'autres utilisateurs.

### Résultats

Les résultats du projet sont stockés sous la forme de DataFrames Pandas. Ces DataFrames sont indexés par des dates avec une ligne par heure, contenant une colonne par exchange pour le VWAP horaires ainsi qu'une colonne globale pour le VWAP de tous les trades.

### Contribution et Utilisation

Ce projet est ouvert à des contributions pour l'amélioration des calculs ou de la manipulation des données. Pour toute question ou suggestion, n'hésitez pas à ouvrir une issus ou à soumettre une pull request.
