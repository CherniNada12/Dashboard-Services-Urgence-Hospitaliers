# 🏥 Dashboard des Services d’Urgence Hospitaliers  
**Projet Power BI – Nada Cherni**

---

## 📘 Contexte du projet  
Ce projet vise à concevoir un **tableau de bord Power BI interactif** permettant d’analyser les performances du **service des urgences hospitalières**.  
L’objectif est de suivre les principaux indicateurs liés à la fréquentation, au temps d’attente, à la satisfaction des patients et à la gestion des ressources hospitalières.

---

## 🎯 Objectif principal  
Améliorer l’efficacité opérationnelle et fournir des **informations exploitables** sur les performances du service des urgences, grâce à une visualisation claire et dynamique des données.

---

## 🧩 Étapes du projet  

### 1️⃣ Recueil des besoins (Business Requirements)
- Identifier les **indicateurs de performance (KPI)** essentiels.
- Comprendre les besoins métier : flux de patients, gestion du personnel, satisfaction et rapidité de prise en charge.

### 2️⃣ Exploration et préparation des données
- **Source :** `Hospital ER_Data.csv`
- Vérification de la qualité et du format des données.
- Nettoyage, suppression des doublons et gestion des valeurs manquantes.
- Transformation et modélisation des données dans Power Query.

### 3️⃣ Modélisation et traitement
- Création d’un modèle relationnel adapté à l’analyse.
- Définition des mesures DAX :
  - Moyenne du temps d’attente.
  - Score moyen de satisfaction.
  - Pourcentage de patients vus en moins de 30 minutes.
  - Répartition par sexe, âge, race, service.

### 4️⃣ Développement du tableau de bord
- Mise en page ergonomique (Power BI).
- Intégration de filtres interactifs (année, mois, plage de dates).
- Développement de visualisations : barres, camemberts, lignes, heatmaps.

---

## 📊 Tableaux de bord développés  

### 🟣 **Dashboard 1 – Monthly View**
**Objectif :** Analyser les tendances et indicateurs clés sur une base mensuelle.

**Indicateurs principaux :**
- Nombre total de patients.
- Temps d’attente moyen.
- Score moyen de satisfaction.
- Nombre de patients référés.

**Visualisations :**
- Statut d’admission : admis vs non admis.  
- Répartition par âge, sexe et race.  
- Pourcentage de patients vus en moins de 30 minutes.  
- Répartition horaire et journalière (heatmap).  
- Références par département.

![Dashboard 1](Nada%20Cherni%20powerbi/Projet/Dashboard%201.png)


---

### 🟪 **Dashboard 2 – Consolidated View**
**Objectif :** Fournir une **vue globale** sur une période donnée pour observer les tendances cumulées et les corrélations entre variables.

**Indicateurs inclus :**
- Total des patients sur la période sélectionnée.  
- Moyenne du score de satisfaction par groupe d’âge.  
- Corrélation entre temps d’attente et satisfaction.  
- Nombre de patients par heure d’admission.  
- Répartition des patients par département de référence.

**Visualisations :**
- Satisfaction & nombre de patients par âge.  
- Volume de patients par heure.  
- Analyse comparative admission / référence.  

💡 **Insight clé :**
Les groupes d’âge 20–39 ans présentent une baisse de satisfaction lors des pics de fréquentation, indiquant un besoin d’ajustement du flux de traitement.
![Dashboard 1](Nada%20Cherni%20powerbi/Projet/Dashboard%202.png)

---

## 📈 Indicateurs Clés de Performance (KPI)

| Indicateur | Description | Objectif |
|-------------|-------------|-----------|
| 🧍 Nombre de patients | Total des admissions journalières ou mensuelles | Suivre la charge du service |
| ⏱️ Temps d’attente moyen | Durée moyenne avant prise en charge | Identifier les goulots d’étranglement |
| 😀 Score de satisfaction | Évaluation par les patients | Améliorer la qualité du service |
| 🏥 Patients référés | Nombre de patients orientés vers d'autres départements | Évaluer la coordination interservices |

---


## 🛠️ Outils et technologies
- 🟡 **Power BI Desktop (.pbix)** – conception du tableau de bord  
- 🟢 **Microsoft Excel / CSV** – préparation et nettoyage des données  
- 🔵 **DAX (Data Analysis Expressions)** – calcul des mesures et indicateurs  
- 🟣 **Power Query** – modélisation et intégration des données  

---

## 📂 Structure du projet  

Voici la structure des fichiers du projet :  

```bash
Nada Cherni PowerBI/
│
└── Projet/
    ├── Hospital ER_Data.csv              # Jeu de données source
    ├── Hospital Project.pbix             # Fichier Power BI principal
    ├── Nada Cherni 2 idsd1 powerbi.pdf   # Rapport final
    ├── Dashboard 1.png                   # Capture du tableau de bord 1
    └── Dashboard 2.png                   # Capture du tableau de bord 2
---



