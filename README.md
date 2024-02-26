# Web Scraping and Data Analysis Project

## Background

Welcome to my web-scraping and data analysis project! Over time, I learned to identify HTML elements on a page, extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup, and scrape various types of information like HTML tables and recurring elements. Now, it was time to apply these skills to analyze Mars-related data. This assignment consisted of two technical products:

## Deliverable 1: Scrape Titles and Preview Text from Mars News

I started by scraping titles and preview text from Mars news articles using Python and Beautiful Soup in the part_1_mars_news.ipynb file. Here's what I did:

1. Used automated browsing to visit the Mars news site and identified elements to scrape.
2. Created a Beautiful Soup object and extracted text elements from the website.
3. Extracted the titles and preview text of the news articles and stored them in Python data structures.

## Deliverable 2: Scrape and Analyze Mars Weather Data

Next, I scraped and analyzed Mars weather data in the part_2_mars_weather.ipynb file. Here's what I did:

1. Used automated browsing to visit the Mars Temperature Data Site and identified elements to scrape.
2. Created a Beautiful Soup object and scraped the data in the HTML table.
3. Assembled the scraped data into a Pandas DataFrame with appropriate column headings.
4. Examined and converted data types as needed.
5. Analyzed the dataset using Pandas functions to answer specific questions about Mars weather.
6. Exported the DataFrame to a CSV file (mars_weather_data).

## Code Citations

Scraping a table off of a web page and formatting into a list of lists:
(Found in input cell 6 of part_2_mars_weather.ipynb file)

https://saturncloud.io/blog/how-to-scrape-an-html-table-with-beautiful-soup-into-pandas/

Convert Pandas data type into datetime using to_datetime function:
(Found in input cell 10 of part_2_mars_weather.ipynb file)

https://stackoverflow.com/questions/15891038/change-column-type-in-pandas

Sort a series by its index:
(Found in input cell 12 of part_2_mars_weather.ipynb file)

https://www.w3resource.com/pandas/series/series-sort_index.php#:~:text=The%20sort_index()%20function%20is,original%20series%20and%20returns%20None.&text=Axis%20to%20direct%20sorting.,only%20be%200%20for%20Series.
