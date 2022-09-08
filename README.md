# Utiliser Chataigne rapidement

Le but est de 

## L'interface

![Screenshot de l'interface de Chataigne](./images/screen1.png)

L'interface de Chataigne est divisée en 6 parties.
 - Modules, où on ajoute chacun des modules de connexion utilisés dans le projet.
 - Custom Variables
 - Sequences + Sequence Editor, la timeline
 - State Machine, pour créer des conditions et des conséquences ////
 - Inspector, où on peux modifier les paramètres de l'élement selectionné
 - Help + Logger + Warnings

## Modules

La partie module permet d'ajouter des modules de communication, soit avec des protocoles d'échanges de données, des controleurs physiques ou des logiciels.

![Screenshot de la création d'un module MIDI](./images/screen3.png)

En créant un module, on a accès à ses paramètres dans l'Inspector.

### Controleur Midi

![Screenshot de la création des paramètres du module MIDI](./images/screen4.png)

Pour un module de communication MIDI par exemple, on peux choisir notamment le controleur MIDI dont l'on souhaite récuperer les données.

![Screenshot de la création de la connexion en MIDI](./images/screen5.png)

J'utilise ici le controleur Launch Control.

![Screenshot de la création de la connexion en MIDI](./images/screen6.png)

Lorsque la case `Auto Add` est cochée, les valeurs des touches de mon controleur apparaissent automatiquement dans la partie Values lorsque j'appuie dessus, 0 étant non pressée et 127 la valeur pressée.

## State Machine

On peux exploiter ce genre de données dans la State Machine, en créant des conditions.

![Screenshot de la création d'un State'](./images/screen7.png)

On peux créer un State en double-cliquant sur la partie State Machine.

En cliquant sur le + en haut à droite, on peux créer une Action et  choisir ses conditions dans les paramètres de l'Inspector.

![Screenshot des conditions d'un state'](./images/screen8.png)

## Connecter Madmapper et Chataigne

