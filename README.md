# Machine Learning Project: Megaline Plan Recommendation

**Project Description**

This project consists of a machine learning model for the telecommunications operator Megaline. 
The objective is to analyze the behavior of customers who have already migrated to the new plans—Smart or Ultra—and, based on this data, develop a classification model that can predict the most suitable plan for new customers. 
The central challenge is to create a model with the highest possible accuracy, with a minimum accuracy target of 0.75, to ensure that the recommendations are precise and useful for the company.

**Methodology and Analysis** 

The exploratory data analysis (EDA) and modeling were performed in a Jupyter Notebook. 
The steps followed include: Data Analysis: Initial exploration of the dataset to check for integrity, variable types, and the presence of missing data.

**Exploratory Analysis:**

Investigation of customer behavior on the different plans (Smart and Ultra) through visualizations, such as bar charts and boxplots, to identify patterns in the consumption of minutes, messages, and data.

**Data Preparation:**

The dataset was already pre-processed, allowing the modeling stage to begin directly. The dataset was split into training, validation, and test sets to ensure the model is evaluated impartially. 

**Modeling and Training:**

Several classification models (such as Decision Tree, Random Forest, and Logistic Regression) were trained and evaluated to find the one that best fits the data. 

**Model Evaluation:**
The final model was evaluated on a test set to verify if its accuracy meets the target of 75% or higher, thus validating the solution's effectiveness.

**Dataset**

The dataset used, users_behavior.csv, contains information on customer behavior, including:
calls: number of calls
minutes: total call duration in minutes 
messages: number of text messages 
mb_used: internet data volume used in MB 
is_ultra: target variable (0 for Smart plan, 1 for Ultra plan)

**Technologies and Libraries**

Python 3 Pandas: For data manipulation and analysis.
Scikit-learn: For building the machine learning models.
Matplotlib and Seaborn: For data visualization and exploratory analysis

