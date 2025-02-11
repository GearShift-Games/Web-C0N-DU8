# Jérémy Roy-Coté

 ![Jérémy_Roy_Coté](../img/jeremy_roy-cote.webp)

Je suis le programmeur d'interconnectivité du jeu C0N DU8. J'ai pour rôle de détecter les intéractions du joueur avec la Kinect et les boutons et d'envoyer les données entre les logiciels Touchdesigner, Arduino IDE et Unity. De plus, Je gere le détection du joueur et l'exclusion des personnes autre que le joueur qui sont vue par la Kinect.

 ## Réalisations

### Semaine 1

La première semaine, j'ai conceptualisé la manière que les boutons seraient lié au vélo stationnaire.

![S1 Développement des boutons](./Semaine_1_conception_Boutons.webp)

Moi et mon équipe avons ensuite fini de solidifier notre approche sur comment faire le jeu.

je me suis ensuite attardé sur la détection du joueur avec la Kinect et l'envois des données vers Unity.

![S1 detection Touchdesigner](./Semaine_1-Touchdesigner.webp)

![S1 reception OSC Unity](./Semaine_1_Unity_Reception_OSC_Basique.webp)

![S1 traitement OSC unity](./Semaine_1_Unity_Traitement_OSC.webp)

### Semaine 2

La deuxième semaine j'ai établit la connection entre Arduino IDE et Unity pour permettre la réception des données venant des boutons.

![S2 detection boutons Arduino](./Semaine_2_Arduino_Bouton.webp)

![S2 boutons](./Semaine_2_Boutons.webp)

J'ai ensuite reglé le problème de détection du joueur quand il y a plusieur personnes dans le champ de vision de la Kinect. Le code passe a travers toutes les personnes et choisi seulement la personne sur le vélo stationnaire.

![S2 selection joueur](./Semaine_2_Touchdesigner_Selection_Joueur.webp)

Le code si dessous permet de recommencer le jeu si le joueur quitte la zone.

![S2 detection joueur](./Semaine_2_Unity_Detection_Joueur.webp)


### Semaine 3

La troisième semaine j'ai continué de peaufiner le code Touchdesigner pour maintenant permettre à chaque joueur de calibrer la sensibilité de la détection de leurs mouvements.

![S3 nouveau Touchdesigner](./Semaine_3_Touchdesigner.webp)

![S3 changement des valeurs dans Touchdesigner](./Semaine_3_Touchdesigner_Calibration.webp)

J'ai aussi ajouté un début de tutoriel dans unity pour permettre au joueur de comprendre comment calibrer leur sensibilité.

