# Task 3 - KMeans Clustering

## Objectif

Cette tâche vise à introduire l'algorithme de clustering KMeans, un algorithme fondamental en machine learning non supervisé pour la découverte de groupes dans les données.

## Contenu

- **KMeans_Clustering.ipynb** : Notebook Jupyter contenant l'implémentation de l'algorithme KMeans
- **data/** : Dossier pour les jeux de données

## Concepts Couverts

1. **Théorie du clustering KMeans** :
   - Concept de clustering non supervisé
   - Algorithme des k-moyennes
   - Initialisation des centroïdes

2. **Implémentation pratique** :
   - Utilisation de scikit-learn
   - Sélection du nombre optimal de clusters (méthode du coude)
   - Évaluation de la qualité du clustering

3. **Visualisation** :
   - Représentation des clusters
   - Position des centroïdes

4. **Évaluation du modèle** :
   - Silhouette score
   - Inertie (within-cluster sum of squares)

## Résultats Attendus

À la fin de cette tâche, vous devriez être capable de :
- Comprendre le concept de clustering non supervisé
- Implémenter l'algorithme KMeans avec scikit-learn
- Déterminer le nombre optimal de clusters
- Évaluer la qualité du clustering obtenu

## Instructions d'Utilisation

1. Placez votre jeu de données dans le dossier `data/`
2. Créez un notebook Jupyter pour l'implémentation
3. Suivez les concepts présentés dans ce README

## Notes

Le clustering KMeans est sensible aux valeurs extrêmes et nécessite une initialisation appropriée des centroïdes. La méthode du coude est souvent utilisée pour déterminer le nombre optimal de clusters.