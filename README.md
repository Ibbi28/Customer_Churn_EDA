# Telco Customer Churn Analysis: Understanding and Acting on Customer Attrition

## 🌟 Executive Summary

This project presents a concise data analysis and visualization of customer churn within a telecommunications dataset. By exploring key customer attributes, services used, contract details, and demographics, the analysis aims to highlight significant factors contributing to churn. The insights derived offer a clear understanding of churn patterns, enabling the identification of high-risk customer segments and informing the development of targeted customer retention strategies.

---

## 📊 About the Dataset

**📘 Context:**  
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs."  
— *IBM Sample Data Sets*

This dataset is instrumental for understanding customer churn behavior and developing effective customer retention strategies through data analysis.

**📈 Content:**  
Each row in the dataset represents a customer, and each column contains customer attributes. Key information includes:

* **Churn Information:** `Churn` (whether the customer left within the last month)
* **Services Signed Up:** `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`
* **Customer Account Information:** `tenure`, `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`
* **Demographic Information:** `gender`, `SeniorCitizen`, `Partner`, `Dependents`

**💡 Inspiration:**  
This project aims to:
* Understand factors contributing to customer churn through in-depth analysis
* Build a foundation for evaluating and developing customer retention strategies
* Enhance skills in data preprocessing, exploratory data analysis (EDA), and data visualization

**🔗 Data Source:**  
The dataset used is publicly available from IBM's sample data sets.  
[Telco Customer Churn - IBM Community](https://community.ibm.com/community/user/dataandsolutions/blogs/greg-kogan1/2022/10/25/telco-customer-churn-v2)

---

## 📌 Dashboard Summary: Key Insights & Actions

This section encapsulates the most critical findings and actionable recommendations derived from the customer churn analysis.

**🚨 Churn Risk is Highest for:**
* **Month-to-month contracts**
* Customers without **Online Security** or **Tech Support**
* **Senior Citizens**
* Users paying via **Electronic Check**
* Customers in their **first few months** (low tenure & charges)

**✅ Most Loyal Segments:**
* **Two-year contract holders**
* Customers with **Online Security** and **Tech Support**
* Those with **high Total & Monthly Charges**
* Customers with **No Internet Service**

**🎯 Strategic Recommendations:**
* **Promote longer contracts** (1-2 years) to significantly reduce churn rates
* **Bundle Online Security + Tech Support** for new and existing customers to foster higher retention
* **Engage early:** Target customers with low tenure/charges for proactive support and onboarding assistance
* **Upsell mid-tier users** to premium plans, which correlates with increased loyalty
* **Audit "Electronic Check" users** and offer more convenient and reliable auto-pay alternatives

---

## 💻 Technologies Used

* **Python:** The primary programming language for data analysis
* **Pandas:** For data manipulation and analysis
* **NumPy:** For numerical operations
* **Matplotlib:** For static data visualizations
* **Seaborn:** For enhanced statistical data visualizations
* **Plotly:** For interactive and dynamic visualizations
* **Jupyter Notebook:** For interactive analysis and presentation

---

## ✍️ Author

* [LinkedIn Profile](https://www.linkedin.com/in/ibrahim-muhammad-yousuf)
* Email: ibrahimmyousuf2002@gmail.com
