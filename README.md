# Deep Learning Lab - PyTorch

## 📌 Description
Lab de Deep Learning avec PyTorch pour des tâches de régression et classification multi-classe.

## 🎯 Objectifs
- **Part 1**: Régression sur le dataset NYSE
- **Part 2**: Classification multi-classe sur Predictive Maintenance

## 🛠️ Technologies Utilisées
- PyTorch
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- SMOTE (imbalanced-learn)

## 📊 Résultats

### Part 1 - Régression
- Architecture: DNN avec 3 couches cachées
- Meilleur R² Score: **X.XX**
- Optimiseur: Adam
- Régularisation: L2 + Dropout

### Part 2 - Classification
- Classes: 5 types de défaillances
- Accuracy: **XX.X%**
- F1-Score: **X.XX**
- Data Augmentation: SMOTE

## 📁 Structure du Projet
```
deep-learning-lab/
│
├── Part1_Regression.ipynb          # Notebook régression NYSE
├── Part2_Classification.ipynb      # Notebook classification
├── README.md                        # Ce fichier
├── requirements.txt                 # Dépendances
└── models/                          # Modèles sauvegardés
    ├── best_regression_model.pth
    └── best_classification_model.pth
```

## 🚀 Installation
```bash
# Cloner le repository
git clone https://github.com/VOTRE_USERNAME/deep-learning-lab.git
cd deep-learning-lab

# Installer les dépendances
pip install -r requirements.txt
```

## 💻 Utilisation

### Google Colab (Recommandé)
1. Ouvrir le notebook dans Google Colab
2. Runtime → Change runtime type → GPU
3. Exécuter toutes les cellules

### Local
```bash
jupyter notebook Part1_Regression.ipynb
```

## 📈 Datasets
- **NYSE**: [Kaggle - NYSE Dataset](https://www.kaggle.com/datasets/dgawlik/nyse)
- **Predictive Maintenance**: [Kaggle - Machine Predictive Maintenance](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

## 🎓 Ce que j'ai appris
- Architecture des réseaux de neurones profonds (DNN/MLP)
- Utilisation de PyTorch pour la régression et classification
- Techniques de régularisation (Dropout, L2, Batch Normalization)
- GridSearch pour l'optimisation des hyperparamètres
- Data Augmentation avec SMOTE
- Évaluation de modèles (métriques, confusion matrix)

## 👤 Auteur
**Votre Nom**
- GitHub: [@votre_username](https://github.com/votre_username)
- Université: Université Abdelmalek Essaadi - FST Tanger
- Master: MBD (Big Data)

## 📝 License
Ce projet est sous licence MIT.

---
*Projet réalisé dans le cadre du cours de Deep Learning - Pr. ELAACHAK LOTFI*
