# 🤖 AI Assure Identification

## 📌 Contexte

Ce projet a été réalisé dans le cadre d'une initiative proposée lors d'une alternance à la **CNAV (Caisse Nationale d’Assurance Vieillesse)**.

Il vise à illustrer comment des techniques d'Intelligence Artificielle peuvent être utilisées pour améliorer la qualité des données au sein du **RGCU (Répertoire de Gestion des Carrières Unique)**.


## 🎯 Objectif

L’objectif principal est de construire un modèle de **Machine Learning supervisé** capable de déterminer si un assuré est :

* ✅ **Identifié** (données complètes et exploitables)
* ❌ **Non identifié** (données manquantes, incohérentes ou insuffisantes)

👉 Il s’agit donc d’un **problème de classification binaire**.


## 📊 Données

⚠️ **Important :**

* Les données utilisées dans ce projet sont **entièrement fictives**
* Elles ne représentent **en aucun cas les données réelles des assurés**
* Elles ne reflètent pas les traitements réellement effectués au sein du RGCU
* Elles ont été générées à des fins de démonstration uniquement


## 🧪 Méthodologie

Le projet suit les étapes classiques d’un pipeline de Data Science :

### 1. Analyse exploratoire (EDA)

* Compréhension des données
* Analyse des valeurs manquantes
* Étude de la variable cible

### 2. Nettoyage des données

* Gestion des valeurs manquantes
* Correction des incohérences
* Conversion des types de données

### 3. Feature Engineering

Création de variables pertinentes :

* Présence du NIR
* Présence du nom et prénom
* Nombre de champs renseignés
* Taux de complétude des données

### 4. Modélisation

Plusieurs modèles de classification ont été testés :

* Régression logistique
* Arbre de décision
* Random Forest

### 5. Optimisation

* Utilisation de **RandomizedSearchCV** pour améliorer les performances

### 6. Évaluation

* Accuracy
* Precision / Recall
* Analyse des erreurs


## 🧠 Approche

Le modèle apprend à détecter si un assuré est identifiable à partir de :

* La **complétude des données**
* La présence d’informations clés (NIR, identité)
* La cohérence globale des informations

👉 Ce projet s’inscrit également dans une logique de :

* **qualité des données**
* **détection d’anomalies**


## 🛠️ Technologies utilisées

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn


## ⚠️ Avertissement

Ce projet est une **preuve de concept (POC)**.

Il ne doit pas être utilisé en production sans :

* validation métier
* conformité réglementaire
* respect du RGPD


## 🚀 Apports du projet

Ce travail permet de démontrer :

* L’intérêt du Machine Learning pour améliorer la qualité des données
* La capacité à détecter automatiquement des dossiers incomplets
* Le potentiel d’intégration de l’IA dans les systèmes d’information publics


## 👨‍💻 Auteur

Alex Alkhatib: Projet réalisé dans le cadre d'une alternance à la CNAV
dans un objectif de démonstration des applications de l’IA au sein du RGCU.
