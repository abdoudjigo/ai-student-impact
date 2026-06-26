# AI Student Impact — Analyse Exploratoire

> Étude de l'impact de l'IA générative sur les performances académiques des étudiants — 50 000 observations, 16 variables.

---

## Contexte

Ce projet s'inscrit dans le cadre de la formation **DEV DATA P8** à l'**Orange Digital Center de Dakar**. Il vise à construire une maîtrise solide de l'analyse de données en Python à travers un cas réel et volumeux.

L'objectif n'est pas seulement d'analyser — c'est de développer des réflexes d'analyste : poser les bonnes questions avant d'écrire la première ligne de code.

---

## Dataset

| Propriété | Valeur |
|-----------|--------|
| Source | [AI Student Impact Dataset — Kaggle](https://www.kaggle.com) |
| Volume | 50 000 lignes × 16 colonnes |
| Format | CSV |

**Variables clés :**

- `Post_Semester_GPA` — Performance académique en fin de semestre
- `Skill_Retention_Score` — Rétention des compétences acquises
- `Burnout_Risk_Level` — Niveau de risque d'épuisement

---

## Stack technique

| Outil | Usage |
|-------|-------|
| Python 3 | Langage principal |
| Pandas | Manipulation et nettoyage des données |
| NumPy | Calculs numériques et statistiques |
| Matplotlib | Visualisation de base |
| Seaborn | Visualisation statistique avancée |

---

## Structure du projet

```
projet_data/
│
├── data/
│   └── ai_student_impact_dataset.csv
│
├── notebooks/
│   ├── 01_exploration.ipynb       # Découverte du dataset
│   ├── 02_statistiques.ipynb      # Analyses descriptives
│   └── 03_visualisation.ipynb     # Graphiques et insights
│
├── outputs/
│   └── figures/                   # Exports visuels
│
└── README.md
```

---

## Analyses couvertes

**Statistiques descriptives**
- Moyenne, médiane, écart-type
- Quartiles (Q1, Q2, Q3) et percentiles
- IQR — Interquartile Range

**Détection d'anomalies**
- Valeurs atypiques (outliers)
- Distributions asymétriques

**Visualisations**
- Histogrammes de distribution
- Boxplots comparatifs
- Scatter plots et corrélations

---

## Démarche

```
Exploration → Nettoyage → Statistiques → Visualisation → Insights
```

Chaque notebook correspond à une étape. Les notebooks sont conçus pour être parcourus dans l'ordre.

---

## Auteur

**DJIGO**  
Formation DEV DATA P8 — Orange Digital Center, Dakar  

---

*Transformer des données brutes en insights clairs et exploitables.*