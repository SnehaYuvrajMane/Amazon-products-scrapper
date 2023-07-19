# Amazon Product Scrapper

This is a script that takes various products from the given dataset and scrapes the `amazon.in` to get the products data and stores the data in a csv file.

## 📌 working of the project
The project works in various steps

**step 1:** Import the required libraries.

**step 2:** Import the dataset and read the data from the dataset.

**step 3:** Iterate through the data. In this step we perform certain actions as follows:
1. Read the roduct link.
2. Get the product data by using selenium.
3. put that data in BeautifulSoup.
4. get the required fields.
5. add the data to a list of products.

**Step 4:** Store the list of products to the csv file.


> 📓 **Note:** The project has around 2000 products so may take some time to scrape. The output is stored in a file named **Scraped_data_amzn.csv**.
