# Real Estate Website Scraping: Project Overview

In this project, I scraped data from [Nigerian Property center](https://nigeriapropertycentre.com/) a real estate website in Nigeria. My focus was on houses for rent in Victoria Island Oniru Lagos. **[Oniru](https://www.neighbourhoodreview.com/a-comprehensive-review-of-oniru/)** is a neighbourhood in the spectacular Victoria Island area of Lagos. It’s a highbrow neighbourhood with serene and clean surrounding, made up of apartments with state-of-the-art designs. The Oniru area is one of the most sought after locations for property acquisition in Lagos. Many people prefer the area when making plans on where to reside in Lagos, also several companies have offices around the area.

I scraped over 350 house information put up for rent from one of the biggest real estate web sites in Nigeria, nigeriapropertycentre.com using python Beautiful Soup, the Requests Library and Pandas Dataframe.

The results are stored inside a CSV File.

# Code and Resources Used
* Python Version: 3.7
* Packages: pandas, beautifulSoup, requests Library

# Web Scraping
I wrote the script to scrape 380 house information put up for rent. I scraped the following information:

* Title
* Address
* Price
* Other information

# Data Cleaning
After scraping the data, I needed to clean it up. I made the following changes: 
* I used the apply(lambda x:x.strip("")) to remove some unintelligile characters and the str.replace () to remove words not needed from the the dataframe created
* I also used Microsoft Excel for cleaning the data


CSV Result Snapshot
<img width="877" alt="Snapshot" src="https://user-images.githubusercontent.com/92667306/142947253-3de58e57-c3a9-4076-bcd6-7e5efb0aafaa.PNG">

