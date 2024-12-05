 # Home-Credit-Default-Risk

## Summary of Business Problem and Project Objective:
Many individuals lack access to loans due to insufficient or non-existent credit histories.
Objective: Develop a predictive model to assess loan default risk, enabling better lending decisions and financial inclusion.

## Steps & Contributions to the Project
- Built a supervised classification model to predict loan default risk for clients with limited credit history.
- Cleaned and preprocessed data, handling missing values and aligning training and test sets.
- Implemented and compared models (Logistic Regression, Random Forest, Gradient Boosting) using metrics like AUC (0.617), precision, and recall.
- Identified key predictors (e.g., demographic and external scores) to improve credit risk assessment.
- Delivered business recommendations to enhance financial inclusion and reduce loan defaults.

## Group's Solution to the Business Problem:
- Built a classification model using alternative data (e.g., demographics, external scores) to predict default risk.
- Conducted feature selection and preprocessing to improve prediction accuracy and stability.
- Compared multiple machine learning models to find the best-performing approach.

## The Business Value of the Solution:
- Improved risk identification for loan approvals, reducing default rates.
- Expanded financial inclusion by enabling underserved clients to access loans responsibly.
- Enhanced decision-making with insights into key predictors of default risk.

## Difficulties my Group Encountered Along the Way:
- Aligning training and test datasets due to inconsistent column structures and factor levels.
- Addressing missing values and high-dimensional data with extensive preprocessing.
- Interpreting AUC and other metrics for business-friendly communication.

## What I Learned in the Project:
- Handling complex datasets with missing values and high cardinality.
- Comparing and interpreting machine learning models using business-relevant metrics.
- Translating technical findings into actionable recommendations for stakeholders.


### EDA
Analyzing outliers, columns with missing values by %, etc. This and highly correlated factors were the columns used in modeling.

![]([https://github.com/anaiscorral/Home-Credit-Default-Risk/blob/main/EDA%20.png)
![](https://github.com/anaiscorral/Home-Credit-Default-Risk/blob/main/EDA%202.png)
![](https://github.com/anaiscorral/Home-Credit-Default-Risk/blob/main/EDA%203.png)

### Findings

After EDA, these are the key predictors we focused on. With this, we were able to identify, based on demographics, the lower-risk profile clients for better targets and loan decisions from Home Credit.

![](https://github.com/anaiscorral/Home-Credit-Default-Risk/blob/main/Findings.png)
![](https://github.com/anaiscorral/Home-Credit-Default-Risk/blob/main/Findings%202.png)
![](https://github.com/anaiscorral/Home-Credit-Default-Risk/blob/main/Findings%203.png)
