# Diabetes Analysis Project (R)
This repository contains an exploratory data analysis (EDA) project in R that investigates potential relationships between various factors and diabetes occurrence. The data used in this project includes variables such as gender, age, BMI, smoking history, hypertension, heart disease, HbA1c level, and blood glucose level, all related to diabetes diagnosis.

## Dataset
The dataset contains anonymized medical data on individuals, which includes:

-gender: Categorical (male, female, other)  
-age: Continuous (age of individuals in years) 
-hypertension: Binary (0 - no, 1 - yes)  
-heart_disease: Binary (0 - no, 1 - yes)  
-smoking_history: Categorical (never, current, former, etc.)  
-bmi: Continuous (Body Mass Index)  
-HbA1c_level: Continuous (average blood sugar level over the past 2-3 months, with values > 6.5% indicating potential diabetes)  
-blood_glucose_level: Continuous (current blood sugar level)  
-diabetes: Binary (0 - no diabetes, 1 - diabetes   
## Project Goals  
The primary goal of this project is to explore potential patterns and correlations between diabetes and the various factors mentioned above. The analysis seeks to answer questions such as:

Does gender affect the likelihood of developing diabetes?  
Is there a relationship between smoking habits and diabetes?  
Are heart disease and hypertension linked to diabetes?  
How do BMI and HbA1c levels correlate with diabetes?  
## Steps and Approach  
### Data Preparation:  

Loaded and cleaned the dataset.  
Converted categorical variables such as gender, hypertension, heart disease, and smoking history to factors for easier analysis.  
### Exploratory Data Analysis:  

Descriptive statistics and visualizations were used to understand the dataset better.  
Bar charts, boxplots, and density plots were used to visualize distributions and relationships.  
Example analyses include exploring the age distribution, gender breakdown, BMI outliers, and relationships between key variables like heart disease, smoking history, and diabetes.  
### Key Questions Addressed:

Gender and Diabetes: We found that men have a higher chance of developing diabetes compared to women. Approximately 1 in 9 men are diabetic compared to 1 in 13 women.  
Smoking and Diabetes: A more nuanced relationship exists between smoking history and diabetes.  
Individuals who are current smokers or have smoked in the past tend to show slightly higher rates of diabetes, but non-smokers make up the majority of both the diabetic and non-diabetic groups.  
Heart Disease and Diabetes: Strong evidence supports a correlation between heart disease and diabetes, with diabetics being more prone to heart conditions.  
Hypertension and Diabetes: Similarly, there is a noticeable link between hypertension and diabetes.  
BMI and Diabetes: Diabetics tend to have a higher BMI, with the majority of individuals with diabetes having a BMI around or above 27.  
HbA1c Level and Diabetes: HbA1c levels above 6.8 are almost exclusively associated with diabetics.  
Blood Glucose and Diabetes: Blood glucose levels in diabetics are predictably higher, with notable gaps and patterns in the data suggesting that diabetic individuals maintain higher glucose levels even in controlled environments.  
### Advanced Insights:

Relationships between multiple variables were explored, such as age, BMI, and blood glucose, showing that older individuals are more likely to have higher BMI and blood glucose levels.  
Density plots were used to illustrate how different age groups, BMI ranges, and glucose levels interact with the presence of diabetes.  
## Visualizations
The project includes a variety of visualizations that help illustrate the relationships within the dataset:  

Bar charts to represent categorical distributions (e.g., gender, hypertension).  
Boxplots to identify outliers and distributions (e.g., BMI).  
Density plots for continuous variables (e.g., HbA1c level, blood glucose level).  
Stacked and filled bar charts for comparisons between categorical variables and diabetes prevalence.  
## Tools & Libraries  
The following R libraries were used:  

tidyverse, dplyr, ggplot2 for data manipulation and visualization.  
psych, mice, corrplot for statistical analysis.  
vcd for association statistics.  
## Conclusion  
This analysis helps identify significant risk factors for diabetes and illustrates how variables like BMI, HbA1c level, and heart disease are interconnected with the likelihood of developing diabetes.  
The insights gained can potentially inform further research and medical decision-making.  

