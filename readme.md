Guide d'utilisation pour exécuter le Jupyter Notebook
=====================================================

Ce guide présente les étapes nécessaires pour exécuter le Jupyter Notebook fourni dans ce répertoire.

Prérequis
---------

- Avoir une version de Python installée sur votre machine
- Avoir sélectionné un environnement Jupyter

Installation des packages nécessaires
-------------------------------------

Pour exécuter le notebook, il est nécessaire d'installer certains packages Python. Vous pouvez le faire en utilisant les commandes suivantes :

`pip install -U scikit-learn`
`pip install seaborn`
`pip install xgboost`

Exécution du notebook
---------------------

Une fois que les packages sont installés, vous pouvez exécuter le notebook en ouvrant le fichier `Projet_Machine_Learning.ipynb` dans Jupyter Notebook.

Prédiction de données
---------------------

Si vous souhaitez prédire des données, vous pouvez exécuter le fichier `Projet_Machine_Learning_trained_models.ipynb` dans Jupyter Notebook.

Nous avons sauvegardé nos deux modèles les plus performants (un pour la regression et un pour la classification)

Vous pouvez saisir des features de maisons de deux façons différentes :

- Si vous souhaitez prédire le prix d'une maison uniquement, vous pouvez remplir les caractéristiques nécessaires de cette maison dans le np.array des cellules associées aux modèles

- Si vous souhaitez prédire le prix de plusieurs maisons, vous pouvez remplir le fichier data_to_predict.csv dans le dossier data, puis exécuter les cellules associées aux modèles

Un fichier `data_description.txt` est à votre disposition pour séléctionner les valeurs de caractéristiques pour estimer le prix de votre/vos maison(s).

Bonnes prédictions!
