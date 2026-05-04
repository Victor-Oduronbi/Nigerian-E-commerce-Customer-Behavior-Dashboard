# E-Commerce Customer Segmentation & Business Intelligence 🛍️📊\
\
📌 **Overview**\
This project applies data science workflows to evaluate customer behavior for a simulated Nigerian e-commerce platform. By engineering RFM (Recency, Frequency, Monetary) scores from 100,000+ raw transaction records from the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_customers_dataset.csv) on Kaggle. This analysis profiles high-value shoppers and runs simulated A/B tests to measure campaign effectiveness.\
\
🚀 **Key Findings & Business Impact**
* *The "At-Risk" Goldmine*: Our At-Risk Loyalists represent massive dormant value. A simulated campaign targeting this group proved highly effective.
* *Hypothesis Testing Success*: A targeted promo code yielded a 9% lift in average revenue among lapsed buyers.
* *The P-Value (0.00001)*: The experiment returned a P-value far below the 0.05 threshold, proving the marketing campaign's success was not a random coincidence.
* *Bottom Line*: Scaling this 9% lift across the entire 'At-Risk' segment would generate an estimated *₦10,913,507.88 Million* in incremental monthly revenue.\
\
<img width="1187" height="584" alt="image" src="https://github.com/user-attachments/assets/5eeec683-6b15-456b-8329-d82df6a2df1a" />\
\
🛠️ **The Toolkit**
* *Language*: Python
* *Core Math*: Scipy (T-Tests), NumPy, Pandas
* *Visualization*: Matplotlib, Seaborn
* *Interactive BI*: Plotly (for 3D data mapping)\
\
📂 **Project Structure**
* *notebooks*: The main Jupyter Notebook containing the data mapping, RFM math, and statistical tests.
* *data*: The Olist datasets utilized for localized simulation.\
\
📈 **Step-by-Step Process**
* *Data Localization*: Mapped Brazilian regional states to high-volume Nigerian economic hubs (Lagos, FCT, Kano, Rivers) to create a localized narrative.
* *RFM Modeling*: Analyzed transactional histories to score users on how recently they bought, how often they buy, and how much they spend.
* *Hypothesis Testing*: Split a stagnant demographic into a Control and Promo group to conduct an independent t-test on simulated uplift.
* *Interactive Mapping*: Projected 5,000+ customer records into an interactive 3D landscape for dynamic stakeholder manipulation.\
  \
📊 Customer Mapping\
\
  <img width="3541" height="2052" alt="image" src="https://github.com/user-attachments/assets/14322e86-7783-41d3-be74-b6af76d3e6dc" />\
📌 **How to Run**:
* Clone this repo.
* Install requirements: pip install pandas seaborn numpy matplotlib plotly scipy
* Open notebook/Nigerian E-commerce Customer Behavior Dashboard Analysis.ipynb in Jupyter.\
\
📬 **Contact**\
*Oduronbi Victor* – (LinkedIn) www.linkedin.com/in/victor-oduronbi-62b22132b – (Email) victoroduronbi@gmail.com
