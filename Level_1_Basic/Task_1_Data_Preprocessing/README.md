# Task 1 - Data Preprocessing

## Objectif

Cette tâche vise à introduire les techniques essentielles de prétraitement des données, une étape fondamentale dans tout projet de machine learning.

## Contenu

- **Data_Preprocessing.ipynb** : Notebook Jupyter contenant les étapes de prétraitement des données
- **requirements.txt** : Liste des bibliothèques Python nécessaires
- **data/** : Dossier pour les jeux de données brutes

## Concepts Couverts

1. **Exploration des données** :
   - Chargement des données avec pandas
   - Analyse descriptive des données
   - Identification des types de variables

2. **Traitement des valeurs manquantes** :
   - Détection des valeurs manquantes
   - Stratégies de remplacement (moyenne, médiane, suppression)

3. **Encodage des variables catégorielles** :
   - Label Encoding
   - One-Hot Encoding (concept)

4. **Normalisation et standardisation** :
   - Mise à l'échelle des caractéristiques
   - Utilisation de StandardScaler

5. **Division des données** :
   - Création des ensembles d'entraînement et de test

## Résultats Attendus

À la fin de cette tâche, vous devriez être capable de :
- Charger et explorer un jeu de données
- Identifier et traiter les valeurs manquantes
- Encoder les variables catégorielles
- Normaliser les données numériques
- Diviser les données en ensembles d'entraînement et de test

## Instructions d'Utilisation

1. Installez les dépendances :
   ```
   pip install -r requirements.txt
   ```

2. Placez votre jeu de données dans le dossier `data/`

3. Ouvrez le notebook Jupyter :
   ```
   jupyter notebook Data_Preprocessing.ipynb
   ```

4. Suivez les instructions dans le notebook et adaptez le code à votre jeu de données

## Bibliothèques Utilisées

- **pandas** : Manipulation et analyse des données
- **numpy** : Calcul numérique
- **matplotlib & seaborn** : Visualisation des données
- **scikit-learn** : Prétraitement des données et division des ensembles

## Notes

Le notebook est conçu de manière générique et peut être adapté à différents jeux de données en modifiant simplement le chemin du fichier de données.