# OASIS INFOBYTE DATA ANALYTICS INTERNSHIP

**Intern Name:** Lavishka Pahwa    
**Course:** Bachelor of Computer Applications (BCA)   
**Internship:** Oasis Infobyte Data Analytics Internship

## 📊 Project 1: Exploratory Data Analysis on Retail Sales

### Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Superstore Retail Sales dataset using Python. The analysis explores sales, profit, customers, products, regions, shipping methods, and other business-related factors.

### Objectives

* Understand the retail sales dataset.
* Check and clean the data.
* Analyze sales and profit patterns.
* Identify profitable product categories and sub-categories.
* Analyze customer segments and regions.
* Study shipping modes and order priorities.
* Analyze the relationship between sales and profit.
* Generate useful business insights through data analysis and visualization.

### Dataset

**Dataset:** Sample Superstore Sales

The dataset contains **8,399 retail sales records** and **23 columns**, including:

* Order Date
* Order Quantity
* Sales
* Discount
* Profit
* Unit Price
* Shipping Cost
* Customer Name
* Region
* Customer Segment
* Product Category
* Product Sub-Category
* Product Name
* Ship Date

### Data Cleaning

The dataset was checked for:

* Missing values
* Duplicate records
* Data types
* Numerical statistics

The dataset initially contained **63 missing values in Product Base Margin**. These missing values were handled during the data-cleaning process.

### Analysis Performed

The project includes analysis of:

* Total and average Sales
* Total and average Profit
* Sales and Profit by Product Category
* Sales and Profit by Region
* Order Quantity by Product Category
* Profit by Product Sub-Category
* Top products by Sales
* Top products by Profit
* Sales and Profit by Customer Segment
* Yearly Sales and Profit
* Monthly Sales and Profit
* Sales and Profit by Ship Mode
* Sales and Profit by Order Priority
* Average Discount by Product Category
* Shipping Cost by Ship Mode
* Correlation analysis
* Sales vs Profit visualization

### Key Findings

* **Technology** generated the highest overall sales and profit among the product categories.
* **Central** recorded the highest regional sales and profit.
* **Corporate** customers contributed the highest sales and profit among customer segments.
* **Regular Air** generated the highest sales and profit among shipping modes.
* Sales and Profit showed a **moderate positive relationship**.
* Some product sub-categories generated negative profit and may require further investigation.

### Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Excel
* GitHub

### Project File

The complete analysis is available in:

**`EDA_Retail_Sales.ipynb`**

### Conclusion

The EDA provided useful insights into retail sales performance, profitability, customer segments, products, regions, and shipping methods. These findings can help identify important business patterns and support data-driven decision-making.

---

**Oasis Infobyte Data Analytics Internship — Project 1**

## 📊 Project 2: Customer Segmentation Using K-Means Clustering

### Project Overview
This project focuses on segmenting ecommerce customers into different groups based on their online behaviour, membership duration, and yearly spending.

### Objectives
- Understand and inspect the customer dataset.
- Check for missing and duplicate values.
- Select relevant numerical features for clustering.
- Standardize the data using StandardScaler.
- Use the Elbow Method to determine the suitable number of clusters.
- Apply the K-Means clustering algorithm.
- Analyze customer behaviour in each cluster.
- Create visualizations to understand the customer segments.
- Provide business insights and marketing recommendations.

### Dataset
The dataset contains 500 ecommerce customer records and 7 columns, including:

- Email
- Address
- Avatar
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent

### Key Findings
- The customers were divided into 4 clusters using K-Means.
- Cluster 1 represents high-value customers with the highest yearly spending and longer membership duration.
- Cluster 0 represents customers with lower spending and shorter membership duration.
- Cluster 2 is the largest customer group.
- Cluster 3 has higher website activity with moderate-to-high spending.

### Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Project File
The complete project is available in:

`Customer_Segmentation.ipynb`

## 🧹 Project 3: Data Cleaning

### Project Overview
This project focuses on cleaning and preparing a concert tours dataset for further analysis.

### Data Cleaning Tasks Performed
- Checked the dataset structure and data types.
- Identified and handled missing values.
- Checked for duplicate records.
- Cleaned and standardized column names.
- Converted gross-related columns from text to numeric format.
- Cleaned the Peak and All Time Peak columns by removing reference markers.
- Created separate Start Year and End Year columns from the Year(s) column.
- Identified possible outliers using the IQR method.
- Retained valid outliers because they may represent genuine high-performing concert tours.
- Saved the cleaned dataset as a new CSV file.

### Dataset
The dataset contains information about major concert tours, including:

- Rank
- Peak
- All Time Peak
- Actual Gross
- Adjusted Gross
- Artist
- Tour Title
- Year(s)
- Number of Shows
- Average Gross

### Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

### Project Files
- `Data_Cleaning_Project.ipynb`
- `Cleaned_Concert_Tours_Data.csv`
