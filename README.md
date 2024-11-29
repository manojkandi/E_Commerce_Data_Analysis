## E-Commerce Data Analysis Project 

## Project Overview  
E-Commerce Data Analysis Project is a data engineering project aimed at analyzing large-scale E-Commerce data to generate actionable insights. This project helps the marketing department identify key sales trends, product popularity, and regional performance, supporting data-driven business decisions.

## Table of Contents  

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Insights and Visualizations](#insights-and-visualizations)  
- [Future Enhancements](#future-enhancements)  

## Features  
- Data Generation: Synthetic e-commerce data with realistic variations across products, locations, and time periods.  
- Data Analysis: Analyze sales performance by category, location, and product.  
- Visualization: Generate insightful visualizations to track trends, product popularity, and regional sales performance.  
- Scalable: Easily customizable for larger datasets or additional features.

## Technologies Used  

- Programming Language: Python  
- Libraries:  
  - `pandas` (Data manipulation)  
  - `matplotlib` (Data visualization)  
  - `csv` (Data generation)  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/manojkandi/E_Commerce_Data_Analysis.git
   cd E_Commerce_Data_Analysis
   ```

2. Create and activate a virtual environment (optional but recommended):  
   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/macOS
   env\Scripts\activate     # For Windows
   ```

3. Install dependencies:  
   ```bash
   pip install pandas matplotlib
   ```

## Usage  
### Step 1: Generate Synthetic E-Commerce Data  
Run the data generator to create a dataset with 10,000 records:  
```bash
python ecommerce_data_generator.py
```

### Step 2: Analyze and Visualize Data  
Execute the analysis script to generate visual insights:  
```bash
python ecommerce_analysis.py
```

### Step 3: View Visualizations  
The script will generate the following plots:  
- Monthly Sales Trends  
- Top 10 Most Popular Products  
- Sales by Location  
- Sales Performance by Category  


## Project Structure  
```
E-Commerce Data Analysis Project/
│
├── ecommerce_data_generator.py       # Script to generate synthetic CSV data
├── ecommerce_analysis.py             # Script to analyze and visualize the data
├── ecommerce_data.csv                # Generated dataset (after running the generator script)
└── README.md                         # Project documentation
```


## Insights and Visualizations  

### 1. Monthly Sales Trends  
Tracks total sales per month, helping identify seasonal trends.  

### 2. Top 10 Most Popular Products  
Displays the most frequently purchased products by quantity.

### 3. Sales by Location  
Highlights the total sales in different geographic regions.  

### 4. Sales Performance by Category  
Breaks down total sales by product category.


## Future Enhancements  
- Interactive Dashboards: Integrate with Tableau or Power BI for dynamic visualizations.  
- SQL Integration: Store and query data from a relational database for better scalability.  
- Predictive Analytics: Implement machine learning models to forecast future sales trends.  



