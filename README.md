# Quantium_Sales
# Quantium Retail Strategy & Customer Analytics

## 📌 Project Overview
This project was completed as part of the Quantium Virtual Experience Program. The goal was to act as a Data Analyst for a retail client, analyzing highly granular transactional data to identify customer purchasing behaviors and evaluating the financial impact of a new store layout via A/B testing.

This repository contains two main analytical components:
1. **Customer Segmentation & Purchasing Trends:** Identifying which demographics drive the most revenue in the snack/chips category.
2. **Store Trial Assessment (A/B Testing):** Evaluating the performance of trial stores (with a new layout) against statistically matched control stores.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Data Visualization), SciPy (Statistical Testing)
* **Environment:** Jupyter Notebook / Google Colab

## 📊 Key Insights & Business Impact
### Part 1: Customer Analytics
* **Top Spenders:** "Older Families" and "Young Singles/Couples" in the 'Mainstream' category account for the highest total sales.
* **Purchasing Behavior:** Mainstream Young Singles/Couples are more likely to buy premium, larger pack sizes (e.g., 175g) compared to other demographics, making them a key target for premium brand promotions.
* **Pricing Strategy:** Budget-conscious segments tend to buy smaller, more frequent packs, indicating a need for dynamic pricing or bulk-discount strategies.

### Part 2: Store Trial Evaluation
* **Control Matching:** Successfully identified matching control stores (Stores 233, 155, and 237) based on historical monthly sales and customer counts using correlation and magnitude distance metrics.
* **Financial Uplift:** The trial stores demonstrated a statistically significant uplift in both total sales and customer counts during the trial period compared to their respective control stores.
* **Recommendation:** Roll out the new store layout across the broader retail network, as the A/B test proves it drives measurable revenue growth.

## 📁 Repository Structure
* `quantium_retail_strategy_and_analytics.ipynb`: The main Jupyter Notebook containing the full ETL process, exploratory data analysis, and statistical testing.
* `QVI_transaction_data.csv`: Raw transactional data (Note: Excluded from repo due to size limits, available upon request).
* `QVI_purchase_behaviour.csv`: Raw customer demographic data.

## 🚀 How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook and the required Python libraries installed (`pip install pandas numpy matplotlib seaborn scipy`).
3. Place the raw CSV data files in the same directory as the notebook.
4. Run all cells in `quantium_retail_strategy_and_analytics.ipynb`.
