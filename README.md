# 🍽️ Restaurant Tips Analysis  

## 📖 Project Description  
This project aims to use the **restaurant tips dataset** to practice creating composition plots and visualizations.  
We will examine the relationship between different variables and the tips given.  

The dataset consists of information from **244 restaurant bills**, collected in the **US in 1987**. It includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.   

## 📊 Dataset  
- **Source**: https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv
- **Description**: It contains information on restaurant bills, including:  
  - `total_bill`: Total bill amount (USD)  
  - `tip`: Tip amount (USD)  
  - `sex`: Gender of the customer (Male/Female)  
  - `smoker`: Whether the customers are smokers  
  - `day`: Day of the week
  - `time`: Meal time (Lunch/Dinner)  
  - `size`: Meal size (number of people)
- **Access**: The dataset can be accessed:
```
import pandas as pd
df = pd.read_csv('https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv')
```

## 🎯 Goals  
The main objectives of this project are:  
- To analyze how **tips vary across different categories** such as gender, time of day, day of week, and whether the customer is smoker.  
- To explore the relationship between **total bill and tip percentage**. 
- To visualize patterns and trends in customer tipping behavior.

## 📈 Results & Insights  
- **Average Tip %**: Customers generally tip around **15–20% of the total bill**.  
- **Gender & Time**: Male customers tend to leave slightly higher tips during dinner compared to lunch, while female customers show more consistent tipping patterns.  
- **Day of Week**: Tipping is generally higher on weekends (Sat & Sun), reflecting larger dining groups and higher bills.  
- **Group Size**: Larger parties tend to leave **higher absolute tips** but a **lower tip percentage** compared to smaller groups.  
- **Visualization Samples**: The notebook includes bar plots, scatter plots, and box plots to illustrate these findings.
