# Customer & Product Profitability Analysis

## Problem Statement
Our marketing department wants to optimize their strategy by focusing on the most profitable customer segment and bestselling products. Instead of marketing to everyone, they need to:

1. Identify the **top 3 most profitable products**.
2. Understand the **characteristics of our most loyal customers**.
3. Formulate a **hypothesis on why customers prefer these products**.

---

## Data Overview
We analyzed two datasets:
- **`transaction_data.csv`**: Contains transactional details of customers.
- **`purchase_behaviour.csv`**: Captures customer purchasing patterns.

### Key Data Insights:
- **Unique Customers**: The dataset shows repeat customers, indicating the need for loyalty analysis.
- **Unique Dates**: The dataset spans **364 days**, confirming it represents a full year's worth of data.
- **Unique Products**: Multiple products are sold, but we aim to identify the **top revenue contributors**.

---

## Findings
### 1. **Top 3 Most Profitable Products**
We define profitability as:
\[ \text{Profitable Products} = \text{Total Sales} - \text{Cost Price} \]

Since cost price is unavailable, we rank products based on total revenue (`TOT_SALES`). The top 3 revenue-generating products are:

1. **Dorito Corn Chp Supreme 380g** - Highest revenue contributor
2. **Smiths Crnkle Chip Orgnl Big Bag 380g** - Second highest revenue contributor
3. **Smiths Crinkle Chips Salt & Vinegar 330g** - Third highest revenue contributor

### 2. **Characteristics of Loyal Customers**
Loyal customers are defined as those making **frequent repeat purchases**. Our analysis shows that for (frequency_of_repeat_purchases : n =10) :
- Majority are **OLDER FAMILIES	and YOUNG FAMILIES**.
- Well, the distribution of customer is almost equal across the 3 categories but still Their is a slight edge to buy Majorly **Budget products** over other options.


### 3. **Hypothesis on Customer Loyalty**
We hypothesize that:
- Older and young families prefer **budget products** due to cost-conscious purchasing behavior.
- Household necessities drive repeat purchases rather than brand preference..
- Promotional discounts and bundled deals are strong motivators for **repeat buyers**..


---

## Repository Contents
- `customer-profitability-analysis.ipynb` - Jupyter Notebook with the complete analysis.
- `transaction_data.csv` - Transaction dataset.
- `purchase_behaviour.csv` - Purchase behavior dataset.

---

## How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-profitability-analysis.git
   cd customer-profitability-analysis
   ```
2. Open `customer-profitability-analysis.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells sequentially to reproduce the analysis.

---

## Authors
- **Sanket**  


