
# Amazon Product Analytics & Customer Insight Analysis

## Project Overview

This project analyzes Amazon product catalog data to uncover insights about customer engagement, pricing strategies, discount behavior, and product satisfaction.

The goal is to provide data-driven recommendations for business stakeholders including:

- Category Managers
- Pricing Strategy Teams
- Product Quality Teams
- Marketing & Merchandising Teams

The analysis identifies patterns in product popularity, discount effectiveness, and customer satisfaction to support better strategic decisions.

---

## Business Questions

1. Where is the product catalog concentrated and where is customer attention focused?
2. What does overall customer satisfaction look like?
3. Do larger discounts improve ratings or product popularity?
4. Does price influence product popularity?
5. Which products are Star Products vs Risk Products?

---

## Dataset Description

The dataset contains Amazon product and review information including:

- Product category
- Discounted price
- Actual price
- Discount percentage
- Product rating
- Rating count (engagement proxy)
- Customer reviews

Rating count is used as a proxy for product popularity.

---

## Methodology

### Data Cleaning

- Removed currency symbols from price columns
- Converted prices to numeric format
- Converted discount percentages to numeric
- Cleaned rating counts by removing commas
- Converted ratings to numeric
- Removed duplicate records

### Feature Engineering

Additional variables created:

- Discount amount
- Log-transformed price
- Log-transformed rating count
- Main category grouping

---

## Key Insights

### Catalog Distribution

Most products are concentrated in:

- Electronics
- Home & Kitchen
- Computers & Accessories

Electronics receives the largest share of customer attention.

### Customer Satisfaction

Ratings are heavily clustered around **4.0 – 4.3**, indicating strong overall satisfaction.

### Discount Strategy

Discount percentage shows a **weak negative relationship with ratings**.

Large discounts do not consistently improve product satisfaction.

### Price vs Popularity

Popularity exists across all price levels. Premium products can perform strongly when perceived value is high.

---

## Star Products vs Risk Products

### Star Products

Definition:

- Rating ≥ 4.3
- Rating count in top 10%

Recommended actions:

- Featured placement
- Increased marketing promotion
- Cross-selling and bundling

### Risk Products

Definition:

- Rating ≤ 3.8
- Rating count in top 10%

Recommended actions:

- Investigate customer complaints
- Improve product descriptions
- Review supplier quality

---

## Visualizations

The analysis includes the following visualizations:

- Catalog Mix by Category
- Customer Attention by Category
- Rating Distribution
- Discount vs Rating Analysis
- Discount Distribution
- Price vs Popularity (Log-Log)

---

## Strategic Recommendations

1. Prioritize high-attention categories such as Electronics.
2. Monitor low-rating products with high visibility.
3. Use data-driven pricing strategies instead of aggressive discounting.
4. Promote high-performing Star Products.
5. Develop dashboards to track rating trends and category performance.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Author

**Syed Irteza Md Moinuddin**

Email: syedirteza99@gmail.com  
LinkedIn: https://www.linkedin.com/in/syed-irteza-md-moinuddin-16234120b/

