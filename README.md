# Cleaning Data in Python
Cleaning book data from three data sources (API, .csv file, and web page). 

API pull for NYT bestseller lists from the New York Times [Books API](https://developer.nytimes.com/docs/books-product/1/overview).

Demonstrates technical skills for cleaning data from various sources. Data is procured from a flat file (.csv), web scraping (web page), and an API pull. 
Each data source is cleaned individually. Cleaned data sets are then loaded into SQL tables. SQL tables are then combined into a single data table. 
The combined data set is then used to produce visualizations. 

## How to Run Code Locally
- Clone repo
- Go into repository on local device
- In the config.py file, add your API secret key to the my_key variable instead of YOUR SECRET KEY and save changes
- Run Python Code file using Jupyter Notebook server (such as Anaconda) or other preferred Python IDE

## Libraries Used
To clean .csv file:
- pandas
- numpy

To clean web page data:
- requests
- bs4

To clean data pulled from API:
- itertools
- requests
- urllib3
- json

To build data base:
- sqlite3
- sqlalchemy

For visualizations:
- math
- matplotlib

## Contact
Gillian Tatreau – gillie.tatreau97@gmail.com

Project Link: https://github.com/gilliantatreau/Cleaning-Data-in-Python
