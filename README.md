# ACX3300 Projects - Financial Statement Analysis and Fraud Prediction

This repository contains two projects completed as part of the ACX3300 course, focusing on financial statement analysis and fraud prediction. These projects showcase my ability to apply statistical and econometric techniques to real-world financial data, demonstrating skills that are highly relevant to roles in financial analysis, risk management, and forensic accounting.

**Project 1: Forecasting Earnings and Return on Net Operating Assets**

* **Problem:** Accurate forecasting of financial performance metrics is crucial for investment decisions and corporate planning. This project aimed to forecast earnings per share (EPS) and return on net operating assets (RNOA) using various statistical models.
* **Task:**
    * Clean and prepare financial data from Compustat.
    * Construct relevant financial ratios and variables.
    * Implement and evaluate the performance of different forecasting models, including random walk, moving average, and regression models based on the Soliman (2008) framework.
* **Methods:**
    * Data cleaning and winsorization to handle outliers.
    * Descriptive statistics and correlation analysis.
    * Time series forecasting techniques.
    * Ordinary least squares (OLS) regression.
    * Stepwise regression for model selection.
    * Backtesting to assess model accuracy.
* **Findings:**
    * The moving average model generally outperformed the random walk model in forecasting EPS.
    * The Soliman (2008) regression model provided valuable insights into the drivers of RNOA.
    * Backtesting revealed that a simple 1-year random walk model often outperformed the more complex Soliman (2008) model in predicting RNOA, highlighting the importance of model parsimony.
* **Key Learnings:**
    * The importance of rigorous data cleaning and preparation in financial analysis.
    * The application of various forecasting techniques and their relative strengths and weaknesses.
    * The significance of model selection and validation in ensuring robust predictions.

**Project 2: Predicting Accounting Fraud Using the Dechow et al. (2011) Model**

* **Problem:** Accounting fraud poses significant risks to investors and the integrity of financial markets. This project aimed to evaluate the effectiveness of the Dechow et al. (2011) model in predicting fraudulent financial reporting.
* **Task:**
    * Prepare and analyze financial data from Compustat and Audit Analytics.
    * Construct variables based on the Dechow et al. (2011) model.
    * Estimate logistic regression models to predict the likelihood of fraud.
    * Assess the model's predictive power using various metrics.
* **Methods:**
    * Data cleaning and winsorization.
    * Descriptive statistics and correlation analysis.
    * Logistic regression.
    * Model selection using stepwise regression.
    * Backtesting to evaluate model performance in a real-world setting.
* **Findings:**
    * The Dechow et al. (2011) model demonstrated some predictive power in identifying fraudulent firms, but its performance varied compared to the original study.
    * Certain financial variables, such as changes in receivables and inventory, were not statistically significant predictors of fraud in this dataset.
    * The model's predictive power was not considered acceptable based on the area under the ROC curve, suggesting the need for further refinement or alternative approaches.
* **Key Learnings:**
    * The application of logistic regression in a fraud prediction context.
    * The importance of understanding the limitations of statistical models and the need for continuous improvement.
    * The challenges of predicting rare events like accounting fraud.

**Skills Developed**

* **Technical Skills:**
    * Data cleaning and preparation using SAS.
    * Statistical analysis and modeling using SAS and PROC SQL.
    * Proficiency in logistic regression and time series forecasting.
    * Experience with model selection and validation techniques.
* **Soft Skills:**
    * Critical thinking and problem-solving in a financial context.
    * Ability to interpret and communicate complex statistical results to both technical and non-technical audiences.
    * Attention to detail and accuracy in data analysis.
