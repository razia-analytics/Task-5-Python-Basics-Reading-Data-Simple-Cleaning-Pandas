**Python Basics: Reading & Cleaning Data with Pandas**

This Task demonstrates basic data handling in Python using the Titanic dataset. It covers reading data, exploring, cleaning, and simple transformations using Pandas.

**Tools Used**

Python, Pandas, Google Colab

**Key Steps**

Read the dataset with pd.read_csv() and explored using .head() and .info().

Identified missing values using .isnull().sum() and cleaned them: filled Age with median, Embarked with mode, and dropped Cabin.

Removed duplicate rows using .drop_duplicates().

Converted categorical columns (Survived, Pclass, Sex, Embarked) to category type.

Created new features: Age_Category and Fare_Band for better analysis.



