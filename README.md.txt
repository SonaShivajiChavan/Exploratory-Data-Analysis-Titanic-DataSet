Exploratory Data Analysis:
Data analysis is a statistical method used to describe variability among observed, correlated variables. The goal of performing factor analysis is to search for some unobserved variables called factors.

EXPLORATORY DATA ANALYSIS ON TITANIC DATASET:
This dataset has passenger information who boarded the Titanic along with other information like survival status, Class, Fare, and other variables. The unfortunate event which was occurred on 15 April 1912, the Titanic sank after colliding with an iceberg, aboard 2224 peoples.

Requirements:

Python, jupyter notebook.
Numpy, Pandas, matplotlib.pyplot, seaborn and sklearn library.
Dataset(titanic.txt), added in the repository.

This project addresses the following Data Analysis topics:
Data Exploration and Preparation
Data Representation and Transformation
Data Visualization and Presentation

Data Analysis:
Data Exploration and Preparation Learn about data: Are there missing data? Is it categorical? if not, min , max, avg values? if yes, what are the categories? distribution of variables Duplicate entry.
Data Representation and Transformation Few Passengers didn't pay for the ticket, so there may be a possibility that they didn't purchase a ticket or it was "complimentary" (ticket No. 112050,112059). After checking sample entries, i found out some of the passengers did get a complimentary ticket. This may also help to analyze whom(Important figure in society) to distribute the promotion ticket.
Transformation on dataframe: Droping some of the columns which many not contribute much to our machine learning model such as Name, Ticket, Cabin etc


- Data prepocessing: It is a process to convert raw data into meaningful data using different techniques.
- Data preprocessing techinques are: 1. Data Cleaning
                                     2. Data Integration
                                     3. Data Reduction
                                     4. Data Transformation
                                     5. Data Discretization

- Data Cleaning: It is a technique for identifying the missing values, smooth out noise while identifying outliers, correcting inconsistencies in the data.
- Data Integration: It is a techinque to merges data from multiple sources into a coherent data store, such asa data warehouse.
- Data Reduction: It is a technique use to reduce the data size by aggregating, eliminating redundant features, or clustering, for instance.
- Data Transformation: It is a technique, data are transformed into appropriate forms for ML model training, such as normalization, may be applied where
  data are scaled to fall within a range 0 to 1 or -1 to 1.
- Data Discretization: It is a technique tranforms numeric data by mapping values to interval or concept labels.


Missing value/data: There are the best 6 methods to handle missing data or values. It is the part of Data Preprocessing and this is the most important step to build Machine Learning/Data Science project. The following are the most popular methods to handle missing data.
•Ignore missing values row / Delete row
•Fill missing value manually
•Use global constant
•Measure of central tendency (Mean, Median & Mode)
•Measure of central tendency for each class
•Most probable value ( ML Algorithms) #!pip install scikit-learn

- Feature Scaling: It is a method to scale numeric features in the same scale or range (-1 to 1, 0 to 1). This step is involved in data prepocessing
  and before ML model training. It is also called Data Normalization.
. we apply feature scaling on independent variables.
. those algorithms calculate distance and gradient descent based algorithms required Feature Scaling.
. tree based algorithms not required FS.

- Standardization: rescales the feature such as mean=0 and standard deviation=1. The result of Standardization is Z called as Z-score normalization.
- Normalization: rescale the feature in fixed range between 0 to 1, also called as Min-Max Scaling.
