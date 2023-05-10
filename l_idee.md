# l_idee

##Étape 1

Dans cette exercice nous allons allumer l'écran de LED quand le bouton A est préssé. 

Quand l'enseigant pose une question, tu peux maintenent faire un signe lumineux plutot que de lever le doigt =)

##Étape 2

Commençons par ajouter une condition dans le crochet ``||basic:toujours||``.

Dans la  section ``||logic:logique||`` glisser et déposer ``||logic:si vrai alors sinon||`` au crochet ``||basic:toujours||``.

##Étape 3

Dans la section ``||input:entrée||`` glisser et déposer ``||input:bouton A est pressé||`` à la place de ``||logic:vrai||``.

##Étape 4

Dans la section ``||basic:base||`` glisser et déposer ``||basic:montrer LEDs||`` dans le crochet ``||logic:si alors||``.

Puis dessiner le signe que vous voulez.

##Étape 5

Dans la section ``||basic:base||`` glisser et déposer ``||basic:effacer l'écran||`` dans le crochet ``||logic:sinon||``.

##Étape 6

Et voilà! Il ne reste plus qu'à **téléverser** le code sur le micro:bit. 

1. **Connecter le micro:bit** à votre ordinateur avec le câble USB.
2. **Télécharger votre code** avec le bouton Télécharger en bas à gauche de l'écran.
3. Dans le gestionnaire de fichiers de votre ordinateur, **glisser le fichier téléchargé** vers le micro:bit.
4. Durant le transfert, la DEL orange au dos du micro:bit va clignoter rapidement. Une fois que c'est terminé, **votre code est sur l'appareil**.

[Voyez ici la vidéo aide-mémoire](https://youtu.be/H8utNPE3sJo) par GénieLab, et [voici la procédure détaillée](https://makecode.microbit.org/device/usb) dans la documentation de MakeCode (en anglais seulement).