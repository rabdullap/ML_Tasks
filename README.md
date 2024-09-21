# ML_Tasks 1
How to measure the central tendency is explained and coded in this task we are given house_price.csv which contains property prices in the city of Bangalore. we need to examine price per square feet do the following: Detect the outliers and remove it using: 
1)Mean Function 
2) Percentile method 
3. IQR(Inter quartile range method) 
4.Normal distribution 
5.Zscore method Also, plot the box plot(for all the numerical columns), histplot(to check the normality of the column(price per sqft column)) Check the correlation between all the numerical columns and plot heatmap. Scatter plot between the variables to check the correlation between them. 
dataset: https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view
# ML_Task 2
Q1.Suppose a child psychologist claims that the average time working mothers spend talking to their children is at least 11 minutes per day. You conduct a random sample of 1000 working mothers and find they spend an average of 11.5 minutes per day talking with their children. Assume prior research suggests the population standard deviation is 2.3 minutes. Conduct a test with a level of significance of alpha = 0.05.
Q2. A coffee shop claims that their average wait time for customers is less than 5 minutes. To test this claim, a sample of 40 customers is taken, and their wait times are recorded. The sample mean wait time is found to be 4.6 minutes with a standard deviation of 0.8 minutes. Perform a hypothesis test at a significance level of 0.05 and determine whether there is enough evidence to support the coffee shop's claim.
# ML_Task3
Objective: The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, and noise. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning. Dataset: Dataset for Data preprocessing Key Components to be fulfilled: Data Exploration: Explore the data, list down the unique values in each feature and find its length. Perform the statistical analysis and renaming of the columns. Data Cleaning: Find the missing and inappropriate values, treat them appropriately. Remove all duplicate rows. Find the outliers. Replace the value 0 in age as NaN Treat the null values in all columns using any measures(removing/ replace the values with mean/median/mode) Data Analysis: Filter the data with age >40 and salary<5000 Plot the chart with age and salary Count the number of people from each place and represent it visually Data Encoding: Convert categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms. Feature Scaling: After the process of encoding, perform the scaling of the features using standardscaler and minmaxscale
Data Set:https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view

# ML_Task4
Problem Description A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the company wants to know: • Which variables are significant in predicting the price of a car • How well those variables describe the price of a car Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market. Business Goal You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for the management to understand the pricing dynamics of a new market. Dataset: Data Dear students, Apply any 5 algorithms to the regression problem provided. For example: Linear Regression Decision Tree Regressor Random Forest Regressor Gradient Boosting Regressor Support Vector Regressor Rootmap:

Understand problem statement
Import necessary libraries and data
Check the data Info() Describe(( Isnull() Duplicated() Df. Columns Length of unique values in each column.
Data preprocessing Drop car id Find unique values in categorical or count plot extract company name from car name and address this new col to df also remove car name column. There are spelling mistakes in company name. Treat this. Label encoding all the categorical columns Outliers detection and removal( if present)
Feature selection Find correlation matrix Remove multicolinearity (remove features with High correlation .85 to 1)
Data splitting Test, train
Model selection and implementation
Model evaluation**
