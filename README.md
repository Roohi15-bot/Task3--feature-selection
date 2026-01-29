# Task 3: Feature Selection
   Description

The goal of feature selection is to identify and choose the most important attributes (features) that influence customer churn. These features help the model understand why customers leave the service. Examples of such features include contract type, monthly charges, and customer tenure.

  Skills Used

1) Feature relevance analysis

2) Domain knowledge for identifying influential attributes

3) Understanding customer behavior

4) Data preprocessing and analysis


 # Step 1: Load the Dataset

The customer churn dataset is first loaded to understand its structure, columns, and data types.

 # Step 2: Remove Unnecessary Columns

Columns that do not help in predicting churn (such as customer ID) are removed because they do not affect customer behavior.

 # Step 3: Handle Data Issues

Text-based values are converted into a usable format.

Missing values are identified and handled properly.

All features are made suitable for analysis.

#  Step 4: Identify Important Features

Different methods are used to measure how much each feature influences churn, such as:

Statistical analysis

Machine learning-based importance ranking

These methods help in selecting only the most relevant attributes.

#  Step 5: Select Top Influencing Features

From all available features, only the most important ones are chosen for further modeling, such as:

Contract type

Monthly charges

Tenure

Payment method

Internet service type

This reduces complexity and improves prediction accuracy.

 # You can find code here : https://colab.research.google.com/drive/1C7nyd5YT0GU5Axr7fp5n_-FGweqSwseT?usp=sharing
 
# Result 

The feature selection process successfully identifies the key attributes that have the strongest impact on customer churn. Features related to customer commitment (contract type and tenure) and service cost (monthly charges) are found to be highly influential.

# Observations

Customers with shorter contract periods are more likely to churn.

Higher monthly charges increase the chance of churn.

Customers with low tenure (new customers) are more likely to leave.

Payment and service type also play an important role in churn behavior.

Selecting only relevant features improves model performance and reduces noise in data.
