# MyoCoach : GUI

Ce projet s'inscrit dans le cadre d'un produit développé par la société Orthopus :  [Le MyoCoach](https://wiki.orthopus.com/myocoach/home)

Cette application permet la visualisation des signaux EMG et permet aux utilisateurs de s'entrainer en observant les signaux brut ou à travers un jeux qui est un clone inspiré de [FlapPyBird](https://github.com/sourabhv/FlapPyBird) avec un système de jeux différents.

L'application MyoCoach est codé en python avec PyQt5

## Installation

Testé sous MacOS et Linux.

### 1. Téléchargement des sources

[Téléchargez ce dépôt](https://github.com/orthopus/MyoCoach_GUI/archive/master.zip) et décompressez le dans le répertoire de votre choix. Renommez le dossier `MyoCoach_GUI-master` en `MyoCoach_GUI`.

Il est possible de cloner directement ce dépôt dans le répertoire de votre choix :

```
$ git clone git@github.com:orthopus/MyoCoach_GUI.git
```

### 2. Installation des dépendances

Installer les paquets suivants :
 * [Python](https://www.python.org/downloads) (3.6.x ou supérieur) ;
 * [pip](https://techworm.net/programming/install-pip-python-mac-windows-linux/) (19.0.x ou supérieur) ;

Installer `virtualenv` :
```
$ pip install virtualenv
```

### 3. Installation du programme principal

Dans un terminal, aller dans le dossier `MyoCoach_GUI` et lancer l'installation :

```
$ cd MyoCoach_GUI/
$ make install
```

Cette commande crée un _virtualenv_ et installe les dépendances nécessaires à l'application. Ces dépendances sont listées dans le fichier [requirements.txt](requirements.txt).

### 4. Lancer l'application

```
$ make play
```

## ScreenShot

![Signal Widget](MyoCoach_ScreenShot_Signal.png)
![FlappyBird Widget](MyoCoach_ScreenShot_FlappyBird.png)

## Auteur

* **David Gouaillier** - *Initial work*

## Licence

Ce projet est sous une licence Open Source CC BY-SA 4.0 - regarder le fichier [LICENSE.md](LICENSE.md) pour plus de détails.
