
# 🚗 Exploratory Data Analysis (EDA) on Used-Car Dataset

##  Project Overview  
This project demonstrates Exploratory Data Analysis (EDA) techniques on a used-car dataset to uncover valuable insights regarding vehicle pricing, mileage, and various features. The analysis provides data-driven conclusions that can help in understanding the factors influencing car prices and resale value.

##  Key Steps and Methodology  

### Data Collection & Understanding  
- Imported and examined the dataset containing attributes such as brand, model, year, price, fuel type, mileage, etc.  
- Utilized pandas functions like .head(), .info(), and .describe() to explore the dataset’s structure.  

### Data Cleaning & Preprocessing  
- Handled missing values by imputing or removing incomplete records.  
- Removed duplicate entries to maintain data integrity.  
- Standardized column names for consistency.  
- Converted data types where necessary (e.g., converting year to integer and price to float).  

### Feature Engineering  
- Derived additional insights by creating new features.  
- Calculated Car Age using the formula: Current Year - Manufacturing Year.  

### Exploratory Data Analysis (EDA)  
#### Univariate Analysis  
- Visualized distributions of numerical features (e.g., Price, Mileage) using histograms and KDE plots.  
- Identified outliers using box plots to detect anomalies in pricing and mileage.  

#### Bivariate & Multivariate Analysis  
- Correlation Analysis: Examined relationships between price and factors such as mileage, fuel type, and brand.  
- Scatter Plots: Explored the impact of car age and mileage on pricing.  
- Heatmaps: Identified interdependencies between multiple numerical features.  

### Data Visualization  
Utilized Matplotlib & Seaborn to generate insightful visualizations:  
- Histogram & KDE Plots: Illustrated price and mileage distributions.  
- Boxplots: Highlighted pricing and mileage outliers.  
- Bar Charts: Compared the average price of cars across brands.  
- Heatmaps: Displayed feature correlations to detect significant relationships.  

### Key Business Insights  
- Older cars typically have lower prices, but luxury brands tend to retain value better.  
- Higher mileage reduces car price—an inverse relationship between mileage and value.  
- Fuel type impacts pricing—electric and hybrid cars are priced higher than petrol or diesel vehicles.  
- Brand influence is significant—certain brands exhibit a higher resale value compared to others.  

## 📂 Project Files  
- EDA_Used_Car_Dataset.ipynb – Jupyter Notebook containing the entire EDA process, including data cleaning, visualization, and insights.  

## Tools & Technologies Used  
- Python (pandas, numpy) for data manipulation.  
- Matplotlib & Seaborn for data visualization.  
- Jupyter Notebook for interactive analysis.  

---  
