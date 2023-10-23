# ACCURATE-CALORIE-BURN-PREDICTION-WITH-MACHINE-LEARNING-XGBOOST-IN-FOCUS-
The application of machine learning models, including the XGBoost regressor, Linear Regression,  Decision Tree Regressor, and Random Forest Regressor, allowed us to evaluate prediction accuracy. The results  demonstrated that the XGBoost regression model consistently outperformed other algorithms.

**A. Data Collection:** 
MODELING AND ANALYSIS 
Our research journey commences with the pivotal step of data collection. To assemble the requisite dataset, we 
turn to Kaggle, a prominent and trusted data repository renowned for its diverse and comprehensive datasets. 
Specifically, we utilize Kaggle as the primary data source for our study. This rich dataset is subsequently loaded 
into the Colaboratory (Colab) program, a robust and versatile platform for data analysis. Notably, the data we 
have retrieved encompasses a wide range of information, comprising both categorical and numerical attributes. 

**B. Data Preprocessing:** 
Within this dataset, we discover a treasure trove of valuable information, comprising a substantial collection of 
15,000 instances. These instances span across two distinct CSV files, aptly named "exercise.csv" and 
"calorie.csv." Each entry in this comprehensive dataset corresponds to an individual, encapsulating a wealth of 
attributes, including but not limited to height, weight, gender, age, exercise duration, heart rate, and body 
temperature. This meticulously collected dataset forms the bedrock of our analysis, allowing us to delve into 
the intricate relationships between these attributes and calorie burn. 

**C. Data Analysis:** 
In the pursuit of insightful data analysis, we rely on the capabilities of the Colab platform, chosen for its 
prowess in processing and visualizing complex datasets. To initiate our analysis, we upload the aforementioned 
dataset files, "exercise.csv" and "calorie.csv," into the platform. During the course of our analysis, we uncover 
intriguing observations, such as the notable presence of an average body temperature of approximately 40 
degrees Celsius. Additionally, it becomes apparent that individuals engaged in physical activity tend to exhibit 
higher body temperatures, shedding light on the relationship between exercise and physiological responses. 
Notably, heart rate and core body temperature emerge as pivotal factors during this analytical phase. To 
enhance the comprehensibility of our findings, we employ various visualization techniques, ranging from tables 
to charts. Furthermore, we delve into the exploration of correlation types, including positive and negative 
correlations, to gain deeper insights into the interplay between different data records. Subsequently, we 
introduce the XGBoost Regressor model, a powerful machine learning tool, and rigorously evaluate its 
predictive capabilities. This evaluation involves testing the model with a specific dataset and comparing its 
predicted calorie burn values with the actual values, enabling a thorough assessment of its performance. 

**D. Machine Learning Model:** 
In the realm of machine learning, this stage is pivotal, as it marks the application of our chosen algorithms to 
estimate the mean absolute error—a critical metric for gauging prediction accuracy. In this instance, we 
leverage multiple algorithms, including the XGBoost regressor, Linear Regression, Decision Tree Regressor, and 
Random Forest Regressor, to scrutinize and assess their respective performance levels. Utilizing key 
performance indicators, we gauge the models' ability to produce accurate predictions, shedding light on the 
precision of each algorithm's calorie burn estimations. Importantly, the XGBoost regression algorithm has been 
selected for its demonstrated effectiveness and efficiency in predicting calorie expenditure. 

**E. Evaluation:** 
Our analysis of this dataset extends to making predictions regarding calorie expenditure based on exercise 
duration and a myriad of additional factors, encompassing age, gender, body temperature, and heart rate at 
various time points during physical activity. The overarching objective is to identify a machine learning model 
capable of delivering lower mean absolute error, indicative of more accurate and reliable calorie burn 
predictions. Through the rigorous application of various machine learning methodologies, we aim to enhance 
our understanding of the intricate relationship between physiological variables and calorie expenditure during 
exercise, ultimately striving to provide more precise estimations of calorie burn for informed health and fitness 
decisions.


**XGB Regressor** 

Evaluation of the model's performance using various metrics:- 

r2 score(R-squared (R2)) score: 0.9962383848898505 

MAE (Mean Absolute Error): 2.748654327124357 

MSE (Mean Squared Error): 15.102769892432217 

RMSE (Root Mean Squared Error): 3.8862282347325174 

**Linear Regression** 

Evaluation of the model's performance using various metrics:-

r2 score(R-squared (R2)) score: 0.9655977245826504 

MAE (Mean Absolute Error): 8.479071745987955 

MSE (Mean Squared Error): 138.12408611460899 

RMSE (Root Mean Squared Error): 11.752620393538157 

**Decision Tree Regression**

Evaluation of the model's performance using various metrics:- 

r2 score(R-squared (R2)) score: 0.9926221108057348 

MAE (Mean Absolute Error): 3.4726666666666666 

MSE (Mean Squared Error): 29.622

RMSE (Root Mean Squared Error): 5.442609668164712 

**Random Forest Regression**

Evaluation of the model's performance using various metrics:- 

r2 score(R-squared (R2)) score: 0.99766556152047 

MAE (Mean Absolute Error): 1.80648 

MSE (Mean Squared Error): 9.372699266666668 

RMSE (Root Mean Squared Error): 3.061486447245303 



In summary, the XGBoost Regressor excels in terms of both predictive accuracy and generalization ability, as evidenced by its high R2 score, low MAE, MSE, and RMSE, and its avoidance of over fitting. This makes it the best-performing model among the four considered for this regression task. 
