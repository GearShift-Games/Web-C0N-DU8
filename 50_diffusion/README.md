# Diffusion

Documentation du projet finalisé 

* ![Image 1](https://placehold.co/400x400?text=1+image)
* ![Image 2](https://placehold.co/400x400?text=2+image)
* ![Image 3](https://placehold.co/400x400?text=3+image)
* ![Image 4](https://placehold.co/400x400?text=4+image)


* Vidéo 

* Documentation vidéo de l'installation en action

# Instruction d'utilisation

### 1: Entrez dans la zone de jeux et installez vous sur le vélo stationnaire

### 2: Commencez à pédaler et effectuez les 3 tutoriels interractifs

### 3: Pédalez comme si votre vite en dépendait et rendez vous le plus loin possible dans le jeu

### 4: Apres avoir finis la derniere course vous pouvez restez dans la zone et attendre le que le jeu recommence ou vous pouvez quittez la zone de jeu.


# Manuel d'instruction pour opération

### 1: Lancement de touchdesigner
image

### 2: Lancer Unity et ouvrir la scène Intro
image

### 3: Lancer OBS et envoyé la projection au projecteur
image

### 4: Débutez la scène intro pour commencer le jeu
image

# Fonctionnement du projet

### 1: En pédalant le vélo envoie des données OSC vers Touchdesigner qui les envoie par la suite a Unity.

### 2: Unity recois les données de la kinect et du vélo depuis TouchDesigner afin de les utiliser comme donnée de vitesse, de roation ainsi que de détection.

### 3: Au lancement de la scene d'Intro, une vidéo de gameplay est joué en boucle jusqu'a ce qu'un utilisateur rentre dans la zone de détection de la Kinect.

### 4: Quand un tutoriel est réussi, le prochain tutoriel est lancé jusqu'a ce que chacun d'entre eux soit complété.

### 5: Suite a la complétion des 3 tutoriels, la premiere course est automatiquement lancé.

### 6: Si un joueur perd, il reprend au premier circuit peu importe son progrèsé

### 7: Après avoir complété toutes les course, la scène d'Outro est lancé.

### 8: Dans la scène d'Outro l'utilisateur a le choix entre quitté l'installation ou restez dans la zone de détection et recommencez.

### 9: Si le joueur reste un total de 10 secondes, le jeu va recommencer a partir du premier circuit.

### 10: Si le joueur quitte la zone pendant plus de 3 secondes, le jeu va automatiquement revenir a la scèene d'introduction(cette étape est valable durant l'entiereté de l'expérience.)

