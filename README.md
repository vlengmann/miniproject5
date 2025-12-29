
# Mini Project 5:

This project showcases a broad knowledge of **data cleaning**, **unsupervised learning**, **supervised learning**, and **predictive modeling** across various datasets.

The analysis includes **feature scaling**,**dimensionality reduction**, **clustering**,**regularization**, and **cross-validated model comparison**.

## Datasets  


`State` State-Level socio economic indicators from `datasets`
- **Population**
- **Income**
- **Illiteracy**
- **Life Exp**
- **Murder**
- **HS Grad**
- **Frost**
- **Area**


`College` dataset (from `ISLR`)
- **Private**
- **Apps**
- **Accept**
- **Enroll**
- **Top10perc**
- **Top25perc**
- **F.Undergrad**
- **P.Undergrad**
- **Outstate**
- **Room.Board**
- **Books**
- **Personal**
- **PhD**
- **Terminal**
- **S.F.Ratio**
- **Perc.alumni**
- **Expend**
- **Grad.Rate**

Planetary Dataset of 101 confirmed exoplanets   
[Exoplanets Wiki](https://en.wikipedia.org/wiki/Exoplanet)
- **Mass**-planetary mass
- **Period**-orbital period around it's star
- **Eccentricity**- how non circular orbits are (1 is more ecclipsed, 0 is circular)

## Objective

Across all datasets, this project emphasizes 
- Proper preprocessing and scaling
- Validation
- Interpretation of unsupervised and supervised models
- Comparison of multiple approaches for conclusions

---

**State Dataset**  
Exploring state-level socio economic characterstics by standardizing variables and applying PCA to show dominant sources of variation and relationships among features

---
**College Dataset**
Compare multiple regression and dimensionality reduction techniques (linear regression, ridge, lasso, PCR and PLS) using Leave One Out Cross Validation to highlight regularization effects and predictive performance to determine enrollment of various schools


---
**Exoplanet Dataset**
Analyze groupings among exoplanets by applying hierachical clustering and k-means clustering to standardized features while comparing the clustering structures

## Methods & Analysis  

**State Dataset**  
1. Exploratory Data Analysis and Cleaning
2. Standaridization of variables
3. PCA to test variable significance of each cluster 
---
**College Dataset**

1. Fit a linear model using LOOCV to estimate the test error
2. Fit a ridge regression model using the chosen lamda by LOOCV
3. Fit a lasso model chosen by LOOCV
4. Fit a PCR model chosen by LOOCV
5. Fit a PLS model chosen by LOOCV
6. Compare results of all models
---
**Exoplanet Dataset**
1. Exploratory Data Analysis
2. Standardization of variables: single, complete, average
3. Dendograms of Complete Linkage and Euclidean Distance
4. HCA with Scaled features
5. K means, with K=3
6. Compare results
---
## Skills Demonstrated

- Data Cleaning
- Expoloratory Data Analysis
- Prinicipal Component Analysis
- Variance analysis within PCA 
- PCA Bipolts and Loadings
- Cross Validation (LOOCV)
- Partial Least Squares
- Ridge & Lasso Regression
- Prinicipal Components Regression
- Standardization
- Dendograms demonstrating complete linkage and euclidean distance
- Heierarchical and K means Clustering

## Screenshots

### PCA Biplot

<img src="https://github.com/user-attachments/assets/ee5101a4-f688-4457-94a1-292fd1305846" width="633" />

*The PCA biplot demonstrates variation across two principal dimensions, where the first dimension reflects differences in education, income, and illiteracy, and the second dimension captures variation related to state size and population.*


### Hierarchical Clustering (Complete Linkage)

<img src="https://github.com/user-attachments/assets/b11b2428-2532-4c13-ad9f-a726125b1348" width="548" />

*This dendrogram shows separation among observations driven primarily by differences in orbital eccentricity and physical scale.*

### K-Means Clustering (K = 3)

<img src="https://github.com/user-attachments/assets/be3800c3-1079-4524-bbfe-6875c8c5ff76" width="562" />

*K-means clustering produces groupings consistent with the hierarchical clustering results, indicating stable and interpretable cluster structure.*


