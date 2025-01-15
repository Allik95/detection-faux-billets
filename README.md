# Détection des Faux Billets

Ce projet fait partie de mon portfolio en tant que Data Analyst. Il illustre l'utilisation de techniques avancées de traitement et d'analyse de données pour résoudre un problème concret : identifier si un billet en euros est authentique ou non.

---

## 🎯 **Objectifs du projet**

1. Analyser et prétraiter les données scannées de billets.
2. Comparer différentes techniques de machine learning pour identifier le modèle le plus performant.
3. Développer une application fonctionnelle pour la prédiction.
4. Fournir un support explicatif pour vulgariser les résultats.

---

## 🛠️ **Techniques et outils utilisés**

### Langages et environnements
- **Python** : Principal langage de programmation.
- **Jupyter Notebook** : Environnement de développement interactif.

### Bibliothèques principales
- **Pandas** : Manipulation des données.
- **NumPy** : Calculs numériques.
- **Matplotlib/Seaborn** : Visualisation des données.
- **Scikit-learn** : Implémentation des algorithmes de machine learning.

### Algorithmes utilisés
- K-Means (Clustering).
- Régression Logistique.
- K-Nearest Neighbors (KNN).
- Random Forest.

---

## 📊 **Structure du projet**

### 1. Préparation des données
- **Validation des données** : Vérification des valeurs manquantes et traitement des anomalies.
- **Analyse exploratoire** : Visualisation des variables clés et analyse des corrélations.

### 2. Modélisation
- Séparation des données en jeux d'entraînement et de test.
- Entraînement de plusieurs modèles de machine learning.
- Comparaison des performances à l'aide de métriques comme la précision, le rappel, et le score F1.

### 3. Développement de l'application
- Interface utilisateur pour soumettre les caractéristiques d'un billet et recevoir un diagnostic en temps réel.

### 4. Présentation des résultats
- Visualisations interactives des performances des modèles.
- Tableau comparatif des scores.

---

## 🚀 **Comment utiliser ce projet ?**

### Étape 1 : Cloner le dépôt
```bash
git clone https://github.com/Allik95/detection-faux-billets.git
```

### Étape 2 : Installer les dépendances
Assurez-vous d'avoir Python installé, puis utilisez pip pour installer les bibliothèques nécessaires :
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
```

### Étape 3 : Lancer le notebook
Ouvrez le fichier `Carvalho_Romain_1_Notebook_Analyse_012025.ipynb` dans Jupyter Notebook ou un autre IDE compatible.

### Étape 4 : Tester l'application
Exécutez le script de l'application pour démarrer l'interface utilisateur.

```bash
python app.py
```

---

## 🌟 **Résultats clés**

- Le modèle **Régression Logistique** a obtenu les meilleures performances avec une précision de 98%.
- Les variables les plus importantes pour la détection sont :
  - `length` : Longueur du billet.
  - `margin_low` : Marge inférieure.
  - `margin_up` : Marge supérieure.


---

## 🖇️ **Liens utiles**
- [Documentation Scikit-learn](https://scikit-learn.org/stable/)
- [Mon portfolio](https://romaincarvalho.com)

## 👤 **Auteur**
[Carvalho Romain]  
[Romaincrvlh@gmail.com]  
[LinkedIn](https://www.linkedin.com/in/romain-carvalho-551605206/?originalSubdomain=fr)
# detection.des.faux.billets
 
