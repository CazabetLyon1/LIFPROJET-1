# LIFPROJET

Ce projet a été créé dans le cadre d'un Data Challenge dont la présentation se situe [ici]( https://www.sfds.asso.fr/fr/jeunes_statisticiens/manifestations/610-data_challenge_jds_2018/).

## Objectif

Les organisateurs du challenge fournissent trois fichiers (situés dans le dossier Data) :
* conso_train.csv : la consommation éléctrique de l'île de Ouessant sur un an
* meteo_train.csv : diverses données météorologiques au même endroit et à la même période
* meteo_prev.csv : les données métérologiques sur la semaine suivante

Le but est de prédire la consommation éléctrique sur la semaine suivante en utilisant l'ensemble de ces fichiers.

## Pré-requis

La lecture des fichiers sous forme de Notebook peut se faire directement sur GitHub.

Pour la modification et les tests, il est nécessaire d'installer [Anaconda](https://www.anaconda.com) et d'utiliser jupyterlab.

## Le projet

Ce repository git présente plusieurs méthodes que nous avons testés pour effectuer la prédiction.
* visualizing permet d'avoir un premier aperçu des données.
* Les méthodes de prédiction ont chacune leur dossier. Nous conseillons de les explorer dans cette ordre : AR, ARIMA puis LMTS.
