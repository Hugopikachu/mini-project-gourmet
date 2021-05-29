# Mini Projet ML

Rendu final du mini projet ML proposé par l'IA School.

## Étapes imposées

1) Récupération de données sur l'internet via scraping
2) Nettoyage et traitement des données
3) Entraînement d'un modèle de regression, de classification ou de clustering
4) Présentation des performances du modèle choisi

## Données

Pour ce projet, j'ai choisi l'étude du site de [Marmiton](https://www.marmiton.org).

L'un des problèmes rencontrés était l'utilisation de méthodes anti-scraping 
par Marmiton pour les addresses IP détectées comme nuisibles (en générant dynamiquement
les éléments structurels de la pages et leurs identifiants)

## Objectif

En récupérant les données des recettes, et nottament les plats principaux, je souhaite 
proposer une analyse des similitudes parmis les aliments courants et leur apparitions dans 
la composition des recettes.

Par clustering, je souhaite pousser l'analyse pour distinguer des groupes d'ingrédients
semblables et potentiellement interchangeables dans les recettes.

Pour aller plus loin, l'utilisation d'un modèle neuronal de type Tok2Vec permettra 
une analyse plus fine des ingrédients apparaissant dans les mêmes contextes ou 
dans des préparations similaires et donc interchangeables.

## Utilisation

Les dépendances sont listées dans le fichier **requirements.txt** et peuvent être installées
via `pip install -r requirements.txt`

L'ensemble du projet est contenu dans le notebook **marmiton.ipynb**