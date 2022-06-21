TL;DR:
*iPython notebooks pour la partie "Programmation fonctionnelle" du cours INF4083 Langages de Programmation (UQO)*

# Introduction à la programmation fonctionnelle
## Concept
En programmation impérative, on conceptualise un programme comme une séquence d'affectations qui modifient des variables en mémoire. On utilise des branchements conditionnels et des boucles pour sauter ou répéter des opérations.

En programmation fonctionnelle, on conceptualise un programme comme une série de fonctions, qui prennent des données en entrée et retournent de nouvelles données en sortie. Pour obtenir la fonctionnalité désirée, on compose ces fonctions entre elles.

## Principes:

+ Données immuables: on évite de modifier la valeur des données, on en crée plutôt de nouvelles
+ Éliminer les séquences d'instructions et privilégier celles dont l'ordre d'exécution est indifférent
+ Utiliser des expressions conditionnelles à la place d'instructions conditionnelles
+ Pour les calculs en plusieurs étapes, privilégier la composition de fonctions
+ Élimination des boucles, avec plusieurs techniques pour les remplacer:
  + Récursivité plutôt qu'itération
  + Usage de map/reduce/filter
  + Création de listes et dictionnaires à l'aide d'expressions
  
## Bénéfices:

+ Programmes plus faciles à paralléliser
+ Conception plus "déclarative" des programmes (quoi faire plutôt que comment le faire) => programmes plus concis et programmeurs plus productifs
+ Amélioration de la vérification:
  + Meilleures possibilités de raisonner mathématiquement sur un programme
  + Il est plus facile de tester des fonctions que des blocs d'instructions quelconques

## Techniques clés: 
*Pour chaque technique, voir le notebook correspondant (cliquer sur le fichier ci-dessus)*

+ [[https://github.com/ntartania/INF4083_notebooks/blob/master/ExpressionsConditionnelles.ipynb | Expressions conditionnelles]]
+ Récursivité et récursivité terminale
  + *En particulier, manipulation de listes par des fonctions récursives*
+ Fonctions de première classe:
  + manipulation directe de fonctions à l'aide de variables et d'expressions fonctionnelles
  + fonctions d'ordre supérieur: fonctions passées en entrée/sortie d'autres fonctions
  + parmi les fonctions d'ordre supérieur, voir notamment map-reduce-filter

Voir aussi le notebook "Solutions des exercices"

