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

# 2. The Soultion

The delivered solution is a Telegram bot.

**The user just needs to send the store number and the bot will answer what's the total ammount of sales for the next 6 weeks.**

![rossmann_bot](https://user-images.githubusercontent.com/72186071/107792260-ae4d6700-6d33-11eb-8d4f-7e47cc938784.gif)


# 3. ML Forecast Solution Strategy

My strategy to solve this challenge was:

**Step 01. Data Description:** Use statistics metrics to identify data outside the scope of business.

**Step 02. Feature Engineering:** Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

**Step 03. Data Filtering:** Filter rows and select columns that do not contain information for modeling or that do not match the scope of the business.

**Step 04. Exploratory Data Analysis:** Explore the data to find insights and better understand the impact of variables on model learning.

**Step 05. Data Preparation:** Prepare the data so that the Machine Learning models can learn the specific behavior.

**Step 06. Feature Selection:** Selection of the most significant attributes for training the model.

**Step 07. Machine Learning Modelling:** Machine Learning model training

**Step 08. Hyperparameter Fine Tunning:** Choose the best values for each of the parameters of the model selected from the previous step.

**Step 09. Convert Model Performance to Business Values:** Convert the performance of the Machine Learning model into a business result.

**Step 10. Deploy Model to Production:** Publish the model in a cloud environment so that other people or services can use the results to improve the business decision.

# 4. Top 3 Insights

**Hypothesis 01:** Stores with more assortments should sell more.

![hyp1ross](https://user-images.githubusercontent.com/72186071/112799436-b7c13300-9044-11eb-8b36-3031092f0d72.png)

**False.** As observed, stores with a basic assortment have a higher volume of sales.

**Hypothesis 02:** Stores that have consecutive sales campaigns should sell more.

![hyp2ross](https://user-images.githubusercontent.com/72186071/112799300-8d6f7580-9044-11eb-8fce-a6ddbbccd68a.png)

**False.** As observed, stores with less sales campaigns sell more.

**Hypothesis 03:** Stores should sell more in christmas holidays.

![hypothesis 3 rossmann](https://user-images.githubusercontent.com/72186071/112799064-3a95be00-9044-11eb-9c22-2103ea6f96de.png)

**False.** As observed, stores sell more in public holidays.


# 5. Machine Learning Model Applied
Tests were made using different algorithms.

# 6. Machine Learning Model Performance
The chosen algorithm was the **xgBooostRegressor**. In addition, I made a performance calibration on it.

![ml performance](https://user-images.githubusercontent.com/72186071/112800321-dd9b0780-9045-11eb-8f07-c8b9eeedfcf6.png)

# 7. Business Results

## Stores x MAPE

![business performance by MAPE](https://user-images.githubusercontent.com/72186071/112799989-72513580-9045-11eb-8326-a5b74c1fbefc.png)

# 8. Conclusions

For the first cycle the resultus were already satisfatory to complete our task, for sure in the next cycle i can improve it.

# 9. Lessons Learned

Instead of opting to the best performed ML algorithm on the first cycle I should go for the one that will give me the best speed and accuracy.

# 10. Next Steps to Improve

**1.** **Run a Design Discovery** to uncover facts that could be missing in our analysis in order to enrich the data that we have and improve the model performance.

**2.** Build a **model retraining pipeline**.

**3.** Build a project to **predict customers in the store for the next 6 weeks**.



