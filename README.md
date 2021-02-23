# web_scraping_challange
Mission to Mars
Flask web application that scrapes various websites for data related to the Mars Mission and displays the information in a single HTML page.

Scrapping
NASA Mars News
Script collects the latest News Title and Paragraph Text.
JPL Mars Space Images - Featured Image
Script finds the image url for the current Featured Mars Image and assigns the url string of the full size image.
Mars Weather
Script visits the Mars Weather twitter account and scrapes the latest Mars weather tweet.
Mars Facts
Script visit the Mars Facts webpage and uses Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.
Mars Hemispheres
Script visits the USGS Astrogeology site and obtains the full resolution images for each of Mars' hemispheres.
MongoDB and Flask Application
The MongoDB is currently hosted on the Database-as-a-Service https://mlab.com/. It requires a config.py file (hidden) using a driver via the standard MongoDB URI. 
The config.py contains a variable "authentication=" set to the MongoDB URI.
