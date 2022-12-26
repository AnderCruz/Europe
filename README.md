# Operations Data Analyst Challenge


## Data

You can find more info about the data in the tables in the [data dictionary](Dictionary.yml).

  1. **contacts**: a transaction table containing Customer Service (CS) contacts.

  2. **specialists**: a dimension table containing information about CS specialists.

  3. **users**: a dimensions table containing information about N26 customers.

  4. **surveys**: a transaction table containing survey responses.



## Task

An "Operations Data Analyst" and the Operations Extended Leadership Team has tasked you to do an analysis for them.

### 1. Customer Service Overview

a. You'll first want to give a *high-level* overview of what happened in Customer Service, based on the given data. Pick a set of (at least 3) KPIs you deem appropriate and visualise their development. *Hint:* In this sub-task, restrict yourself to **contacts, specialists, surveys**.

b. As we need to communicate to Workforce (WF) Management how much resources will be needed in the future, please determine how many members of staff will be needed per day of the week for the next 7 days after the last day in the dataset. You don't need to separate external and internal specialists as this will be done by the WF Manager.

### 2. CS Specialists.

Create weekly leaderboards: breakdown per week for the top 5 inhouse CS specialists with respect to 3 KPIs that you think are suitable for measuring specialist performance. Plot the leaderboards showing full names and scores. 

*Notes: Let's say a week starts on Monday and has 7 days. Let's only consider weeks that are entirely contained in the dataset.*

### 3. Present

Consolidate all your findings into a PPT / Google Slides Presentation, aimed at the Operations Extended Leadership Team. You will present these slides during your technical interview.

___ 

Please submit all your source code as a Python / R Notebook and comment it well, so that we can understand your line of thought and approach to the problems.
If you are unsure about anything, make an assumption and explain your thinking behind it. This can either be as a comment in your code or in a separate document and will help us understand your decision-making better.
