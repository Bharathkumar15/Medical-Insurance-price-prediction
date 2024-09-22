# Medical-Insurance-price-prediction

Hello Everyone,

I hope you're all doing well.

In this analysis, we will be focusing on predicting medical insurance prices based on several key factors, including Body Mass Index (BMI), lifestyle habits (such as smoking), geographic region, gender, number of children, and age. These features play a significant role in determining the cost of medical insurance premiums.

To start, i imported a dataset from Kaggle, which contains relevant data on medical insurance charges. Then performed an Exploratory Data Analysis (EDA) to gain insights into the structure of the data, identify trends, and understand relationships between variables.

To enhance the performance of our Machine Learning (ML) models, the following preprocessing steps were carried out:

Label Encoding was applied to binary variables such as gender and smoking status to convert them into numerical form.
I used get_dummies to handle categorical variables, specifically the region column, by creating separate binary variables for each unique region. This process ensures that our models can effectively learn from the data without introducing bias from categorical features.
Following preprocessing, the dataset was split into training and testing sets, allowing us to evaluate model performance accurately. Two different regression models were then built to predict medical insurance prices:

Linear Regression: A simple yet powerful algorithm that models the relationship between the input features and insurance charges. (r2_score: 0.725, mean_squared_error: 36330052.34)

Random Forest Regressor: A more advanced ensemble learning method that uses multiple decision trees to improve predictive accuracy and handle complex relationships between features.((r2_score: 0.915, mean_squared_error: 11234499.35)

I utilized the following libraries for data analysis and model building:

Pandas: For data manipulation and structuring, particularly in handling tabular data.
NumPy: For efficient numerical computations, particularly with arrays and matrix operations.
Matplotlib and Seaborn: For visualizing data trends and relationships through various plots and graphs.
Scikit-learn: For implementing machine learning algorithms (e.g., Linear Regression and Random Forest Regressor), as well as handling preprocessing tasks like data splitting and encoding.
Through this approach, So that we aim to compare the performance of these models and understand which one provides more accurate and reliable predictions for insurance pricing.

Thank you,
Bharath Kumar L
 
