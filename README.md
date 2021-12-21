# webscraping-zomato
Web Scraping Zomato with Python and Beautifulsoup

PROJECT GOALS
-------------
The goal with the project was to get more acquianted with BeatifulSoup, and to create a good dataset with restaurants in Lisbon, since I had not been able to find any.
At the end of the project, an interactive dataframe was built with ipywidgets.

LIMITATIONS
-----------
Zomato has dynamic html classes, which can make webscraping the website difficult. If the Webscraping code does not run correctly, it's likely because Zomato changes their html class names.
For that, I provide the restaurants_backup.csv, with the information I was able to webscrape beforehand.
