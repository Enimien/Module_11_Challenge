# Module_11_Challenge
This project involves creating two technical products related to Mars exploration data. The tasks involve web scraping and data analysis using Python. The deliverables are as follows:

Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyze Mars weather data from a table.
Firstly we import the dependencies Splinter and BeautifulSoup and also Visit the Mars news site
creates a Beautiful Soup object and parses the HTML content to scrape and extract text elements from a webpage.
Store Data in Python Structures:Store each title and preview text in a Python dictionary.
Each dictionary should have two keys, title and preview.
Store all dictionaries in a Python list and  Store the scraped data in a JSON file for easier sharing

While delivarable 2
This project involves web scraping and data analysis related to Mars temperature data. The goal is to extract data from an HTML table on the Mars Temperature Data Site and assemble it into a structured Pandas DataFrame for further analysis.
Web Scraping
Use automated browsing to visit the Mars Temperature Data Site at Mars Temperature Data Site.
Create a Beautiful Soup object to scrape the data in the HTML table.
Extract relevant data elements and assemble them into a Pandas DataFrame.
2. Data Cleaning
Ensure the DataFrame columns have the same headings as the table on the website.
Convert the data to the appropriate datetime, int, or float data types.
3. Data Analysis
Number of Months on Mars: Determine how many months exist on Mars.
Martian Days Data: Calculate how many Martian (and not Earth) days worth of data exist in the scraped dataset.
Coldest and Warmest Months on Mars:
To find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Lowest and Highest Atmospheric Pressure Months on Mars:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
Terrestrial Days in a Martian Year:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
4. Export Data
Export the DataFrame to a CSV file for further use and sharing.