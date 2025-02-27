*English Version*

# Final Report: Exploratory Data Analysis (EDA) - Titanic

## **Context and Objectives**
The objective of this analysis was to identify the factors influencing passenger survival during the sinking of the Titanic in 1912.  
We explored various variables such as gender, age, social class, and ticket price to understand which had a significant impact on survival chances.

1. **Data Loading and Preprocessing**: Importing libraries, loading data, handling missing values.  
2. **Exploratory Data Analysis**: Univariate analysis to understand variable distributions.  
3. **Bivariate Analysis**: Studying relationships between each variable and survival.  
4. **Multivariate Analysis**: Cross-referencing multiple variables to identify deeper trends.  
5. **Detection and Treatment of Outliers** to avoid bias.  
6. **Summary of Results and Key Insights** to conclude on the most determining factors.

## **Summary of Results and Key Insights**

### **1- Sociodemographic Factors Influencing Survival**

#### **Gender**  
- **Survival rate of women**: ~**74%**  
- **Survival rate of men**: ~**19%**  
Confirms a strong disparity linked to the *"women and children first"* rule.  

#### **Age**  
- **Survival rate of children (≤10 years)**: ~**59%**
- **Survival rate of adolescents (11-17 years)**: ~**43%**
- **Survival rate of adults (18-50 years)**: ~**36%**
- **Survival rate of seniors (51-59 years)**: ~**40%**  
- **Survival rate of elderly passengers (≥60 years)**: ~**22%**  
Young children had a survival advantage, whereas elderly passengers had lower survival rates.

#### **Class (Pclass)**  
- **Survival rate in 1st class**: ~**63%**  
- **Survival rate in 2nd class**: ~**47%**  
- **Survival rate in 3rd class**: ~**24%**  
First-class passengers had priority access to lifeboats, significantly increasing their survival chances.

### **2- Influence of Ticket Characteristics**

#### **Ticket Price (Fare)**  
- **Average ticket price of survivors**: ~**48.4**  
- **Average ticket price of non-survivors**: ~**22.12**  
Confirms a correlation between ticket price and survival.  

#### **Cabins (Has_Cabin)**  
- **Survival rate of passengers with a cabin**: ~**67%**  
- **Survival rate of passengers without a cabin**: ~**30%**  
Having a cabin was a strong indicator of better access to lifeboats.  

### **3- Impact of Embarkation Port**  
- **Cherbourg (C)**: **Survival rate ~55%** (majority of passengers in 1st class).  
- **Southampton (S)**: **Survival rate ~34%** (majority of passengers in 3rd class).  
- **Queenstown (Q)**: **Survival rate ~39%** (mainly 3rd class passengers).  

---

### **4- Influence of Family Size**  
- **Traveling alone**: **Survival rate ~30%**.  
- **Small families (2-3 members)**: **Survival rate ~50%**.  
- **Large families (≥4 members)**: **Survival rate ~23%**.  

---

## **Final Conclusion**  
The analysis revealed that **gender, class, ticket price, and having a cabin** were the main factors influencing Titanic passengers' survival.  

🔹 **Women and children** had significantly higher survival chances.  
🔹 **Social class** played a crucial role, with first-class passengers having the highest survival rates.  
🔹 **Ticket price and having a cabin** were strong indicators of survival.  
🔹 **Survival rates were higher among passengers who embarked at Cherbourg**, mainly due to their high proportion in 1st class.  
🔹 **Family size also influenced survival**, with larger families struggling to evacuate together.  

## **Future Perspectives**  
- Test **Machine Learning models** to predict passenger survival.  
- Explore advanced visualizations to better understand variable interactions.  

## **Business Applications**  
The techniques and analyses used in this study can be adapted for real-world business applications, particularly in **e-commerce and digital marketing**:

- **Customer Segmentation and Targeting**:  
  - Use transactional and demographic data to segment customers based on their purchasing behavior (similar to how Titanic passengers were analyzed).  
  - Adapt marketing strategies to different profiles to improve conversion rates and customer retention.  

- **Customer Scoring and Churn Prediction**:  
  - Build predictive models to identify customers at risk of churn by analyzing purchasing behaviors, product returns, and website interactions.  
  - Implement personalized retention campaigns to anticipate and reduce customer loss.  

- **Pricing and Promotion Optimization**:  
  - Analyze purchasing behaviors in relation to product prices, similar to the effect of ticket price on Titanic survival.  
  - Develop a dynamic pricing model (like Amazon or Uber) based on demand, seasonality, and customer habits.  

- **Marketing Campaign Performance Analysis**:  
  - Use exploratory data analysis to assess advertising campaign effectiveness by tracking conversion rates across acquisition channels (Google Ads, Facebook Ads, etc.).  
  - Identify which segments respond best to different campaigns and optimize the marketing budget accordingly.  

- **Personalized Product Recommendations**:  
  - Apply clustering techniques (K-Means, PCA...) similar to Titanic class analysis to group customers based on their purchasing behavior and recommend relevant products.  
  - Implement a recommendation system based on purchase history and site navigation to maximize average cart value and cross-sales.  

- **User Experience (UX/UI) Optimization**:  
  - Analyze navigation data (time spent on pages, clicks, heatmaps...) to identify friction points in the customer journey and enhance user experience.  
  - Conduct A/B testing to determine which website versions convert best, using similar comparative techniques as in the Titanic analysis (e.g., impact of age, gender, and ticket price on survival).  

*Thank you for following this analysis!*

---

*Version Française*

# Rapport final : Analyse Exploratoire des Données (EDA) - Titanic

## **Contexte et Objectifs**
L'objectif de cette analyse était d’identifier les facteurs influençant la survie des passagers lors du naufrage du Titanic en 1912.
Nous avons exploré diverses variables, telles que le sexe, l'âge, la classe sociale et le prix du billet, afin de comprendre lesquelles ont eu un impact significatif sur les chances de survie.

1. **Chargement des Données et Prétraitement**: Imports des librairies, chargement des données, gestion des valeurs manquantes. 
2.  **Exploration des données** : Analyse univariée pour comprendre la distribution des variables.  
3. **Analyse bivariée** : Étude des relations entre chaque variable et la survie.  
4. **Analyse multivariée** : Croisement de plusieurs variables pour identifier des tendances plus fines.  
5. **Détection et traitement des outliers** pour éviter les biais.  
6. **Synthèse des résultats et insights clés** pour conclure sur les facteurs les plus déterminants.

## **Synthèse des résultats et insights clés**

### **1- Facteurs sociodémographiques influençant la survie**

#### **Sexe**  
- **Taux de survie des femmes** : ~**74%**  
- **Taux de survie des hommes** : ~**19%**  
Confirme une forte disparité liée à la règle *"women and children first"*.  

#### **Âge**  
- **Taux de survie des enfants (≤10 ans)** : ~**59%**
- **Taux de survie des adolescents (11-17 ans)** : ~**43%**
- **Taux de survie des adultes (18-50 ans)** : ~**36%**
- **Taux de survie des seniors (51-59 ans)** : ~**40%**  
- **Taux de survie des personnes âgées (≥60 ans)** : ~**22%**  
Les jeunes enfants ont bénéficié d’un avantage, tandis que les personnes âgées ont eu un taux de survie réduit.

#### **Classe (Pclass)**  
- **Taux de survie en 1ère classe** : ~**63%**  
- **Taux de survie en 2ème classe** : ~**47%**  
- **Taux de survie en 3ème classe** : ~**24%**  
Les passagers en 1ère classe avaient un accès prioritaire aux canots, augmentant significativement leur survie.

### **2- Influence des caractéristiques du billet**

#### **Prix du billet (Fare)**  
- **Moyenne du prix du billet des survivants** : ~**48.4**  
- **Moyenne du prix du billet des non-survivants** : ~**22.12**  
Confirme une corrélation entre le prix du billet et la survie.  

#### **Cabines (Has_Cabin)**  
- **Taux de survie des passagers ayant une cabine** : ~**67%**  
- **Taux de survie des passagers sans cabine** : ~**30%**  
La présence d’une cabine était un indicateur fort d’un meilleur accès aux canots.  


### **3- Impact du port d'embarquement**  
- **Cherbourg (C)** : **Taux de survie ~55%** (majorité de passagers en 1ère classe).  
- **Southampton (S)** : **Taux de survie ~34%** (majorité de passagers en 3ème classe).  
- **Queenstown (Q)** : **Taux de survie ~39%** (principalement des passagers en 3ème classe).  

---

### **4- Influence de la taille des familles**  
- **Voyager seul(e)** : **Taux de survie ~30%**.  
- **Petites familles (2-3 personnes)** : **Taux de survie ~50%**.  
- **Grandes familles (≥4 personnes)** : **Taux de survie ~23%**.  

---

## **Conclusion finale**  
L’analyse a révélé que **le sexe, la classe, le prix du billet et la présence d’une cabine** étaient les principaux facteurs influençant la survie des passagers du Titanic.  

🔹 **Les femmes et les enfants** avaient significativement plus de chances de survivre.  
🔹 **La classe sociale** a joué un rôle crucial, avec une nette supériorité de survie en 1ère classe.  
🔹 **Le prix du billet et la présence d’une cabine** étaient des indicateurs forts de la survie.  
🔹 **Le taux de survie était plus élevé parmi les passagers embarquant à Cherbourg**, principalement en raison de leur forte proportion en 1ère classe.  
🔹 **La taille de la famille influençait également la survie**, les grandes familles ayant des difficultés à évacuer ensemble.  

**Perspectives futures**  
- Tester des modèles de **Machine Learning** pour prédire la survie des passagers.  
- Explorer des visualisations avancées pour mieux comprendre les interactions entre variables.  

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


*Merci d’avoir suivi cette analyse !*