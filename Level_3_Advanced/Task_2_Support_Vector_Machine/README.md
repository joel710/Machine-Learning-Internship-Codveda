# Task 2 - Support Vector Machine

## Objectif

Cette tâche vise à introduire les machines à vecteurs de support (SVM), un algorithme puissant en machine learning supervisé pour la classification et la régression, basé sur la recherche d'hyperplans optimaux.

## Contenu

- **SVM_Model.ipynb** : Notebook Jupyter contenant l'implémentation du modèle SVM
- **data/** : Dossier pour les jeux de données

## Concepts Couverts

1. **Théorie des SVM** :
   - Hyperplans de séparation
   - Vecteurs de support
   - Marge maximale
   - Noyaux (linéaire, polynomial, RBF)

2. **Implémentation pratique** :
   - Utilisation de scikit-learn
   - Choix du noyau approprié
   - Réglage des hyperparamètres (C, gamma)

3. **Prétraitement** :
   - Importance de la normalisation des données
   - Gestion des classes déséquilibrées

4. **Évaluation du modèle** :
   - Comparaison des différents noyaux
   - Analyse de la frontière de décision

## Résultats Attendus

À la fin de cette tâche, vous devriez être capable de :
- Comprendre le concept des machines à vecteurs de support
- Implémenter un modèle SVM avec scikit-learn
- Choisir le noyau approprié selon le problème
- Optimiser les hyperparamètres du modèle

## Instructions d'Utilisation

1. Placez votre jeu de données dans le dossier `data/`
2. Créez un notebook Jupyter pour l'implémentation
3. Suivez les concepts présentés dans ce README

## Notes

Les SVM sont efficaces dans des espaces de grande dimension et sont polyvalents grâce aux différents types de noyaux. Ils fonctionnent mieux avec des données normalisées et peuvent être sensibles aux paramètres.