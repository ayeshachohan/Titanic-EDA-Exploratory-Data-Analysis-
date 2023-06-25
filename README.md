# Titanic-EDA-Exploratory-Data-Analysis-
Data analysis of data for survival to age ratio, from pre-processing to visualization all steps.
1PRE-PROCESSING:
1.1-Data cleaning: 
Removing Missing values:
Removing Duplicate values:
Removing Irrelevant Attributes: 
1.2-Data Normalization:
1.3-Data transformation:
Data reduction: 
Data sampling: 
DATA AFTER PRE-PROCESSING:
2. RULE-BASED-CLASSIFICATION
 DATA AFTER RULE-BASED CLASSIFICATION:
3. ASSOCIATION RULE
3.1-Output of Association Rule DATA AFTER ASSOCIATION RULES:
4. CLUSTERS DATA WITH CLUSTERS:
5. VISUALIZATION

1.Data preprocessing

Data preprocessing is the process of cleaning, transforming, and reducing data to make it more manageable and meaningful. It is an important step in the data analysis process, as it can help to improve the accuracy and efficiency of data analysis methods.
• No of attributes = 12
• No of rows = 891

1.1-Data cleaning: This is the process of removing errors and inconsistencies from data. This can involve removing duplicate data, correcting typos, and filling in missing values.
Shape of data
 1.2-Data Normalization:
To normalize the "fare" attribute in a dataset, various normalization techniques can be used, such as Min-Max scaling.
1.3-Data transformation: This is the process of changing the format or structure of data. This can involve converting data from one format to another, or from one data type to another.
“As the data is already in perfect shape and format there is no need for data transformation.”
1.4-Data reduction: 
This is the process of reducing the amount of data without losing important information. This can involve removing redundant data or summarizing data into a smaller representation.
“Data reduction is not required in this process.”
1.5-Data sampling: 
This is the process of selecting a subset of data from a larger dataset. This can be done to reduce the dataset's size or improve the performance of data analysis algorithms.
“Data sampling is not required because all missing values are already removed.”
The specific data preprocessing techniques that are used will depend on the specific needs of the project. However, all data preprocessing techniques have the same goal: to prepare data for further analysis.

2. Rule-based classification

Rule-based classification is a type of machine learning algorithm that uses a set of if-then rules to classify data points. Each rule consists of a condition and an action. The condition specifies a set of criteria that must be met for the rule to be triggered, and the action specifies what should be done when the rule is triggered.

3. Association Rule:
   
The Apriori algorithm is a method for finding association rules in large databases. It works by first finding frequent itemsets, which are sets of items that appear together in a transaction more often than a user-specified threshold.

4. Clusters
   
In this step, the code reads the association rules from the CSV file Rule-based-classification.csv. The features of the variable are then created to store the relevant features for clustering. In this case, the features are Survived, Pclass, Age, and Parch.

5. Visualization
   
Clusters are visualized using a scatter plot. The plt. scatter() function is used to plot the points and the c argument is used to determine the color of each point based on its cluster label.
The plot title is set to "Cluster Visualization" and the x and y-axis labels are set to "Survival" and "Age".

  
