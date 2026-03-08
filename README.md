# ♟️ Pente en C

> Implémentation en langage C du jeu de **Pente**, un jeu de stratégie à deux joueurs sur une grille **19x19**, avec gestion des captures, des alignements gagnants et des cas particuliers comme l’abandon ou le match nul.

## ✨ Aperçu

Ce projet a été réalisé dans le cadre d’un projet d’algorithmique et de programmation en C.  
L’objectif est de proposer une version console complète du jeu **Pent**, jouable à deux joueurs, avec respect des principales règles du jeu.

## 📌 Fonctionnalités

- ✅ Plateau **19x19**
- ✅ Affichage du plateau dans le terminal
- ✅ Saisie des coups au format `ligne,colonne`
- ✅ Vérification des coups invalides
- ✅ Détection des alignements de **5 pions ou plus**
- ✅ Détection des **captures** de pions
- ✅ Victoire par **alignement**
- ✅ Victoire par **captures**
- ✅ Gestion de l’**abandon**
- ✅ Gestion du **match nul**
- ✅ Fichiers de test pour différents scénarios

## 🧠 Règles prises en charge

Le programme gère les règles suivantes :

- Un joueur gagne s’il aligne **au moins 5 pions**
- Un joueur gagne aussi s’il capture **10 pions adverses**
- Une capture a lieu lorsqu’un motif du type  
  `joueur - adversaire - adversaire - joueur`  
  est formé dans une direction valide
- Un joueur peut abandonner en saisissant `0,0`

## 🛠️ Technologies utilisées

- **Langage :** C
- **Bibliothèques :** bibliothèque standard C
- **Compilation :** GCC
- **Exécution :** terminal / console

## 📂 Structure du projet

```bash
.
├── projet.c
├── rapport.pdf
├── match_nul.txt
├── victoire_X_capture.txt
├── victoire_O_capture.txt
├── victoire_X_allignement.txt
├── victoire_O_allignement.txt
├── abondon_joueur_X.txt
└── abondon_joueur_0.txt
