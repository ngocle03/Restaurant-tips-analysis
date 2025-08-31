# 🍽️ Restaurant Tips Analysis  

## 📖 Project Description  
This project explores restaurant tipping behavior using the **Restaurant Tips dataset**.  
The analysis investigates how different factors such as day, time, gender, and group size affect tipping patterns.  
Visualizations and statistical summaries are used to uncover insights about customer behavior.  

## 📊 Dataset  
- **Source**: The dataset comes from the `seaborn` library’s built-in dataset collection (`tips`).  
- **Description**: It contains information on restaurant bills, including:  
  - `total_bill`: Total bill amount (USD)  
  - `tip`: Tip amount (USD)  
  - `sex`: Gender of the payer (Male/Female)  
  - `smoker`: Whether the party included smokers  
  - `day`: Day of the week (Thu, Fri, Sat, Sun)  
  - `time`: Meal time (Lunch/Dinner)  
  - `size`: Party size (number of people)  
- **Access**: The dataset can be directly loaded via seaborn:  

```python
import seaborn as sns
tips = sns.load_dataset("tips")

## 🎯 Goals  
The main objectives of this project are:  
- To analyze how **tips vary across different categories** such as gender, time of day, day of week, and group size.  
- To explore the relationship between **total bill and tip percentage**.  
- To visualize patterns and trends in customer tipping behavior.  

## 📈 Results & Insights  
- **Average Tip %**: Customers generally tip around **15–20% of the total bill**.  
- **Gender & Time**: Male customers tend to leave slightly higher tips during dinner compared to lunch, while female customers show more consistent tipping patterns.  
- **Day of Week**: Tipping is generally higher on weekends (Sat & Sun), reflecting larger dining groups and higher bills.  
- **Group Size**: Larger parties tend to leave **higher absolute tips** but a **lower tip percentage** compared to smaller groups.  
- **Visualization Samples**: The notebook includes bar plots, scatter plots, and box plots to illustrate these findings.  
