# Employee Sentiment Analysis
### LLM Final Assessment
### Jason Clibanoff
#### After reviewing the data and analyzing sentiments, here is a brief summary of the findings.

-----------------------------
Most Positive and Negative Employees:

The top three positive and negative employees were determined by calculating a sentiment score of -1 for negative, 0 for neutral, and +1 for positive for each email, and totalling each employees all time score.
#### Most Positive Employees (Highest All-time Sentiment Scores)
| Email Address      | Sentiment Score      |
|-------|-------|
|lydia.delgado@enron.com | 188      |
|john.arnold@enron.com       |  179     |
| patti.thompson@enron.com      |   147    |

#### Most Negative Employees (Lowest All-time Sentiment Scores)
| Email Address      | Sentiment Score      |
|-------|-------|
|	kayne.coulter@enron.com  | 105   |
| rhonda.denton@enron.com  | 112   |
| eric.bass@enron.com      | 126   |

-------------------------------

Flight Risk :rotating_light::rotating_light::rotating_light:: 

Checking for flight risk with the original criteria of anyone having **four** negative emails within any 30 day span was not very effective, as nearly everyone met that criteria. 
Bobette.riner@ipgdirect.com, eric.bass@enron.com, john.arnold@enron.com, johnny.palmer@enron.com, kayne.coulter@enron.com, patti.thompson@enron.com, and sally.beck@enron.com had at least four negative emails within a rolling 30 day period at some point. Only three employees were initially not ruled a flight risk using this metric. 

Raising the threshold to **more than five** negative messages in a rolling 30 day span, only sally.beck@enron.comis is flagged. This metric might also be flawed, as people who had a spike of negativity in the past are not necessarily all likely to leave. It might be more accurate or at least beneficial to also look at who is trending downwards in recent months. For example johnny.palmer@enron.com's monthly sentiment scores show steep decline over the last six months, yet the only time he met the original threshold was over a year prior to this decline.

-------------
Other key findings:

Looking at the overall sentiment trends for all employees, sentiment tends to dip in February each year, but there is an overall positive trend over time, despite individual scores fluctuating greatly from month to month at times.

Features like the number and percentages of positive and negative words in each email and the monthly message count can be used to accurately predict employees' monthly sentiment scores.

The vast majority of all emails sent across the board are positive, with a breakdown of 1574 positive emails, 444 neutral emails, and 173 negative emails.

-----------------

Usage:

All code is in the employee_sentiment_analysis.ipynb file.

All graphics are in the Visualizations folder.

------------------------------


 
