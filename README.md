# 2023-Travelers-Analytics-Case-Competition-
Task is to provide a method for predicting the claim cost for each policy and to convince  business partner that  predictions will work well. The dataset link is here-- https://www.kaggle.com/competitions/2023-travelers-university-competition/data.
The InsNova data set is based on one-year vehicle insurance policies from 2004 to 2005. There are 45,239 policies, of which around 6.8% had at least one claim. The data is split to two parts: training data and validation data. In the validation and holdout data, claimcst0 (claim cost), clm (claim indicator) and numclaims (claim counts) are omitted. You can build your model on the training data. In the end, use your best model to score the validation and holdout data. We will evaluate your model based on your validation and holdout data prediction.

# Lead a team of 4 in this competetion and ranked  2 overall on this Competation. Team name Pidata.

Files
InsNova_data_2023_train.csv - the training set
InsNova_data_2023_vh.csv - the validation set on which you will make your predictions
sample_submission.csv - a sample submission file in the correct format
Variable Descriptions
id - Policy key
veh_value - Market value of the vehicle in $10,000's
exposure - The basic unit of risk underlying an insurance premium
veh_body - Type of vehicles
veh_age - Age of vehicles (1=youngest, 4=oldest)
gender - Gender of driver
area - Driving area of residence
agecat - Driver’s age category from young (1) to old (6)Driver’s age category from young (1) to old (6)
engine_type - Engine type of vehicles
max_power - Max horsepower of vehicles
driving_history_score - Driving score based on past driving history (higher the better)
veh_color - Color of vehicles
marital_status - Marital Status of driver (M = married, S = single)
e_bill - Indicator for paperless billing (0 = no, 1 = yes)
time_of_week_driven - Most frequent driving date of the week (weekdays vs weekend)
time_driven - Most frequent driving time of the day
trm_len - term length (6-month vs 12-month policies)
credit_score - Credit score
high_education_ind - indicator for higher education
clm - Indicator of claim (0=no, 1=yes)
numclaims - The number of claims
claimcst0 - Claim amount
