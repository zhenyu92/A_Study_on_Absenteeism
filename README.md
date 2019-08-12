# A study on Absenteeism with the Integration of Python, SQL & Tableau 2019.
This project is a part of the learning milestone of a Udemy course delivered by [365 Careers](https://www.udemy.com/python-sql-tableau-integrating-python-sql-and-tableau/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
A real-life example centered around – the ‘Absenteeism at Work’ was introduced in this course. We are required to investigate and explore the problem of ‘Absenteeism at Work’, which involved:
- Download the Dataset
- Date Preprocessing / Cleaning
- Applying Machine Learning Model
- Train & Test the Model
- Connect and Build a SQL Database
- Data Visualization on Tableau

### Environment Prerequisites
`Jupyter Notebook` for Python scripting
`MySQL` for Database / Source
`Tableau 2019` for Data visualization

### Instructions
1. Downloaded the [database](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/Absenteeism_data.csv).
2. Run and execute the [IPython file for Machine Learning Pipeline](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/Absenteeism%20Study%20Project.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Import Dataset
    2 Data Preprocessing
        2.1 Remove Irrelevant Data
        2.2 Convert Variables to Dummies
            2.2.1 Group the Reasons for Absence
            2.2.2 Concatenate Column Values
        2.3 Convert Timestamp
            2.3.1 Extract the Month Value
            2.3.2 Extract the Day of the Week
        2.4 Convert Catagorisation Variable
    3 Load the Processed Data
        3.1 Create the Target
        3.2 Standardize the Data
        3.3 Train Test Split
    4 Applying Logistic Regression
        4.1 Find Intercept and Coefficients
        4.2 Test the Model
    5 Save the Mode
    ```
3. Run and execute the [IPython file for integrating Python & MySQL](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/Absenteeism%20-%20Integration.ipynb).
![alt text](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/SQL%20Database.JPG "MySQL Dataset")
4. Extract the dataset from `MySQL` as [CSV](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/Absenteeism_predictions.csv).
5. Import & Tuning in `Tableau 2019`.
Tableau workbook for this project can be viewed and downloaded from [Here](https://public.tableau.com/profile/derrick1466#!/vizhome/Absenteeism_15655851471430/AgevsProbability?publish=yes).
Screenshot of the Dashboard: 
a. Relationship of Age and Absenteeism Probability
![alt text](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/Age%20vs%20Probability.JPG "Age vs Probability")
b. Relationship of Transportation Expense and Absenteeism Probability
![alt text](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/Transportation%20Expense%20vs%20Probability.JPG "Transportation Expense vs Probability")
c. Relationship of Reasons and Absenteeism Probability
![alt text](https://github.com/zhenyu92/A_Study_on_Absenteeism/blob/master/Reasons%20vs%20Probability.JPG "Reasons vs Probability")

### ML Methods Covered
ML methods covered in this study is `Logistic Regression`.
