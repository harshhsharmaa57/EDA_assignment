# 🍽️ Zomato Data Analysis & Feature Engineering

This project performs **Exploratory Data Analysis (EDA)** and **Feature Engineering** on the Zomato restaurant dataset to extract insights such as:

- Top restaurant chains
- Customer rating distribution
- Cost analysis
- Popular cuisines
- Country-wise trends
- Data preprocessing for ML models

---

## 📂 Project Structure


---

## 📊 Dataset Information

### `zomato.csv`
Contains restaurant-level information including:
- Restaurant name, location, cuisines
- Average cost for two
- Ratings, votes, delivery availability
- Coordinates (latitude, longitude)

### `Country-Code.xlsx`
Maps `Country Code → Country Name` for regional analysis.

---

## ⚙️ Workflow

1. **Load datasets**
2. **Data cleaning & handling missing values**
3. **Merge country mapping**
4. **Visualize insights**
   - Rating distribution
   - Country-wise restaurant count
   - Price bucket analysis
   - Most common cuisines
5. **Feature engineering**
6. **Prepare dataset for ML pipelines (if needed)**

---

## 🧠 Key Insights (Generated in Notebook)

✔ Majority of restaurants are from **India**  
✔ Most restaurants offer **price range 1 or 2**  
✔ Online delivery availability varies significantly by country  
✔ Some chains dominate review count and votes  
✔ Cuisines like **North Indian, Chinese, Fast Food** top the list  

(*Exact graphs and numbers are available in the notebook*)

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/zomato-eda.git
cd zomato-eda


