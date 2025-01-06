Introduction

According to Dias' analysis of 201 journal publications about business failure, the most well-defined causes are bankruptcy, business closure, ownership change, and failure to satisfy expectations. Forecasting,
particularly before a crisis, may shield the company from its effects, making it possibly more advantageous for the stakeholders than forecasting bankruptcy. One of the most alarming signs that a business
is on the verge of collapse is payment default. (Kohv & Lukason, 2021). Based on Basel II-which is used for risk assessment, in the banking sector, reduced-form regression-based default forecasting techniques
have gained popularity. These techniques entail multivariate regression models that forecast a firm's credit quality using information about the firm's economic and financial fundamentals. A credit score is an output.
Banks and investors use the probability of default (PD) forecasts to assess debtors before deciding whether or not to lend to them.
(Moscatelli et al., 2020). Not only are large corporates the clients of banks, but also small and medium enterprises (SMEs) are special clients who deal with banks for loans. Because lending to SMEs is riskier than lending to large corporations, techniques and risk management tools have been
developed by their characteristics (Kohv & Lukason, 2021), to make wise credit decisions, to fairly compensate the risk in the expected returns, or
to prevent financing unhealthy enterprises. The interest rates are to be shifted in the range between 4.25% - 4.50% (Federal Reserve Board). In the first place, it is essential to evaluate a firm's likelihood of failure.
Nowadays, financial ratios from historical accounting data are employed as predictor variables in machine-learning approaches to forecasting loan failure.

 METHODOLOGY

Data Source: Small Business Administration (SBA) dataset is from Kaggle. The number of observations is 899,164 and 26
features and one target. The target is determining if the firm will pay in full or default. it is a binary classification problem. The analysis will be conducted after the data-cleaning process. 
For implementation, Kaggle Notebook for (Artificial Neural Network), Visual Studio Notebook (Python 3.9.7 for pre-processing, visualization, and building machine learning models) The researchers used Kaggle Notebook, Visual Studio Notebook, Numpy, Pandas, Matplotlib, Seaborn, Date-Time, Plotly, SHAP and Power Bi (for some visualizations). 

EDA process: plotting data distribution to know if there are outliers, which distribution data follows, and if the target is balanced or not, if there are typos and strange symbols. The data cleaning process contains: removing null values, removing typos, and dropping unnecessary features.
 
For feature extraction: generating new columns that are important for analysis and prediction such as SBA proportion, duration between approval date and disbursement date, and loans backed by real estate). One Hot Encoding for categorical
features and Label Encoding for the target. For an imbalanced target, SMOTE will be used.
 
 For prediction: several supervised ML models will be used to compare prediction MCC, F1 score, and AUC score for evaluating models (Random Forest Tree, Xgboost, AdaBoost, Catboost,
 Logistic Regression, Neural Network). Overfitting will be solved using hyperparameter tuning.
