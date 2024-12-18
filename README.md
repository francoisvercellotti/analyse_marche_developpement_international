# Analyse de marché pour l'exportation de poulets biologiques

<div align="center">
  <img src="https://github.com/user-attachments/assets/6938eea5-d323-4d73-bef0-c592ac3dcee7" alt="Aperçu du tableau de bord" width="600"/>
</div>

---

Dans le cadre de ma mission en tant que Data Analyst pour l’entreprise **La Poule Qui Chante**, mon objectif est de réaliser une étude de marché afin d’identifier les pays cibles pour l’exportation de nos poulets biologiques.

L’entreprise souhaite étendre son activité à l’international, et cette analyse servira de base pour orienter les décisions stratégiques de la direction.

---

## Contexte du projet

La Poule Qui Chante est une entreprise agroalimentaire française spécialisée dans l’élevage et la vente de poulets labellisés **“Agriculture Biologique”**. Actuellement active uniquement en France, l’entreprise envisage une expansion à l’international, sans pays ou continent spécifique identifié pour l’instant.

Le **PDG**, Patrick, a fixé les objectifs suivants :
1. Identifier les regroupements de pays présentant des opportunités pour l’exportation.
2. Fournir une analyse détaillée des données pour appuyer les recommandations stratégiques.

---

## Objectif

L’objectif principal est de proposer une segmentation des pays en fonction de données socio-économiques, politiques, et environnementales pour identifier des clusters pertinents. Cette segmentation permettra de recommander des pays prioritaires pour une expansion à l'international.

---

## Étapes clés du projet

1. **Collecte des données** :
   - Source principale : Organisation des Nations Unies pour l'alimentation et l'agriculture (**FAO**).
   - Sources complémentaires : Banque mondiale, données publiques internationales.
   - Application de l’analyse **PESTEL** (Politique, Économique, Socioculturel, Technologique, Environnemental, Légal) pour enrichir les données.

2. **Préparation et nettoyage des données** :
   - Intégration et consolidation des données issues de différentes sources.
   - Nettoyage des données pour assurer la qualité et la cohérence des variables.
   - Analyse des valeurs manquantes et gestion des outliers.
   - Création de nouvelles variables par **feature engineering**.

3. **Analyse exploratoire des données (EDA)** :
   - Visualisation des distributions.
   - Analyse des corrélations entre variables.
   - Identification des variables les plus pertinentes pour la segmentation.

4. **Réduction des dimensions** :
   - Application de l'**Analyse en Composantes Principales (ACP)** pour réduire la complexité.
   - Rotation VARIMAX pour améliorer l'interprétabilité des dimensions sous-jacentes des données
   - Création du cercle des corrélations et analyse des projections des pays.

5. **Clustering** :
   - Méthodes utilisées :
     - Classification Ascendante Hiérarchique (**CAH**).
     - Algorithme de **K-Means**.
   - Comparaison des performances entre ACP et données brutes.
   - Détermination du nombre optimal de clusters.

6. **Recommandations** :
   - Présentation des clusters identifiés.
   - Justification des choix stratégiques pour chaque groupe de pays.
   - Proposition de 2 à 3 pays prioritaires pour une analyse approfondie.

## Résultats attendus

1. Une segmentation claire des pays en fonction des critères pertinents.
2. Une liste priorisée des pays cibles pour l’expansion internationale.
3. Des recommandations stratégiques basées sur les clusters identifiés.
4. Une présentation compréhensible pour un public non technique.


---

## Compétences mobilisées

### Gestion de projet
- Organisation des étapes clés pour garantir une livraison dans les délais.
- Collaboration avec les parties prenantes pour ajuster les livrables aux attentes.

### Traitement des données
- Nettoyage, transformation, et structuration des données pour optimiser leur exploitation.
- Création de nouvelles variables par **feature engineering**.

### Analyse des données
- Identification des indicateurs pertinents pour répondre aux besoins stratégiques.
- Utilisation d’analyses multivariées pour identifier les corrélations significatives.

### Clustering et réduction des dimensions
- Réalisation d’une **ACP** puis rotation **VARIMAX** avant analyse des projections des individus.
- Implémentation de **CAH** et **K-Means** pour segmenter les pays.

### Visualisation et storytelling avec les données
**1. Présentation des résultats sous forme de graphiques clairs et intuitifs**

- Utiliser des graphiques simples pour rendre les résultats compréhensibles.

<img src="https://github.com/user-attachments/assets/4a5a4d73-0f62-4fc6-9ecd-2a341734da3f" width="400" />

**2. Utilisation d'un langage adapté pour un auditoire non technique**

- Simplifier les termes techniques pour rendre les données accessibles à tous.

<img src="https://github.com/user-attachments/assets/65763c10-ca42-4391-8a88-0519f5182a1c" width="400" />

**Exemples supplémentaires :**

<img src="https://github.com/user-attachments/assets/8c5b73c7-c58d-4647-9ce2-7988d26080f8" width="400" />
<img src="https://github.com/user-attachments/assets/528ef3d9-c151-4478-8fab-507f9f180a3f" width="400" />





---

## Outils utilisés

- **Python** :
  - Librairies principales : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy.
- **Jupyter Notebook** : Documentation et organisation du code.
- **GitHub** : Gestion de version et collaboration.
- **Excel** : Vérification et consolidation manuelles des données.

---
## Conclusion

Ce projet m'a permis de développer des compétences avancées en **analyse multivariée**, **clustering**, et **communication de données stratégiques**. Je suis confiant dans la pertinence des recommandations proposées pour guider l’expansion internationale de **La Poule Qui Chante**.

---

