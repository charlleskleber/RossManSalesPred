# Store Sales Forecast

## Forecasting 6 weeks of sales volume for Rossmann Store.

![rossmann_original](https://user-images.githubusercontent.com/72186071/106330645-578b5c00-6262-11eb-9faa-47e8862fe463.jpg)

# 1. Context.

In a quarterly report meeting at Rossmann, the directors board identified an increase in competitors stores openings.

After a customer survey, the following insights were identified:

Customers preferred to buy from the competition because the service was better.
Customers bought the same product from the competition because it offered better prices.
Customers preferred to go to the competition’s store because the physical environment were more pleasant and some even had a cafeteria chain inside them.

## 1.2 Initiatives

Based on the research insights, initiatives have been outlined such as:

Redesign the entire training program for store managers and attendants.
Review the entire pricing strategy.
Make partnerships with chains of coffee shops and bakeries.
Deploy self-service totems to customers who preferred to shop without the assistance of attendants.

However, to carry out all these initiatives, well-structured financial planning with a minimum margin of error must be made so that the company wouldn't waste money during the implementation of the initiatives.

The CFO responsible for this plan had a huge difficulty to carry it out because it was necessary to know how much each store was selling and how much it could sell in the short term. In addition, there was no easy, automated, or convenient way to obtain this information.


# 3. ML Forecast Solution Strategy

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

**Step 10. Deploy Model to Production:** Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

# 4. Top 3 Data Insights

**Hypothesis 01:** Stores with more assortments should sell more.

**False.** As observed, stores with a basic assortment have a higher volume of sales.


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



