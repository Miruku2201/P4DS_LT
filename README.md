## Data analysis and prediction of housing price in Ha Noi, Viet Nam.
Performing data analysis and prediction of housing price in Ha Noi, Viet Nam using machine learning algorithms.
## Data
The data is collected from [Kaggle](https://www.kaggle.com/datasets/ladcva/vietnam-housing-dataset-hanoi) and contains 82497 rows and 12 columns. 
## Data analysis
The data analysis is performed using Python and Jupyter Notebook. The data analysis is divided into 3 parts:
1. Data cleaning and preprocessing:
    - Remove duplicate rows
    - Remove rows with missing values
    - Remove rows with invalid values
    - Remove outliers
    - Remove unnecessary columns
    - Convert data types
    - Feature engineering
2. Data visualization:
    - Histogram
    - Box plot
    - Scatter plot
    - Heat map
    - Correlation matrix
3. Data analysis: answer some questions about the data using the visualization results:
    - It is possible that the same unit of area but the price of houses in Hanoi is different in length or width?
    - How will the status of houses included in the price / sale section be at different times?
    - How does the location of the homes affect the price?
## Prediction
- Handle outliers using Box Outlier Clipper.
- Create a pipeline to handle categorical and numerical data.
- Survey the performance of 3 machine learning algorithms: ANN, Random Forest, Multi-layer Perceptron.
- Use GridSearchCV to find the best parameters for the model.
