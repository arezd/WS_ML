# ANAP


Critère de Performance

Le critère de performance des contributions des participants est le RMSE (Root Mean Square Error).

Il s'agit de la racine carrée de la moyenne arithmétique des carrés des écarts entre les prévisions et les valeurs cibles détenues.
Il est utilisé comme suit :

    le jeu de données est séparé en un jeu de données d'entraînement et un jeu de données de test
    la variable cible est communiquée avec le jeu de données d'entraînement, elle est tenue confidentielle
    pour le jeu de données de test
    le jeu de données de test est séparé en une partie publique et une partie privée
    le score (RMSE) entre contribution et variable cible détenue est fourni au fil de l'eau pour la partie publique,
    pas pour la partie privée
    le score (RMSE) entre contribution et variable cible détenue sur la partie privée sert de score final pour déterminer
    les trois premiers concurrents
    sous réserve de fraude détectée, les trois premiers concurrents sont invités à fournir leurs modèles (documentation, code)
    le classement final est déterminé par l'ANAP en fonction de l'analyse des modèles proposés, avec comme critères principaux 
    la pertinence, la clarté et la reproductibilité.

Format du fichier à fournir

Le fichier de résultats à fournir est un fichier au format .csv, comportant sur chaque ligne l'identifiant de ligne
et les valeurs futures estimées de la variable cible pour les années du jeu de données de test.

  

