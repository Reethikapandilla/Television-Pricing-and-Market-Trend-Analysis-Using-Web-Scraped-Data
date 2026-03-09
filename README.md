# **Television Pricing and Market Trend Analysis Using Web Scraped Data**

### **Project Overview**

This project focuses on analyzing television product data collected through web scraping to understand market trends, pricing patterns, and customer preferences. The dataset was scraped from an e-commerce platform and processed using Python-based data analysis techniques.

The objective of the project is to convert raw unstructured product listings into a structured dataset and perform Exploratory Data Analysis (EDA) to uncover meaningful insights related to TV pricing, brand distribution, resolution types, and customer ratings.

### **Problem Statement**

Comparing television products across online platforms can be challenging due to differences in price, features, discounts, and specifications.

This project addresses the problem by:

- Collecting TV product data from an e-commerce platform

- Cleaning and structuring the scraped dataset

- Analyzing pricing patterns, ratings, and market distribution

- Identifying key trends that influence TV pricing and customer preferences

- The final analysis provides insights that help understand market trends and purchasing patterns. 

### **Project Objective**

The main objectives of this project are:

- Collect television product data using web scraping

- Clean and preprocess raw scraped data

- Analyze pricing trends and product characteristics

- Identify patterns related to resolution, screen size, brand, and ratings

- Generate insights to support better purchasing decisions

### **Data Source**

Platform: Flipkart (E-commerce website)
Data Type: Web Scraped Product Listings

The dataset contains information such as:

- TV Brand

- Price

- Original Price

- Resolution

- Screen Size

- Customer Ratings

- Number of Ratings

- Number of Reviews

- Warranty

- Discount

The raw scraped data initially contained 8 columns, which were later cleaned and transformed into 13 structured columns for analysis. 


### **Technologies & Libraries Used**

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook

- Web Scraping Techniques


### **Data Collection (Web Scraping)**

Television product data was automatically collected from Flipkart product listings.

The scraping process involved:

- Extracting product information such as brand, price, resolution, ratings, and reviews

- Converting raw webpage content into a structured dataset

- Saving the collected data for further analysis

- The raw dataset contained mixed text, numbers, and symbols, which required preprocessing before analysis. 


### **Data Cleaning & Preprocessing**

Several preprocessing steps were performed to prepare the dataset for analysis:

- Handling missing values

- Removing duplicate entries

- Cleaning unwanted text and symbols

- Converting columns such as price, rating, reviews, and discount into numeric formats

- Splitting combined fields into meaningful columns

After preprocessing:

- 0% null values

- 0% duplicate records

Dataset fully structured for analysis. 

## **Exploratory Data Analysis (EDA)**

### **Univariate Analysis**

Univariate analysis was used to understand the distribution of individual variables.

Visualizations used:

- Price Distribution

- TV Resolution Distribution

- Rating Boxplot

- Market Share of Top Brands

### Key Findings:

- TV prices are right-skewed, with most TVs in the lower to mid-price range

- Most customer ratings cluster around 4 stars

- Ultra HD TVs appear most frequently in the dataset

### **Bivariate Analysis**

Bivariate analysis explores relationships between two variables.

Visualizations include:

- Price vs Screen Size

- Average Price vs Warranty by Resolution

- Average Price by Resolution

- Top Brands by TV Count

### Key Findings:

- Price increases as screen size increases

- Higher resolution TVs generally have higher average prices

- Premium TVs often come with longer warranties

### **Multivariate Analysis**

A correlation heatmap was used to analyze relationships between multiple numerical variables.

#### Key Observations:

- Strong positive correlation between price and original price

- Number of ratings and reviews are highly correlated

- Price has a weak positive relationship with rating and warranty

### Key Insights

- TV prices increase with higher screen resolution and larger screen size

- Ultra HD TVs show the highest pricing and variability

- Budget and mid-range TVs dominate the market

### **Conclusion**

This project demonstrates how web scraping combined with data analysis can provide valuable insights into market trends. Resolution and product positioning strongly influence TV pricing
Budget and mid-range TVs dominate consumer demandPremium TVs form a smaller but higher-value market segment. Data analytics helps businesses and consumers better understand pricing strategies, 
market competition, and consumer preferences in the television market.
