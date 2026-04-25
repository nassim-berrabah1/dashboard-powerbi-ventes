# 📈 Dashboard Power BI — Analyse des Ventes & Performances

Rapport multi-pages interactif analysant les performances commerciales par région, manager et catégorie de produit, à partir d'un dataset de ventes réelles.


# 📌 Contexte
Projet réalisé en mars 2026 dans le cadre de la formation BUT Informatique — Sciences des Données (IUT Villetaneuse, Université Sorbonne Paris Nord).

Source des données : Fichier Excel fourni (3 tables : Orders/Sales, Returns, People) — données réelles
Outil : Power BI Desktop


# 📊 Aperçu du Dashboard
Page 1 — Vue d'ensemble
<img width="1655" height="926" alt="image" src="https://github.com/user-attachments/assets/09c2f400-333b-4c63-bda2-5ad6cb54f8ac" />
Page 2 — Performances par manager & ville
<img width="1652" height="928" alt="image" src="https://github.com/user-attachments/assets/08b29365-cc21-47af-a423-55139c063558" />
Page 3 — Analyse par catégories & produits
<img width="1654" height="920" alt="image" src="https://github.com/user-attachments/assets/e5dc3ac7-623c-426f-9b39-eebfb59f99b0" />


# 🗂️ Structure du rapport (3 pages)
Page 1 — Vue d'ensemble géographique

KPI card : Chiffre d'affaires total
Filled Map (carte choroplèthe) : CA par état américain, avec interaction sur le slicer
Slicer : Filtre multi-sélection par état

Page 2 — Performances par manager & ville

Histogramme empilé : Quantités vendues par manager (couleur par personne)
Graphique à barres empilées : Profit par manager (en dollars)
Carte KPI : Chiffre d'affaires et profit associés à la sélection
Carte géographique : Nombre de villes totales / sélectionnées
Slicer : Filtre par ville avec vue manager/profit/quantité dynamique

Page 3 — Données par catégories & sous-catégories

Treemap : CA par sous-catégorie (taille = volume de ventes)
Graphique à barres : Quantités vendues par nom de produit
Carte KPI : Donnée numérique associée à la sélection (catégorie ou sous-catégorie)
Graphique en courbe : Évolution du chiffre d'affaires par année


# ⚙️ Compétences Power BI mobilisées
CompétenceDétailImportationFichier Excel multi-feuilles (3 tables)Nettoyage (Power Query)Promotion des en-têtes, suppression de lignes vides, typage des colonnesModélisationSchéma en étoile : table faits Orders reliée aux dimensions People et ReturnsVisuelsKPI cards, filled map, treemap, barres empilées, histogramme, courbe temporelleInteractivitéSlicers, cross-filtering, drill-down catégorie → sous-catégorieEsthétiqueThème cohérent, logo université, organisation logique en 3 pages


# 🔍 Principaux résultats

Les managers les plus performants concentrent une part disproportionnée du profit, indépendamment du nombre de villes couvertes
La visualisation par filled map permet d'identifier immédiatement les états générant le plus de CA
Le Treemap des sous-catégories révèle une concentration des ventes sur quelques produits clés
L'évolution temporelle du CA montre une tendance exploitable pour la planification commerciale


# 📁 Contenu du repo
📦 dashboard-ventes-powerbi
 - 📄 DM2_BERRABAH_Nassim.pbix   ← Fichier Power BI
 - 📄 rapport.pdf
 - 📄 README.md

Le fichier .pbix contient les données embarquées. Nécessite Power BI Desktop pour être ouvert.


# 👤 Auteur
Nassim Berrabah — BUT Informatique, Sciences des Données
IUT de Villetaneuse, Université Sorbonne Paris Nord
