🚗 Car Dataset Analysis using Pandas
📌 Project Overview

This project focuses on analyzing a car dataset using Python and Pandas. The analysis is performed by solving structured questions to clean, filter, and transform the data to extract meaningful insights.

🛠️ Tools & Technologies
Python
Pandas
Jupyter Notebook
📂 Dataset Description

The dataset contains car-related attributes such as:

Make
Origin
Weight
MPG_City
Other performance-related features
⚙️ Commands Used
import pandas as pd → Import Pandas library
pd.read_csv() → Load dataset
head() → Display first 5 rows
shape → Show dataset dimensions
df.isnull().sum() → Identify missing values
fillna() → Handle missing values using mean
value_counts() → Count unique values
isin() → Filter specific records
apply() → Apply function on column
🔍 Analysis Approach

The project is carried out by solving real-world data analysis questions using Pandas operations like data cleaning, filtering, and transformation.

❓ Analysis Questions
Find all the null values in the dataset and handle them using isnull() and fillna().
Identify different types of car 'Make' and their counts using value_counts().
Filter records where 'Origin' is Asia or Europe using isin().
Remove records where 'Weight' is greater than 4000.
Increase 'MPG_City' values by 3 using apply().
🚀 Conclusion

This project helps in understanding fundamental data analysis techniques such as handling missing values, filtering data, and applying transformations using Pandas.
