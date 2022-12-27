# MediaPhoto

## Système pour la gestion de galeries photos

### Principes généraux :
MediaPhoto est une application de gestion de galeries photos permettant à ses utilisateurs de :
- Créer des galeries
- Stocker des photos et les associer à une galerie
- Naviguer dans des galeries et visualiser des photos
- Classer les photos et les galeries grâce à des mots-clés

L’application est utilisable sur tous les types de terminaux.



## Authors

- [Christopher JUE](https://github.com/JUEChristopher)
- [Khaoula BOULHDIR](https://github.com/KhaoulaCode)
- [Mehdi TAHRI](https://github.com/MehdiThr)
- [Bradley BARBIER](https://github.com/Catif)

## Installation du projet :

####  Génération du fichier `main.css`
Lancer `sass html\style\sass\:html\style\css\` à la racine du projet dans votre terminal

#### Installation et configuration de la base de donnée
Dans un premier temps, récupéré le fichier `conf/demo_database.sql` et importé le dans votre SGBD favori.

Renommer le fichier `conf/db.ini.example` en `conf/db.ini` puis remplacer les données par celle correspondante à la base de donnée faite à l'étape précédente.

#### Lancement du serveur Local
Lancer `php -S localhost:8000` pour lancer un serveur local à partir de php.


#### Comptes de démo
Dans la banque de données préalablement installée, des comptes ont été générés.
Leurs informations de connexion sont : 
- email : **user<$number>@photomedia.fr**
- password : **user_<$number>**

<$number> étant un nombre allant de 0 à 25.

exemple : 
- email : **user15@photomedia.fr**
- password : **user_15**
