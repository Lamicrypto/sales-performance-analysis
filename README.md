# Sales Performance Analysis

## Project Overview

This project analyzes sales performance using the Sample Superstore dataset. The analysis focuses on understanding sales trends, profitability, discount strategies, customer segments, shipping methods, and geographical performance.

The project applies data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization techniques to generate meaningful business insights and recommendations.

---

## Project Objectives

The main objectives of this project are to:

* Analyze overall sales and profitability.
* Identify the most profitable and least profitable product categories and sub-categories.
* Examine the relationship between discounts and profit.
* Evaluate sales and profitability across geographic regions, cities, and states.
* Analyze performance across different customer segments.
* Compare sales and profitability across shipping modes.
* Identify areas of strong and weak business performance.
* Provide data-driven recommendations to support business decision-making.

---

## Dataset

The project uses the **Sample Superstore dataset**, which contains sales transactions and business-related information.

The dataset includes the following columns:

* Ship Mode
* Segment
* Country
* City
* State
* Postal Code
* Region
* Category
* Sub-Category
* Sales
* Quantity
* Discount
* Profit

After data cleaning, the dataset contained **9,977 records and 13 columns**.

The data preparation process included:

* Checking for missing values.
* Identifying duplicate records.
* Removing 17 duplicate rows.
* Reviewing descriptive statistics.
* Examining the distribution of numerical variables.

---

## Tools and Technologies

The following tools and technologies were used:

* **Python**
* **Pandas** – Data manipulation and analysis
* **Matplotlib** – Data visualization
* **Jupyter Notebook** – Analysis environment
* **VS Code** – Development environment
* **Git and GitHub** – Version control and project management

---

## Exploratory Data Analysis

The exploratory analysis covered the following areas:

### Sales Distribution

The distribution of sales was examined to understand the spread of order values and identify potential extreme observations.

### Sales and Profit by Product Category

Sales and profit were analyzed across Furniture, Office Supplies, and Technology categories.

Technology generated the highest total sales and recorded the strongest profit margin, while Furniture recorded a significantly lower profit margin.

### Sales and Profit by Product Sub-Category

Product sub-categories were analyzed to identify high-performing and loss-making products.

Copiers recorded the highest total profit, while Tables recorded the largest loss. Other profitable sub-categories included Phones, Accessories, and Paper.

### Discount and Profit Analysis

The analysis examined how different discount levels affect profitability.

The results indicate that higher discount levels are generally associated with lower profitability. Discounts of 30% or more frequently resulted in negative average profits.

This suggests that excessive discounting can significantly reduce profitability.

### Discount and Profit by Product Category

Technology recorded the lowest average discount and the highest average profit among the three major product categories.

Furniture had the highest average discount and the lowest average profit, suggesting that discounting may be contributing to weaker profitability in this category.

### Discount and Profit by Product Sub-Category

The analysis showed that some sub-categories with relatively high discount levels experienced negative profitability.

Tables and Bookcases recorded negative average profits, while Copiers, Phones, and Accessories demonstrated stronger profitability.

This indicates that discount strategies should be tailored to individual product sub-categories rather than applied uniformly.

### Regional Performance

The West region recorded the highest total sales and profit, making it the strongest-performing region.

The South region recorded the lowest sales, while the Central region showed comparatively lower profitability.

### Customer Segment Analysis

The Consumer segment generated the highest total sales and profit.

However, the Home Office segment recorded the highest profit margin, indicating stronger profitability relative to its sales volume.

### Shipping Mode Analysis

Standard Class generated the highest total sales and profit due to its high order volume.

First Class recorded the highest profit margin, indicating stronger profitability relative to its sales volume.

### City-Level Analysis

New York City recorded the highest sales and profit among the cities analyzed.

However, some cities with significant sales volumes, including Philadelphia, Houston, and Chicago, recorded negative profits.

This demonstrates that high sales volume does not necessarily guarantee profitability.

### State-Level Profitability Analysis

California and New York recorded the highest total profits among the states analyzed.

Texas recorded the largest loss, followed by states such as Ohio, Pennsylvania, and Illinois.

The results demonstrate significant geographic differences in profitability.

---

## Key Business Insights

The analysis produced several important findings:

1. **Technology is the strongest-performing product category** based on sales and profit margin.
2. **Furniture has a relatively weak profit margin**, despite generating substantial sales.
3. **High discounts are generally associated with lower profitability**, particularly at discount levels of 30% or more.
4. **Tables and Bookcases require profitability improvement**, as both recorded negative average profits.
5. **The West region is the strongest-performing region** based on total sales and profit.
6. **The Consumer segment generates the highest total revenue and profit**, while Home Office has the highest profit margin.
7. **New York City is a major profitable market**, while some high-sales cities generate losses.
8. **California and New York are among the most profitable states**, while Texas has the largest overall loss.
9. **High sales do not always translate into high profitability**, highlighting the importance of monitoring profit margins alongside revenue.

---

## Business Recommendations

Based on the findings, the following recommendations are proposed:

### 1. Review Discount Strategies

The company should reduce excessive discounting, especially where discounts are associated with negative profitability.

Discount policies should be based on product category, sub-category, and market conditions.

### 2. Improve Furniture Profitability

The Furniture category requires closer attention due to its relatively low profit margin.

Management should review pricing, product costs, discount levels, and product mix within this category.

### 3. Review Loss-Making Products

Products such as Tables and Bookcases should be investigated to determine the causes of negative profitability.

Possible actions include adjusting prices, reducing discounts, renegotiating supplier costs, or reviewing product offerings.

### 4. Focus on High-Performing Products

The company should continue investing in profitable sub-categories such as Copiers, Phones, and Accessories while maintaining appropriate pricing strategies.

### 5. Develop Regional Strategies

The company should study successful strategies used in high-performing regions such as the West and East and consider applying relevant practices to weaker regions.

### 6. Investigate Loss-Making Locations

States and cities with negative profits should be investigated to identify the causes of poor performance.

Targeted strategies should be developed for markets such as Texas and other underperforming locations.

### 7. Balance Sales Growth with Profitability

Management should avoid focusing solely on sales volume. Profitability and profit margin should be considered when evaluating products, customers, locations, and shipping methods.

---

## Project Structure

```text
sales-performance-analysis/
│
├── data/
│   └── SampleSuperstore.csv
│
├── sales_performance_analysis.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## How to Run the Project

### 1. Clone the Repository

Clone the project repository from GitHub to your local machine.

### 2. Install the Required Libraries

Install the dependencies listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

Open:

```text
sales_performance_analysis.ipynb
```

using Jupyter Notebook or VS Code.

### 4. Run the Notebook

Run all cells from the beginning to the end to reproduce the analysis and visualizations.

---

## Conclusion

This project demonstrates how data analysis and visualization can be used to evaluate business performance and generate actionable insights.

The analysis shows that profitability is influenced by several factors, including discount levels, product categories, geographic markets, customer segments, and sales strategies.

The findings highlight the importance of balancing sales growth with sustainable profitability. By reducing excessive discounts, improving underperforming product categories, investigating loss-making markets, and focusing on profitable business segments, organizations can make more informed decisions and improve overall financial performance.

---

## Author

**Balogun Olamide Timothy**

Data Analyst | AI & Machine Learning Enthusiast

Nigeria
