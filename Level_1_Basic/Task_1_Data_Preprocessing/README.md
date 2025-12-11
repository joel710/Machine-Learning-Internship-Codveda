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
   - Visualisation des distributions

2. **Traitement des valeurs manquantes** :
   - Détection des valeurs manquantes (y compris les caractères spéciaux comme '?')
   - Stratégies de remplacement (moyenne, médiane, mode, suppression)
   - Gestion des valeurs manquantes codées de manière non-standard

3. **Détection et traitement des valeurs aberrantes** :
   - Méthode IQR (Interquartile Range)
   - Visualisation des outliers
   - Techniques de traitement (winsorization)

4. **Encodage des variables catégorielles** :
   - Label Encoding
   - One-Hot Encoding (concept)

5. **Normalisation et standardisation** :
   - Mise à l'échelle des caractéristiques
   - Utilisation de StandardScaler

6. **Division des données** :
   - Création des ensembles d'entraînement et de test

7. **Visualisation avancée** :
   - Matrice de corrélation
   - Matrice de confusion (illustration)

## Résultats Attendus

À la fin de cette tâche, vous devriez être capable de :
- Charger et explorer un jeu de données
- Identifier et traiter les valeurs manquantes
- Détecter et traiter les valeurs aberrantes
- Encoder les variables catégorielles
- Normaliser les données numériques
- Diviser les données en ensembles d'entraînement et de test
- Créer des visualisations pertinentes des données
- Interpréter les matrices de corrélation et de confusion

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

## Notes sur les Versions

Les bibliothèques sont spécifiées avec des versions minimales compatibles avec Python 3.13. Si vous utilisez une version plus ancienne de Python, vous pouvez ajuster les versions dans le fichier requirements.txt.

## Notes

Le notebook est conçu de manière générique et peut être adapté à différents jeux de données en modifiant simplement le chemin du fichier de données.

Il est important de toujours vérifier les différentes façons dont les valeurs manquantes peuvent être représentées dans un dataset (NaN, '?', '', 'None', etc.) car cela affecte directement la qualité du prétraitement des données.