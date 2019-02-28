# Mission-to-Mars

In this assignment, web application is build that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page. BeautifulSoup has been used to scrape data from several websites containing Mars news. Different types of data included were images of Mars, tweets about the current Mars weather, a table of Mars facts, and headlines with the latest Mars news. After scraping the data, data are stored in MongoDB and then loaded it into an HTML file using a Flask/Jinja template that interfaces with Python. Finally, formatted the HTML using Bootstrap and configured the app such that clicking a button on the webpage would re-scrape and load the data.

## Prerequisites

The Python libraries `flask`, `flask_pymongo`, `BeautifulSoup`, and `splinter` must be installed in order for the code to run. The initial data scraping can be run either in a Jupyter Notebook or in Python.

## Built With

* Python / Jupyter Notebook
* Pandas
* BeautifulSoup
* Flask
* Splinter / Selenium
* MongoDB
* HTML 5.0
* Bootstrap