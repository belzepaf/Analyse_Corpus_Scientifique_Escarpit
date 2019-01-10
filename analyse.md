---
title: Analyse Corpus Scientifique Escarpit
author: Mélanie Aubry ; Cécile Portal
date: 10/01/2019
---

# Description du dossier

Ce dossier est une analyse de corpus réalisée sur Iramuteq. Ce corpus contient 23 textes de Robert Escarpit classés comme *"Articles et Communications scientifiques"*. C'est un compte-rendu de notre expérience qui présente ce que nous avons fait, ce que nous avons obtenu et notre avis. Vous pourrez retrouver tout notre dossier sur __GitHub__ en cliquant [ici](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit).

# Choix des métadonnées

## Variables

Nous avons regroupé tous les textes dans un même fichier .txt et encodé ceux-ci de la façon suivante :

~~~~
**** *variableX *variableX.1
texte texte texte texte

**** *variableY *variableY.2
texte texte texte

A noter que :
**** : introduit chaque texte
*nomvariable : crée une variable
~~~~
De plus nous avons intégré les métadonnées suivantes, en fonction des dates de publication de chacun des textes, de leurs sujets et de leur type : 
* *date_XXXX
* *subject_XXXX
* *type_XXXX

Notre choix de variables repose donc sur différentes catégories. En voici un exemple :

| *date_XXXX      | *subject_XXXX     | *type_XXXX      |
| -------------| -------------| -------------|
| 1950         | infocom      | articles scientifiques      |
| 1970        | histoire       | article       |
| 1990      | sociologie      | discours    |

[Lien vers la version .txt]()

## Regroupement de textes

Les textes que l'ont choisi de mettre ensemble --> Sous corpus

# Analyse statistique

# Nuage de mots

txtxtxt

# Analyse méthode Reinert - Dendrogramme

dendrogramme des classes lexicales

## Graphe des classes avec taille des mots proportionnelle à leur fréquence

## Graphe des classes avec taille des mots proportionnelle à score de chi-2

## Graphe des modalités de la variable chronologique
