# Data Science Salary Analytics
## by Cedric Aubin
## Introduction

An Exploratory analysis into Data science industry job salaries with the purpose of uncovering insights and communicating findings through data visualisation.
The salaries were collected by [ai-jobs](https://salaries.ai-jobs.net/download/), a website that lists data analyst jobs. The purpose of this analysis is to investigate which factor in the dataset mostly affect the salary earned.

## Utilities

- Conda
- Python 3
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Dataset

> The salaries dataset we will work with is from [ai-jobs](https://salaries.ai-jobs.net/download/). Ai-jobs collects salary information anonymously from professionals all over the world in the AI/ML and Big Data space and makes it publicly available for anyone to use, share and play around with. The data is being updated regularly with new data coming in, usually on a weekly basis.
The primary goal is to have data that can provide better guidance in regards to what's being paid globally. So newbies, experienced pros, hiring managers, recruiters and also startup founders or people wanting to make a career switch can make better informed decisions.

> The dataset was pretty clean and tidy. I only changed some data type to facilitated our work and deleted "dupliates". Regarding the nature of our dataset and variables, there is a posibity that they are not duplicates but for precaution we deleted them.
Data type changed: experience level, company size and remote ratio to ordered-category and employment type to unordered category.


## Summary of Findings

> During exploration we found that there is a strong positive linear relationship between salary and the employee's experience level. We compared salary with the other categorical variables and only work year had a good relationship. We went further to check the correlation between these two categorical variables, experience level and work year and we found that the count on experience level increases over years with an explosion on senior-level/Expert in 2022. But surprisingly, when we checked the relationship between the three variables, the relationship becomes weak.


## Key Insights for Presentation

> For our presentation, we will start by presenting our variable of interest, salary. Then we will show its relationship with experience level, and work year using box and violin plots. Finally, we will draw the three variables on a single violin plot for the top 10 job titles.
