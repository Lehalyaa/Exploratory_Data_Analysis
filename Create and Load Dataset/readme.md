# Experiment 10: Create and Load a Dataset

A dataset is a structured collection of related information, typically organized into rows and columns. It is used as the raw material to uncover patterns, validate scientific hypotheses, or train machine learning models.

### Aim:

To create or load an external dataset and perform operations in it.

### Tools Used:

Google Colab, Jupyter Notebook

### Theory:

#### Introduction:

To perform data analysis over any data, we need a structured form of data that are related to each other. In this dataset, all the data can be used together to derive one common conclusion.

Creating a dataset is the process of transforming "raw" information—whether it’s numbers from a sensor, text from a website, or answers from a survey—into a structured, machine-readable format.

#### Creating a Dataset:

To create a dataset in Python, the following steps are needed:

--> Collection: Gather data into Python objects (like lists or dictionaries).

--> Structuring: Use a library (like Pandas) to turn those objects into a table (DataFrame).

--> Persistence: Save that table to a hard drive so it can be "loaded" later.

To perform the above steps in Python, the Pandas module is required. There are two methods by which these steps can be performed:

Method 1:

* Create a DataFrame of the data present using a dictionary and then store it inside the CSV file.

To do this, the *.to_csv** command is used.

Method - 2:

* Generating Synthetic Data: This method is used when there is no real-time data. This method creates a dataset with random numbers, and later the to_excel command is used to save the dataset into an Excel file.

### Loading a Dataset

If there is real-time data that can be recorded and is already saved in the form of rows and columns, then it can be easily imported into Google Colab or Jupyter Notebook, and all similar operations can be performed in it using the Pandas module.

Method 1:

Importing an External Dataset: Importing an external dataset into Google Colab is done using the files tab in the left corner section. After importing, one can perform all the operations that can be performed on the dataset that was created by us only.

#### Advantages of storing data in a dataset:

* Uniformity and Machine Readability

* Interoperability: Creation and access of data can be done in various software.

* Computational Scalability and Vectorization

#### Learning Outcomes:

* Datasets are used to store the data in the form of rows and columns, which are also called features and attributes.

* Datasets can either be created in Python or an external dataset can be loaded inside, and operations can be performed in it.

#### Conclusion:

Thus, datasets have been created or loaded, various operations have been performed on them, and the output is verified.
