# MachineLearning-Learn

**1. Machine Learning Course - Kaggle**

- **Data Exploration**: Utilizing pandas to explore and manipulate the Melbourne home prices dataset.

- **First Machine Learning Model**: Selecting features, defining, fitting, predicting, and evaluating a Decision Tree model.

- **Model Validation**: Splitting data into training and validation sets to measure model accuracy using Mean Absolute Error (MAE).

- **Underfitting and Overfitting**: Addressing model performance issues by adjusting the complexity of the Decision Tree model.

- **Random Forest**: Introducing the Random Forest model as a means to improve predictions by averaging multiple decision trees.

**2. Intermediate Machine Learning Course - Kaggle**

- **Introduction to ML**: The notebook begins with an introduction to machine learning, importing necessary libraries, and preparing the dataset for house price prediction.

- **Model Evaluation**: It defines five random forest models with different parameters and uses a function to calculate the mean absolute error (MAE) to evaluate their performance.

- **Missing Values**: The notebook discusses three approaches to handle missing values: dropping columns with missing values, imputation, and an extension to imputation.

- **Categorical Variables**: It explores handling categorical variables using techniques like dropping categorical variables, ordinal encoding, and one-hot encoding.

- **Pipelines**: The notebook introduces pipelines to streamline preprocessing and modeling steps.

- **Cross-Validation**: It explains the concept of cross-validation and demonstrates how to implement it.

- **XGBoost**: The notebook covers the XGBoost model, parameter tuning, and how to prevent overfitting with early stopping.

- **Data Leakage**: It concludes with a discussion on data leakage and how to avoid it.

**3. Feature Engineering - Kaggle**

- **Mutual Information (MI)**: Using MI to rank features based on their association with the target, capturing any kind of relationship beyond just linear.

- **Creating Features**: Generating new features through mathematical transformations, counts, and group transforms to capture more information.

- **Clustering with K-Means**: Utilizing K-Means clustering to create features that capture complex spatial relationships.

- **Principal Component Analysis (PCA)**: Implementing PCA to reduce dimensionality and discover important relationships in the data.
  
- **Target Encoding**: Applying target encoding to categorical features to capture information related to the target variable.

**4. Data Cleaning - Kaggle**

- **Handling Missing Values**:
Techniques to identify and handle missing data points, such as dropping rows or columns and filling in missing values with appropriate strategies.

- **Scaling and Normalization**:
Differences between scaling (changing the range of your data) and normalization (changing the shape of the distribution of your data).

- **Parsing Dates**:
Converting string dates into datetime objects for easier manipulation.
Extracting specific components of a date, such as year, month, day, etc.

- **Character Encoding**s:
Understanding the concept of character encodings.
Dealing with common encoding issues that arise when reading and writing files.

- **Inconsistent Data Entry**:
Identifying and correcting inconsistencies in data entries, which is a common problem in real-world data.
Techniques to clean up and standardize the data entries for further analysis (Fuzzywuzzy library).

**5. Visualize a Linear Regression Algorithm**

- **Importing Libraries**: The notebook begins by importing necessary Python libraries for data handling and machine learning, including pandas, numpy, and sklearn.

- **Dataset Overview**: It uses the Advertising.csv dataset, which includes variables like TV, Radio, Newspaper advertising budgets, and Sales figures.

- **Linear Regression Model**: A Linear Regression model is built to predict Sales based on the TV advertising budget.

- **Visualization**: The relationship between TV advertising and Sales is visualized using a scatter plot and a regression line, indicating a positive correlation.
