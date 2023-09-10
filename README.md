# webscraping-challenge
Module 11 Challenge - Web Scraping
Contributor: Katy Yelle

### Repository Structure
    -Main Folder
        -README.md
        -.gitignore

    -Sub Folders
        -Mars
            -part_1_mars_news.ipynb
            -part_2_mars_weather.ipynb
            -output folder

### Overview
-part_1_mars_news.ipynb </br>
This jupyter notebook file scrapes titles and preview text from Mars news articles from https://static.bc-edx.com/data/web/mars_news/index.html 

-part_2_mars_weater.ipynb </br>
This jupyter notebook file scrapes, cleans, visualizes and analyzes Mars weather data from a table from https://static.bc-edx.com/data/web/mars_facts/temperature.html. The scraped data is then analyzed to answer the following questions: 
    -how many months exist on mars?
    -how many martian days worth of data are in the data set?
    -what are the coldest and warmest months on Mars (at the location of Curiosity)?
    -which months have the lowest and highest atmospheric pressure on Mars?
    -how many terristrial (Earth) days exist in a Martian year?
 
 The created DataFrame is then exported to a CSV file saved in the 'output' folder. 