# E-commerce Sales Data Analysis

## Overview

This project focuses on analyzing e-commerce sales data to perform customer segmentation using machine learning techniques. The dataset contains sales transactions from November 2018 to April 2019, including details such as product information, customer IDs, order quantities, sales values, discounts and returns. The goal is to segment customers based on their purchasing behavior to enable targeted marketing strategies and improve business outcomes.

## Features

- **Data Preprocessing**: Handles missing values, outliers and irrelevant records to prepare the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Includes univariate and bivariate analysis to uncover patterns and relationships in the data.
- **Feature Engineering**: Extracts and transforms features such as recency, tenure and average return rate to better represent customer behavior.
- **Customer Segmentation**: Uses K-means clustering to group customers into distinct segments based on their purchasing patterns.
- **Visualization**: Provides clear visualizations of data distributions, correlations and clustering results.

## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)
- Required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

### Steps

1. Clone the repository (if applicable):
   ```bash
   git clone https://github.com/NicholusMuthomi/E_commerce_Sales_Analysis/.git
   ```

2. Navigate to the project directory:
   ```bash
   cd e-commerce-sales-analysis
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the analysis script:
   ```bash
   python e_commerce_sales_analysis.ipynb
   ```

## Code Functionality

- **Data Loading and Cleaning**: Loads the dataset and performs initial checks for duplicates, missing values, and data types.
- **Exploratory Data Analysis**: Analyzes individual features (e.g., product types, sales values) and relationships between features (e.g., sales vs. discounts).
- **Feature Engineering**: Extracts new features like customer tenure and average return rate, and applies transformations (e.g., log scaling).
- **Model Building**: Uses K-means clustering to segment customers and evaluates the optimal number of clusters using the elbow method.
- **Visualization**: Generates plots to illustrate customer segments and their characteristics.

## Results

The analysis identified four distinct customer segments:
1. **High-Spenders (Cluster 2)**: Comprise 42% of customers, generate significant revenue and have moderate return rates.
2. **Regular Customers (Cluster 0)**: Make up 50% of customers, exhibit average spending and return rates.
3. **Low-Spenders (Clusters 1 and 3)**: Smaller groups with lower spending and higher return rates.

## Business Implications

- **Targeted Marketing**: Focus on high-spenders (Cluster 2) to maximize revenue. Offer personalized discounts or loyalty programs to retain them.
- **Improve Retention**: Engage regular customers (Cluster 0) with updates and promotions to encourage repeat purchases.
- **Reduce Returns**: Address high return rates in low-spender segments (Clusters 1 and 3) by improving product descriptions or offering incentives for keeping purchases.

## Contributing

Contributions are welcome, If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or feedback, please reach out to [Email Address](muthominicholus22@gmail.com).
