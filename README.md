# Mission to Mars

## Overview
Robin's web app looks great and works well, but she wanted to give it a little more polish. She was looking at pictures of Mars' hemispheres when she discovered the site was scrape-friendly. She wants to update the present online app to incorporate photos from all four hemispheres. This will include adding more scraping code to retrieve the high-resolution photos, updating Mongo to include the new data, and changing the design of her web interface to accommodate these images.

## Resources
Software:
- Anaconda 4.7.12
- BeautifulSoup 4.8.1
- Splinter 0.12.0
- Flask 1.1.1
- PyMongo 3.10.0

## WorkDone
Image and table data scrapping from [NASA Mars News](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest). Wrote a Python script to scrape the data and store it in a Mongo DataBase. Then using Flask and Bootstrap, uploaded the data to a webpage. 

## Challenge Summary
Scraped images from [Mars' hemispheres](https://courses.bootcampspot.com/courses/95/assignments/600?module_item_id=2564) and displayed them in a grid format on the webpage. Also added a new HTML template for the scraping page which includes a "Go Back" button to return to the home page. Used CSS classes to display the table in a more sophisticated manor. 

#### Portfolio Screenshot
--------------------------------------site_image comes here------------------------------------------------------------------------