# task--4-ds
#1. Libraries Import:
#We use pandas and numpy for data handling.

#seaborn and matplotlib for visualization.

#scikit-learn for preprocessing, model training, and evaluation.

#2. Dataset Loading:
#Loads house_prices.csv into a DataFrame for manipulation.

#3. Missing Value Handling:
#Missing numerical values are filled with median.

#Missing categorical values are filled with mode.

#4. Exploratory Data Analysis (EDA):
#Distribution plot for Size.

#Boxplot for Price to spot outliers.

#Correlation matrix checks relationships between numerical features and Price.

#5. Preprocessing Pipeline:
#StandardScaler scales Size and Number of Rooms.

#OneHotEncoder converts Location to numeric categories.

#These transformations are applied using ColumnTransformer.

#6. Modeling Pipeline:
#Pipeline makes training consistent and clean.

#Includes preprocessing and LinearRegression.

#7. Train-Test Split:
#80% for training, 20% for testing, using a fixed random seed for reproducibility.

#8. Model Training and Prediction:
#Trains a linear regression model on processed data.

#Predicts Price for test samples.

#9. Model Evaluation:
#RMSE: Measures average error (lower is better).

#R² Score: How well the model explains variability (closer to 1 is better).

#10. Predicted vs Actual:
#Displays side-by-side comparison for evaluation and insight.
