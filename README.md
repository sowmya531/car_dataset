🚗 Car Dataset Analysis using Pandas


📌 Project Overview

This project focuses on analyzing a car dataset using Python and Pandas. The analysis is performed by solving structured questions to clean, filter, and transform the data to extract meaningful insights.

🛠️ Tools & Technologies

1.Python
2.Pandas
3.Jupyter Notebook

📂 Dataset Description

The dataset contains car-related attributes such as:

->Make
->Origin
->Weight
->MPG_City
->Other performance-related features

⚙️ Commands Used

1.import pandas as pd → Import Pandas library
2.pd.read_csv() → Load dataset
3.head() → Display first 5 rows
4.shape → Show dataset dimensions
5.df.isnull().sum() → Identify missing values
6.fillna() → Handle missing values using mean
7.value_counts() → Count unique values
8.isin() → Filter specific records
9.apply() → Apply function on column

🔍 Analysis Approach

The project is carried out by solving real-world data analysis questions using Pandas operations like data cleaning, filtering, and transformation.

❓ Analysis Questions

1.Find all the null values in the dataset and handle them using isnull() and fillna().
2.Identify different types of car 'Make' and their counts using value_counts().
3.Filter records where 'Origin' is Asia or Europe using isin().
4.Remove records where 'Weight' is greater than 4000.
5.Increase 'MPG_City' values by 3 using apply().

🚀 Conclusion

This project helps in understanding fundamental data analysis techniques such as handling missing values, filtering data, and applying transformations using Pandas.
