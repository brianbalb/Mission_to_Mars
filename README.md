# Mission_to_Mars
Request for Web Scrapping Project

# Overview

The request for this project was to build a Web Application that would scrape several website and website pages for the use of collecting relevent and current Mars Data.The extracted data would be stored in a NoSQL database and the results would publish in an HTML page.

## Resources

Python 3.7
splinter 0.14.0
webdriver-manager 3.3.0
Flask 1.1.2
Flask-PyMongo 2.3.0
BeautifulSoup (bs4) 0.0.1
html5lib 1.1
lxml 4.6.3

# Use Web App 

1, Selecting the "Scrape New Data" button will obtain the latest news, images, and facts about Mars.
2. News titles and summaries are extracted from NASA Mars Exploration Program News. 
3. The featured images are extracted from the Jet Propulsion Laboratory's Space Images. 
4. Mars hemisphere images are extracted from Astropedia. 
5. Finally, the Mars facts are gathered from Galaxy Facts. 

* (The scraping code used in this project is scraping.py.) *

**After running app.py, the extracted data is successfully stored in MongoDB. A mars_app database must exist in mongo for the code to properly run.**

# Update the Web App

Additionally I added a Bootstrap 3 components, allows the four Mars hemisphere images to be displayed side-by-side on Desktop browsers, instead of a line. Allowing the end users to see all four images at once.
