Follow the project here:  
[Working with FRED API](http://nbviewer.ipython.org/github/c-trl/economic-trends-vs-headline-sentiment-nlp-analysis/blob/master/fred-api.ipynb).  
[Web-Scraping News Headlines](http://nbviewer.ipython.org/github/c-trl/economic-trends-vs-headline-sentiment-nlp-analysis/blob/master/headline-scraping.ipynb)

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

---
###Potential Newspaper Archives:
Wall Street Journal (http://betaweb.dowjones.com/api/#headlines)  
The Washington Post (http://apiportal.washingtonpost.com/)  
The New York Times (http://developer.nytimes.com/docs/read/article_search_api_v2)  
USA Today (http://developer.usatoday.com/docs/read/USATODAY_Articles_Service)  

###Network Sites:
CNN (http://www.cnn.com/services/rss/)  
AP (http://www.programmableweb.com/api/associated-press)
