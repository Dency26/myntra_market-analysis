MYNTRA MARKET ANALYSIS PROJECT

PROJECT ANALYSIS
0 The dashboard provides key insights into the company's most popular, most expensive and top brands in each product category.

DATASET USED
- **Source:** [https://www.kaggle.com/datasets/ashishjangra27/myntra-168k-products]
- **License:** Public domain
The dataset contains 168029 rows and 10 columns. The columns include brand name, rating, rating_count, marked_price, discounted_price, sizes, product link, image link, product tag and brand tag.

DATA CLEANING AND TRANSFORMATION
Basic data cleaning (finding missing values, correcting improper cases, removing duplicates) and creation of new useful columns (discounted amount, discount percentage, unique ID, weighted rating) are done in excel. Some important columns created are:
o	Discounted_ amount= marked_price-discounted_price
o	Discount_percent=round((discount_price/marked_price) *100,0)
o	Extract unique_id for each product from product link using ‘text to columns’
o	Number of available sizes in each product category
o	Removed duplicated columns based on extracted unique ID
o	The rating is converted to a more reliable weighted rate score
Weighted rating=rating*LN (rating_count +1)
DATA ANALYSIS
The data after cleaning contains 146136 rows and 16 columns. The data is then analyzed using various excel functions, table, power query and pivot tables. Analysis is done product wise and brand wise to have better understanding of brand/product performance, customer satisfaction, product popularity and discount.

DASHBOARD DEVELOPMENT
Interactive dashboard is created with the help of slicers and pivot charts.
Key Performance Indicators (KPIs): Incorporated KPIs to provide quick insights into total brands and total product categories in Myntra.
Interactive slicers help to choose a product category and shows the top 5 brands based on average weighted rating, top 5 most expensive brands based on discounted price and top 5 most popular based on average rating count. The number of brands and product types are also shown dynamically in a box.
 <img width="975" height="363" alt="image" src="https://github.com/user-attachments/assets/426013bf-45d1-4dac-a152-a968605df13e" />


CONCLUSION
This market analysis dashboard project creates an interactive dashboard which gives a quick insight into the various top 5 brands of each product category. This analysis gives insights into the most popular brands, most expensive ones and top-rated brands of the selected product. This is an easy way to understand the customer preference and number of brands and product associated with each product category.
