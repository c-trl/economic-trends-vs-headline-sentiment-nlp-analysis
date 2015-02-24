Follow the project [here](http://nbviewer.ipython.org/github/c-trl/economic-trends-vs-headline-sentiment-nlp-analysis/blob/master/fred-api.ipynb).

##Economic Trends and Headline Sentiment NLP Analysis
This study aims to find symmetry in economic trends and news headline sentiment.  It is expected that as economic downturn approaches, headline sentiment should begin to decrease.  For example, warnings of impending recession before the Great Recession in 2007 in headlines should be reflected in significant decreases in news headline sentiment as late as Q3 2007.  How accurate are news headlines in reflecting actual economic trends?  This project looks to answer that question.

A timeline of economic trends will be defined which will be used to reference news headline sentiment against.  Potential applications of this study include utilizing news headline sentiment as a possible predictor for economic trends.  While prediction of the economy as a whole is a large attempt, perhaps certain individual economic indicators may be predictable by headline sentiment.

##In this project:
* Web data mining 
* Utilization of Federal Reserve Economic Data's API
* HTML parsing
* Natural Language Processing
* Database creation/manipulation
* Regression analysis

##Steps:
* Automation of web-mining; scrape article text from a list of publications to a list of articles
* For each article, parse for date and headline data
* Send to dataframe
* Add a column to the df using sentiment estimator
* Plot sentiment, regress against various economic indicators
