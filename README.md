# Problematic internet use

This is a submission for Vancouver DataJam October 2024. 
Group Members: Helena, Hunter, Melvika, Susu, Tien, Michealea
Mentor: Tav Mcgregor

## Objective: As children age, they tend to spend more time on the computer

Internet use can become problematic in certain individuals when online activities such as video gaming, social media use, web-streaming, pornography viewing and buying become excessive1. Recent studies have revealed that problematic internet use is quite prevalent (exists in up to 11.2% of young adults), and is associated with negative outcomes such as difficulties in regulating emotions, decreased avoidance of harmful activities and increased impulsivity

## Summary:
This was a large, complex dataset with ~60 features and over 2,700 observations.  Many of the features were missing data and therefore unusable. Nevertheless, through a combination of EDA, summary statistics, and regression modeling (both linear and logistic regression) we discovered that some important risk factors in PII among young people.

## Methods:

### EDA
- What: we're we working with (start_here.csv, data_dictionary.csv)
Briefly describe datasets: size (rows x cols); complexity (types of info: [fitness: measurements; scores] [demographic] [no survey responses] - fill out all “instruments” and briefly describe - 12 types of measurement (instruments) + 1 output variable.  [recall that output variable is the product of survey]
- How: How did we approach this:
* EDA: key decisions re: dropping data
* What columns to drop (low correlation; missing data (+50%); low information, e.g. season of participation) 
* Result: a more efficient, more informative data set to work with
* Correlation Analysis

### Linear Regression
Confidence in the importance of Screen-time, Age, and Gender, which we then input into our Logistic Regression

### Logistic Regression
- First attempt: We run a multinomial logistic regression with the variables that we think are the most important: age, gender, BMI, and Internet Usage.
- We divide into different subsets: elementary, middle school student, and college students


Final result is in the Logistic_Regression.ipynb
