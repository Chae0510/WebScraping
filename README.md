# 0. File description
---
#### 1. DataAnalysis.ipynb 
👉 Contains code that implements web scraping. It extracts data from Etsy using Python's requests and the BeautifulSoup library. 

#### 2. items.csv
👉 Scraped data is stored.
#### 3. updated_items.csv
👉 Contains the preprocessed data from items.csv
#### 4. webscraping.ipynb
👉 Provides analysis of various variables, including basic statistical measurements and visualizations of data, such as selling prices, discount rates, and free shipping. (Extract data from Etsy using requests and the BeautifulSoup library)
# 1. WebScraping
---
#### 1-1. Choose a website with publicly accessible data that includes a numerical target variable. Suggested websites: Indeed, Etsy.
#### 1-2. Use a programming language of choice (consider Python with libraries like BeautifulSoup and Selenium) to write a simple web scraper to extract specific information related to the target variable from the chosen website. (At least 1000 rows)
#### 1-3. Focus on fundamentals such as making HTTP requests, parsing HTML, and extracting relevant data.
#### 1-4. Save it as .csv

#### Output: items.csv
<img width="799" alt="image" src="https://github.com/Chae0510/WebScraping/assets/85086390/e28d83e0-d4b2-4a1a-93a3-77e45e0d65c4">

#### link: [etsy](https://www.etsy.com/search?q=bracelet&anchor_listing_id=854275908&ref=hp_bubbles_VDAY24_CoreMarkets&mosv=sese&moci=1226894514292&mosi=1231853541395&is_merch_library=true%27)
<img width="1411" alt="image" src="https://github.com/Chae0510/WebScraping/assets/85086390/797b089e-06db-4454-bdee-05387fd3428b">

---
# 2. Data Analytics, and Visualization
---
### Condition
#### 2-1. Obtain a small dataset by collecting data using the web scraper from Part 1. The dataset should include the numerical target variable.
#### 2-2. Use a tool like Pandas for data manipulation and analysis.
#### 2-3. Apply basic statistical measures (mean, median, standard deviation) to understand the distribution of the target variable.

#### After Preprocessing
<img width="511" alt="image" src="https://github.com/Chae0510/WebScraping/assets/85086390/08d8b388-ab93-4077-af4b-9904c4e82b72">

1. convert 'k' values to numeric in Total Reviews
2. Drop rows with NaN in 'Total reviews'
