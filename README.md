# Churn Prediction

The project aims to collect and process customer data, using machine learning models to predict the bank's churn rate after customers have used the bank's services.

---

## Folder Structure
**Churn_prediction/
├── data/ # Contains BankChurners.csv file
├── train/ # Contains churn_train.ipynb notebook
├── visualization/ # Contains Data_Visualization.ipynb notebook
└── dashboard/ # Contains ChurnDashboard.pbix file**
---

## Result Scores Model:
The final model achieved:
- **88% accuracy** 
- **F1-score of 0.93** for the churned customer class, indicating strong predictive performance.

---

## Insights from Dashboard:

![Churn Prediction Insights](https://github.com/user-attachments/assets/2d8d64cb-a0fa-4d36-8ff1-ac80d6efd0a3)

- **Churned customers** account for **16.07%**, while **83.93%** remain active, highlighting an opportunity to improve customer retention strategies.
  
- The **Blue card** dominates all other card categories, with **Silver**, **Gold**, and **Platinum** cards being used by only a small number of customers. This suggests that most customers belong to the general or standard segment.

- **Customers aged between 40–50** show the highest transaction volume and count, indicating that this age group is highly active and valuable. This group should be prioritized for customer engagement efforts.

- The highest **average credit limit** belongs to customers earning over **$120K**, reaching up to **$20,000**. In contrast, customers earning **less than $40K** have a credit limit of around **$4,000–$5,000**, showing a clear correlation between income and credit limit.

- The **median credit utilization ratio** is **17.60%**, suggesting that most customers use their credit conservatively — potentially a sign of good financial control or limited borrowing needs.

- The total **customer tenure (Months on Book)** reaches **364,000 months**, indicating a significant base of long-term customers.

---

### Link to Dashboard:
You can explore the Power BI dashboard [here](https://github.com/thanhthao2004/Churn_prediction/tree/main/dashboard).
