# flipkart_review_scrapper
End to End project deployed on Heroku cloud

Demo link -  https://flipkart-review-scraperr.herokuapp.com/ 

##Overview

This is a Flask web app which fetches reviews of a particular product from Flipkart.

##Introduction:

Web scraping is a technique using which the webpages from the internet are fetched and parsed

to understand and extract specific information similar to a human being. Web scrapping

consists of two parts:

• Web Crawling→ Accessing the webpages over the internet and pulling data from
them.

• HTML Parsing→ Parsing the HTML content of the webpages obtained through web

crawling and then extracting specific information from it.

Hence, web scrappers are applications/bots, which automatically send requests to websites and

then extract the desired information from the website output.

Let’s take an example:

how do we buy a phone online?

We first look for a phone with good reviews

We see on which website it’s available at the lowest price

We check whether it’s delivered in our area or not

If everything looks good, then we buy the phone.

What if there is a computer program that can do all of these for us? That’s what web scrappers
necessarily do. They try to understand the webpage content as a human would do.

Other examples of the applications of web scrapping are:
• Competitive pricing.

• Manufacturers monitor the market, whether the retailer is maintaining a minimum price
or not.

• Sentiment analysis of the consumers, whether they are happy with the services and
products or not.

• To aggregate news articles.

• To aggregate Marketing data.

• To gain financial insights from the market.

• To gather data for research.

• To generate marketing leads.

• To collect trending topics by media houses.

And, the list goes on.

 we’ll take the example of buying a phone online further and try to scrap the
reviews from the website about the phone that we are planning to buy.

For example, if we open filpkart.com and search for ‘iPhone’, the search result will be as

follows:




![flikpart_page1](https://user-images.githubusercontent.com/86100724/141657888-7644a6d4-4070-4f0c-962d-db7c7ec0499c.png)

![flipkart_page2](https://user-images.githubusercontent.com/86100724/141657929-1d38f250-1cea-4c51-b4c3-780977e72974.png)

2. Prerequisites:

The things needed before we start building a python based web scraper are:

• Python installed.
• A Python IDE (Integrated Development Environment): like Vscode , PyCharm, Spyder etc.
• Flask Installed. (A simple command: pip install flask)

Sample Ouput:

![image](https://user-images.githubusercontent.com/86100724/141658027-7ee6cc1f-aba2-4df1-9113-e5b6e44cbb43.png)

Search result:

![image](https://user-images.githubusercontent.com/86100724/141658042-a5fb82a1-dcab-4aa4-8027-96841cc597cf.png)

###Heroku:

The Python app that we have developed is residing on our local machine. But to make it
available to end-users, we need to deploy it to either an on-premise server or to a cloud
service. Heroku is one such cloud service provider. It is free to use(till 5 applications).
We’ll deploy this application to the Heroku cloud, and then anybody with the URL can then
consume our app.






