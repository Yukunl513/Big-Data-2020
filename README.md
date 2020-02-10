# Big-Data-2020
Yelp Crawling data - The stores information about donuts in New York City Manhattan Borough
Fristly - Locate the Url that we want to crawling data: https://www.yelp.com/search?find_desc=donuts&find_loc=New%20York%2C%20NY&cflt=donuts
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
