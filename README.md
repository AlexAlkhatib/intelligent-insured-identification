# 🫆 Intelligent Insured Identification

## 📌 Contexte

Lors de mon alternance à la **CNAV (Caisse Nationale d’Assurance Vieillesse)**, j’ai identifié une problématique clé liée au **RGCU (Répertoire de Gestion des Carrières Unique)** :

👉 **la qualité et la complétude des données assurés**, essentielles pour leur identification et leur exploitation.

Dans mon mémoire, j’ai proposé l’utilisation de l’Intelligence Artificielle pour répondre à ce besoin.

🎯 Ce projet est la **concrétisation technique de cette idée**.


## 🚀 Objectif

Développer un modèle de **Machine Learning supervisé** capable de déterminer automatiquement si un assuré est :

* ✅ **Identifié** → données complètes, cohérentes et exploitables
* ❌ **Non identifié** → données manquantes, incohérentes ou insuffisantes

👉 Problème traité : **classification binaire appliquée à la qualité des données**


## 🧠 Approche

Plutôt que de se baser uniquement sur des règles métier statiques, ce projet propose une approche basée sur :

* la **complétude des données**
* la présence d’informations clés (**NIR, identité**)
* la **cohérence globale des informations**

👉 Le modèle apprend à détecter automatiquement des profils exploitables.


## 📊 Données

⚠️ **Important**

* Les données utilisées sont **entièrement fictives**
* Elles ont été générées pour simuler des cas réalistes :

  * données complètes
  * données manquantes
  * incohérences (NIR invalide, erreurs, etc.)

❗ Elles ne représentent **en aucun cas** les données réelles du RGCU ni les traitements actuels.


## 🧪 Méthodologie

Le projet suit un pipeline Data Science complet :

### 🔍 1. Analyse exploratoire

* Distribution des données
* Analyse des valeurs manquantes
* Étude de la variable cible

### 🧹 2. Nettoyage

* Gestion des données incohérentes
* Conversion des types
* Standardisation

### ⚙️ 3. Feature Engineering

Création de variables clés :

* `nir_present`
* `nom_present`
* `prenom_present`
* `nb_champs_renseignes`
* `taux_completude`

### 🤖 4. Modélisation

Modèles testés :

* Régression logistique
* Arbre de décision
* Random Forest

### 🔥 5. Optimisation

* **RandomizedSearchCV**

### 📈 6. Évaluation

* Accuracy
* Precision / Recall
* Analyse des erreurs


## 📊 Résultats

👉 Le modèle apprend efficacement à distinguer :

* les dossiers exploitables
* les dossiers incomplets

👉 Les variables les plus importantes :

* présence du NIR
* taux de complétude
* nombre de champs renseignés


## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn


## ⚠️ Limites

* Données synthétiques
* Simplification des règles métier
* Pas d’intégration système réel


## 🚀 Apports

Ce projet démontre :

* la **valeur de l’IA pour la qualité des données**
* la capacité à transformer une **idée métier en solution technique**
* le potentiel d’intégration de l’IA dans les systèmes publics


## ⚠️ Disclaimer

Ce projet est une **preuve de concept (POC)** à but démonstratif.


## 👨‍💻 Auteur

**Alex Alkhatib**

Projet réalisé suite à une réflexion menée lors d’une alternance à la CNAV, avec une volonté de concrétiser une application réelle de l’IA.


## 🔒 Propriété intellectuelle et clause de non-responsabilité

Ce projet est un travail personnel indépendant inspiré par les défis généraux du secteur.

Il ne contient aucune information, code ou donnée confidentielle provenant d'anciens employeurs.

Toutes les données utilisées dans ce projet sont synthétiques et ont été générées à des fins de démonstration uniquement.
