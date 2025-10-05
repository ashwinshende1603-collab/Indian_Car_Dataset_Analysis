# 🚗 Indian Car Dataset Analysis using Python

## 📘 Project Overview
This project explores and analyzes the **Indian Car Market Dataset** to understand trends in price, mileage, fuel types, and other key performance metrics of cars sold in India.  
The goal is to clean, visualize, and derive meaningful insights using **Python** and its data science libraries.

---

## 📂 Dataset Information
**Source:** [Kaggle – Indian Car Dataset](https://www.kaggle.com/datasets/soumyadipghorai/all-cars-in-india-price-and-specifications)  
**Attributes include:**
- `Car_Name` – Model of the car  
- `Price` – Price in lakhs (₹)  
- `Mileage` – Fuel efficiency (km/l)  
- `Fuel_Type` – Type of fuel (Petrol / Diesel / CNG / Electric)  
- `Transmission` – Manual / Automatic  
- `Owner_Type` – First / Second / Third owner  
- `Year` – Year of manufacture  

---

## 🧰 Technologies & Libraries Used
| Tool | Purpose |
|------|----------|
| **Python** | Core analysis |
| **Pandas** | Data cleaning & manipulation |
| **NumPy** | Numerical computations |
| **Matplotlib / Seaborn** | Data visualization |
| **Plotly** | Interactive charts |
| **Jupyter Notebook** | Development environment |

---

## 🔍 Data Exploration & Cleaning
1. **Loaded dataset** and explored shape, data types, and summary stats  
2. **Handled missing values** using median/mode imputation  
3. **Detected and removed outliers** using IQR (Interquartile Range) method  
4. **Cleaned inconsistent text cases** (Fuel Type, Transmission)  
5. **Converted datatypes** (e.g., Price → numeric, Year → datetime)  

---

## 📊 Exploratory Data Analysis (EDA)
Some of the key analyses performed:
- Distribution of car prices across fuel and transmission types  
- Correlation between **price**, **mileage**, and **year**  
- Average mileage comparison across fuel types  
- Top car brands by price and efficiency  
- Outlier visualization using boxplots  

### 📈 Sample Visuals:
- **Price vs Mileage Scatter Plot**  
- **Distribution of Fuel Types (Pie Chart)**  
- **Correlation Heatmap**  
- **Boxplot for Price Outliers**

---

## 📉 Insights & Findings
🔸 **Diesel cars** generally offer higher mileage than petrol cars  
🔸 **Automatic transmissions** are more common in higher-priced cars  
🔸 Car **prices increase with newer models** (recent years)  
🔸 **CNG cars** provide best mileage but limited availability  
🔸 Outlier removal significantly improved the data consistency  

---

## 🧮 Future Scope
- Predicting car prices using **Machine Learning models**  
- Deploying an **interactive dashboard** using Streamlit or Dash  
- Extending dataset with new EV models for 2025+ market trends  

---

## 🧑‍💻 Author
**👤 Ashwin Shende**  
📧 [Email Me](mailto:ashwinshende1603@gmail.com)  
🔗 [Kaggle Profile](https://www.kaggle.com/ashwinshende166)  

---

## ⭐ Acknowledgments
- Dataset credits: Kaggle Open Datasets  
- Python community for open-source libraries  

---

### 🌈 “Data speaks louder than words — let’s decode the drive behind every car!”
