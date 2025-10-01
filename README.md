# 📊 Data Jobs Dashboard : Analyse du Marché des Métiers de la Donnée

## Introduction

Ce projet Power BI, **"Data Jobs Dashboard"**, offre une analyse approfondie des tendances du marché de l'emploi dans le domaine de la donnée. Il permet d'explorer des indicateurs clés tels que le nombre d'offres d'emploi, les salaires médians (annuels et horaires), l'évolution des postes au fil du temps, et des statistiques détaillées par titre de poste. L'objectif est de fournir des insights précieux aux professionnels de la data, aux étudiants, aux recruteurs et aux décideurs stratégiques.

## Fonctionnalités Clés du Dashboard

Le tableau de bord est organisé en plusieurs sections interactives pour une exploration facile :

1.  **Vue d'Ensemble des Emplois (`Data Jobs Dashboard`)** :
    _ **Indicateurs globaux** : Nombre total d'offres (Job Count), Taux de satisfaction salariale (Salary Star Rating), Salaires médians annuels et horaires.
    _ **Tendances temporelles** : Graphique "Jobs over Time" montrant l'évolution du nombre d'offres.
    _ **Répartition des offres** : Graphique "Job Counts" par titre de poste, mettant en évidence les rôles les plus demandés (ex: Data Engineer).
    _ **Analyse salaire vs. poste** : Nuage de points "Hourly vs Median Salary" comparant les salaires horaires médians aux salaires annuels médians par type de poste.
    _ **Statistiques détaillées** : Table "Job Stats" fournissant des chiffres précis (Job Count, Salary Median, Hourly Median, Salary Star Rating) pour chaque titre de poste.
    _ **Filtre interactif** : Un slicer "Job Title" permet de filtrer l'ensemble du dashboard par type de poste.
    ![Dashboard page 1](/Images/Dashboard.png)
2.  **Exploration Détaillée par Poste (`Job Title Drill Through`)** :
    _ Accès via la fonctionnalité "Drill Through" depuis la page "Data Jobs Dashboard" en sélectionnant un titre de poste.
    _ **Statistiques salariales avancées** : Vues détaillées des salaires annuels et horaires pour le poste sélectionné.
    _ **Conditions de travail** : Diagrammes circulaires sur le télétravail ("Work From Home"), la mention du diplôme non requise ("No Degree Mention"), et l'assurance santé ("Health Insurance").
    _ **Localisation géographique** : Carte "Jobs Globally" visualisant la répartition mondiale des offres pour le poste sélectionné.
    _ **Plateformes de recrutement** : Bar chart "Job Platform" montrant les canaux les plus utilisés pour la publication des offres.
    _ **Type de contrat** : Bar chart "Job Schedule Type" indiquant la prédominance du temps plein.
    ![Dashboard page 2](/Images/job_drill.png)

## Technologies Utilisées

- **Power BI Desktop** : Pour la conception du tableau de bord, l'intégration des données, la modélisation et la création des visualisations interactives.
- **DAX (Data Analysis Expressions)** : Pour les calculs complexes et les mesures personnalisées.
- **Power Query / M Language** : Pour la transformation et le nettoyage des données sources.
## Structure du Projet (dans Power BI)

- **Modèle de Données** : Organisation des tables et des relations pour optimiser les performances et la clarté.
- **Mesures DAX** : Définition des indicateurs clés (salaires médians, décomptes, etc.).
- **Visualisations** : Utilisation variée de graphiques (lignes, barres, nuages de points, jauges, cartes, tables) pour une représentation claire et interactive des données.
- **Fonctionnalité Drill Through** : Mise en place d'une exploration hiérarchique pour affiner l'analyse sur des postes spécifiques.

## Comment Utiliser le Dashboard

1.  **Télécharger le fichier Power BI** : `Data Jobs Dashboard.pbix` depuis ce dépôt.
2.  **Ouvrir avec Power BI Desktop**.
3.  **Naviguer entre les pages** : Utilisez les boutons de navigation "Home", "Data Jobs" et "Job Title Drill Through" (ce dernier s'active en sélectionnant un point sur un graphique ou une ligne dans la table et en utilisant le menu contextuel "Drill Through").
4.  **Interagir avec les filtres** : Utilisez le slicer "Job Title" pour affiner votre analyse sur un ou plusieurs postes spécifiques.
5.  **Explorer les détails** : Cliquez sur les éléments des graphiques pour voir les interactions et les filtres automatiques.

## Contact

Pour toute question ou collaboration, n'hésitez pas à me contacter :

- **Mohamed EL ARCHAOUI**
- **LinkedIn** : [Lien vers votre profil LinkedIn, ex: `linkedin.com/in/mohamed-el-archaoui`]
- **Email** : [Votre adresse e-mail, ex: `mohamedelarchaoui766@gmail.com`]

---


