# AnakinAssignment

## Web Scraping Task

For this assignment: Go to [https://food.grab.com/sg/en/](https://food.grab.com/sg/en/) and enter any place in Singapore. The website will display a number of restaurants around the given location.

Scroll down and you will see more restaurants

For this assignment, you have to fetch and give the latitudes and longitudes of all the restaurants on this page

 To access it on your browser, you would have to use a VPN or a proxy. Hope that helps. As you will notice, latitudes and longitudes are not available on the page -- but there is a way to get them from the **same page** - without using any third-party service such as maps opening each restaurant separately etc. The assignment is to find a way to get the data from the same page and code it. 

Do not use any python maps libraries like Geopy, Geopandas etc. or even Google Maps, Open Maps etc. The data is directly given from Grab. You have to find it and then, write a code to scrape it. 

Do note that we need the latitudes and latitudes of ALL restaurants for all of Singapore - which should be more than a hundred on one page (in a city like Manila, Philippines).

# Approach 

This Python script utilizes Selenium to scrape restaurant data from the GrabFood website. It navigates through the pages, fetching restaurant names, coordinates, and cuisine types, and appends them to a JSON file. The script iterates over multiple pages by clicking the 'Load More' button, ensuring comprehensive data collection.

## Programming language used to solved this problem

- Python

## Tools used
 
- Selenium

# If you like my work please give it a star

Thank you!
