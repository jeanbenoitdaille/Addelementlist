# Addelementlist
Ajouter des éléments à une liste 
Pour ajouter plusieurs éléments dans une liste en une seule fois, on utilise la fonction extend.

En effet, si vous utilisez la fonction append, vous allez ajouter une liste à l'intérieur de votre liste.

Pour ajouter plusieurs éléments d'un coup sans créer une sous-liste, il faut donc utiliser la fonction extend, qui va ajouter à la fin de votre liste les différents éléments que vous lui passez.

Il peut y avoir de la confusion dans le fait que vous devez passer une liste à la fonction extend.

Ainsi vous ne pouvez pas faire :

ma_liste.extend(4, 5, 6) 

Il faut à la place faire :

ma_liste.extend([4, 5, 6]) 

Bien que l'on passe une liste en argument de la fonction extend, cette fonction va bien ajouter les éléments à l'intérieur de votre liste sans créer de sous-liste.
