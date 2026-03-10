# 📚 Analyse des Ventes et du Comportement Client : Étude Statistique d'une Librairie

## 📖 Résumé du Projet
Ce projet consiste en une analyse exploratoire et statistique complète des données de vente d'une librairie. L'objectif est d'identifier les tendances de consommation, de segmenter la clientèle et de valider mathématiquement les corrélations entre les profils clients et leurs habitudes d'achat.

---

## 🔬 Méthodologie Statistique (Approche Académique)

### 1. Ingénierie des Données (ETL)
*   **Consolidation :** Fusion de 3 bases de données hétérogènes (Clients, Produits, Ventes).
*   **Data Cleaning :** Traitement des doublons, gestion des dates et nettoyage des prix (détection des prix négatifs ou aberrants).
*   **Feature Engineering :** Création de variables pivot (âge des clients, fréquence d'achat).

### 2. Analyse de Concentration et d'Inégalité (UE STA101)
*   **Courbe de Lorenz :** Visualisation de la répartition du chiffre d'affaires.
*   **Indice de Gini :** Calcul du coefficient pour mesurer la concentration des ventes (Loi de Pareto : 20% des clients font-ils 80% du CA ?).
*   *Lien Cnam : Maîtrise des indicateurs de dispersion et de concentration.*

### 3. Étude des Corrélations (Approche Inférentielle)
Utilisation de tests statistiques pour répondre à des problématiques métiers :
*   **Corrélation de Pearson/Spearman :** Analyse du lien entre l'âge du client et le montant total des achats.
*   **Test du Chi-deux ($\chi^2$) :** Analyse de l'indépendance entre le genre des clients et les catégories de livres achetés.
*   **ANOVA (Analyse de Variance) :** Étude de l'influence de la catégorie de prix sur la fréquence d'achat.

---

## 📈 Résultats et Insights
*   **Segmentation :** Identification de profils types (Gros acheteurs, Clients occasionnels, Spécialistes).
*   **Saisonnalité :** Mise en évidence des cycles de vente mensuels et hebdomadaires.
*   **Fiabilité :** Validation scientifique des tendances observées par des tests de significativité.

---

## 💻 Stack Technique
*   **Langage :** Python 3.9 (Distribution Anaconda).
*   **Bibliothèques :** `Pandas` (ETL), `Matplotlib` & `Seaborn` (Visualisation), `Scipy.stats` (Tests mathématiques).

---

## 👨‍💼 À propos de l'Auteur : Abdelali EL MAMOUNI
*   **Expert Senior en Systèmes d'Information** (15 ans d'expertise internationale au Canada).
*   **Lean Six Sigma Black Belt** : Spécialiste de la rigueur statistique appliquée au business.
*   **Data Analyst Certifié (Niveau 6)**.

*Ce projet démontre ma capacité à passer d'une simple lecture de données à une analyse prédictive et explicative robuste, répondant aux exigences du grade de Licence du Cnam.*
