**What Drives the Price of a Car?**<br>
This project analyzes a large dataset of used cars to determine what factors influence car prices. The dataset, ~426,000 cars is used here.<br>
The analysis follows the CRISP-DM framework, a widely used industry process for data science projects. The ultimate goal is to provide insights for a used car dealership on <br> what consumers value in a used car, enabling better pricing, acquisition, and sales strategies.<br>

**Project Objectives**<br>
1.	Explore the dataset and understand its structure.<br>
2.	Clean and preprocess the data (handle missing values, drop irrelevant columns, encode categorical features).<br>
3.	Identify key features that impact the price of a car.<br>
4.	Provide business recommendations for dealerships and sales teams.<br>
**Steps taken to analyze the project**<br>
The steps to take to describe the data include the following<br>
1.	read the data from vehicles.csv<br>
2.	Get the information about the columns in the data<br>
3.	Use describes to get basic stats for the data for numerical columns including id, price, year, odometer.<br>
4.	Under the categorical data<br>
**Methodology**<br>
This project is structured around the CRISP-DM framework:<br>
1.	Business Understanding<br>
o	Identify the key features that matters most to dealerships and sales teams.<br>
o	Success if defined by pinpointing the car features that drive higher resale prices.<br>
2.	Data Understanding<br>
o	Summary statistics and visual exploration of the dataset.<br>
o	Checking duplicates, missing values, and categorical distributions.<br>
3.	Data Preparation<br>
o	Cleanup data by<br>
o	Dropping irrelevant or redundant columns.<br>
o	Handling missing values (removal or imputation).<br>
o	Encoding categorical variables (e.g one-hot encoding).<br>
o	Feature scaling for numerical attributes if required.<br>
4.	Modeling & Exploration<br>
o	Correlation analysis of features with price.<br>
o	Feature importance ranking using ML models (Linear Regression, etc.).<br>
o	Visualizations of price distributions across categorical and numeric features.<br>
5.	Evaluation<br>
o	Interpretability of feature importance.<br>
o	Which features explain most of the price variance.<br>
6.	Deployment / Recommendations<br>
o	Provide actionable insights for dealerships:<br>
o	Which features increase car value.<br>
o	Which features have little/no effect.<br>
o	Strategic inventory and pricing guidelines.<br>
**Key Insights**<br>
•	Mileage, age of the car, and diesel are strong predictors of price.<br>
•	Some columns (e.g., VIN, ID numbers) add no predictive value and were dropped.<br>
•	Dealerships can optimize inventory acquisition by focusing on makes/models that hold value better.<br>
•	Sales teams can tailor offers knowing which features customers value most.<br>

 **Example Visualizations**<br>
•	Distribution of car prices.<br>
•	Correlation heatmap of numerical features.<br>
•	Feature importance bar charts.<br>
•	Box plots of categorical features (e.g., make, color) vs. price.<br>

**Various Charts from the Project**<br>

![CarsOdometerDistribution](images/CarsOdometerDistribution.png)
![CarsPriceDistribution](images/CarsPriceDistribution.png)
![CarsVsManufacturer](images/CarsVsManufacturer.png)
![CarsYear](images/CarsYear.png)
![ComplexityPlotwithMSE](images/ComplexityPlotwithMSE.png)
![Heatmapnumerical](images/Heatmapnumerical.png)
![LinearRegressionResults](images/LinearRegressionResults.png)
![odometervsprice](images/odometervsprice.png)


