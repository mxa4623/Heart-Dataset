# ![](https://img.webmd.com/dtmcms/live/webmd/consumer_assets/site_images/articles/health_tools/did_you_know_this_could_lead_to_heart_disease_slideshow/493ss_thinkstock_rf_heart_illustration.jpg) Heart Capstone

Table of Contents:
1) [Executive Summary](#Executive-Summary)
2) [Goals][#Goals]
3) [Modeling and Evaluation Notebooks](#Modeling-and-Evaluation-Notebooks)
4) [Notebooks](#Notebooks)
5) [Approach and Process](#Approach-and-Process)
6) [Conclusion](#Conclusion)

## Executive Summary
- I was given the task to collect a dataset and work on it. I focused on the dataset on Heart Diseases which I found on CDC website. Once I get the data I need, I must clean it with EDA and do some Feature Engineering on it to make it presentable. After doing the basic alteration and modifications on the dataset at hand, I must do some Visualization on it to find the correlation and relationship between the data variables. That dataset will then be used for predicting and modeling purposes.
- The reason behind choosing the data related to Heart Diseases is to find out which Gender, Race and Age group is more at risk of the said diseases. This would help the Insurance Companies make better plans for their members.
- ![](https://img.webmd.com/dtmcms/live/webmd/consumer_assets/site_images/articles/health_tools/how_heart_disease_affects_your_body_slideshow/493ss_webmd_ed_anatomy_of_heart.jpg)

# Goals
- The goal of this project is to run Predictive Classification Models and find out in how much accuracy I can predict Heart Conditions in regards to Categories such as Age, Race & Gender etc. It will help us find out which Category is more at risk of Heart disease.

## Modeling and Evaluation Notebooks
Since we were given the task to work on a desired dataset, we divided the task at hand in 8 different notebooks. 
- The first notebook is reserved for Data Cleaning, EDA and Feature Engineering. We cleaned the dataset, did some feature engineering on the dataset at hand.
- The second notebook is reserved for Visualization where we focused more on correlation, distribution, scatter plots and line plots. 
- The third one is reserved for Modeling for Stroke Disease where we focused on working Random Forest Classification, Extra Tree Classification and did OneVSRest Classification to get the best scores out of the model. We also did Confusion Matrix on it.
- The fourth one is reserved for Modeling for Heart Failure where we focused on working Random Forest Classification, Extra Tree Classification and did OneVSRest Classification to get the best scores out of the model. We also did Confusion Matrix on it.
- The fifth one is reserved for Modeling for Heart Attack where we focused on working Random Forest Classification, Extra Tree Classification and did OneVSRest Classification to get the best scores out of the model. We also did Confusion Matrix on it.
- The sixth one is reserved for Modeling for Cardiovascular Heart Disease where we focused on working Random Forest Classification, Extra Tree Classification and did OneVSRest Classification to get the best scores out of the model. We also did Confusion Matrix on it.
- The seventh one is reserved for Modeling for Coronary Heart Disease where we focused on working Random Forest Classification, Extra Tree Classification and did OneVSRest Classification to get the best scores out of the model. We also did Confusion Matrix on it.
- The eighth one is reserved for Modeling for Heart Disease where we focused on working Random Forest Classification, Extra Tree Classification and did OneVSRest Classification to get the best scores out of the model. We also did Confusion Matrix on it.

## Notebooks
| Topic | Description | Link |
| --- | --- | --- |
| EDA and Feature Engineering | Jupyter notebook of EDA and Feature Engineering and combining the two datasets | [Link](./EDA-and-Feature-Engineering.ipynb)|
| Visualization | Visualizing the Distribution, Correlation, Charts and fixing outliers of the dataset | [Link](./Visualizations.ipynb)|
| Modeling Stroke | Jupyter notebook for Modeling on Stroke Disease of the dataset including Random Forest, Extra Tree Classification and OneVsRest Classification | [Link](./Modeling_Stroke.ipynb) |
| Modeling Heart Failure | Jupyter notebook for Modeling on Heart Failure Disease of the dataset including Random Forest, Extra Tree Classification and OneVsRest Classification | [Link](./Modeling_Heart_Failure.ipynb) |
| Modeling Heart Attack | Jupyter notebook for Modeling on Heart Attack Disease of the dataset including Random Forest, Extra Tree Classification and OneVsRest Classification | [Link](./Modeling_Heart_Attack.ipynb) |
| Modeling Cardiovascular Heart Disease | Jupyter notebook for Modeling on Cardiovascular Heart Disease of the dataset including Random Forest, Extra Tree Classification and OneVsRest Classification | [Link](./Modeling_Cardiovascular_Diseases.ipynb) |
| Modeling Coronary Heart Disease | Jupyter notebook for Modeling on Coronary Heart Disease of the dataset including Random Forest, Extra Tree Classification and OneVsRest Classification | [Link](./Modeling_Coronary_Heart_Disease.ipynb) |
| Modeling Heart Disease | Jupyter notebook for Modeling on Heart Disease of the dataset including Random Forest, Extra Tree Classification and OneVsRest Classification | [Link](./Modeling_Heart_Diseases.ipynb) |
| Data Dictionary | Data Dictionary of the Dataset|[Link](./DataDictionary.md)|

## Approach and Process
The approach towards this task was kept simple and realistic. Once I was successful in getting the dataset, I focused on how to clean it. I used the columns that would play a role in the outcome and started from there. I did feature engineering on the dataset and dummified the Topic column to get 6 diseases in binary columns. I also dummified the Breakout Category. I did the Random Forest Classification, Extra Tree Classification and OneVSRest Classification on the dataset we cleaned, and feature engineered. I also ran the confusion matrix on it.

## Conclusion
- I ran models on the diseases separately and checked the predictive scores. The scores for Stroke disease were low because it was approximate 62% of the dataset and thats the reason the results are overfit as well. The term overfit is used when the training score is greater than the testing score. The models on other diseases ran smoothly and the scores were approximate 90% for each. I also ran One Vs Rest Classification model to check the scores for all the diseases at once. The score came out low and overfit. The reason was the same, Stroke disease values were approximate 62% of the dataset. We also ran Confusion Matrix and Checked the True Positive, True Negative, False Positive and False Negative values of the models I ran. This gave me a better view of what my models look like. I was better able to check True Negative values which is a good thing.

