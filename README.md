This is the machine learning code written during my Data Centric Computing course (ES114).
<br>
This code performs linear regression on a dataset to predict product prices based on their respective areas. It begins by importing necessary libraries, including pandas for data manipulation, numpy for numerical operations, scikit-learn's linear regression module, and matplotlib for plotting. The dataset is loaded from a CSV file, and a new "area" column is added with predefined values.

A scatter plot is created to visualize the relationship between area and price. Next, a new DataFrame is created by excluding the "price" and "product" columns, and the target variable 'y' is set to the "price" column.

A linear regression model is instantiated, trained on the data in 'new_df' with 'y' as the target variable. Finally, the code predicts the price for an area value of 20 using the trained model. This code essentially automates the process of predicting product prices based on area using a linear regression model.
<br>
Author: Monu Sunia, BTech'22 IIT Gandhinagar

