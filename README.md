# mars_analysis
The objective was to scrap data from a Mission to Mars website that contained data collected by Curiosity. The first portion of the project deliverable was to scrape all of the title and preview text from all of the posted Mars new articles.

To determine what data to scrap, the DevTools on the Chrome Browser was used to identify tags and attributes that could be used to cleanly scrape data. 

Once the data was scraped it had to be placed into a dictionary using a for loop. Placing the data in a dictionary format helps to store the data for use and easier analysis.

The dicitonary was then converetd to a json format and printed for display.

The second deliverable for the project was to scrape data from a Mission to Mars website from a table that contained data collected from Curiosity. The data was presented with Martian data relating to temperature, pressure, and Earth and Martian timeframes.

Using the DevTools again to deteremine the tag or attributes required to scrape the data from the table. The table data went through for loops to create a list of the scraped data. The data in the dataframe was converted to the correct data type to help with geting accurate calculations of the scraped data. This data was then placed into a dataframe to help with performing the analysis of the scraped data.

The analysis consisted of determingin the average temperature on Mar for the presented Mars months. Also the max and min temperatures observed on Mars. The average pressure for all Mars months.

To determing the number of days on Mars the temperature over the months was plotted. The associated days of the highest and lowest peaks of temperature data was subtracted to calculate the number of days in a year for Mars. There are about 687 earth days in a Mars year.

The data was then saved to a csv file for future use.

