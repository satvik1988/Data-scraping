# Data-scraping
Data-scraping-
The main focus is on data scraping from two from two links and creating the new dataset. then ploting the distribution of happiniess score per country. finding 10 least happy countries,average hapiness,countries above median and finally ploting the correlation between 2pais of variables.
Here are the links which are refered form wiki.
https://en.wikipedia.org/wiki/World_Happiness_Report#2019_report
 https://simple.wikipedia.org/wiki/List_of_countries_by_continents
 
Fill in the fields to see the markdown badge snippet.
please fill this before executing the code on binder
try:
    import sklearn
except ModuleNotFoundError:
        !pip install scikit-learn
try:
    import matplotlib.python as pit
except ModuleNotFoundError:
        !pip install matplotlib
        
!pip install xlrd

try:
    import pandas as pd
except ModuleNotFoundError:
        !pip install pandas
try:
    from bs4 import BeautifulSoup
except ModuleNotFoundError:
        !pip install bs4
