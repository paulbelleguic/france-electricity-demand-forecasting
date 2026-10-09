# France Electricity Demand Forecasting

## Présentation

Ce projet vise à prévoir la consommation électrique française du lendemain afin d’aider à anticiper les besoins du réseau électrique.

L’objectif est de construire une prévision à partir des consommations passées et de variables temporelles, puis de la comparer à des méthodes simples ainsi qu’à la prévision officielle publiée par RTE.

## Problème étudié

La production et la consommation d’électricité doivent rester équilibrées en permanence. Une prévision fiable de la consommation à J+1 peut aider RTE à anticiper les besoins et à préparer l’équilibre du réseau.

La question principale du projet est la suivante :

> Peut-on prévoir la consommation électrique française du lendemain à partir des données historiques, et comment cette prévision se compare-t-elle à une méthode naïve et à la prévision J-1 de RTE ?

## Données

Les données proviennent du jeu public [Données éCO2mix nationales consolidées et définitives](https://odre.opendatasoft.com/explore/dataset/eco2mix-national-cons-def/information/), publié par RTE sur la plateforme Open Data Réseaux Énergies.

Le jeu de données contient notamment :

- la consommation électrique réellement observée ;
- les prévisions réalisées par RTE à J-1 et le jour même ;
- la production électrique par filière ;
- les échanges d’électricité ;
- une estimation du taux de CO₂ ;
- la date et l’heure de chaque mesure.

Le fichier brut est conservé localement dans `data/raw/` et n’est pas versionné avec Git. Les instructions permettant de le télécharger seront ajoutées au projet.

## Méthode prévue

Le projet sera construit progressivement :

1. inspection et validation des données ;
2. nettoyage et préparation des séries temporelles ;
3. analyse exploratoire ;
4. création de prévisions naïves servant de références ;
5. entraînement de modèles de prévision ;
6. évaluation chronologique sur des données futures non vues ;
7. comparaison avec la prévision J-1 de RTE ;
8. analyse des erreurs et des limites ;
9. automatisation et documentation du pipeline.

## État du projet

Projet en cours de construction.

Aucun résultat ni aucune performance ne sont encore annoncés.