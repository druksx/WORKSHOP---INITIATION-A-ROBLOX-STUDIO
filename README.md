# Initiation à Roblox Studio
Bonjour et bienvenue dans ce Workshop d'initiation à Roblox Studio.
<br>Cette première prise en main est faite pour vous constituer des bases solides !
<br>Si vous avez la moindre question, n'hésitez pas à venir nous les poser à la table :).
<br><br>Notez toutefois qu'il est nécessaire de venir à ce Workshop avec Roblox Studio d'installé (enfin c'est mieux pour vous, pour pas que vous ne perdiez de temps)
<br>De plus, il vous faudra un compte roblox pour pouvoir acceder a Roblox Studio.
<br>**Pour ce faire, veuillez suivre les instructions présentes [juste ici](https://create.roblox.com/docs/studio/setting-up-roblox-studio#installing-studio).**
<br><br>**Bon Workshop à vous !**

## Section 1 : Prise en main de Roblox Studio

### Tâche 1 : Explorer l'interface de Roblox Studio

Ouvrez Roblox Studio.
<br>Créer votre place, en appuyant sur le "+" et en selectionant un template.
<br>Familiarisez-vous avec l'interface utilisateur, y compris les outils principaux et les onglets comme le Visualiseur, l'Explorateur et les Propriétés.

### Tâche 2 : Créer et manipuler un Part dans l'Explorateur

Insérez un Part simple dans votre espace de travail en utilisant l'onglet "Modèle".
<br>Sélectionnez le Part que vous avez inséré et utilisez la fenêtre des Propriétés pour changer ses attributs, comme la taille, la couleur et la position.

## Section 2 : Apprentissage de la programmation avec Knit dans Roblox

### Tâche 1 : Création d'un Part par Script
- Dans "ServerScriptService", ajouter un scrip qui créer un Part.
- Le Part doit être visible et accessible dans votre **Workspace** au lancement de votre jeu.
- **Référence :** [Creating Parts with Code](https://developer.roblox.com/en-us/api-reference/function/Instance/new)
<br><br>N'oubliez pas de rajouter des Propriétés à votre Part! Certaines Propriétés comme sa position et son parent sont nécessaire à l'affichage de votre Part.
  
### Tâche 2 : Manipulation des Propriétés d'un Part
- Écrivez un script qui change la couleur et la transparence d'un Part existant.
- Utilisez TweenService si vous souhaitez animer la modification des propriétés.
- **Référence :** [Properties of Parts](https://developer.roblox.com/en-us/api-reference/class/Part)
- **Référence :** [TweenService](https://create.roblox.com/docs/fr-fr/reference/engine/classes/TweenService)

### Tâche 3 : Comprendre l'Ancrage et les Collisions
- Créez un script pour alterner l'état d'ancrage d'un Part.
- Ajoutez une interaction pour désactiver les collisions avec d'autres objets.
- **Référence :** [Anchored](https://developer.roblox.com/en-us/api-reference/property/BasePart/Anchored)

### Tâche 4 : Utilisation des Boucles While
- Écrivez un script avec une boucle while pour faire pivoter un Part indéfiniment.
- Assurez-vous d'inclure une condition de sortie sécurisée pour éviter une boucle infinie.
- **Référence :** [Loops](https://developer.roblox.com/en-us/articles/Loops)
<br><br>Si vous souhaitez faire une boucle infinie, n'oubliez pas de limiter les appelles de boucle.

### Tâche 5 : Explorer les Services Roblox
- Utilisez Players pour écrire un script qui envoie un message de bienvenue à chaque joueur qui rejoint le jeu.
- Utilisez le Workspace pour changer l'éclairage global du jeu.
- **Référence :** [Client-Server Model](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent)
- [(Au cas où)](https://create.roblox.com/docs/fr-fr/scripting/events/remote)
- **Référence :** [Services](https://developer.roblox.com/en-us/articles/Loops)

### Tâche 6 : Interaction avec les Événements
- Attachez un événement à un Part pour qu'il réagisse lorsqu'un joueur le touche.
- Le script doit vérifier si c'est bien un joueur qui a touché le Part.
- **Référence :** [Touched Event](https://developer.roblox.com/en-us/api-reference/event/BasePart/Touched)

### Tâche 7 : Comprendre le Modèle Client/Serveur
- Créez un exemple où un script local communique avec un script serveur via RemoteEvent.
- **Référence :** [Client-Server Model](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent)
- [(Au cas où)](https://create.roblox.com/docs/fr-fr/scripting/events/remote)

### Tâche finale

**Objectif :**
Concevoir un mini-jeu "Tapez la Taupe" où le joueur doit cliquer/toucher sur des objets qui apparaissent aléatoirement à divers emplacements pendant un court intervalle de temps.

Des "taupes" (ou un objet équivalent) émergent à intervalles aléatoires de trous sur le terrain.
Le joueur doit cliquer (ou taper) sur les taupes avant qu'elles ne disparaissent pour marquer des points.
Le jeu se termine après un nombre déterminé de taupes apparues, et le score est affiché.


