# TELCO Customer Churn Analysis

This project analyzes customer churn patterns using a Telco customer dataset. The goal is to identify key factors that contribute to churn and propose actionable recommendations to reduce customer loss and improve retention.

---

## Key Highlights

- **Contract Type vs Churn**  
  - **42%** churn in **Month-to-Month** contracts  
  - **11%** in **One-Year**, and **3%** in **Two-Year** contracts  
  - *Long-term contracts significantly reduce churn.*

- **Payment Method vs Churn**  
  - **45%** churn in **Electronic Check** users  
  - ~**15-18%** churn in **Credit Card / Mailed / Bank Transfer**  
  - *Electronic checks might lack customer trust—promote secure options.*

- **Tenure vs Churn**  
  - **50%** churn in customers with <1 year of tenure  
  - **35%** for 1–3 years  
  - **15%** for >3 years  
  - *Early engagement is crucial to reduce churn.*

- **Internet Service Type vs Churn**  
  - **30%** churn in **Fiber Optic** users  
  - **20%** churn in **DSL** users  
  - *Fiber users may be dissatisfied with speed, price, or competition.*

- **Senior Citizens vs Churn**  
  - **41%** churn in **Seniors (65+)**  
  - **26%** churn in **Non-seniors**  
  - *Targeted services and support could improve retention in this group.*

---

## Visualizations

- **Bar Charts** – Churn by payment method and contract type
- **Line Graphs** – Tenure vs Churn rate
- **Distribution Charts** – Customer demographics and service usage
-  *Visuals clearly depict churn trends across various attributes.*

---

## Files

- `customer_churn_analysis.ipynb` – Full EDA and visualization notebook
- `customer-churn.csv` – Dataset used for the analysis
- `churn-analysis.pdf` – Analytical summarization of the dataset

---

## Tools Used

- **Python**
  - `Pandas`, `NumPy` – Data handling
  - `Matplotlib`, `Seaborn` – Visualization
- **Jupyter Notebook / Google Colab**
- **Git & GitHub** – Version control and code sharing

---

## Conclusion

This project highlights the importance of analyzing customer behavior in reducing churn. It shows how structured data analysis can drive strategic decisions such as contract policy, payment gateway preferences, and customer segmentation.

---
