# [Analysez les ventes de votre entreprise](https://openclassrooms.com/fr/paths/65/projects/146/assignment)

#### Compétences évaluées : 

  - Maîtriser les concepts statistiques fondamentaux
  - Nettoyer un jeu de données
  - Décrire un jeu de données par la statistique descriptive

<br>

## Notebooks : 

📗 ***[Notebook - Nettoyage des données](https://github.com/Gladouu/P4/blob/main/P4_01_scriptdonnées.ipynb)***

📗 ***[Notebook - Analyse des données](https://github.com/Gladouu/P4/blob/main/P4_02_scriptanalyse.ipynb)***

<br>

## Scénario : 

Vous êtes data analyst d'une grande chaîne de librairie, fraîchement embauché depuis une semaine ! Vous avez fait connaissance avec vos collègues, votre nouveau bureau, mais surtout, la machine à café high-tech. Mais revenons à votre mission : il est temps de mettre les mains dans le cambouis ! Le service Informatique vous a donné l’accès à la base de données des ventes. À vous de vous familiariser avec les données, et de les analyser. Votre manager souhaite que vous réalisiez une présentation pour vous "faire la main".

Comme vous l'avez appris dans vos recherches avant de postuler, votre entreprise, "Rester livres" s'est d'abord développée dans une grande ville de France, avec plusieurs magasins, jusqu'à décider d'ouvrir une boutique en ligne. Son approche de la vente de livres en ligne, basée sur des algorithmes de recommandation, lui a valu un franc succès !

<br>

## Les données : 
Vous avez accès à ces données, extraites directement de la base de l’entreprise vers les fichiers CSV. Voici les fichiers à votre disposition :
  - les ventes (appelées “Transactions”) ;
  - la liste des clients ;
  - la liste des produits.

Téléchargez le jeu de données à [cette adresse](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/dataset_P4.zip).

<br>

## Livrables : 

Un fichier .zip contenant ces fichiers :
  - le script destiné à nettoyer le jeu de données ;
  - le script contenant les différentes analyses effectuées ;
  - les graphiques dans un format image (PNG ou JPG) ;

<br>

## Overview : 

Après une première partie concernant le nettoyage des données, où il fallait nottament repérée des sessions de tests, des valeurs abérrantes (prix inférieur à 0€) ou bien encore imputer le prix manquant de certains produits, on a pu, par la suite, analyser les données de l'entreprise selon 3 axes : 

  - Les clients

<img width="662" alt="Capture d’écran 2021-10-21 à 16 59 09" src="https://user-images.githubusercontent.com/45063193/138304480-87d05843-9dac-43eb-9259-dcf3dbfe0d0c.png">

  - Les produits

![13  Répartition prix - categ - boxplot](https://user-images.githubusercontent.com/45063193/138305694-900cabf5-c542-48ee-85bd-93edea2fb307.jpg)

  - Les transactions

<img width="1089" alt="Capture d’écran 2021-10-21 à 17 01 05" src="https://user-images.githubusercontent.com/45063193/138304827-9a5b91f2-266d-4f09-95b5-fb8a6e96110d.png">

<br>
<br>

Cette analyse a ensuite laisser place à l'étude des corrélations. Par exemple, entre l'âge du client et le montant total, l'âge et la fréquence d'achat ou bien encore, l'âge et la catégorie. Tirer des conclusions sur ces corrélations n'était pas aussi évident qu'il n'y parait. 

<img width="962" alt="Capture d’écran 2021-10-21 à 16 56 45" src="https://user-images.githubusercontent.com/45063193/138304040-3d93dfd6-799a-4ed5-a637-fb41bea61ece.png">
