# Le_soleil

##Étape 1

**Dans cet exercice nous allons allumer et faire clignoter un soleil**


##Étape 2

Dans ``||basic:Base||``, trouver et ajouter ``||basic:montrer LEDs||`` dans le crochet ``||basic:toujours||``.

Dessner un soleil dans la matrice de LED en cliquant sur les petits carrés.

***Astuce:*** *Cliquer sur le ? pour avoir un indice visuel de ce qu'il faut faire.*


##Étape 3

Nous allons faire clignoter le soleil en effaçant l'écran après avoir affiché le soleil.

Trouver ``||basic:effacer écran||`` dans l'onglet ``||basic:base||``. 

Ajouter le bloc à la suite de ``||basic:montrer LEDs||``.


##Étape 4

Le soleil clignote très rapidement, nous allons donc ajouter une pause dans la boucle ``||basic:toujours||``.

Trouver ``||basic:pause(ms)||`` dans la section ``||basic:base||`` et ajouter en un avant ``||basic:effacer écran||`` et un juste après ``||basic:effacer écran||``. 



##Étape 5

La boucle ``||basic:toujours||`` se divise en deux parties.

La première partie affiche le soleil et attend 1 seconde.

Une fois la seconde écoulée, l'écran s'efface  et attend une seconde supplémentaire avant de boucler. 

##Étape 6

Et voilà! Il ne reste plus qu'à **téléverser** le code sur le micro:bit. 

1. **Connecter le micro:bit** à votre ordinateur avec le câble USB.
2. **Télécharger votre code** avec le bouton Télécharger en bas à gauche de l'écran.
3. Dans le gestionnaire de fichiers de votre ordinateur, **glisser le fichier téléchargé** vers le micro:bit.
4. Durant le transfert, la DEL orange au dos du micro:bit va clignoter rapidement. Une fois que c'est terminé, **votre code est sur l'appareil**.

[Voyez ici la vidéo aide-mémoire](https://youtu.be/H8utNPE3sJo) par GénieLab, et [voici la procédure détaillée](https://makecode.microbit.org/device/usb) dans la documentation de MakeCode (en anglais seulement).