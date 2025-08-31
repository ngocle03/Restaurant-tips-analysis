# 🍽️ Restaurant Tips Analysis  

## 📖 Project Description  
This project uses the **restaurant tips dataset** to practice creating composition plots and visualizations. The analysis explores how different factors (such as gender, smoking status, day of the week and time of day) relate to tipping behavior in restaurants. 

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
- **Access**: The dataset is publicly available as part of the [Seaborn library’s example datasets](https://github.com/mwaskom/seaborn-data) (`tips.csv`). You can access it directly via:

```
import seaborn as sns
tips = sns.load_dataset("tips")
```

## 🎯 Goals  
The main objectives of this project are:  
- Explore tip distributions across different groups.  
- Compare tipping behavior by:  
  - Smokers vs. non-smokers  
  - Male vs. female customers  
  - Weekdays vs. weekends  
  - Lunch vs. dinner  
- Practice creating composition plots and statistical visualizations.  
- Derive insights about customer tipping behavior.

## 📈 Results & Insights  
### 1. Overall Tip Distribution
- Most tips fall between **$2–$4**.  
- Very few tips exceed **$8–$10**, showing a **right-skewed distribution**.  

### 2. Smokers vs. Non-smokers
- **Smokers**: Tips cluster tightly around **$2.5–$4**, showing more consistency.  
- **Non-smokers**: Wider spread, ranging from very low (~$1) to moderately high (> $6).  
- **Comparison**: Non-smokers are less predictable in tipping, while smokers are more consistent.  

### 3. Male vs. Female Customers
- **Males**: Tips are centered around **$3–$4**, slightly higher on average.  
- **Females**: Show greater variability, with both lower ($1–$2) and some higher tips.  
- **Comparison**: Males tip more consistently, females show wider spread.  

### 4. Weekdays vs. Weekends
- **Weekdays**: Tips mostly in the **$2–$4** range, smaller volume and less variation.  
- **Weekends**: More tips, wider spread up to **$10**, higher frequency around $2–$4.  
- **Conclusion**: Weekends bring in more customers and higher, more varied tips.  

### 5. Lunch vs. Dinner
- **Lunch**: Lower, concentrated tips (**$1–$3**), rarely exceeding $5.  
- **Dinner**: Higher and more spread out tips, clustering around **$3–$5**, some > $8.  
- **Conclusion**: Customers give larger and more varied tips during dinner.

## 📑 Notebook
For full analysis, visualizations, and code:  
➡️ See the Jupyter Notebook: [Restaurant tips analysis.ipynb](./Restaurant%20tips%20analysis.ipynb)  

You can also jump to specific sections inside the notebook:  
- [Overall Tip Distribution](./Restaurant%20tips%20analysis.ipynb#Overall-Tip-Distribution)  
- [Smokers vs. Non-smokers](./Restaurant%20tips%20analysis.ipynb#Smokers-vs.-Non-smokers)  
- [Male vs. Female Customers](./Restaurant%20tips%20analysis.ipynb#Male-vs.-Female-Customers)  
- [Weekdays vs. Weekends](./Restaurant%20tips%20analysis.ipynb#Weekdays-vs.-Weekends)  
- [Lunch vs. Dinner](./Restaurant%20tips%20analysis.ipynb#Lunch-vs.-Dinner)  
