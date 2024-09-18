# Salifort-Motors-Employee-Retention

## Introduction 
The Hr department at Salifort Motors are looking to dive deep into improving employee satisfaction levels at the company. They have collected data from employees and now are looking to put that data to good use. The company wants to answer the following question; <br> **Whats likely to make an employee leave?** <br> The goal of this project will be to analyze the data collected by the HR department and build a model that predicts whether an employee leaves the company or not. If there is a way to predict an employee leaving than it is highly likely to uncover factors that led to them departing. The interview and hiring process is a very time consuming process , increasing employee retention would be beneficial to the company.

## Response
From looking at the data we will build a ***logistic regression*** model because our outcome variable is categorical.

## Impact 
This model can help discover whether an employee will leave or not and which factors can lead them to make such a decision. The insights found with this model can help the HR department make informed decisions based on employee retention.

## Model Results 
### Logistic Regression Confusion Matrix
![image](https://github.com/user-attachments/assets/d1c3c70d-ea33-42b1-8434-186d82765ceb)
<br>As seen above, the model accurately predicted **2165 True Negatives**, employees who did not leave the company in the top left hand corner. Also, accurately predicted **123 True Positives**,  employees who did leave the company in the bottom right corner, known as True Positives. This model, is ideal if you want to predict whether an employee will stay at the company, but if we want to accurately predict whether someone will leave we might want to choose a higher level model such as a tree based model to achieve a higher accuracy.

![image](https://github.com/user-attachments/assets/798a78d5-82ee-43c5-8147-e6112818d079)
From the model we can see above that the following features display the most importance: **‘satisfaction_level’, ‘tenure’, ‘last_evaluation’, ‘number_project’, and ‘average_monthly_hours’**.

These variables showed to be the most valuable in predicting the outcome variable *‘left’*, which tells us whether an employee left the company or stayed.

## Key Insights
**In order to retain employees, we can implement the following:**
- Cap the number of projects that employees can work on so that burn out does not occur.
- 4 year employees seem to have extremely low satisfaction scores, we should think about promoting employees who have been at the company for 4 years or longer. Now, if this is not an option then further research can be done to understand why employees at a 4 year mark are so dissatisfied. 
- Most employees at this company had been overworked, so either provide them a reward from their time and effort and do not require them to work such extensive hours.
- Consider informing employees on overtime policies if they are not familiar with them.
- A scale should be put in place for evaluation scores and not explicitly given to those who work 200 + hours per month!








