# Overview of proposed changes to LC Python lessons

1. Update the current [Intro to Python lesson](https://librarycarpentry.org/lc-python-intro/) to move to JupyterLab and use a more relevant LIS related dataset (~ 4 to 6 hours).
2. Create a new Using Web APIs with Python lesson (~ 2.5 hours)
3. Create a new Web Scraping with Python lesson (~ 2.5 hours)

### Introduction to Python
Possible datasets: 

- Chicago public library circulation data, adapted from [data.gov open datasets](https://catalog.data.gov/dataset/?q=chicago+%22circulation+by+location%22).
- [LC OpenRefine data](https://librarycarpentry.org/lc-open-refine/#downloading-the-data)
- [LC Unix shell data](https://librarycarpentry.org/lc-shell/#data-files)

##### Episode 1: Getting Started
Introduce JupyterLab environment + discuss examples of how library workers use Python in their work.

##### Episode 2: Variables
Adapt current LC episode

##### Episode 3: Data types and lists
Adapt current LC episodes

##### Episode 4: Built-in functions
Adapt current LC episode

##### Episode 5: Libraries and Pandas
Adapt current LC episode to focus on Pandas package. Intro .info, .head

##### Episode 6: Importing data & built-in Pandas functions
Create new df from CSV and explore Pandas functions. Use [SWC df episode](http://swcarpentry.github.io/python-novice-gapminder/08-data-frames.html) to introduce loc, iloc, slicing, basic stats (sum, mean), .to_csv()

##### Episode 7: For loops & conditionals
Adapt current episode

##### Episode 8: Looping over datasets
Cut or adapt current episode (glob)

##### Episode 9: Functions 
Adapt functions episode 

##### Episode 10: Reflect, Wrap up


### Using Web APIs with Python
Dataset: 

- OpenRefine CSV to build API calls
- [OpenAlex API](https://docs.openalex.org/)

##### Episode 1: Getting Started
##### Episode 2: Dictionaries
- Advanced lists

##### Episode 3: OpenAlex API - Documentation
##### Episode 4: HTTP Requests 
##### Episode 5: Conditionals & functions for Requests
- Variable scope

##### Episode 4: JSON
##### Episode 5: Data cleaning with Pandas
##### Episode 6: Saving to pickle

### Web Scraping with Python
Dataset: 

- Build HTML page to GitHub pages (so we have control)
- What data to use?

##### Episode 1: Getting Started
##### Episode 2: Introduction to HTML and CSS
- Chrome, Inspect a webpage
- HTML tags, attributes
- CSS selectors


##### Episode 3: Lightweight scraping tools 
- Chrome Scraper extension
- Introduce DOM


##### Episode 4: Requests & BeautifulSoup
- Connect to a single URL


##### Episode 5: For loops and saving to dictionaries
- Scrape page


##### Episode 6: Saving to Pandas
##### Episode 7: Scraping multiple pages
- Intro to building list of URLs and using for loop to scrape all
