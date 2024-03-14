# Web Scraping Challenge
### Background
After conclusion of module 11 lessons, use the knowledge gained to extract information via both 
browsing with Splinter and HTML Parsing with Beautiful Soup. Use skills learned to collect data,
organize and store data, analyze data, and turn the data to visual graphs.

### Challenge Deliverables
* Deliverable 1: Scrape titles and preview text from Mars news articles 
    - `part_1_mars_news.ipynb`
    - optional: json file of data scraped
* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table
    - `part_2_mars_weather.ipynb`
    - exported data to a csv file

### Instructions/Requirements
## **Part 1: Scrape Titles and Preview Text from Mars News (40 points)**

* Automated browsing (with Splinter) was used to visit the Mars news site, and
the HTML code was extracted (with Beautiful Soup). (10 points)

* The titles and preview text of the news articles were scraped and extracted. (20 points)

* The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)

## **Part 2: Scrape and Analyze Mars Weather Data (60 points)**

* The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)

* The data was analyzed to answer the following questions: (10 points)

    * How many months exist on Mars? (5 points)
    * How many Martian days' worth of data are there? (5 points)

* The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (30 points)

    * Which month, on average, has the lowest temperature? The highest? (10 points)
    * Which month, on average, has the lowest atmospheric pressure? The highest? (10 points)
    * How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. (10 points)

* The DataFrame was exported into a CSV file. (5 points)

## Notes
* Ran into an error `typeerror 'str' object is not callable` when plotting the last graph for part 2,
utilized the following stack overflow link to resolve issue.
https://stackoverflow.com/questions/65172029/why-do-i-get-str-object-is-not-callable
