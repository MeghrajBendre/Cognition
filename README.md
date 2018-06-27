# Cognition  

Sentiment Analysis Tool for products based on the recent tweets and review articles fetched from Google. The entire project was done
as a part of Veritas CE2016 Hackathon. The task was to be completed within 48 hours and a live demo had to be given to the judges and 
a ten minute video demo was to created for public viewing. The back end of the project was done in Python using the Django Framework 
whilst the front end was a web page using HTML, CSS, JavaScript, and Bootstrap. We have used the tweepy library for fetching the tweets 
and GoogleSearcher library(using Selenium) to get the links of the review articles. These articles were then scraped using Beautiful 
Soup API. The Sentiment analysis of all the data was done using a Naive Bayes Algorithm and the output was the percentage positivity, 
percentage negativity, and percentage neutrality in the data. For statistical interpretation of data, several graphs were shown
(like the tweet count vs time) using the amCharts.

# Installations  
Install python 2.7, pip from python.org  

Once these two are installed then use pip to install these following modules:
pip install django  
pip install beautifulsoup  
pip install bs4  
pip install unirest  
pip install requests  
pip install tweepy  
pip install collections  
pip install json  
pip install urllib2  
pip install lxml  
pip install pickle  
pip install re  
pip install selenium  
  
  
# Usage   
Go to sentiment_analysis folder and execute the following command:
python manage.py runserver
A localhost server will start running at '127.0.0.1:8000'
Visit this over a browser, preferrably google chrome

If at all after execution the program throws some error of type "{package_name} module not found",
then it is because of some dependency. Execute command "pip install {package_name}" to install that package. Inconvenience regretted.


