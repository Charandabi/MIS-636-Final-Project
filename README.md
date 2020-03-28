# MIS-636: Final-Project

# Prediction of the Success of Bank Telemarketing

#### Drexel University, Department of Decision Science

# Abstract
>_Within the banking industry, optimizing targeting for telemarketing is a key issue under a growing pressure to revenue management. The objective of this study is to use of data-driven models to predict the success of direct marketing campaigns (such as phone calls) to sell long term deposits._


# Data

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution across 2008 to 2013.The classification goal is to predict if the client will subscribe a term deposit (variable y).
Different types of variables are included in data, including:client data, Parameters related with the last contact of the current campaign and Social and economic context attributes.
This dataset is obtainable from the following link: 
https://www.kaggle.com/suhasshastry/bank-marketing-analysis-for-term-deposit

# Outline of the Project

This project was developed in the following sections:

- Data Description  
- Discriptive Statistics
- Visualizations
- Data Preprocessing
- Making Predictions and Model Assessment  
    - All variables are included in the model
    - Highly-corelated variables are excluded
    - Variables subjected to cause bias are excluded
    - Variables assumed to be less imporatnt in making difference are excluded
- Discussion on the Statistical Significance
    
# Required Libraries
- Pandas
- numpy
- seaborn
- matplotlib
- sklearn
- statsmodels

# Remarks

- Client data, parameters related with the last contact of the current campaign, and economic context attributes can decently predict the success or failure of a telemarketing campaign in the Banking industry.

- Current results are based on obtainable data from a Portuguese banking institution, thus not essentially generalizable. 

- Curent dataset lacks important information about the interst rate factor while it is assumed to be of great importance in discouraging or incentivizing clients in response to telemarketing campaigns.

