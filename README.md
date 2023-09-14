# web-scraping-challenge

<font size="3">**News and Weather on Mars**  
**Contributors:** Thomas Keene
---
## Repository Overview:
This repository contains two technical deliverables along with their associated output files. The primary two deliverables are as follows:
- Deliverable 1: Scraped titles and preview text from Mars news articles (part_1_mars_news.ipynb).
- Deliverable 2: Scraped and analyzed Mars weather data (part_2_mars_weather.ipynb).

## Background
For Deliverable 1, automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted with Beautiful Soup. The titles and preview text of the news articles were scraped and extracted and the scraped information was stored in a Python data structure (specifically, a list of dictionaries). Once completed, the scraped data were stored in a file (to ease sharing the data with others). This was done by exporting the scraped data to a JSON file.

For Deliverable 2, automated browsing (with Splinter) was used to visit the Mars weather site, and the weather data (contained in an HTML table) was extracted with Beautiful Soup. The extracted data was then assembled into a Pandas DataFrame. The data types were then examined, and subsequently recast to either "int", "float", or "datetime" (as necessary) to facilitate further data analysis. The results of the analyses were presented both as raw values, as well as with corresponding graphs. Finally, the DataFrame was saved as a .csv file (to ease sharing the data with others).

## Resources:
Some coding I looked at for inspiration:
- https://github.com/zachaa/web-scraping-challenge
- https://github.com/Andrew-Bourgeois/web-scraping-challenge

## Acknowledgements:
I wish to thank my teaching staff:
- Hunter Hollis
- Sam Espe
- Randy Sendek
