# Bottleneck — Analyse et optimisation des stocks avec Python

Projet réalisé dans le cadre de ma formation **Business Intelligence Analyst chez OpenClassrooms**.

L’objectif de ce projet était de consolider plusieurs sources de données commerciales, d’en contrôler la qualité puis d’analyser les ventes, les stocks, les marges et les valeurs atypiques afin d’identifier des leviers d’amélioration pour l’entreprise.

## Objectifs

- Explorer et contrôler la qualité de plusieurs jeux de données.
- Nettoyer et préparer les données avant analyse.
- Fusionner plusieurs sources ERP et Web.
- Analyser le chiffre d’affaires et les performances commerciales.
- Étudier les niveaux de stock, leur valorisation et leur rotation.
- Identifier les produits et prix atypiques.
- Analyser les marges et certaines corrélations.
- Restituer les résultats de manière claire et exploitable.

## Outils utilisés

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**
- **Excel**

## Travaux réalisés

### Préparation et nettoyage des données

Exploration des différentes sources, contrôle des types de données, recherche d’incohérences et préparation des données nécessaires à l’analyse.

Les différentes sources ont ensuite été rapprochées afin de constituer une base exploitable pour les analyses.

### Analyse du chiffre d’affaires

Calcul du chiffre d’affaires global et analyse des performances par produit.

Une analyse de type **Pareto** a également été utilisée afin d’identifier les produits contribuant le plus au chiffre d’affaires.

### Détection des valeurs atypiques

Analyse de la distribution des prix et identification des valeurs atypiques à l’aide de plusieurs approches :

- boxplots ;
- méthode IQR ;
- Z-score.

L’objectif était de distinguer les valeurs réellement inhabituelles des produits naturellement positionnés sur des gammes de prix élevées.

### Analyse des stocks

Étude :

- des quantités disponibles ;
- de la valorisation du stock ;
- de la rotation des produits ;
- des produits présentant des stocks particulièrement élevés ou faibles.

### Analyse des marges

Analyse des marges afin d’identifier les produits les plus intéressants en termes de rentabilité et de compléter l’analyse fondée uniquement sur le chiffre d’affaires.

### Analyses complémentaires

Plusieurs relations entre variables ont été étudiées afin d’identifier d’éventuelles corrélations et tendances dans les données.

## Livrables

### Notebook d’analyse

[`bottleneck_analysis.ipynb`](./bottleneck_analysis.ipynb)

Le notebook contient les étapes de préparation, nettoyage, fusion, analyse et visualisation des données.

### Présentation finale

[`bottleneck_presentation.pdf`](./bottleneck_presentation.pdf)

Présentation synthétique des principaux résultats et recommandations issues de l’analyse.

## Compétences mobilisées

- Nettoyage et préparation des données
- Manipulation de DataFrames avec Pandas
- Fusion de plusieurs sources de données
- Analyse exploratoire des données
- Analyse univariée et multivariée
- Détection de valeurs atypiques
- Analyse du chiffre d’affaires
- Analyse des stocks et des marges
- Visualisation des données
- Interprétation des résultats
- Restitution d’une analyse à destination de décideurs

## Structure du dépôt

```text
bottleneck-stock-analysis-python/
│
├── README.md
├── .gitignore
├── bottleneck_analysis.ipynb
└── bottleneck_presentation.pdf
```

## Données

Les fichiers de données sources fournis dans le cadre de la formation OpenClassrooms ne sont pas redistribués dans ce dépôt.

Le dépôt présente uniquement mon travail d’analyse ainsi que les livrables réalisés à partir de ces données.

---

**Projet réalisé dans le cadre de la formation Business Intelligence Analyst — OpenClassrooms.**
