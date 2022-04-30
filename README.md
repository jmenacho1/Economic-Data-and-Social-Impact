![image1](smiley.jpg)

![firstimage](/Images/crude_retail_1.jpg)
---

# Economic Data and NYC Social Impact since 2006

---

## Project Goal
 
* Use Statistical Model for Predictive Purposes

**What are we trying to solve for?**

- [X] Seek to Use the Most Relevant Features of NYC Shootings Dataset to Predict Future Period Shootings
- [X] Combine Macroeconomic Data along with Primary Dataset to deduct causality between Economic Datapoints and NYC shootings
- [X] Utilize NLP to Assess News Story Sentiment and overlay with Primary Dataset

## What is hypothesis?

<p>A Softening in Economic Barometers leads to Social Unrest 

 ---

## Process

* Bring in and Clean Data
* Assess various Features in dataset and attempt to intuitively maintain Relevant Ones
* Visualize correlation Matrix
* Run Linear Regression and Assess Model
* Perform PCA to determine Correct Features to be Used
* Visualize Uplift in Model Change
* Run and Evaluate Decision Tree Regression
* Run and Evaluate Random Forrest Regression
* Run and Evaluate Gradient Boosting Regressor
* Change Features to be more Intuitive and Discrete
* Rerun and Evaluate Linear Regression, Decision Tree, and Random Forrest Models
* Perform NLP Analysis and attempt to incorporate into Dataset 

---
## What Data/Modeling issues did we Run into?

![image2](deadend.jpg)

* NLP - API Data Permissioning and Inability to Attain Long-Term Historical Data
    * NewsAPI, NYT, and Bloomberg dead ends

* Initial Regression Model proved to be too perfect because of Linearity between Features and Labels

![image3](axis.jpg)

![image4](regression.jpg)

## Where did we get our data?

* "Data.gov"
    * NYPD Shooting Incident Data (Historic)
    * NYPD Shooting Incident Data (YTD)

* Bloomberg Data for Economics

## Caveats and Considerations
* General Economic Prosperity enjoyed over scope of Dataset
* Different Crime-battling regimes and Methods (i.e. Stop-And-Frisk)
* Is Social Unrest that is Independent of Economic Malaise skewing Data?
