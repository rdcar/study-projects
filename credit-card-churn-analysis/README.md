# Bank Credit Card Churn Analysis (EDA)

This project focuses on an exploratory data analysis (EDA) of customer churn in credit card services. The analysis was conducted to identify key patterns and factors contributing to cancellations and to provide actionable insights for reducing the churn rate.

## Project Context
A bank manager is concerned about the increasing number of customers canceling their credit card services. The goal is to predict customer churn and propose strategies to retain customers by improving their experience and satisfaction. This dataset contains information on 10,000 customers, including attributes such as age, income, marital status, credit card limit, and category.

**Dataset Source:**  
[Credit Card Customers Dataset](https://www.kaggle.com/sakshigoyal7/credit-card-customers)

## Project Outline

1. **Import the Dataset**
   - Load the dataset and preprocess the data by removing unnecessary columns and handling missing values.
2. **Data Visualization and Cleaning**
   - Explore the dataset's structure and statistics.
   - Clean the data by addressing missing and null values.
3. **Exploratory Data Analysis (EDA)**
   - Analyze patterns in customer behavior and churn.
   - Use histograms to compare churned and active customers for various attributes.
   - Correlation analysis to identify key factors influencing churn.
4. **Hypotheses for Card Cancellation**
   - Derive insights from correlations and attribute distributions.
5. **Conclusions**
   - Summarize findings from the analysis.
6. **Suggestions to Reduce Cancellation Rate**
   - Propose actionable strategies to lower the churn rate.

## Key Findings

1. **Number of Products Contracted**  
   - Customers with fewer products (up to 2) have a significantly higher churn rate compared to those with 6 products.  
   *(Pearson Correlation: -0.15)*
2. **Transaction Amount**  
   - Most cancellations are among customers who spent up to USD 5,000 in the last year. Higher transaction amounts correlate with lower churn rates.  
   *(Pearson Correlation: -0.37)*
3. **Usage Frequency**  
   - Higher usage is associated with lower churn frequency.
4. **Customer Service Contacts**  
   - Customers with more than two service contacts show a sharp increase in churn rates.  
   *(Pearson Correlation: 0.2)*

## Recommendations

1. **Incentivize Card Usage**  
   - Launch loyalty programs such as points or cashback rewards to encourage higher usage.
2. **Enhance Customer Service**  
   - Improve the customer service experience by reducing response times and resolving issues effectively.
3. **Proactive Customer Engagement**  
   - Implement a notification system after the second contact with customer service to take immediate retention measures.

## Tools and Libraries
- **Python**: Data analysis and visualization
- **pandas**: Data manipulation
- **plotly**: Interactive visualizations
- **seaborn & matplotlib**: Correlation analysis and heatmaps

## How to Run
1. Clone the repository and open the notebook in Jupyter or Google Colab.
2. Ensure the dataset (`ClientesBanco.csv`) is in the same directory.
3. Execute the cells to process the data and visualize results.
4. Analyze the conclusions and recommendations.

## Results
This project highlights key customer behaviors influencing churn, providing a foundation for designing retention strategies. Explore the detailed analysis and visualizations in the notebook.

## License
This project is licensed under the MIT License. Feel free to use and adapt the code for your needs.
