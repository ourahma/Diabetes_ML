# Diabetes ML  
Un projet de Machine Learning utilisant **KNeighborsClassifier** pour prédire si une personne est diabétique ou non en se basant sur des données médicales.

## Objectif  
Développer un modèle de classification utilisant **KNN** pour détecter le diabète en se basant sur certaines caractéristiques comme le **glucose**, l’**insuline**, l’**IMC** et l’**âge**.

## Technologies utilisées  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## Structure du projet  
- `diabetes.ipynb` : Notebook contenant le code du modèle et son entraînement  
- `diabetes.csv` : Dataset utilisé pour l'entraînement  

## Installation  
1. Clone ce repository :  
   ```bash
   git clone https://github.com/ourahma/Diabetes_ML.git
   ```
2. Installe les dépendances :  
   ```bash
   pip install Scikit-learn pandas numpy matplotlib
   ```
3. Lance le notebook :  
   ```bash
   jupyter notebook diabetes.ipynb
   ```

## Approche  
- Prétraitement des données (remplacement des valeurs nulles par la moyenne).  
- Normalisation des données avec **MinMaxScaler**.  
- Sélection des caractéristiques **Glucose, Insulin, BMI, Age**.  
- Entraînement du modèle **KNN** avec `n_neighbors=24`.  
- Évaluation de la précision (~78,57 %).  

## Résultats  
- **Précision du modèle** : 78.57 %  
- **Classification Report** :  
  ```
  precision    recall  f1-score   support
     0.0       0.81      0.87      0.84       100
     1.0       0.72      0.63      0.67        54
  ```

##  Auteur  
 
Maroua Ourahma  
- Email : marouaourahma@gmail.com 
- LinkedIn : [linkedin.com/in/ourahma](www.linkedin.com/in/maroua-ourahma-293426235)  

