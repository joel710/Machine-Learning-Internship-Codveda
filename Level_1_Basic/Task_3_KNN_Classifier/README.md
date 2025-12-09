# Task 3 - KNN Classifier

## Objectif

Cette tâche vise à introduire l'algorithme du K-Nearest Neighbors (KNN), un classifieur non-paramétrique simple mais efficace en machine learning supervisé.

## Contenu

- **KNN_Classifier.ipynb** : Notebook Jupyter contenant l'implémentation du classifieur KNN
- **data/** : Dossier pour les jeux de données
- **requirements.txt** : Liste des bibliothèques Python nécessaires (hérité de la tâche précédente)

## Concepts Couverts

1. **Théorie du KNN** :
   - Principe des voisins les plus proches
   - Distance euclidienne
   - Classification par vote majoritaire

2. **Implémentation pratique** :
   - Utilisation de scikit-learn
   - Normalisation des données (importante pour KNN)
   - Entraînement du classifieur

3. **Évaluation du modèle** :
   - Précision (accuracy)
   - Rapport de classification
   - Matrice de confusion

4. **Optimisation** :
   - Sélection du nombre optimal de voisins (k)
   - Impact de k sur la performance

## Résultats Attendus

À la fin de cette tâche, vous devriez être capable de :
- Comprendre le concept du classifieur KNN
- Implémenter un classifieur KNN avec scikit-learn
- Normaliser les données pour améliorer la performance
- Évaluer la performance du classifieur
- Optimiser le paramètre k
- Interpréter les matrices de confusion

## Instructions d'Utilisation

1. Installez les dépendances (si pas déjà fait) :
   ```
   pip install -r ../Task_1_Data_Preprocessing/requirements.txt
   ```

2. Placez votre jeu de données dans le dossier `data/`

3. Ouvrez le notebook Jupyter :
   ```
   jupyter notebook KNN_Classifier.ipynb
   ```

4. Suivez les instructions dans le notebook et adaptez le code à votre jeu de données

## Bibliothèques Utilisées

- **pandas** : Manipulation et analyse des données
- **numpy** : Calcul numérique
- **matplotlib & seaborn** : Visualisation des données
- **scikit-learn** : Implémentation du classifieur KNN et évaluation

## Notes

Le KNN est sensible à l'échelle des données, c'est pourquoi la normalisation est importante. Le choix de k est crucial : une valeur trop petite peut rendre le modèle sensible au bruit, tandis qu'une valeur trop grande peut lisser excessivement les frontières de décision.