*English Version*

# Exploratory Data Analysis (EDA) - Titanic

## Overview
This project aims to analyze the Titanic dataset to identify the factors that influenced passenger survival.  
Through an **exploratory data analysis (EDA)** approach, we seek to understand how variables such as gender, age, social class, and ticket price played a role in survival chances.

## Repository Content
- **Titanic_EDA.ipynb** : Notebook containing the complete analysis.  
- **train.csv** : Dataset used for analysis.  
- **requirements.txt** : List of dependencies required to run the project.  
- **README.md** : Project documentation.  

## Dataset Description
The dataset includes the following columns:
- **PassengerId** : Unique identifier for each passenger  
- **Survived** : Survival indicator (0 = No, 1 = Yes)  
- **Pclass** : Travel class (1st, 2nd, 3rd)  
- **Name** : Passenger's name  
- **Sex** : Passenger's gender  
- **Age** : Passenger's age  
- **SibSp** : Number of siblings/spouses aboard  
- **Parch** : Number of parents/children aboard  
- **Ticket** : Ticket number  
- **Fare** : Ticket price  
- **Cabin** : Cabin number (if available)  
- **Embarked** : Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

## Methodology
The analysis follows several key steps:

1. **Data Loading & Preprocessing**: 
   Importing libraries, loading the dataset, handling missing values.  
2. **Exploratory Data Analysis (EDA)**: 
   Univariate analysis to understand variable distributions.  
3. **Bivariate Analysis**: 
   Studying relationships between variables and survival.  
4. **Multivariate Analysis**: 
   Cross-analysis of multiple variables to identify deeper trends.  
5. **Outlier Detection & Treatment**: 
   Identifying, analyzing, and treating extreme values to ensure reliable interpretations.  
6. **Summary of Key Insights**: 
   Drawing conclusions on the most influential survival factors.  

## Key Findings

- **Women had a significantly higher survival rate (~74%) than men (~19%).**  
- **1st class passengers had a survival rate of ~63%, compared to only ~24% in 3rd class.**  
- **Children (≤10 years) had a higher survival rate (~59%) than adults (18-50 years) (~36%) or elderly passengers (≥60 years) (~22%).**  
- **Passengers with a cabin had a survival rate of ~67%, compared to ~30% for those without a cabin.**  
- **Ticket price was correlated with survival: survivors paid an average fare of ~48.4, while non-survivors paid ~22.1.**  
- **Passengers embarking at Cherbourg had a higher survival rate (~55%), mainly because they were in 1st class.**  

## Visualizations
Here are some previews of the visualizations obtained in the analysis:
![Violinplot-Survival](https://github.com/Paul-Buchholz/Titanic-EDA/blob/main/images/violinplot_survival.png?raw=true)
![Boxplot-Fare](https://github.com/Paul-Buchholz/Titanic-EDA/blob/main/images/boxplot_fare.png?raw=true)

## Future Explorations
- **Implement Machine Learning models to predict survival probabilities.**
- **Explore more advanced visualizations (network diagrams, detailed heatmaps).**

## Business Applications
The techniques and analyses used in this study can be adapted for real-world business cases, particularly in **e-commerce** and **digital marketing**:

- **Customer Segmentation & Targeting**:
  - Using transactional and demographic data to segment customers based on purchasing behavior (similar to how we segmented Titanic passengers).
  - Adjusting marketing strategies to different profiles to enhance conversion and retention.
- **Customer Scoring & Churn Prediction**:
  - Building predictive models to identify customers at risk of churning by analyzing purchase behaviors, returns, and website interactions.
  - Designing personalized retention campaigns to anticipate and reduce customer losses.
- **Price & Promotion Optimization**:
  - Analyzing buying behavior based on price, similar to how ticket price influenced Titanic survival.
  - Implementing a **dynamic pricing model** (like Amazon or Uber) based on demand, seasonality, and consumer habits.
- **Marketing Campaign Performance Analysis**:
  - Applying exploratory analyses to evaluate the effectiveness of advertising campaigns by tracking conversion rates across acquisition channels (Google Ads, Facebook Ads, etc.).
  - Identifying the segments that respond best to different campaigns and optimizing the marketing budget accordingly.
- **Personalized Product Recommendations**:
  - Using clustering techniques (K-Means, PCA...) similar to Titanic class analysis to group customers based on shopping behavior and recommend relevant products.
  - Implementing a **recommendation system** based on purchase history and site navigation to maximize average order value and cross-selling.
- **User Experience & UX/UI Optimization**:
  - Leveraging navigation data (time spent on a page, clicks, heatmaps...) to identify friction points in the customer journey and enhance the user experience.
  - Conducting **A/B testing** on e-commerce sites and analyzing which variations convert best using techniques similar to Titanic comparisons (e.g., influence of age, gender, and ticket price on survival).

## Installation & Execution
1. **Clone the project**:  
```bash
git clone https://github.com/Paul-Buchholz/Titanic-EDA.git
cd Titanic-EDA
```
2. **Install dependencies**:
If you haven't installed the required libraries, run:
```bash
pip install -r requirements.txt
```
3. **Launch Jupyter Notebook**:
Open the analysis by running:
```bash
jupyter notebook
```
Then open and execute the file **Titanic_EDA.ipynb**.

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Manipulation)
- **Matplotlib, Seaborn** (Data Visualization)

## License
This project is under the MIT License.



  **Feel free to contribute and share your improvements!**
  
  
  
---

*Version Française* 

# Analyse Exploratoire des Données (EDA) - Titanic

## Présentation
Ce projet vise à analyser les données du Titanic afin d'identifier les facteurs ayant influencé la survie des passagers.  
À travers une approche **exploratoire (EDA)**, nous cherchons à comprendre comment des variables telles que le sexe, l'âge, la classe sociale et le prix du billet ont joué un rôle dans les chances de survie.

## Contenu du dépôt
- **Titanic_EDA.ipynb** : Notebook contenant l'analyse complète.  
- **train.csv** : Dataset utilisé pour l'analyse.  
- **requirements.txt** : Liste des dépendances nécessaires à l'exécution du projet.  
- **README.md** : Documentation du projet.  

## Données utilisées
Le dataset comprend les colonnes suivantes :
- **PassengerId** : Identifiant unique du passager  
- **Survived** : Indicateur de survie (0 = Non, 1 = Oui)  
- **Pclass** : Classe de voyage (1ère, 2ème, 3ème)  
- **Name** : Nom du passager  
- **Sex** : Sexe du passager  
- **Age** : Âge du passager  
- **SibSp** : Nombre de frères/sœurs/conjoints à bord  
- **Parch** : Nombre de parents/enfants à bord  
- **Ticket** : Numéro de ticket  
- **Fare** : Prix du billet  
- **Cabin** : Numéro de cabine (si disponible)  
- **Embarked** : Port d'embarquement (C = Cherbourg, Q = Queenstown, S = Southampton)  

## Méthodologie
L'analyse suit plusieurs étapes clés :

1. **Chargement des Données et Prétraitement**: 
	Imports des librairies, chargement des données, gestion des valeurs manquantes. 
2.  **Exploration des données** : 
	Analyse univariée pour comprendre la distribution des variables.  
3. **Analyse bivariée** : 
	Étude des relations entre chaque variable et la survie.  
4. **Analyse multivariée** : 
	Croisement de plusieurs variables pour identifier des tendances plus fines.  
5. **Détection et traitement des outliers** 
	pour éviter les biais en détectant, analysant et traitant les valeurs extrêmes pour garantir une interprétation fiable des résultats.  
6. **Synthèse des résultats et insights clés** 
	pour conclure sur les facteurs les plus déterminants.

## Résultats Clés

- **Les femmes avaient un taux de survie bien plus élevé (~74%) que les hommes (~19%).**  
- **Les passagers de 1ère classe avaient un taux de survie de ~63%, contre seulement ~24% en 3ème classe.**  
- **Les enfants (≤10 ans) avaient plus de chances de survivre (~59%) que les adultes (18-50ans)(~36%) ou les personnes âgées(≥60 ans)(~22%).**  
- **Les passagers ayant une cabine avaient un taux de survie de ~67%, contre ~30% pour ceux sans cabine.**  
- **Le prix du billet était corrélé à la survie : les survivants avaient payé en moyenne ~48.4, contre ~22.1 pour les non-survivants.**  
- **Les passagers ayant embarqué à Cherbourg avaient un taux de survie plus élevé (~55%).** (majorité de passagers en 1ère classe)

## Visualisations
Voici quelques aperçus des graphiques obtenus dans l'analyse :
![Violinplot-Survival](https://github.com/Paul-Buchholz/Titanic-EDA/blob/main/images/violinplot_survival.png?raw=true)
![Boxplot-Fare](https://github.com/Paul-Buchholz/Titanic-EDA/blob/main/images/boxplot_fare.png?raw=true)
Voici le rapport final : 

## Possibles explorations futures
- **Tester des techniques de Machine Learning pour prédire la survie.**
- **Explorer des visualisations plus avancées (diagrammes en réseau, heatmaps détaillées).**

## Applications Business
Les techniques et analyses utilisées dans cette étude peuvent être réutilisées et adaptées à des cas réels en entreprise, notamment dans le domaine du e-commerce et du marketing digital :

- **Segmentation et ciblage des clients** :
  - Utiliser des données transactionnelles et démographiques pour segmenter les clients en fonction de leurs comportements d'achat (comme nous avons segmenté les passagers du Titanic).
  - Adapter les stratégies marketing aux différents profils pour améliorer la conversion et la fidélisation.
- **Scoring client et prévision du churn** :
  - Construire des modèles prédictifs pour identifier les clients à risque de désabonnement ou de churn en analysant les comportements d’achat, les retours produits, ou les interactions avec le site.
  - Définir des campagnes de rétention client personnalisées pour anticiper et réduire les pertes de clients.
- **Optimisation des prix et promotions** :
  - Analyser les comportements d’achat en fonction du prix des produits, à l’image de l’influence du prix du billet sur la survie des passagers du Titanic.
  - Mettre en place un modèle de tarification dynamique (comme Amazon ou Uber) basé sur la demande, la saisonnalité et les habitudes des consommateurs.
- **Analyse des performances des campagnes marketing** :
  - Appliquer des analyses exploratoires pour évaluer l’efficacité des campagnes publicitaires en observant les taux de conversion en fonction des canaux d’acquisition (Google Ads, Facebook Ads, etc.).
  - Identifier les segments qui réagissent le mieux aux différentes campagnes et optimiser le budget marketing en conséquence.
- **Personnalisation des recommandations produit** : 
  - Utiliser des techniques de clustering (K-Means, PCA...) similaires à l'analyse des classes sociales du Titanic pour regrouper les clients selon leurs comportements d'achat et recommander des produits pertinents.
  - Implémenter un système de recommandations basé sur l’historique d’achat et la navigation sur le site pour maximiser le panier moyen et les ventes croisées.
- **Optimisation du parcours utilisateur et UX/UI** : 
  - Exploiter les données de navigation (temps passé sur une page, clics, heatmaps...) pour repérer les points de friction dans le parcours client et améliorer l’expérience utilisateur.
  - Tester différentes versions d’un site e-commerce (A/B testing) et analyser quelles variantes convertissent le mieux en utilisant des techniques similaires aux analyses comparatives du Titanic (ex. influence de l’âge, du sexe et du prix du billet sur la survie).

## Installation et Exécution
1. **Cloner le projet** :  
```bash
git clone https://github.com/Paul-Buchholz/Titanic-EDA.git
cd Titanic-EDA
```
2. **Installer les dépendances** :
Si vous n’avez pas encore installé les bibliothèques nécessaires, exécutez :
```bash
pip install -r requirements.txt
```
3. **Lancer Jupyter Notebook** :
Ouvrez et exécutez le notebook:
```bash
jupyter notebook
```
Then open and execute the file **Titanic_EDA.ipynb**.
## Technologies utilisées
Python
Pandas, NumPy (Manipulation des données)
Matplotlib, Seaborn (Visualisation des données)

## Licence
Ce projet est sous licence MIT.


**N'hésitez pas à contribuer et à partager vos améliorations !**