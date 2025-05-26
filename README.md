# Day-1
Day-1 Task

Task 1: Data Cleaning & Preprocessing
Objective: Learn how to clean and prepare raw data for ML.
Tools: Python, Pandas, NumPy, Matplotlib/Seaborn

I'll be working on Titanic Dataset and use jupyter notebook for coding.

Step-1: Importing the dataset and required libraries.

Step-2: Found out null values and handling them by using fillna() with median/mean. Dropping the columns which are not needed for this dataset like PassengerId, Name and Ticket. They do not affect survival.

Step-3: Converting categorical values to numerical using encoding so that they can be used for classification tasks or for finding correlation. Encoding for gender and Embarked columns.

Step-4: Observing the distribution and Normalizing/Standardizing the data so that distance based measures can be used appropriately. Else, there will be errors as larger values will affect the distance a lot. If data is following normal distribution, then standardization will be better as it is not sensitive to outliers.

Step-5: Visualizing outliers and removing them by finding interquartile range or log transformation (if the distribution is right skewed).
