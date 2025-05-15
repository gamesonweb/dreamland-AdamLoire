[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tcwhlYLU)



# GamesOnWeb - Dreamland

**Auteurs :** Adam Loire, Antoine Bondet

GamesOnWeb est un projet de jeu en 3D développé avec Babylon.js. Ce projet est encore en phase de développement initial et constitue une base pour un jeu d'exploration dans un univers onirique. Le jeu se déroule dans un musée où le joueur peut accéder à différents "rêves" en traversant des portraits téléporteurs.

## 🎯 Objectif du Jeu

Dreamland est un jeu d'exploration dans un univers onirique. Pour l'instant, le joueur peut simplement se déplacer et explorer le musée et les premiers rêves accessibles via les portraits téléporteurs. Un objectif fixe sera bientôt intégré pour donner une mission précise au joueur.

## 🌐 Fonctionnalités Actuelles
- **Lobby - Musée :** Un espace central contenant des portraits téléporteurs.
- **Gravité Personnalisée :** Gestion de la gravité par raycast pour un contrôle plus fin des collisions et des déplacements.
- **Caméra :** Caméra libre avec contrôle à la souris et un offset derrière le joueur.
- **Déplacement Personnalisé :** Système de déplacement basé sur `moveWithCollisions`.
- **Premier Rêve :** Un environnement de test accessible via un portrait téléporteur.
- **Objets 3D :** Modèle de personnage (`MC5.glb`) et objets divers comme des sucettes et gâteaux.

## 🛠️ Structure du Projet
```
├── assets/
│   ├── models/
│   │   └── MC5.glb
│   ├── textures/
│   └── dreams/
├── src/
│   ├── camera.js
│   ├── controls.js
│   ├── main.js
│   ├── map.js
│   └── player.js
├── index.html
```

## 🚀 Fonctionnalités à Venir
- **Nouveaux Rêves :** Ajout de plusieurs environnements thématiques accessibles depuis le musée.
- **Interactions Avancées :** Détection de collision avec les objets pour déclencher des événements spécifiques.
- **Système de Quêtes :** Intégration de missions ou objectifs pour chaque rêve.
- **Effets Visuels :** Particules, transitions de téléportation, effets sonores.
- **Optimisation des Assets :** Réduction des tailles de fichiers et amélioration des textures.

## ✅ Prochaines Étapes
- Créer un système de téléportation plus fluide entre les rêves.
- Ajouter des plateformes supplémentaires pour tester les déplacements et collisions.
- Intégrer une interface utilisateur pour le choix des rêves.

## 📌 Remarque
Ce projet est encore en phase de prototypage. Les fonctionnalités listées sont sujettes à modification au fur et à mesure de l'avancement du développement.
