Analyse des facteurs de risque du cancer du col de l'utérus
Ce projet de science des données se concentre sur l'analyse et la modélisation des facteurs de risque liés au cancer du col de l'utérus. Le travail est organisé en deux parties distinctes, chacune explorée dans un notebook Jupyter.

Description du jeu de données
Le jeu de données utilisé provient d'une étude médicale et contient diverses caractéristiques de patientes, notamment leur âge, le nombre de grossesses, l'utilisation de méthodes contraceptives, ainsi que des informations sur le risque d'infection par le VPH (HPV).

Projets
1. Régression Linéaire (1. Regression Lineaire.ipynb)
Ce premier notebook explore l'application d'un modèle de régression linéaire.

Objectif : Analyser la relation entre les facteurs de risque et une variable cible continue (par exemple, le nombre de biopsies ou une autre mesure quantitative). L'objectif est de comprendre l'influence de chaque facteur sur le résultat et d'identifier les corrélations significatives.

Méthodologie : Le notebook présente les étapes de l'analyse, incluant la préparation des données, l'ajustement du modèle de régression, et l'interprétation des coefficients pour déterminer l'importance de chaque variable.

2. Classification des facteurs de risque (2. Classification.ipynb et 2. Classification - HPV.ipynb)
Ce deuxième volet se concentre sur la classification, un type d'apprentissage supervisé.

Objectif : Construire un modèle capable de prédire la présence ou l'absence du cancer du col de l'utérus (ou d'une autre maladie liée) en se basant sur les données des patientes.

Méthodologie : Le notebook explore différents algorithmes de classification (comme la Régression Logistique, les Machines à Vecteurs de Support (SVM) ou les Forêts Aléatoires) pour construire un modèle prédictif robuste. Les performances de chaque modèle sont évaluées afin de trouver la meilleure approche pour la prédiction.

Prérequis
Pour lancer et exécuter ce projet, assurez-vous d'avoir les bibliothèques Python suivantes installées. Elles sont listées dans le fichier requirements.txt.

Vous pouvez les installer avec la commande suivante :

Bash

pip install -r requirements.txt
Utilisation
Cloner le dépôt (si ce n'est pas déjà fait) :

Bash

git clone https://github.com/luclmj5440/TP-BIG-DATA.git
Naviguer vers le répertoire du projet :

Bash

cd "Cervical Cancer (Risk Factors)"
Lancer Jupyter Notebook :

Bash

jupyter notebook
Ouvrez ensuite les fichiers 1. Regression Lineaire.ipynb et 2. Classification.ipynb pour explorer les analyses.

Auteur
Nom : Luc LUMANJI MBUNGA
