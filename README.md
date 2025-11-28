# 🧬 Jeu de la Vie

Projet réalisé par **David Antoine**, **Leslie Ocloo** et **Michèle Marques**.

---

## 📌 Présentation

Le **jeu de la vie** se joue sur une grille. Chaque case est occupée par une cellule qui peut être
vivante ou morte. À chaque génération, chaque cellule peut naître, mourir, ou rester dans
son état. Les règles qui permettent de passer d'une génération à l'autre sont précises et ont
été choisies avec soin pour que l'évolution des organismes soit intéressante et semble
imprévisible.

---

## 📘 Règles du Jeu

En premier lieu, notons que sur une grille, chaque case a exactement huit voisins. Les règles
du jeu de la vie sont les suivantes :

### 🔵 Survie
- **une cellule vivante** ayant exactement **2 ou 3 voisins vivants** survit à la génération
suivante 

### 🔴 Mort
- **une cellule vivante** ayant de **4 à 8 cellules voisines vivantes** meurt d'étouffement à la
génération suivante ;  
- **une cellule vivante** ayant **zéro ou une cellule voisine vivante** meurt d'isolement à la
génération suivante ;

### 🟢 Naissance
- sur **une case vide** ayant exactement **3 voisins vivants**, une cellule naîtra à la
génération suivante

### ⚠️ Important
La nouvelle génération doit être calculée **à partir de l’état complet de la génération actuelle**,  
puis mise à jour **uniquement après analyse de toute la grille**.

---

## 🎯 Objectifs du Projet

- Implémenter les règles du Jeu de la vie.
- Mettre à jour la grille génération après génération.
- Afficher visuellement l’évolution de l’automate.
- Étudier les motifs célèbres (oscillateurs, motifs stables, vaisseaux…).
- Mettre en place une interface graphique pour visualiser et interagir avec le jeu.

