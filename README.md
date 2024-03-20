#Boston Houses Project


>  project **Boston Housing** :
    - nous lançons le projet en utilisant toutes les "feature" fournies, puis nous entraînons le modèle. Toutes les notes sont écrites dans le fichier "first_training.ipynb"
    - le le score du project pour la premiere execution est 73%
    - MAE: 3.5965040304338713
    - MSE: 23.6996604511815
    - RMSE: 4.8682297040280975

    * pour optimiser le modele
    
        - le premiere option : "polynomial feature " mais c'est un concept tres avance
        - le deuxieme option : "scale" 
        - le troisieme option : retire les colonne qui aucune effect sur colonne **medv** , j'ai test 3 colonne mais aucune result optimise 


            * mais a la fin j'ai choisi l'option "scale", Vous trouverez le résultat dans "opt_training.ipynb".
