# Marketing ROI & Sales Forecasting: Identifying Revenue Drivers and Pricing Pitfalls

## Project Overview
This project provides a deep-dive analysis of a digital retailer's marketing performance (2010–2011). Using a dataset of **18,000 campaign records**, I built an end-to-end analytical pipeline to evaluate marketing efficiency and forecast sales revenue. 

The core value of this work lies in the **synthesis of statistical modeling and business strategy**, identifying where marketing budgets are optimized and where promotional strategies (like aggressive discounting) may be failing.

---

### Quick Links
* 💾 **Dataset Source:** [Kaggle E-Commerce Marketing Dataset](https://www.kaggle.com/datasets/amineipad/e-commerce-marketing-and-sales-revenue-prediction/data)
* 📓 **Full Analysis:** [Jupyter Notebook](My Project.ipynb)

---

## Key Business Insights ("Gold Nuggets")
* **The Discount Trap:** Analysis showed that discount rates exceeding 20% often lead to diminishing returns. While they boost short-term volume, they erode profit margins faster than they acquire new customer value.
* **Quality over Quantity:** CTR (Click-Through Rate) proved to be a more stable predictor of revenue than the absolute volume of Impressions, suggesting that creative quality and targeting outweigh pure budget volume.
* **The "Hidden Factors" of Sales:** Our regression analysis ($R^2 = 0.16$) revealed that traditional metrics (Spend, Reach) explain only a portion of sales variance. This suggests that **brand equity, product quality, and competitor activity** are dominant forces that require further qualitative study.
* **Channel Efficiency:** **Social Media** and **Search** channels consistently outperformed Affiliate marketing in terms of conversion stability and ROI.

---

## Technical Toolbox
* **Data Warehouse:** **Google BigQuery (SQL)** for cloud-based data validation and initial filtering.
* **Language:** **Python 3.x**
* **Libraries:** * `Pandas` & `NumPy`: For complex ETL and data cleaning.
    * `Seaborn` & `Matplotlib`: For advanced statistical visualizations.
    * `Scikit-learn`: For Linear Regression modeling and forecasting.
    * `Scipy`: For hypothesis testing and statistical validation.

---

## Modeling & Statistical Interpretation
**Model Performance:** $R^2 = 0.1639$

While a low R-squared might seem like a technical failure, in business analysis, it is a **critical insight**. 
* **My Interpretation:** This result explicitly tells stakeholders that sales are influenced by more than just "paid reach." It highlights the importance of unmeasured variables like brand loyalty and external market shocks.
* **Statistical Validation:** Conducted Independent T-tests to ensure that performance variations across different marketing channels were not due to random chance.

---

## Methodology
1.  **SQL Pre-processing:** Executed queries in BigQuery to handle 18,000 records, filtering out anomalies (negative values) and ensuring data integrity.
2.  **Exploratory Data Analysis (EDA):** Segmented data by Region and Product Category to find "hidden" pockets of growth.
3.  **Data Cleaning:** Handled missing timestamps and standardized categorical variables for modeling.
4.  **Strategic Reporting:** Concluded with data-driven recommendations for budget reallocation.

---

## Conclusion
This project demonstrates my ability to transform raw data into a strategic narrative, using Python to bridge the gap between technical metrics and executive decision-making.
