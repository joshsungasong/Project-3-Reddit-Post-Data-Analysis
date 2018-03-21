# Project 3: Reddit Post Data Analysis

# Content of this repository

This repository contains a Jupyter Notebook containing code that showed importing the CSV file that I created after web scrapping Reddit.com. It shows coding for data cleaning/munging, feature engineering, exploratory data analysis, natural language processing, and model building.

# Description of the data set

The dataset consists of data that was scrapped from Reddit through Python's BeautifulSoup to pull the attributes of a Reddit post explained above. It includes, for each Reddit post collected, the number of comments, the number of upvotes, the title of the post, the time posted, and the 

# Key findings from the project
I was able to discover that the time of day along with the number of upvotes are a good predictor of whether a Reddit post is above or below the median number of comments. It means that a post uploaded unto Reddit during working hours and in the morning will be able to draw more comments than of other times of days. 

# Key limitations of my project

A big limitation here is that my data was collected at a specific time of day. It was not collected at different days to get a more wide data set to be more representative. I'm only collecting posts collected probably only within a day or less than a day. A better approach would have been to web scrape at different points of the day and for a few weeks or even for a month.

# List of concepts and skills utilized for this project

I used a variety of concepts and skills for this project and they are listed below:
- Web Scrapping through BeautifulSoup
- Logistic Regression Classifier
- Random Forests Classifier
- Natural Language Processing
    - CountVectorizer
    - TF-IDF Vectorizer
- Model Building
- Exploratory Data Analysis
- Data Cleaning/Munging
- Feature Engineering
