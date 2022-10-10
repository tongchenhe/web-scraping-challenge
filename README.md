# web-scraping-challenge

## Part 1
We parsed the [Mars News](https://redplanetscience.com/) website by using Splinter and Beautiful Soup. We scraped the titles and preview texts of the 20 most recent Mars news articles and converted them into a Python data structure. The data is then stored in a MongoDB database.

## Part 2
We retrieved the data from the [Mars Temperature Data](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) site and stored the data into pandas DataFrame.  
After that, we answered the following questions with related visualization using pandas:
 * How many months exist on Mars?
 * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
 * What are the coldest and the warmest months on Mars (at the location of Curiosity)?
 * Which months have the lowest and the highest atmospheric pressure on Mars?
 * About how many terrestrial (Earth) days exist in a Martian year? (using a visual estimate)