# Wordpress_Workshop

Un Workshop sur l'installation de Wordpress la création de plugin !


# 1. Installation de LocalByFlyWheel


Local by FlyWheel est une solution qui permet de créer un serveur avec Wordpress d'installer dessus et une base de donnée.
Nous installerons ce petit soft afin de gagner du temps sur la création de serveur et l'installation 

Vous pouvez le télécharger juste ici : https://localbyflywheel.com/

Une fois installé vous pourrez créer votre site en lui donnant un nom ! Puis au choix de l'environnement, choisissez Custom.
Puis -> PHP 7.3.5
     -> MySQL 8.0.16

choisissez vos logs (UserName : root | PassWord : toor).

Une fois votre serveur créé, prenez le temps d'explorer l'interface admin et de découvrir Wordpress pendant quelques minutes.


# 2. Votre Premier Plugin


Nous allons donc passer à la création de notre premier plug-in !

Objectif : Afficher un ensemble de quotes (amusez-vous prenez en de film ou de jeux-video ou autres) sur chaque page de l'interface admin de Wordpress

Pour cela vos aurez besoin de créer un dossier pour votre plugin dans le repertoire suivant :
~/Local Sites/Nom_De_Ton_site/app/public/wp-content/plugins/

ensuite créer un fichier .php afin d'écrire votre plugin à l'intérieur.

Vous trouverez un template pour votre plugin dans le github. Amusez-vous !

N'oubliez que le PHP vous permets d'utiliser du html et du css alors n'hésitez pas


# 3. Modifiez un plugin existant.

Choississez un ou plusieurs plug-ins déjà existant. De préférence des plug in simple comme contact-form7 ou autre connerie que vous trouverez ;)
afin de vous familiariser un peu plus avec les hooks et la manière dont ils sont utilisés.
N'hésitez pas à en modifier quelques uns ! Wordpress est open-source ;)



# 4. Implémenter un footer dans le front depuis le Back-office

Le but de cet exercice sera de créer une option dans le back-office (post-type) qui permettra de faire de créer un footer à notre front et de pouvoir le modifier à tout moment sans toucher au footer.php

En premier construisez votre custom post-type
puis faite en sorte de pouvoir modifier le footer grâce aux hooks

N'hésitez pas à vous documenter ou à venir me voir.
