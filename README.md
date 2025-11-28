# 🧬 Jeu de la Vie — Conway's Game of Life

Projet réalisé par **David Antoine**, **Lesli Ocloo** et **Michèle Marques**.

---

## 📌 Présentation

Le **Jeu de la vie** est un automate cellulaire imaginé par le mathématicien **John Conway**.  
Il se déroule sur une grille où chaque case représente une cellule pouvant être **vivante** ou **morte**.  
À chaque génération, les cellules évoluent selon des règles simples mais capables de produire des comportements complexes, parfois imprévisibles.

---

## 📘 Règles du Jeu

Chaque cellule possède **8 voisins** : horizontalement, verticalement et en diagonale.  
Les règles qui déterminent l’évolution de la grille sont :

### 🔵 Survie
- Une **cellule vivante** ayant **exactement 2 ou 3 voisins vivants** survit.

### 🔴 Mort
- 4 à 8 voisins vivants → la cellule **meurt d'étouffement**.  
- 0 ou 1 voisin vivant → la cellule **meurt d'isolement**.

### 🟢 Naissance
- Une **cellule morte** entourée de **exactement 3 voisins vivants** devient vivante.

### ⚠️ Important
La nouvelle génération doit être calculée **à partir de l’état complet de la génération actuelle**,  
puis mise à jour **uniquement après analyse de toute la grille**.

---

## 🎯 Objectifs du Projet

- Implémenter les règles du Jeu de la vie.
- Mettre à jour la grille génération après génération.
- Afficher visuellement l’évolution de l’automate.
- Étudier les motifs célèbres (oscillateurs, motifs stables, vaisseaux…).

---

## 📂 Structure du projet (exemple)

