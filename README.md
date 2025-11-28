# Jeu-de-la-vie

Le jeu de la vie se joue sur une grille. Chaque case est occupée par une cellule qui peut être
vivante ou morte. À chaque génération, chaque cellule peut naître, mourir, ou rester dans
son état. Les règles qui permettent de passer d'une génération à l'autre sont précises et ont
été choisies avec soin pour que l'évolution des organismes soit intéressante et semble
imprévisible.
En premier lieu, notons que sur une grille, chaque case a exactement huit voisins. Les règles
du jeu de la vie sont les suivantes :
 une cellule vivante ayant exactement 2 ou 3 voisins vivants survit à la génération
suivante ;
 une cellule vivante ayant de 4 à 8 cellules voisines vivantes meurt d'étouffement à la
génération suivante ;
 une cellule vivante ayant zéro ou une cellule voisine vivante meurt d'isolement à la
génération suivante ;
 sur une case vide ayant exactement 3 voisins vivants, une cellule naîtra à la
génération suivante.
Notons que c'est l'ensemble de la génération actuelle qui doit être pris en compte pour
l'établissement de l'état des cellules à la génération suivante.
