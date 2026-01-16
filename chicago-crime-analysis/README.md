# Chicago Crime Analysis
## Contexte
Projet académique – Master 1 MIASHS  
Méthodes Quantitatives & Modélisation pour l’Entreprise

Projet d’analyse de données basé sur environ 30 000 incidents criminels issus des données ouvertes de la ville de Chicago.

## Description
Ce projet vise à analyser la criminalité à Chicago afin d’identifier des indicateurs
opérationnels, des profils spatio-temporels et des priorités d’action à des fins d’aide
à la décision.

## Données
- Source : Chicago Open Data
- Volume : ~30 000 enregistrements
- Variables principales : type de crime, date/heure, localisation, arrestation, unité policière

## Analyses réalisées
- Nettoyage des données et feature engineering
- Statistiques descriptives
- Analyse spatio-temporelle
- Analyse des taux d’arrestation
- Construction d’un score décisionnel (`problem_score`)

## Résultats principaux
- Crimes les plus fréquents : THEFT, BATTERY, CRIMINAL DAMAGE, NARCOTICS
- Pics horaires : 18h–23h (mercredi, vendredi, samedi)
- Zones les plus touchées : West Side, South Side, Downtown
- Forte hétérogénéité des taux d’arrestation selon les infractions
- Identification des unités prioritaires via le score composite

## Outils
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Structure du projet
