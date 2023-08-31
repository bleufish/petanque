# petanque
Gestion sous Microsoft Excel d'un tournois en ronde suisse pour la pétanque.

Le tournois se joue en 4 parties avec un appariement en ronde suisse jusqu'a 32 équipes.  Une équipe rencontrent de préférence une autre équipe du même niveau si elle ne l'a pas déjà rencontrée et que d'autre équipe sont disponibles. 

## Description
Le classeur est composé de 4 onglets :
- Aide
- Equipes : contient la liste des équipes
- Rencontres : composé de 2 tableau :
    - Rencontres : permet de définir les rencontres entre équipe, soit en saisissant manuellement les rencontres oi en cliquant sur le bouton Tirage Partie.
    - Résultats : permet de saisir les point de chaque équipes.
- Tableau de bord : affiche le suivi et le classement (colonne Rang).

## Mode d'emploi
* entrer le nom des équipes dans l'onglet Equipes.
* dans l'onglet Rencontre, cliquer sur le bouton Tirage Partie pour calculer les rencontres entre équipe. Pour la première partie, l'appariement est effectué au hasard. Pour les autres partie, les rencontres sont calculées en faisant rencontrer les équipes proches au classement et qui ne se sont pas déjà rencontrées (si possible).
* saisir le résultat des rencontres dans le tableau résultat de l'onglet Rencontres
* l'onglet Tableau de bord affiche un récapitulatif des rencontres, il est possible de classer ce tableau en cliquant sur la flèche de la colonne sur laquelle on veut trier
	
__Remarques__ :	
- Si le nombre d'équipes est impair, une équipe nommé 'toujours perdant' est créée. Il faudra lui attribuer automatiquement une défaite (0 - 13).
- La répartition des équipes (tableau Rencontres de l'onglet Rencontres) peut être saisie manuellement à la place d'être calculée par le bouton 'Tirage Partie'.


