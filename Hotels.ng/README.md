# Hotels.ng Web Scraping

## Task
Write a python script to automate the collection of public information from a website and save it in a tabular format. 

## Aim 
To Collect hotel listings information from hotels. ng website and save as a CSV document.

## About the website
[Hotels.ng](https://hotels.ng/) is an online travel agency specialising in hotel bookings within Nigeria. They help clients book hotel rooms online. They also provide comprehensive help and support to clients and make the hotel booking process smooth and easy. In addition, they provide hotel recommendations and reviews.

The data I scraped
- name
- address
- facilities
- average price per night
- rating

## Libraries
For this, I use Selenium to automate the browser. Other libraries that are used include:
- Requests
- BeautifulSoup
- lxml

## Data Cleaning
After scraping the data, I carried out data cleaning using Excel.

- Dirty Data
<img width="945" alt="Hotels ng dirty data" src="https://user-images.githubusercontent.com/92667306/161396374-0998a148-2894-4719-af36-886c5d818e0c.PNG">

- Clean Data
<img width="871" alt="Clean data" src="https://user-images.githubusercontent.com/92667306/161397381-39d00cf2-32c9-4f4b-bea8-4ded1cc86a65.PNG">

## Result output
A total of  854 hotel listings data for hotels in Kaduna, Abuja, Lagos, and Rivers State were extracted from the website. 
