# Zomato-Web-Scraping
Web scraping Zomato with Python and Beautifulsoup. Lisbon restaurants dataset available.

PROJECT GOALS
-------------
This small project had two basic objectives:
- Create a simple and versatile dataset with the top restaurants in the Greater Lisbon Area, Portugal.
- Practice Web Scraping with Python and the BeautifulSoup library.

LIMITATIONS
-------------
- Zomato's website uses dynamic JavaScript, which limited the number of restaurants possible to scrape to only the first 9 that were automatically loaded without needing to scroll down. I tried using the Selenium library (which allows to scrape websites with dynamic JavaScript and simulate human interactions) but I found that its documentation was outdated and I could only find resources for deprecated functions.
- Zomato's html structure would varry sporadically. In those cases this code will not fully work (I would have to rerun the request a couple of times). If facing this issue, refer to the restaurants_backup.csv file available.
