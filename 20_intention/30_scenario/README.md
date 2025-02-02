# Scénario
<!-- Ici mettre tous les documents et références concernant la scéanrisation de l'expérience   -->
## Qu'est-ce que vous voulez que l'interacteur vive?
L'interacteur doit vivre des moments de puissance comme si sa vitesse lui procurait une joie dominante et également, l'interacteur doit vivre la pression de devoir être le meilleur le poussant à rouler toujours plus vite.

## Qu'est-ce que vous voulez que l'interacteur ressente?
L'interacteur doit ressentir une surexcitation telle une poussée d'adrénaline d'extrême envergure puis de la satisfaction de sa réussite.

## Qu'est-ce que vous voulez que l'interacteur comprenne?
L'interacteur va comprendre qu'il doit donner son maximum d'effort en endurant une course où le but est de survivre.

## Le comportement de l'interacteur
### La logistique utilisée pour guider nos interacteurs(trices):

1. Un tutoriel sur l'écran tactile sera présent pour illustrer les interactions attendues de l'intéracteur pour gagner.
2. Une mini-map afin de faciliter la navigation de l'utilisateur et de prédire les virages.

3. Des flèches seront là pour pouvoir indiquer à l'utilisateur où il y a des passages alternatifs plus rapides.

4. Les extrémités du circuit seront bleu néon avec la route étant blue marin.

## Les divers encouragements à suivre la progression
### Les récompenses 

1. Les raccourcis offerts

2. Si tu n'es pas dernier, tu peux continuer.

3. Ton temps sera enregistré sur un tableau de classement.

### Les Punitions

1. Tu peux ne pas avoir accès à des raccourcis

2. Foncer dans les murs réduit ta vitesse grandement. 

3. Si tu perds la course, tu devras la recommencer; tu ne progresses pas.

## L'esthétique et élégance
### Esthétique sonore

1. Tempo rapide pour exciter les joueurs et apporter plus d'immersion.

2. Musique électronique pour ajouter un effet futuristique similair à Tron.

### Effets sonores

1. Sons de décompression modifiée pour l'activation du turbo

2. Sons de grincement métallique quand tu tourne de façon serré

3. Sons de collisions

4. Sons de vélos

### Effets visuels

1. Étincelles électriques quand le joueur se penche trop.

2. Choc supersonique quand l'interacteur finit un tour de piste.

3. Flammes par terre quand tu freines.

## L'Espace

### Espace physique

L'interacteur est assis sur le vélo stationnaire et il regarde la projection devant lui tout en pédalant. Des haut-parleurs sont placés à droite et à gauche. L'interacteur pourra interagir avec les boutons sur le vélo de façon analogue. Le lieu de présentation est localisé devant les portes du Grand Studio et du Petit Studio.

### Espace virtuel

Un ordinateur capte la présence du joueur grâce à une Kinect, judicieusement positionnée devant l'œuvre. Le logiciel TouchDesigner prend ensuite ces données captées et les convertit en une position horizontale. Lorsque l'utilisateur pédale, l'énergie générée par le moteur est traduite par le logiciel Arduino IDE, avant d'être transmise à Unity par OSC, où elle influence l'interaction en temps réel. 

## Utilisation du temps

### Temps Chronos

1. Le chronomètre se fit au temps réel

### Temps Kairos

1. Le temps ralenti lors d'une fin de tour (influence temporairement la vitesse du chronomètre).

2. Le temps ralenti momentanément lors du déclenchement du turbo (influence temporairement la vitesse du chronomètre).
