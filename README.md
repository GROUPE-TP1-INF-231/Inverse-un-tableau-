Inverser un tableau en C

Description du programme 

Ce programme permet de renverser l’ordre des éléments d’un tableau saisi par l’utilisateur.
En d’autres termes, le premier élément devient le dernier, le deuxième devient l’avant-dernier, et ainsi de suite.

L’algorithme utilisé est assez simple :

on échange les éléments situés au début du tableau avec ceux de la fin,

on avance progressivement vers le centre du tableau,

on s’arrête quand on a tout inversé.
-----------------------------------

Compilation

Pour compiler le programme, on utilise :

gcc inverser_tableau.c -o inverser_tableau
------------------------------------

Exécution

Une fois compilé, on peut l’exécuter avec :

./inverser_tableau
------------------------------------

Exemple d’utilisation

Entrées données par l’utilisateur :

Entrez la taille du tableau: 5
Entrez les éléments:
1 2 3 4 5

Résultat affiché :
5 4 3 2 1
