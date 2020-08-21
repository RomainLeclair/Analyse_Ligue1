# Analyse de la Ligue1 depuis 1995 : Project Overview
* C'est un simple notebook avec quelques analyses sur la Ligue 1 en fonction des données disponibles
* Utilisation de webScrabing à l'aide de *BeautifoulSoup*
* Un nettoyage des données pour pouvoir utiliser ces dernières le plus facilement
* Une analyse de donnée assez simple en analysant les vainqeurs du championnats, les cartons rouges , ...

# Données
Les données que nous avons utilisés viennet d'un site espagnol. https://www.bdfutbol.com/t/tfra2019-20.html <br>
Nous avons utilisés les données de la Ligue1 qui allait de la saison 1995-1996 à 2019-2020

# Code et Ressources utilisés
**Python Version**: 3.7

**Tutorial of**: https://github.com/amandaiglesiasmoreno/Spanish-League/blob/master/Spanish%20League.ipynb

**Packages**: pandas, numpy, matplotlib, time, requests, bs4

**Beautifoul Soup **: https://pypi.org/project/beautifulsoup4/

**Flask Porduction**: https://flask.palletsprojects.com/en/1.1.x/


# Web Scraping
Nous avons utilisés Beautifoul Soup pour extraitre le tableau des résultats de chaque saison. Nous avons pu récupérer les éléments suivants:
* Classement
* Club
* Points
* Matchs
* Victoire
* Match-Nul
* Défaites
* But marqués
* But encaissés
* Carton jaune
* Carton Rouge


# Data Cleaning

Après avoir obtenu une tabe de données extraite du site. Il a fallu nettoyer ces données:
* Supression des colonnes inutiles
* Rename des colonnes
* Transformation des variables si nécessaire
* Vérificatieu des doublons

# Analyse de données
Après ces étapes, nous avons pu analyser quelques notions qui nous semblait importantes. Voici quelques exemples ci-dessous.
 ![alt text](https://github.com/RomainLeclair/Analyse_Ligue1/blob/master/VainqueurL1.png)

 ![alt text](https://github.com/RomainLeclair/Analyse_Ligue1/blob/master/EvolutionVictoire.png)
 
 ![alt text](https://github.com/RomainLeclair/Analyse_Ligue1/blob/master/CartonRouge.png)


