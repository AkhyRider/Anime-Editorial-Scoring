# 🎬 Anime Editorial Scoring : Data Science Project

 🎯 Objectif du Projet
Développer un outil d'aide à la décision pour une plateforme de streaming.
L'objectif est d'identifier les animes à **"Haute Valeur Éditoriale"** en ne se basant pas seulement sur la popularité, mais sur la **fiabilité technique** (Régularité).

 📊 Méthodologie
Ce projet suit un workflow Data Science complet :
1. **Data Cleaning :** Nettoyage des données aberrantes (notes à 0, animes trop récents).
2. **Feature Engineering :** Création de métriques de stabilité :
   - `Ecart` : Différence entre le meilleur et le pire épisode.
   - `Regularite` : Score inversé sur 10.
3. **Scoring :** Création du `Score_Qualite` (60% Note Globale + 40% Régularité).

🏆 Résultats Clés
- **Studio Leader :** L'analyse a révélé que le studio **Artland** offre la meilleure garantie de qualité moyenne, surpassant les géants du secteur.
- **Top Anime :** L'algorithme a permis de classer *Frieren* et *Claymore* comme des investissements sûrs.
- **Insight Métier :** Une corrélation négative a été observée entre la longueur d'un anime et sa régularité.

 🛠 Outils Utilisés
- **Python** (Pandas, NumPy)
- **Data Visualization** (Seaborn, Matplotlib)
- **Jupyter Notebook**

---
*Projet réalisé dans le cadre de ma formation Data chez Hetic.*
