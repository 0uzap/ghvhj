# Paradice

Présentation:
Ce projet nommé Paradice à pour but de proposer un simulateur de lancer de dés.
Cette application doit sortir le nombre de dés seléctionnés, le nombre de dés ayant attérit sur tel ou tel face ainsi que la moyenne du lancer de ces dés.

Fonctionnement:
Ce projet utilise des classes (censées être abstraites ) Dice ainsi que Dicepool. Dice définit les dés et Dicepool leurs nombres.
Les fichiers contennant ces classes sont ensuite importer dans le fichier myhomepage.dart puis utilisé lorsqu'il y en a besoin.

Explication des fichiers:
Les différents fichiers dice6.dart, ... dice100.dart contiennent les classes filles de dice.dart.
De même les différents fichiers dicepool6.dart, ... dicepool100.dart contiennent les classes filles de dicepool.dart.
myhomepage est le fichier dans lequel toute l'interface de l'application se trouve, les boutons, l'images, les résultats...
