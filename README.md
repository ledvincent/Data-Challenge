# Data-Challenge
Data Challenge concernant la prédiction du type de végétation en forêt et la prédiction de pourboires

Ce répertoire Github contient deux répertoires pour chaque sujet d'étude. 
Les notebooks intitulés forest_pred.ipynb et taxi_pred.ipynb sont les fichiers Jupyter Notebook originaux sur lequel tout le travail était fait.

Pour une meilleure organisation et compréhension, chaque sujet dispose de son propre répertoire.
Les graphiques et résultats sont présentés dans les notebooks, de sorte que aucune exécution n'est nécessaire.

## Structure du répertoire:

Le répertoire comprend 4 jupyter notebook correspondant aux étapes suivis durant l'étude.
1. **Préparation des données et analyse exploratoire des données** : Chargement des données, gestion des valeurs manquantes et transformations initiales. Visualisation et statistiques descriptives pour comprendre la distribution des variables.
2. **Entraînement préliminaire**: Évaluation et comparaison des performances de certains modèles.
3. **Ingénierie des caractéristiques** : Création de nouvelles variables et transformations pour améliorer la qualité des prédictions.
4. **Entraînement et validation des modèles** : Optimisation des hyperparamètres pour des modèles spécifiques. Prédiction sur les données test.

## Instructions pour charger les données

**Sujet Classification:**
Mettre les données csv dans un dossier nommé "forest" et l'inclure dans le répertoire contenant le notebook.

Ex: 
Répertoire principal:  "folder/"
notebook.ipynb -> folder/notebook.ipynb
forest/test.csv  ->   folder/forest/test.csv

**Sujet Régression:**
Mettre les données parquet dans un dossier nommé "taxi" et l'inclure dans le répertoire contenant le notebook.

Ex: 
Répertoire principal:  "folder/"
notebook.ipynb -> folder/notebook.ipynb
taxi/test.csv  ->   folder/taxi/test.csv

Le sujet de régression contient également des modèles fine-tuner pour réutilisation.
