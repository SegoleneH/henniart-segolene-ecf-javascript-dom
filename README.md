# ECF Javascript - Manipulation du DOM

Application de notation dont l'usage est limité à un enseignant. 

L'application se présente sous forme d'une liste d'élèves à qui l'enseignant peut attribuer une note, 

Il doit pouvoir évaluer par note ou par couleur, sans que la note soit gardée en mémoire au changement de mode. Les notes vont de 1 à 5 exclusivement.


# Instructions de développement

Les notes vont de 1 à 5. Si l'utilisateur tape autre chose, il faut remettre la valeur à vide. Il faut que le focus passe automatiquement à la case suivante une fois une case remplie.

Pour les notes par couleur, il y a 4 couleurs (rouge, orange, jaune, vert).
En arrivant sur ce mode, il faut que les cases soient vertes par défaut & que le focus soit sur le 1er input.
Pour changer la couleur, l'utilisateur tape sur 1, 2, 3, ou 4, ce qui remplit la case avec la couleur correspondante.
1-->rouge
2-->orange
3-->jaune
4 & 5-->vert
On ne doit pas voir les chiffres que l'utilisateur tape.

Il y a un bouton pour que l'utilisateur choisisse s'il note en couleur ou par note.

-->Avant son choix, il ne doit pas pouvoir noter, donc les inputs doivent être cachés.

Mais si la touche saisie ne correspond pas à celle que nous avons déterminé, rien ne doit se passer, nous ne devons pas passer le focus sur l'élève suivant.