# AI-ML-intern-Elevate-labs
# 🧹 Data Cleaning & Preprocessing — Titanic & Heart Datasets

## 📘 Overview
This project demonstrates how to clean, preprocess, and encode datasets to prepare them for machine learning models.  
It includes two datasets:
1. **Titanic Dataset** — used for full data cleaning and preprocessing pipeline.  
2. **Heart Dataset (hear.csv)** — used to explore different categorical-to-numerical encoding methods.

The project covers:
- Handling missing values  
- Encoding categorical variables  
- Feature scaling and normalization  
- Outlier detection  
- Data visualization and interpretation

---

## 📂 Datasets Used

### 🛳️ Titanic Dataset
**File:** `Titanic-Dataset.csv`  
**Description:**  
Contains information about Titanic passengers such as age, sex, ticket class, fare, and survival status.

**Key Columns:**
- `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

**Objective:**  
To clean and preprocess data for machine learning — handling missing values, encoding categorical variables, standardizing numeric data, and removing outliers.

---

### ❤️ Heart Dataset
**File:** `hear.csv`  
**Description:**  
Represents health-related data used to demonstrate **different categorical-to-numerical encoding methods** (such as Label Encoding, One-Hot Encoding, and Ordinal Encoding).

**Objective:**  
To compare and visualize the effects of different encoding techniques on categorical data for machine learning.

---

## ⚙️ Data Cleaning & Preprocessing Steps

### 1️⃣ Import & Explore
- Loaded datasets using **Pandas**
- Checked data types, null values, and basic statistics using `.info()` and `.describe()`

### 2️⃣ Handle Missing Values
- Filled missing numeric values with **median**
- Replaced missing categorical values with **mode**
- Dropped columns with excessive missing data (`Cabin`, `Ticket`, etc.)

### 3️⃣ Encode Categorical Variables
- Used **Label Encoding** for binary features like `Sex`
- Used **One-Hot Encoding** for multi-category columns like `Embarked`
- Demonstrated encoding techniques in **Heart Dataset** notebook

### 4️⃣ Feature Scaling
- Applied **StandardScaler** to numerical columns (`Age`, `Fare`) for uniform scaling

### 5️⃣ Outlier Detection & Removal
- Visualized outliers using **Boxplots**
- Removed outliers using **IQR method**

### 6️⃣ Visualization
- Used **Matplotlib** and **Seaborn** for:
  - Distribution plots  
  - Correlation heatmaps  
  - Outlier visualization

---

## 📊 Key Visuals

| Visualization | Description |
|----------------|-------------|
| ![Missing Values Heatmap](screenshots/missing_values.png) | Shows missing data before cleaning |
| ![Fare Boxplot](screenshots/fare_boxplot.png) | Highlights outliers in Fare column |
| ![Correlation Heatmap](screenshots/heatmap.png) | Displays relationships among features |
| ![Encoding Comparison](screenshots/encoding_comparison.png) | Shows results of different encoding methods on Heart dataset |

> 🖼️ *You can replace the image links with your actual screenshots after uploading them to your repository.*

---

## 🧠 What I Learned

- How to explore, clean, and preprocess raw datasets  
- Handling missing values effectively using imputation  
- Encoding categorical variables using **Label**, **One-Hot**, and **Ordinal Encoding**  
- Understanding **Normalization vs Standardization**  
- Detecting and handling **outliers**  
- The importance of preprocessing in improving ML model performance  
- Applying multiple preprocessing techniques to different datasets

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sadiyariyazkhan/data-cleaning-task.git
   cd data-cleaning-task
