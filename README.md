# 🌿 LYWL TECH 256 – Aventure dans la jungle

### Jeu vidéo 2D | Endless Runner | Python & Pygame

##  1. Présentation du projet

**Aventure dans la jungle** est un jeu vidéo 2D de type *Endless Runner*, développé dans un univers de jungle vivant et immersif.

Le joueur contrôle un personnage qui avance automatiquement. Son objectif est de survivre le plus longtemps possible en évitant les obstacles et en obtenant le meilleur score.

Ce projet a été réalisé dans le cadre d'un projet universitaire de deuxième année de Licence Informatique (L2), au sein du groupe **LYWL TECH**.

##  2. Objectifs pédagogiques

Ce projet nous a permis de mettre en pratique plusieurs compétences :

- Programmation orientée objet (POO).
- Développement de jeux vidéo 2D.
- Gestion des événements et des interactions.
- Détection des collisions.
- Gestion du score et des sauvegardes.
- Travail collaboratif avec Git et GitLab.
- Organisation d'un projet informatique.

##  3. Équipe du projet

| Membre | Contributions |
|---|---|
| Louis D | Gameplay, logique du jeu, collisions et score |
| Wijdane | Graphismes, sprites, décors et direction artistique |
| Yousra | Menus, audio, paramètres et gestion du son |

**Encadrement pédagogique :** M. BAURMAUD Anthony.

##  4. Univers et direction artistique

Le jeu propose une aventure dans une jungle mystérieuse.

- Thème : Jungle.
- Ambiance : Aventure et nature.
- Style graphique : Illustrations 2D.
- Décors : Forêt animée et sol défilant.
- Obstacles : Lapins et oiseaux.

##  5. Fonctionnalités

### Gameplay
- Déplacement automatique du personnage.
- Animation de course.
- Saut et glissade.
- Génération aléatoire des obstacles.
- Détection des collisions.
- Score en temps réel.
- Sauvegarde des meilleurs scores.

### Interface et audio
- Menu principal.
- Menu pause.
- Menu paramètres.
- Musique et effets sonores.
- Réglage du volume.

##  6. Commandes du jeu

| Touche | Action |
|---|---|
| ESPACE | Sauter |
| S | Glisser |
| ÉCHAP | Mettre en pause |

La difficulté augmente progressivement au cours de la partie.

##  7. Système d'obstacles

Deux types d'obstacles sont intégrés :

- **Lapin :** obstacle terrestre qui nécessite un saut.
- **Oiseau :** obstacle aérien qui nécessite généralement une glissade.

Les obstacles apparaissent de manière aléatoire afin de renouveler les parties.

##  8. Architecture technique

Le projet repose sur une architecture modulaire :

| Fichier | Rôle |
|---|---|
| `main.py` | Point d'entrée du jeu |
| `init.py` | Gestionnaire du jeu et des états |
| `game.py` | Logique principale |
| `player.py` | Gestion du joueur, du sol et du background |
| `obstacle.py` | Obstacles et collisions |
| `menu.py` | Menu principal |
| `pause.py` | Menu pause |
| `parametre.py` | Paramètres du jeu |

##  9. Technologies utilisées

- **Python** : langage de programmation.
- **Pygame** : bibliothèque de développement de jeux vidéo 2D.
- **Git** : gestion de versions.
- **GitLab** : collaboration et gestion du code source.
- **Programmation orientée objet** : organisation du code.

##  10. Installation et lancement

### Prérequis

- Python 3 installé.
- PIP disponible.

### Installation

Cloner le repository :

```bash
git clone URL_DU_REPOSITORY
```

Accéder au dossier :

```bash
cd endlessrunner
```

Installer Pygame :

```bash
pip install pygame
```

Lancer le jeu :

```bash
python main.py
```

## 11. Structure du projet

```text
endlessrunner/
│
├── assets/
├── game.py
├── player.py
├── obstacle.py
├── menu.py
├── pause.py
├── parametre.py
├── init.py
├── main.py
└── README.md
```

##  12. Gestion de versions et collaboration

Le développement a été organisé avec Git et GitLab.

Les pratiques utilisées comprennent :

- Gestion des versions.
- Branches de développement.
- Merge Requests.
- Collaboration entre les membres de l'équipe.

##  13. Informations sur le projet

- **Nom :** LYWL TECH 256
- **Projet :** Aventure dans la jungle
- **Type :** Projet universitaire
- **Niveau :** L2 Informatique
- **Année :** 2025–2026
- **Version :** 1.0
- **Statut :** Terminé

##  14. Licence et droits

Projet universitaire réalisé en équipe.

Les droits sur le code, les graphismes, les musiques et les ressources utilisées doivent être vérifiés auprès des contributeurs avant toute redistribution.

---

🌿 **LYWL TECH – Game Development: Jungle Edition** 🌿
