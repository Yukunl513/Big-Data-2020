# Yelp Crawling - Selenium
Using selenium to access the multi pages html source. Extract targets information by access page source through BeautifulSoup

## Prerequisites
Selenium
BeautifulSoup

## Installing and Download
pip install bs4
pip install selenium
download the webdriver based on your browser: eg. ChromeDriver - https://chromedriver.chromium.org/

## Crawling page source

### Target information
Yelp Crawling data 
- The stores information about donuts in New York City Manhattan Borough
''' original_url = 'https://www.yelp.com/search?find_desc=donuts&find_loc=New%20York%2C%20NY&cflt=donuts'
    file_path = 'C:/Users/yukun/Desktop/DonutsStores/NYDonuts_page.html'
'''
- Locate the Url that we want to crawling data: https://www.yelp.com/search?find_desc=donuts&find_loc=New%20York%2C%20NY&cflt=donuts
- Build up a local host path to store hmlt file which contains information
- Start selenium with Chrome driver
- Access each page source by Chrome driver and write page source into html file
Secondly - Applying BeautifulSoup to accesss the information stored in each html files
         - Reterieve target information such as: 
              - store_name
              - store_rating
              - store total number of reviews
              - store_phone_number
              - store_location
              - store_neighbors
