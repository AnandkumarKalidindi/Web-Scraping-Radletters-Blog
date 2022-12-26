# WEB SCRAPING RADLETTERS BLOG
Web Scraping the rad letters blog using BeautifulSoup

## OVERVIEW

Web scraping is mainly used for scraping the web pages.Web scraping can done with the help of different prograimming languages.Here, in this project i have used `python` as the programming language and the library used for scraping the data is `BeautifulSoup`. I have used `RadLetters` blog for my web scraping project.Rad letters blog consists of the various popular newsletters from different topics like Arts,Business,Culture,Science,Finance etc.I have divided my project into 3 parts.In the first part scraping all the topics info,and in the second part scraping all the newsletters from all the topics and all the pages and in the third part scraping top 30 newsletters from each topic.The platform used for this project is jupyter notebook.

![Web scraping image](https://user-images.githubusercontent.com/121304061/209560428-abadd1fb-4b3e-4806-95f1-fa097f8850e4.jpg)

## Web Scraping Topics Information

There are different topics newsletters and i have scraped the information of each topic like topic description and topic url.This topics info will give us an idea on the topic and we can read the newsletters based on the topic. I have scraped the data into the dataframe using `Pandas`. Pandas is one of the library in python

## Web scraping Newsletters Information From all the Topics Pages

There are so many and so many newsletters and i have scraped all the newsletters information from all the topics in all the pages.
There are approximately more than 1400 newsletters from 48 topics and the data is scraped into the pandas dataframe.The newsletter info specifies title of the newsletter,topic name,newsletter description and newsletter url.

## Web scraping Top 30 Newsletters from all the Topics

Here, I have scraped the top 30 newsletters information from all the topics and stored it into the dataframe using pandas.The newsletter info specifies title of the newsletter,topic name,newsletter description and newsletter url.
