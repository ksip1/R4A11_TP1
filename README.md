# R4A11_TP1

# Question 1:
Ce fichier a pour nom activity_main.xml et se trouve dans R4A11_TP1/app/src/main/res/layout.

# Question 2:

Dans la vue design de activity_main.xml, aller dans commande attribute et changer le texte "Hello World!" par "Coucou j'ai trouvé comment faire".

# Question 3:

Tout d'abord, il faut avoir une image dans le répertoire mipmap. 
Ensuite, modifier la ligne --> android:roundIcon="@mipmap/nomimage". Dans mon cas, cela va être --> android:roundIcon="@mipmap/imagepose".

# Question 4:

Oui, il faut appuyé sur le bouton "valider" pour afficher le texte saisi sur la deuxième activité car le texte 
qu'on met dans EditText est transmis qu'au moment où l'intent à été crée et lancé.

# Question 5:

Oui, se comportement semble normal.

# Question 6:

Il faut vérifier que l'intent contient bien les données avant de les affiché. Donc 
il n'y a pas de données présent, nous ne pouvons pas affiché un message par défaut.