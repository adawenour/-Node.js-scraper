-Node.js-scraper
================

web scraper will be minimalistic. The technology stack that will be used to accomplished this will be NodeJS, ExpressJS, Request to Help make HTTP calls, Cheerio for Implementation of core jQuery, specifically for the server (helps traverse the DOM and extract data).

The application will visit a URL on my server that activates the web scraper

The scraper will make a request to the website to scrape.

The request will capture the HTML of the website and pass it along to the server.

The scraper will traverse the DOM and extract the data/information I want.

Next, I will format the extracted data into a format that is needed.

Finally, I will save this compiled and formatted data into a JSON file on my local machine. 

The information that will be extracted is the tile of the movie, release year and IMDB community rating of the specfic movie.

Note: Can also use the scraper to extract more information by repeating the stepes above. Simply by finding a unique element or attribute on the DOM that will help single out the data needed. If no unique element exists on the particular tag, I can find the closest tag that does and set that as the starting point. If needed, traverse the DOM to get to the data that is needed to extract the data.


