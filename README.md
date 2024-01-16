# Python Data Cleaning Project (FIFA21 Dataset)

### Introduction

EA Sports FIFA 21 is a popular video game that simulates soccer matches. Often, data collected from this game might be messy, containing inconsistencies, missing values, and various formatting issues. In this project, I will focus on cleaning and preparing messy FIFA 21 data for analysis using Python and Pandas.

### Dataset Source and Overview

The FIFA 21 dataset used in this project was obtained from a data cleaning challenge on Twitter, and it includes player attributes, statistics, and other relevant information.

The original FIFA21 dataset consists of over 18,000 records of player data. Each record represents a unique player and provides various attributes such as player name, age, nationality, club, overall rating, and more.

### Issues found in the data

During the initial exploration and analysis of the FIFA21 dataset, the following issues were identified:

- Missing values: The "Hits" and "Loan Date End" columns contained missing values that needed to be addressed. Careful handling and computation were required to handle these missing values.
- Inconsistent formatting: Inconsistent formatting was observed across different columns, particularly in the "Heights" and "Weights" columns. The values in these columns were stored in different units, necessitating the standardization of the data for consistency.

### Tools Used

The data cleaning project utilized the following tools and libraries:

1. **Python**: Python was used for performing data cleaning tasks.
2. **Pandas**: Pandas played a crucial role in data manipulation, cleaning, and handling missing values.
3. **NumPy**: NumPy was utilized for mathematical operations and array handling during the cleaning process.
4. **Jupyter Notebooks**: Jupyter Notebooks provided an interactive environment for code development, data exploration, and documentation purposes.

### Data Cleaning and Transformation Process

The data cleaning process involved the following steps:
1. **Data Understanding** - Before proceeding with the cleaning process, a thorough understanding of the dataset was gained. The structure, columns, and their meanings were examined. An external data dictionary was created to provide additional information about the columns.
2. **Columns to Clean**
***Data Exploration*** - Exploratory Data Analysis (EDA) was conducted to gain insights into the dataset, identify patterns, and detect anomalies.
***Handling missing values*** - During the EDA, it was discovered that the missing values in the "Hits" and "Loan Date End" columns had valid reasons. The "Hits" column represented the number of times a player was searched in the FIFA database, so players with no searches had blank records. Similarly, the "Loan Date End" column indicated the end date of contracts for players on loan, so players who were free or not on loan had blank records.
***Standardizing formatting*** - Inconsistencies in formatting, such as the varying units in the "Heights" and "Weights" columns, were resolved by applying transformations, lambda functions, and data normalization techniques. This ensured consistent formatting across the dataset.

3. **Exporting Clean Data**

Once the cleaning process was completed, the cleaned dataset was exported to a suitable format, such as CSV or Excel. This ensured that the cleaned data could be easily shared and used for further analysis or modeling purposes.

### Conclusion

In conclusion, this data cleaning project successfully addressed the issues in the FIFA21 dataset and produced a cleaned version of the data. By understanding the data, identifying the columns to clean, and applying appropriate cleaning techniques, the dataset was enhanced for future use. The cleaned data can now be utilized for analysis, modeling, or any other data-driven tasks.

The cleaned dataset is now ready for more advanced analysis, such as exploring player statistics, team performance, or other insights that can provide a deeper understanding of the FIFA 21 game.

### Data Source

https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring/code



