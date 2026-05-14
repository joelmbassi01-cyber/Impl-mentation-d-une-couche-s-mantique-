# Impl-mentation-d-une-couche-s-mantique-

📌**Présentation du projet**

Ce projet présente la conception complète d’une couche sémantique basée sur SQL Server Analysis Services (SSAS) Tabular ainsi que la création de tableaux de bord interactifs avec Power BI.

Le projet s’appuie sur la base de données AdventureWorksDW2019 et met en œuvre les principales composantes d’une architecture décisionnelle moderne :

Modélisation tabulaire
Création de mesures DAX
Gestion des relations et hiérarchies
Développement d’un modèle sémantique (.bim)
Visualisation analytique avec Power BI
Analyse des ventes Internet et Revendeurs

L’objectif principal est de fournir une couche analytique performante permettant l’exploration, l’analyse et la visualisation des données d’entreprise.

🛠️ **Technologies utilisées**
Microsoft SQL Server
SQL Server Analysis Services (SSAS) Tabular
Power BI Desktop
DAX (Data Analysis Expressions)
Visual Studio / SQL Server Data Tools (SSDT)
AdventureWorksDW2019

📂 **Structure du projet**

├── Couche_sem.sln          # Solution Visual Studio
├── Model.bim               # Modèle tabulaire SSAS
└── Visualisations.pbix     # Rapport Power BI

🧠 **Architecture du modèle sémantique**

Le modèle tabulaire est construit autour d’un schéma en étoile composé de plusieurs dimensions et tables de faits.

📊 Tables de dimensions
DimCustomer
DimDate
DimProduct
DimPromotion
DimCurrency
DimEmployee
DimSalesTerritory 

📈 Tables de faits
FactInternetSales
FactResellerSales
FactSalesQuota

📐 **Fonctionnalités implémentées**
✔️ Modélisation tabulaire
Création des relations entre faits et dimensions
Configuration du modèle sémantique
Gestion des clés et hiérarchies
Optimisation du modèle analytique

✔️ Mesures DAX
Le projet contient plusieurs mesures analytiques permettant :

L’analyse des ventes
Le suivi des revenus
L’évaluation des performances commerciales
Le calcul des quotas
Les analyses temporelles
Les indicateurs de croissance

✔️ Visualisation Power BI
Le fichier Power BI permet de visualiser :

Les ventes Internet
Les ventes revendeurs
Les performances par territoire
Les analyses temporelles
Les indicateurs clés de performance (KPI)
Les tendances commerciales

📊 **Exemples d’analyses possibles**
Évolution des ventes par année
Comparaison ventes Internet vs Revendeurs
Analyse des performances par territoire
Analyse des promotions
Analyse des produits les plus performants
Suivi des quotas de vente
Analyse des revenus par client

⚙️ **Configuration requise**
Logiciels nécessaires
SQL Server 2019 ou supérieur
SQL Server Analysis Services (mode Tabular)
Visual Studio avec SSDT
Power BI Desktop
Base de données utilisée
AdventureWorksDW2019

🚀 **Exécution du projet**
1. Cloner le dépôt
git clone https://github.com/votre-utilisateur/votre-repository.git

2. Ouvrir la solution
Ouvrir le fichier avec Visual Studio:
Couche_sem.sln

3. Configurer la connexion SQL Server
Modifier au besoin la source de données dans le modèle tabulaire afin de pointer vers votre instance SQL Server.
Exemple : AdventureWorksDW2019

4. Déployer le modèle SSAS
Compiler le projet
Déployer vers une instance SSAS Tabular
Traiter le modèle

5. Ouvrir le rapport Power BI
Ouvrir Visualisations.pbix puis actualiser les données.

📚 Concepts BI exploités
Ce projet met en pratique plusieurs concepts de Business Intelligence :

Modélisation dimensionnelle
Schéma en étoile
Couche sémantique
Mesures DAX
KPI
Analyse OLAP
Reporting analytique
Data Visualization
SSAS Tabular

🎯 Objectifs pédagogiques
Ce projet a été réalisé dans le but de :

Comprendre l’architecture d’un modèle tabulaire
Développer une couche sémantique professionnelle
Manipuler DAX dans un contexte réel
Concevoir des tableaux de bord Power BI
Développer des compétences en Business Intelligence

👨‍💻 Auteur
Stanislas Joël Mbassi Awona
Projet académique et pratique autour de la Business Intelligence, SSAS Tabular et Power BI.

📄 Licence
Projet à but éducatif et démonstratif.
