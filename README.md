# Analyse et Prédiction du Churn Client dans le Secteur des Télécommunications

## Description
Ce projet vise à analyser le comportement des clients d’un opérateur télécom et à **prédire la résiliation (Churn)** à l’aide de techniques de **Machine Learning**.  
L’objectif est d’identifier les clients à risque afin d’aider l’entreprise à mettre en place des actions de rétention.

##  Objectif
- **Churn = 1** : le client résilie son contrat  
- **Churn = 0** : le client reste

##  Étapes du projet
1. **Prétraitement des données**
   - Nettoyage (valeurs manquantes, doublons)
   - Encodage des variables catégorielles
   - Normalisation/Standardisation (important pour KNN, SVM, etc.)

2. **Exploration & Visualisation**
   - Statistiques descriptives
   - Analyse des distributions
   - Corrélations
   - Comparaison churn vs non churn

3. **Modélisation Machine Learning**
   - Séparation train/test
   - Entraînement de plusieurs modèles (ex : KNN, Logistic Regression, Random Forest, etc.)
   - Ajustement des hyperparamètres (ex : choix de K pour KNN)

4. **Évaluation**
   - Matrice de confusion
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC (si utilisé)
   - Comparaison globale des modèles

5. **(Optionnel) Déploiement / Interface**
   - Application interactive pour tester des prédictions (ex : Streamlit / Tkinter)

##  Technologies utilisées
- Python
- Pandas, NumPy
- Matplotlib / Seaborn
- Scikit-learn
- (Optionnel) Streamlit / Tkinter

##  Structure du projet (exemple)
