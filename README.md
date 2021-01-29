# Store Sales Forecast

## Predicting cardiovascular diseases

![](img/rossmann_original.png)

# 1. Business Problem.


# 2. Business Assumptions.

# 3. Solution Strategy

My strategy to solve this challenge was:

**Step 01. Data Description:** My goal is to use statistics metrics to identify data outside the scope of business.

**Step 02. Feature Engineering:** Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

**Step 03. Data Filtering:** Filter rows and select columns that do not contain information for modeling or that do not match the scope of the business.

**Step 04. Exploratory Data Analysis:** Explore the data to find insights and better understand the impact of variables on model learning.

**Step 05. Data Preparation:** Prepare the data so that the Machine Learning models can learn the specific behavior.

**Step 06. Feature Selection:** Selection of the most significant attributes for training the model.

**Step 07. Machine Learning Modelling:** Machine Learning model training

**Step 08. Hyperparameter Fine Tunning:** Choose the best values for each of the parameters of the model selected from the previous step.

**Step 09. Convert Model Performance to Business Values:** Convert the performance of the Machine Learning model into a business result.

**Step 10. Deploy Modelo to Production:** Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

# 4. Top 3 Data Insights

**Hypothesis 01:** The cases of heart diseases does not significantly depend on the height.

**False.** As observed, up to ~165 cm there are significantly more cases of heart diseases. Then, above this height, there are fewer cases.

**Hypothesis 02:** The are more cases of heart diseases for people who smokes than for people who does not.

**False.** As observed, the great majority of cases are among people who doesn't smoke.

**Hypothesis 03:** The are more cases of heart diseases for people who intakes alcohol than for people who does not.

**False.** As observed, the great majority of cases are among people who doesn't intake alcohol.


# 5. Machine Learning Model Applied
Tests were made using different algorithms.

# 6. Machine Learning Modelo Performance
The chosen algorithm was the **xgBooostRegressor**. In addition, I made a performance calibration on it.

#### Precision, Recall, ROC AUC and other metrics

# 7. Business Results

# 8. Conclusions

# 9. Lessons Learned

# 10. Next Steps to Improve

**2.** **Run a Design Discovery** to uncover facts that could be missing in our analysis in order to enrich the data that we have and improve the model performance.

**3.** Build a **model retraining pipeline**.



