# Home_Sales
This project uses PySpark to analyze home sales data. The analysis includes calculating average prices for homes based on various criteria such as bedrooms, bathrooms, year built, and view ratings.

## Getting Started
To run this project, you will need Python, PySpark, and Jupyter Notebook installed. The dataset used is home_sales_revised.csv.

## Prerequisites
- Python 3.x
- PySpark
- Jupyter Notebook
## Installing PySpark
You can install PySpark using pip:
- pip install pyspark
## Dataset
The dataset home_sales_revised.csv contains information about home sales, including columns for date, date_built, price, bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, and view.

## Running the Analysis
1. Clone the repository:

git clone https://github.com/Neil7777/Home_Sales
2. Open Home_Sales.ipynb in Jupyter Notebook.
3. Execute the cells to run the analysis.
## Analysis Questions
1. Average price for a four-bedroom house sold for each year.
2. Average price of a home for each year the home was built, with 3 bedrooms and 3 bathrooms.
3. Average price of a home for each year the home was built, with 3 bedrooms, 3 bathrooms, two floors, and is greater than or equal to 2,000 square feet.
4. Average price of a home per "view" rating having an average home price greater than or equal to $350,000.
## Results
The results of the analysis can be found in the notebook Home_Sales.ipynb.

## Caching
The temporary table home_sales is cached for some queries to improve performance. The runtime for cached and uncached queries is compared.

## Parquet Data
The home sales data is also saved in parquet format partitioned by date_built. The analysis is run on this parquet data as well, with runtime comparisons.

## Author
- Neil Lawren