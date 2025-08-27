# 📊 Blinkit Sales Analysis

An exploratory data analysis (EDA) of Blinkit grocery sales to understand trends, top-performing products, and outlet performance.

---

## 📂 Dataset Information
- **Rows:** 8,523  
- **Columns:** 12  
- **Key Columns:**  
  - `Item Type`  
  - `Outlet Size`  
  - `Sales`  
  - `Rating`  
  - `Outlet Type`  
  - `Item Visibility`  
  - `Item Weight`  

---

## 🛠 Data Cleaning
- Handled missing values in **Item Weight** using median.  
- Standardized categories in **Item Fat Content** (`Low Fat`, `Regular`).  
- Removed duplicate entries.  

---

## 📈 Analysis Highlights
- **Total Sales:** ₹1,201,681.49  
- **Average Sales per Item:** ₹140.99  
- **Average Rating:** ⭐ 3.97  

### 🔝 Top 5 Selling Categories
1. Fruits and Vegetables – 178,124  
2. Snack Foods – 175,433  
3. Household – 135,976  
4. Frozen Foods – 118,558  
5. Dairy – 101,276  

### ⬇️ Bottom 5 Selling Categories
- Hard Drinks – 29,334  
- Others – 22,451  
- Starchy Foods – 21,880  
- Breakfast – 15,596  
- Seafood – 9,077  

### 🏬 Outlets & Sales
- **Highest Sales Outlet Type:** Supermarket Type1 (~787,550)  
- **Outlet Size Contribution:** Medium-sized outlets dominate (~50%).  

---

## 📊 Visualizations
- Annual sales trend (2011–2022).  
- Top & bottom item categories.  
- Sales distribution by outlet type & size.  
- Correlation heatmap of numeric features.  

---

## ⚙️ Requirements
Install dependencies:
```bash
pip install pandas matplotlib seaborn missingno openpyxl
```

---

## 🚀 Future Work
- Add machine learning models to forecast sales.  
- Build an interactive dashboard with **Streamlit** or **PowerBI**.  

---

## 📬 Contact
Author: Abhinav Bhardwaj  
- LinkedIn: [Your LinkedIn]  
- GitHub: [Your GitHub]  
