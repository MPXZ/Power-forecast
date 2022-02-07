# Power-forecast
# Background
Electricity is now a necessity in daily living, with the advent of smart grids, precise electric load forecasting has become increasingly critical as it enables household to schedule the optimized loads and minimize the use of wasteful electrical products. Since electricity consumption varies according to the time of day, models are constructed using time series data to forecast electricity consumption for any given time.

# Introduction
In this case, I will use various predictive models to see how accurately they are in predicting electricity usage a day ahead. Only two features: 'datetime' and 'electricity load' exist in the dataset. EDA is performed to understand data trend or any seasonility. Windowing method is used to create more useful features.

# Goals
1. Gain preliminary insight of data before building model
2. 80/20 split of data for training and testing
3. Build XGBoost model for prediction
4. Understand challenge behind electricity prediction/forecasting problem

# Content
1. Pre-process.ipynb: histroical electricty data visualization, statistical analysis, cleaning and feature eningeering
2. Model.ipynb:  Build machine leanring model to predict electricity usage one day ahdead
3. Data science report: Detailed explaination of EDA and any insight generate from data and model

# Report Outline
 ### 1. Understanding data:
 #### (a) Gather Sense of our data
 ### 2. Preprocessing
 #### (a) Convert time to datetime object
 #### (b) Distribution and correlation
 #### (c) Windowing
 #### (d) Missing data 
 ### 3.Model 
 #### (a) Featuer importance plot
 #### (b) Model results and evaluation
 #### (c) Insights and recommendation

