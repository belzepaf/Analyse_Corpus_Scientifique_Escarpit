---
title: Analyse Corpus Scientifique Escarpit
author: Mélanie Aubry ; Cécile Portal
date: 10/01/2019
---

# Description du dossier

Ce dossier est une analyse de corpus réalisée sur Iramuteq. Ce corpus contient 23 textes de Robert Escarpit classés comme *"Articles et Communications scientifiques"*. C'est un compte-rendu de notre expérience qui présente ce que nous avons fait, ce que nous avons obtenu et notre avis. Vous pourrez retrouver tout notre dossier sur __GitHub__ en cliquant [ici](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit).

# Choix des métadonnées

## Variables

Nous avons regroupé tous les textes dans des fichiers .txt ([trouvables ici]()) et encodé ceux-ci de la façon suivante :

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


## Regroupement de textes

Nous avons décidé de procéder à plusieurs analyses en créant des __sous-corpus__. Nous séparerons tout d'abord les 19 textes français des 3 textes en anglais et de celui en italien par souci de pertinence et de compréhension. Ensuite, une analyse générale des textes en français sera faite, puis nous analyserons le reste des textes en langue étrangère selon leur language. Nous ne retiendrons que __les formes actives__, car nous pensons que les formes supplémentaires ne sont __pas pertinentes__ pour une analyse. Enfin, dans seconde partie, nous nous attarderons sur la totalité des textes en faisant une analyse par période, pour suivre l'évolution de Robert Escarpit au fil du temps. 

# Analyse selon la langue

## Analyses statistiques

### Analyse des textes en français

Résumé :
* Nombre de textes : 19
* Nombre d'occurences : 88001
* Nombre de formes : 7511
* Nombre d'hapax : 3410 (3.87% des occurences - 45.40% des formes)
* Moyenne d'occurences par texte : 4631.63

![statistiquefr](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/fr/stats.png)

### Analyse des textes en anglais

Résumé :
* Nombre de textes : 3
* Nombre d'occurences : 10207
* Nombre de formes : 2244
* Nombre d'hapax : 1210 (11.85% des occurences - 53.92% des formes)
* Moyenne d'occurences par texte : 3402.33

![statistiqueeng](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/eng/zipf.png)

### Analyse du texte en italien

Résumé :
* Nombre de textes : 1
* Nombre d'occurences : 4321
* Nombre de formes : 1200
* Nombre d'hapax : 705 (16.32% des occurences - 58.75% des formes)
* Moyenne d'occurences par texte : 4321.00

![statistiqueita](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/ita/zipf.png)

## Nuage de mots

### Nuage de mots en français

![nuagefr](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/fr/nuage.png)

### Nuage de mots en anglais

![nuageita](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/eng/nuage_1.png)

### Nuage de mots en italien

![nuageita](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/ita/nuage_1.png)

## Analyse méthode Reinert

dendrogramme des classes lexicales

### Graphe des classes avec taille des mots proportionnelle à leur fréquence

#### Français

![dendrofr](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/fr/dendro.png)

#### Anglais

![dendroeng](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/eng/dendrogramme_1.png)

#### Italien

![dendroita](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/ita/dendrogramme_1.png)

### Graphe des classes avec taille des mots proportionnelle à score de chi-2

#### Français

![graphfr](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/fr/chi2.png)

#### Anglais

![grapheng](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/eng/AFC2DL.png)

#### Italien

![graphita](https://github.com/belzepaf/Analyse_Corpus_Scientifique_Escarpit/blob/master/images/ita/AFC2DL.png)

# Analyse Chronologique des articles de Robert Escarpit
