# Employee Sentiment Analysis
### LLM Final Assessment
### Jason Clibanoff

------------------------------

After reviewing the data and analyzing sentiments, here is a brief summary of the findings.

The top three positive and negative employees were determinded by calculating a sentiment score of -1 for negative, 0 for neutral, and +1 for positive for each email, and totalling each employees all time score.
#### Most Positive Employees (Highest All-time Sentiment Scores)
| Email Address      | Sentiment Score      |
|-------|-------|
|john.arnold@enron.com	| 127      |
|lydia.delgado@enron.com       |  119     |
| sally.beck@enron.com      |   113    |

#### Most Negative Employees (Lowest All-time Sentiment Scores)
| Email Address      | Sentiment Score      |
|-------|-------|
| rhonda.denton@enron.com	      |  65     |
|kayne.coulter@enron.com       |   87    |
| eric.bass@enron.com      |  97     |

-------------------------------

Flight Risk :rotating_light::rotating_light::rotating_light:: 

Checking for flight risk with the original criteria of anyone having four negative emails within any 30 day span was not very effect, as nearly everyone met that criteria. 
Kayne.coulter@enron.com was the only employee initially not ruled a flight risk using this metric. Bobette.riner@ipgdirect.com, don.baughman@enron.com, eric.bass@enron.com, john.arnold@enron.com, johnny.palmer@enron.com, lydia.delgado@enron.com, patti.thompson@enron.com, rhonda.denton@enron.com, and sally.beck@enron.com had at least four negative emails within a rolling 30 day period at some point.

Raising the threshold to more than five negative messages in a rolling 30 day span, only sally.beck@enron.com, bobette.riner@ipgdirect.com, and lydia.delgado@enron.com are flagged. This metric might also be flawed, as people who just send the most emails are more likely to have a few more negative ones mixed in. Lydia.delgado@enron.com is flagged even though she ranks as top two in all time sentiment score. It might be more accurate to instead look at who is trending downwards in recent months.

-------------
Other key findings:

Looking at the overall sentiment trnds for all employees, sentiment tends to drop towards the end of each year, reaching an all time low in November 2010, and trending in the same direction at the end of 2011. Average sentiment reached an all time high in September 2011.

The vast majority of all emails sent across the board are positive, with a breakdown of 1330 positive emails, 547 neutral emails, and 314 negative emails.




 
