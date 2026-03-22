# Experiment 12 - Data Wrangling Using Python
Data wrangling is the process of cleaning, transforming, and organizing raw, messy data into a structured and usable format for accurate analysis and decision-making.

### Aim:

To perform data wrangling using Python and the Pandas library by cleaning, transforming, and preparing raw data into a structured and meaningful format suitable for analysis and decision-making.

### Tools Used:
Jupyter Notebook or Google Colab

### Theory:

#### 1. Data Wrangling
Data wrangling refers to the process of cleaning, transforming, and organizing raw data into a structured format suitable for analysis. It involves multiple steps that ensure the dataset is free from errors and inconsistencies. This process is often time-consuming but is considered one of the most important stages in data analysis.

The main goal of data wrangling is to improve data quality so that accurate and reliable insights can be obtained. It includes tasks such as handling missing values, correcting data formats, removing duplicates, and combining data from different sources.

#### 2. Handling Missing Values
Missing values are common in real-world datasets and can occur due to various reasons such as data entry errors, system failures, or incomplete data collection. If not handled properly, missing data can distort analysis results.

Pandas provides several functions to detect and handle missing values. The isnull() function helps identify missing entries, while dropna() removes rows or columns containing missing values. The fillna() function replaces missing values with a specified value such as zero, mean, or median.

Handling missing values appropriately ensures that the dataset remains consistent and does not introduce bias in analysis.

#### 3. Removing Duplicates
Duplicate records can lead to incorrect interpretations and inflated results during analysis. These duplicates may occur due to repeated data entry or merging datasets without proper checks.

Pandas provides the duplicated() function to identify duplicate rows and the drop_duplicates() function to remove them. Removing duplicates ensures that each data entry is unique and contributes accurately to the analysis.

#### 4. Data Transformation
Data transformation involves converting data into a suitable format or structure that is easier to analyze. This may include changing data types, creating new columns, or applying mathematical operations to existing data.

For example, converting a column from string to integer type or calculating a new column such as total cost from quantity and price are common transformation tasks. These transformations enhance the usability of the dataset and allow deeper insights.

#### 5. Renaming Columns
In many datasets, column names may not be clear or descriptive. Renaming columns improves readability and makes the dataset easier to understand and analyze.

Pandas allows renaming of columns using the rename() function. This helps in maintaining consistency and clarity, especially when working with large datasets.

#### 6. Filtering Data
Filtering is the process of selecting specific rows from a dataset based on certain conditions. It allows analysts to focus only on relevant data for a particular analysis.

For example, filtering data based on a specific category or condition helps in isolating meaningful subsets of data. This makes analysis more efficient and targeted.

#### 7. Sorting Data
Sorting organizes data in a meaningful order, such as ascending or descending. It helps in identifying trends, patterns, and outliers in the dataset.

Pandas provides the sort_values() function to sort data based on one or more columns. Proper sorting improves data readability and simplifies analysis.

#### 8. Merging and Joining Data
In many cases, data is spread across multiple datasets. Merging and joining allow combining these datasets into a single dataset for comprehensive analysis.

Pandas provides functions like merge() to combine datasets based on a common column. This helps in integrating related information and performing more detailed analysis.

### Code Snippets:

* .drop    -    It is used to remove duplicates
  
         df=  df.drop_duplicates()
* .sort    -    It is used to sort certain column or row using any attribute

        df = df.sort_values(by = 'Price'))
* .merge   -    It is sued to merge two DataFrames using a common column

        df3 = pd.merge(df1, df2, on = 'ID")

### Applications:

* **Machine Learning:** Preprocessing data to improve model accuracy.

* **Business Intelligence:** Cleaning customer data for better segmentation.

* **Finance:** Accurate reporting and forecasting.

* **Research:** Preparing survey data for statistical analysis.

### Advantages: 

* Enhances data quality and reliability.

* Reduces errors and inconsistencies.

* Saves time during the analysis phase.

* Supports integration with advanced AI and ML tools.

### Result:
Data wrangling was successfully performed using Python and the Pandas library. Various operations such as handling missing values, removing duplicate entries, transforming data, filtering, sorting, and merging datasets were carried out effectively. The dataset was cleaned and structured properly, making it suitable for accurate analysis and further processing.
