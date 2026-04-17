🚗 Car Dataset Analysis using Pandas
📌 Project Description

This project involves analyzing a car dataset using Python and Pandas. It focuses on data cleaning, handling missing values, filtering records, and applying transformations to extract useful insights.

🔍 Analysis Approach

The project is carried out by solving real-world data analysis questions using Pandas operations like data cleaning, filtering, and transformation.

⚙️ Commands Used
import pandas as pd → To import Pandas library
pd.read_csv() → To load the dataset
head() → Displays first 5 rows
shape → Shows number of rows and columns
df.isnull().sum() → Finds null values in each column
fillna() → Fills missing values (used mean in this project)
value_counts() → Counts unique values in a column
isin() → Filters specific values
apply() → Applies function on a column

❓ Analysis Questions
Find all the Null Values in the dataset. If there are any null values, fill them with the mean of that respective column using isnull() and fillna().
Check the different types of 'Make' available in the dataset and their count using value_counts().
Show all the records where 'Origin' is either Asia or Europe using isin().
Remove all the records (rows) where the 'Weight' is above 4000.
Increase all the values of the 'MPG_City' column by 3 using apply().

🛠️ Tools Used
Python
Pandas
Jupyter Notebook

🚀 Conclusion

This project helps in understanding basic data analysis techniques such as handling missing values, filtering data, and applying transformations using Pandas.
