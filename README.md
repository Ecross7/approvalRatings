# I Approve this message: Examining the personified characteristics of U.S. Senators to predict job approval ratings​
UMBC Spring 2024 - DATA606 Data Science Capstone
Team 2: Saikumar Baddam, Elizabeth Cardosa, Ebony Cross-Williams

## Project Introduction
@Sai

## Background 
@Sai

## Datasets
@Sai
 TODO: 
 * describe each dataset used
 * include equations for valence metrics
 * list features and target found in final modeling
 * (optional) include graphics from final presentations EDA slides

Correlation Analysis: 
![Correlation Analysis](https://github.com/Ecross7/approvalRatings/blob/main/notebooks/correlation_analysis.png)

## Models
@ Sai 

| Metric | Decision Tree | CatBoost Regressor | ANN (ReLu) |
| --- | --- | --- | --- |
| Train MSE | 21.69 | 12.61 | 16.40 |  
| Train MAE | 3.35 | 2.58 | 2.90 | 
| Train R2 | 0.56 | 0.75 | 0.69 |
| Test MSE | 24.57 | 17.71 | 22.44 |
| Test MAE | 3.59 | 3.08 | 3.44 |
| Test R2 | 0.60 | 0.74 | 0.578 | 

CatBoost Regressor Feature Importances: 
![CatBoost Feature Importances](https://github.com/Ecross7/approvalRatings/blob/main/notebooks/catbosst_feature_importances.png)

## Conclusions 
@ Sai - TODO: modify with your desired talk-track/conclusions 

* Obtained a good model for predicting Senator's Approval Ratings​
  * Can be used for campaign and election planning​
  * Can be used to glean insights into Senator's performance at any point in cycle​

* Identified key factors for Senator's Job Approval Ratings​
  * The Stage of the election – particularly if in Jungle Primary​
    * "Majority-vote primary paired with a plurality-vote general election"​
  * Ideology – A function of party and voting patterns​
    * Somewhat correlated with "bills-with-companion" and "cosponsored bills"​
  * Valence – A measure of emotional profile


# Future Work: 

## Target User(s)
* Senators/Campaign managers​
  * Identify performance at a given point in time to influence voting decisions, public persona, and engagement​

* Tailor campaign strategies based on predicted approval ratings​
  * Use localized feature importances to understand impacts of demographic and voting behavior on job approval rating​
  
* Voters​
  * Model Senators approval ratings in the future to help identify optimal candidate to vote for

## Deployment 
* User Interface – Intuitive way to interact with and glean insights from model inferences​
  * Visualizations​ 
  * Explanations​
  * App that allows a Senator to use their device camera in real-time or uplaod photos to analyze their emotion and "persona" to predict their JAR 

* Model Retraining - Whenever new polling data comes out retrain model with updated data set​
  * Scheduled vs. Automatic based on available data​
  * Complete retraining vs. Fine-tuning​
  
* DevOps/MLOps – Establish infrastructure to automatically deploy and update project​
  * Continuous model integration​
  * Monitoring of model performance 

## Additional Analysis: 
* Train project-specific emotion classifier/valence regressor
  * Use the EMOTIC dataset to train a model specifically built with a subset of emotions to best represent a politician's "persona" 

* Curate more data
  * Gather more senator images
  * Obtain JARs over longer period of time, representing more senators as well

* World Events effects on JARs
  * Perform analysis of global events, such as COVID-19, wars, economic crisis on JARs and if there are any trends that arrise that could be used to predict future JARs during world events.

* Clustering Analysis
  * Perform clustering to see if natural trends arise in the senator datasets such as relationships between demographic data, persona characeteristics, party, etc. 

# Repository How-to Guide
## data 
@Ebony

## notebooks 
@Ebony

## team_csv_code
@Ebony
