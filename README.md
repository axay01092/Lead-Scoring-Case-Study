# Lead_Scoring_Case_Study
## Problem Statement
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.
The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified as leads. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X Education is around 30%.
Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as 'Hot Leads'. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.
X Education has appointed you to help them select the most promising leads, i.e., the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads. The higher the lead score, the higher the conversion chance, and vice versa. The CEO has given a target lead conversion rate of around 80%.

## Data

You have been provided with a leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc., which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable is the column 'Converted', which indicates whether a past lead was converted or not (1 means converted, 0 means not converted). Please refer to the data dictionary provided in the zip folder for more information about the dataset.
One important aspect to consider is that many categorical variables have a level called 'Select', which needs to be handled as it is effectively a null value.

## Goals of the Case Study

1. Build a logistic regression model to assign a lead score between 0 and 100 to each lead. A higher score indicates a higher likelihood of conversion, while a lower score suggests a lower chance of conversion.

2. Address additional problems presented by the company, which your model should be able to handle. These problems are provided in a separate document and should be filled based on the logistic regression model developed in the first step. Ensure that you include this information in your final presentation.

## Results Expected

- A well-commented Jupyter notebook with the logistic regression model, conversion predictions, and evaluation metrics.
- A Word document filled with solutions to all the additional problems provided.
- A presentation summarizing the overall approach of the analysis, explaining the results in business terms, including visualizations, and summarizing the most important findings.
- A brief summary report of 500 words explaining how you proceeded with the assignment and the learnings you gathered.

Please refer to the respective documents and presentation for a comprehensive understanding of the case study and its outcomes.
