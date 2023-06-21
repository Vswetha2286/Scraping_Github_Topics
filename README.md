# Scraping_Github_Topics

Introduction:

Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It's a useful technique for creating datasets for research and learning.

Problem Statement:

Getting the list of Topics and scraping the top repositories for each topic on Github.

Tools Used: Python,requests,BeautifulSoup,Pandas

Here are the steps to follow:

I'm going to scrape https://github.com/topics.
Parse the downloaded html content using Beautiful Soup.
Will get a list of topics. For each topic, we'll get topic title, topic page URL and topic description from Soup Object.
For each topic, we'll get the top 25 repositories in the topic from the topic page
For each repository, we'll grab the repo name, username, stars and repo URL
Creating a DataFrame using pandas libraries of the scraped data
Finally save the dataframe as a CSV file .
