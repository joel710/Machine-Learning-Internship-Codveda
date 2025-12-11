# Task 2 - Linear Regression

## Objectif

Cette tâche vise à introduire l'algorithme de régression linéaire, l'un des modèles les plus simples mais les plus importants en machine learning supervisé pour les problèmes de régression.

## Contenu

- **Linear_Regression_Model.ipynb** : Notebook Jupyter contenant l'implémentation du modèle de régression linéaire
- **data/** : Dossier pour les jeux de données
- **requirements.txt** : Liste des bibliothèques Python nécessaires

## Concepts Couverts

1. **Théorie de la régression linéaire** :
   - Modèle linéaire univarié
   - Équation de la droite de régression
   - Méthode des moindres carrés

2. **Implémentation pratique** :
   - Utilisation de scikit-learn
   - Entraînement du modèle
   - Prédiction sur de nouvelles données

3. **Évaluation du modèle** :
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - Coefficient de détermination (R²)

4. **Visualisation** :
   - Graphique de la ligne de régression
   - Analyse des résidus
   - Distribution des erreurs

## Résultats Attendus

À la fin de cette tâche, vous devriez être capable de :
- Comprendre le concept de régression linéaire
- Implémenter un modèle de régression linéaire avec scikit-learn
- Évaluer la performance du modèle
- Interpréter les métriques d'évaluation
- Visualiser les résultats et les résidus

## Instructions d'Utilisation

1. Installez les dépendances :
   ```
   pip install -r requirements.txt
   ```

2. Placez votre jeu de données dans le dossier `data/`

3. Ouvrez le notebook Jupyter :
   ```
   jupyter notebook Linear_Regression_Model.ipynb
   ```

4. Suivez les instructions dans le notebook et adaptez le code à votre jeu de données

## Bibliothèques Utilisées

- **pandas** : Manipulation et analyse des données
- **numpy** : Calcul numérique
- **matplotlib & seaborn** : Visualisation des données
- **scikit-learn** : Implémentation du modèle de régression linéaire et évaluation

## Notes sur les Versions

Les bibliothèques sont spécifiées avec des versions minimales compatibles avec Python 3.13. Si vous utilisez une version plus ancienne de Python, vous pouvez ajuster les versions dans le fichier requirements.txt.

## Notes

Le notebook utilise une approche générique pour sélectionner les variables, mais vous pouvez le modifier pour choisir spécifiquement vos variables d'intérêt. La régression linéaire ne fonctionne bien que si une relation linéaire existe entre les variables.