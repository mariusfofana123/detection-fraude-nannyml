# 🛡️ Détection de Fraude et Surveillance de Modèles ML avec NannyML

Ce projet porte sur la surveillance des performances et de la dérive des données (*data drift*) pour des modèles de détection de fraude bancaire en utilisant la bibliothèque Python **NannyML**.

## 📌 Présentation du Projet
Les banques utilisent des modèles de Machine Learning pour détecter la fraude transactionnelle. Cependant, avec l'évolution du comportement des utilisateurs et de l'environnement financier, la distribution des données change et les performances des modèles chutent. 

Ce projet utilise **NannyML** pour surveiller ces variations sur des jeux de données de référence (`reference.csv`) et d'analyse (`analysis.csv`).

## 🛠️ Stack Technique
- **Langage** : Python 3
- **Environnement** : Jupyter Notebook
- **Analyse de données** : Pandas
- **Monitoring ML** : NannyML

## 🚀 Installation & Exécution

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/mariusfofana123/detection-fraude-nannyml.git
   cd detection-fraude-nannyml