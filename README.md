Projet : Analyse et Prédiction des Prix des Téléphones Portables

Ce projet vise à utiliser des techniques de data mining et d'apprentissage automatique pour prédire les prix des téléphones portables à partir de leurs caractéristiques techniques.


Objectifs


Explorer les caractéristiques des téléphones portables (comme la RAM, la résolution, le processeur, etc.).

Identifier les facteurs qui influencent le prix des téléphones.

Construire des modèles prédictifs robustes pour estimer les prix des appareils.


Données


Le projet utilise un fichier CSV intitulé Cellphone.csv contenant les colonnes suivantes :

Product_id : Identifiant unique pour chaque téléphone.

Price : Prix du téléphone (variable cible).

Sale : Nombre de ventes.

Weight : Poids du téléphone.

Resolution : Résolution d'écran.

PPI : Densité de pixels (Pixels Per Inch).

CPU core : Type de processeur.

CPU freq : Fréquence du processeur.

Internal mem : Mémoire interne.

RAM : Mémoire vive.


Bibliothèques Utilisées


Le projet utilise plusieurs bibliothèques R pour la manipulation des données, la visualisation et la modélisation :

tidyverse : Manipulation et visualisation des données.

corrplot : Analyse de corrélation.

scales : Gestion des échelles pour les graphiques.

rpart : Arbres de décision.

glmnet : Modèles de régression avec pénalisation Lasso et Ridge.

ISLR : Illustration des concepts statistiques et apprentissage supervisé.


Structure du Projet


Exploration des données :

Analyse des distributions des variables.

Exploration des corrélations entre les caractéristiques et le prix.

Préparation des données :

Nettoyage des données.

Transformation et normalisation des variables si nécessaire.

Modélisation :

Construction d’arbres de décision avec rpart.

Utilisation de régressions pénalisées avec glmnet.

Validation des modèles :

Utilisation de techniques comme la validation croisée pour évaluer les modèles.

Analyse des erreurs et ajustement des hyperparamètres.

