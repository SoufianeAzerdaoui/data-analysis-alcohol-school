# 📊 Data Analysis Project – Consommation d’alcool et résultats scolaires

## 🎯 Contexte
Ce projet a pour objectif d’analyser le lien entre **la consommation d’alcool des étudiants** et **leurs résultats scolaires** à partir de deux jeux de données publics concernant des élèves portugais (cours de Mathématiques et de Portugais).  
Il s’agit d’un projet académique visant à appliquer les notions de collecte, nettoyage, analyse statistique et visualisation de données.

---

## 📌 Objectifs
- Nettoyer et préparer les données pour l’analyse.
- Vérifier un ensemble d’hypothèses statistiques.
- Réaliser des visualisations claires et interprétables.
- Rédiger un rapport complet et présenter les résultats.

---

## 🗂️ Structure du projet
Le projet est organisé en 4 parties principales :

1. **Collecte (C)** :  
   - Importation des datasets  
   - Fusion des bases (Math & Portugais)  
   - Nettoyage et prétraitement  

2. **Étude (E)** :  
   - Tests statistiques et vérification d’hypothèses  
   - Analyse de corrélation  
   - Extraction et traitement d’échantillons  

---

## 📊 Jeux de données
Les données proviennent de deux fichiers CSV :  

- `student-mat.csv` : étudiants en Mathématiques  
- `student-por.csv` : étudiants en Portugais  

Les principaux attributs incluent :  
- **Informations socio-démographiques** (sexe, âge, adresse, éducation des parents, etc.)  
- **Habitudes de vie** (sorties, temps d’étude, consommation d’alcool en semaine et week-end)  
- **Résultats scolaires** (notes G1, G2, G3)  
- **Autres variables** (relations familiales, absences, santé, etc.)  

📌 **Variable cible** : `G3` (note finale)

---

## 🔍 Hypothèses étudiées
1. Les étudiants dont les parents ont un faible niveau d’instruction consomment-ils plus d’alcool ?  
2. Les étudiants qui n’abusent pas d’alcool réussissent-ils mieux à l’école ?  
3. Les garçons consomment-ils plus d’alcool que les filles ?  
4. La consommation est-elle plus élevée le week-end que la semaine ?  
5. Les étudiants urbains consomment-ils moins que ceux en milieu rural ?  
6. Y a-t-il un lien entre consommation d’alcool et absences scolaires ?  

---

## 🛠️ Technologies utilisées
- **Python 3**  
- **Pandas / Numpy** (prétraitement et nettoyage des données)  
- **Matplotlib / Seaborn** (visualisations)  
- **Scipy / Statsmodels** (tests statistiques et hypothèses)  
- **Jupyter Notebook** (développement et analyse)  

---

## ▶️ Exécution du projet
1. Cloner ce dépôt :  
   ```bash
   git clone https://github.com/username/data-analysis-alcohol-school.git
   cd data-analysis-alcohol-school
