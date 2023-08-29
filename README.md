# Web Scraping Challenge Submission
Web scraping challenge for the UNC Data Analytics Bootcamp.

## Description
This repository contains two main deliverables:
- part_one_mars_news.ipynb
- part_two_mars_weather.ipynb

The _...news.ipynb_ file is a Jupyter Notebook file which uses the Beautiful Soup Python library to collect data from [this Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html).  The script collects headers for the page, as well as the title and preview text for each article on the page.  The article data is then stored into a Dictionary called articles.

The _...weather.ipynb_ file also uses Beautiful Soup, this time to scrape [weather data](https://static.bc-edx.com/data/web/mars_facts/temperature.html) collected by the Curiosity rover on Mars.  The data from this table is compiled into a Pandas Dataframe, which is then used to generate several visualizations to see monthly temperature and pressure data.  Finally, a line graph of the daily temperature data (seen below) is generated and used to approximate the length of a Martian year to 675 Earth days (the true value is Earth 687 days).  

[PICTURE]

Note: for both files, in order for the splinter object Browser to run, a device-specific was specified and passed to the Browser object when it was defined.

## Authorship

Starter code was provided by the UNC Data Analytics Bootcamp for both .ipynb files.  All web scraping and data visualization code was written by Sam Lind.
