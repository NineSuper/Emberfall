![Emberfall](./imgs/Emberfall.png)

**Emberfall** est un projet de jeu multijoueur **top-down** que je développe pour m'initier à **Godot** et réaliser mon rêve de créer un petit jeu amusant à jouer entre amis.

Ce jeu se déroulera dans un monde post-apocalyptique infesté de zombies, où les joueurs devront coopérer pour survivre à des ennemis de plus en plus coriaces au fil de leur aventure.

👽 Inspiré de **Project Zomboid** et **Dead Ahead: Zombie Warfare**.

## 🛠️ Fonctionnalités

🌟 Vue de dessus avec effets de lumière dynamiques. </br>
🎮 Support multijoueur. </br>
🧟‍♂️ Vagues d'ennemis. </br>
🎮 Contrôles du joueur. </br>
⚙️ Menu d'options pour les configurations de touches, affichage et audio. </br>


## 📅 Roadmap
> [!IMPORTANT]
> Toute la base du jeu, ainsi que son univers, est en train d'être refondée.


#### 🖥️ Menus et Interfaces :
	🌐 Écran d'Accueil :
	 [✅] Création d'un écran d'accueil
	 [🚧] Faire tous les onglets
  
	🕹️ Menu de Jeu :
	 [🚧] Faire un menu de jeu
	 [🚧] Mise en place des options (graphique/audio/options/touches)
 
#### 👥 Intégration des Amis et Serveurs :
    [✅] Intégration d'amis Steam en direct/en jeu
    [✅] Visualisation des serveurs en ligne
    [✅] Permettre aux utilisateurs de créer leur propre serveur :
	    - [🚧] Permettre aux utilisateurs de mettre un mot de passe
 	    - [❌] Permettre aux utilisateurs d'être sur la même partie
	    - [❌] Mettre un logo de serveur par défaut si l'utilisateur ne choisit pas d'image
	    - [❌] Mettre une liste de logos de serveur par défaut
    [❌] Implémentation de l'invitation/rejoindre un ami/serveur
    [❌] Permettre aux joueurs non-Steam de créer un compte avec pseudo et photo de profil
#### 🎮 Gameplay :
	🏙️ Environnements :
 	 [❌] Faire la ville d'Embervalle
   
	🎭 Personnages et Entités :
 	 [❌] Refaire tous les squelettes du jeu (Joueur/Ennemis/Items/etc.)
	 [❌] Revoir les mécaniques du joueur à partir de zéro
	 [❌] Développer la classe abstraite pour les ennemis/items/armes
	 [❌] Créer différentes armes avec leurs propres propriétés
	 [❌] Ajout d'items au sol (Armes/pièces/etc.)
	 [❌] Système de lumière autour du joueur
 	
	⚒️ Autres:
	 [❌] Ajouter un HUD au gameplay
#### 🔊 Audio :
	[❌] Ajouter de la musique et des effets sonores (SFX)
#### 🔨 Système et Fonctionnalités :
	🛡️ Gestion des Serveurs :
	 [🚧] Expulser les joueurs du serveur si l'Owner se déconnecte
 
	💾 Sauvegardes :
	 [❌] Revoir les sauvegardes de paramètres et de parties pour une meilleure compatibilité
	 [❌] Mise en place de sauvegarde des paramètres
	 [❌] Mise en place de sauvegarde des parties

## 🌳 Arborescence des fichiers

```
MonProjet/
├── entities/                     # Dossier principal pour les entités
│   ├── NecroNight/
│   ├── Viking/
│   └── PoulDead/
│
├── player/                       # Dossier pour le joueur
│   ├── sprites/
│   ├── audio/
│   ├── Player.tscn
│   └── Player.gd
│
├── items/                        # Dossier pour les items
│   ├── sprites/
│   ├── audio/
│   ├── Item1.tscn
│   └── Item1.gd
│
├── weapons/                      # Dossier pour les armes
│   ├── sprites/
│   ├── audio/
│   ├── Weapon1.tscn
│   └── Weapon1.gd
│
├── menus/                        # Dossier pour les menus et l'interface utilisateur
│   ├── sprites/
│   ├── audio/
│   ├── MainMenu.tscn
│   └── MainMenu.gd
│
├── scenes/                       # Scènes principales et niveaux
│   ├── main/
│   └── levels/
│
├── scripts/                      # Autres scripts généraux
│   ├── managers/
│   └── UI/
│
├── autoload/                     # Scripts ou scènes à charger en singleton
│   ├── Global.gd                 # Script autoload pour la gestion des données globales
│   └── SaveManager.gd            # Script pour la gestion des sauvegardes
│
├── save_data/                    # Dossier pour les fichiers de sauvegarde
│   ├── player_save.json          # Fichier de sauvegarde pour les données du joueur
│   ├── game_save.json            # Fichier de sauvegarde pour les données du jeu (niveau, etc.)
│   └── settings.cfg              # Fichier de configuration pour les paramètres du jeu
│
└── resources/                    # Fichiers ressource spécifiques à Godot
    ├── materials/
    └── prefabs/
```


## 👀 Aperçu actuel 
> [!IMPORTANT]
> Le gameplay ainsi que le style graphique ne sont plus les mêmes à ce jour !

![exemple](./gif/Exemple.gif)

### 📝 Auteur
- 🎫 [@NineSuper](https://www.github.com/NineSuper)
