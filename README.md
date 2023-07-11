# Car-Price-Prediction-using-Machine-Learning
A Indian automobile company Mahindra Auto aspires to enter the US market by setting up their manufacturing unit there  and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. 
they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Indian market. The company wants to know:
- Which variables are significant in predicting the price of a car
- How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.

# Business Goal
You are required to model the price of cars with the available independent variables. It will be used by the management 
to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of 
the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to 
understand the pricing dynamics of a new market.

Step 1: Reading and Understanding the Data
- Importing data using the pandas library
- Understanding the structure of the data

Step 2: Data Cleaning and Preparation Splitting company name from CarName column Fixing invalid values Like:-

- maxda = mazda
- Nissan = nissan
- porsche = porcshce
- toyota = toyouta
- vokswagen = volkswagen = vw
Check for duplicates

Step 3: Data Visualization Create a Distribution plot with car price column Create a Boxplot with car price column
Inference : Check for the Skewness of the Data.

Visualize Categorical Data
- CompanyName
- Symboling
- fueltype
- enginetype
- carbody
- doornumber
- enginelocation
- fuelsystem
- cylindernumber
- aspiration
- drivewheel

Questions to be answered with visualization

- Most favoured car company.
- Most Cars (Gas or Deisel).
- Most preferred Car according to type.
- Most Favoured Engine
- Highest Average Price of Car
- Which cars has highest average price (Gas or Deisel)
- Most common number of cylinders
- Most common type of fuel systems

Visualising numerical data

- Columns that has Positive correlation with Price Column.
- Columns that has Negative correlation with Price.
- Create a Pair Plot with whole dataset.

Use Linear Regression Algorithm

- Include those columns in X which positive correlation with the Price Column.
- Split the Dataset accordingly with the help of train test split module.
- Model Building and Model fitting.
- Predict and Evaluate the Model with r2 Score
