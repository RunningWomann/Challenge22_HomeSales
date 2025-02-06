# Challenge22_HomeSales

Utilize PySpark and Spark SQL on Google Colab to analyze home sales data and determine key metrics.

Data Description:
The dataset contains information for over 33,000 homes sold between 2019-2022. The original dataset can be found here.
The dataset has 11 columns including: id, date, date_built, price, bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, and view rating.

Approach:
Create a Spark Session and read in the CSV file into a dataframe
Preview the first 20 rows of the dataframe
Create temporary views of the data
Run queries on cached and uncached data and compare the run times
Partion the data and leverage parquet formatted data
Run queries in Spark to answer the questions below

Key Questions & Metrics:
1. What is the average price for a four-bedroom house solde each year?
2. What is the average price of a home for each year it was built that has 3 bedrooms and 3 bathrooms?
3. What is the average price of a home for each year that has 3 bedrooms, 3 bathrooms, 2 floors and is greater than or equal to 2,000 square feet?
4. What is the "view" rating for homes costing more than or equal to $350,000?
