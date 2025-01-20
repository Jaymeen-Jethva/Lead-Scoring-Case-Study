# Lead-Scoring-Case-Study
## Problem Statement:

- X Education is an online education provider specializing in courses for industry professionals. The company attracts numerous visitors to its website through marketing channels such as websites, search engines, and referrals. Visitors who provide their contact information by filling out a form become leads, which the sales team then works to convert into customers through calls, emails, and other follow-ups. However, the company struggles with a low lead conversion rate, as only 30 out of 100 leads, on average, become customers. This results in the sales team spending significant time and resources on leads that are either uninterested or not yet ready to purchase.
- To solve this problem, X Education wants to identify the most potential leads, also known as 'Hot Leads'. These are the leads that have a high probability of becoming customers. By focusing on these leads, the company hopes to increase its lead conversion rate and improve its efficiency. The company has hired you to help them with this task. Your job is to build a model that can assign a lead score to each lead based on various factors, such as their demographics, behavior, preferences, etc. The higher the lead score, the more likely the lead is to convert. The lower the lead score, the less likely the lead is to convert. The company's CEO has set a target of achieving an 80% lead conversion rate with this model.

## Data:

- The Leads dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable is the column 'Converted' which has a value of 1 for converted leads and 0 for non-converted leads. One thing to note is that some of the categorical variables have a level called 'Select' which indicates that the lead did not select any option from the list. This is equivalent to a missing value and should be handled accordingly.

## Goals of the Case Study:

- Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

- There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

## File Details:

- Lead Scoring Case study NoteBook.ipynb : Python file containing codes for the lead scoring model and related analysis
- Assignment Subjective Questions Answers.pdf : Answers to subjective questions
- Lead scoring case study PPT.pdf : Presentation file
- Lead Scoring Case Study Summary Report.pdf : Summary of python notebook 
