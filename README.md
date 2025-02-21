# 🌾 Agricultural Production Optimization Engine

## 📌 Overview
This project builds a **Machine Learning Model** using **Logistic Regression** to predict the best crop to grow based on **soil composition and climate conditions**. Advanced techniques like **feature scaling, PCA for dimensionality reduction, and hyperparameter tuning** are applied to improve model accuracy.

---

## 📊 Dataset (`data.csv`)
| Feature | Description |
|---------|------------|
| **N** | Nitrogen content in soil |
| **P** | Phosphorus content in soil |
| **K** | Potassium content in soil |
| **Temperature** | Average temperature (°C) |
| **Humidity** | Air humidity (%) |
| **pH** | Soil acidity level |
| **Rainfall** | Rainfall (mm) |
| **Crop** | The best-suited crop (Target) |

---

## 🛠️ **Technologies Used**
- **Language**: Python  
- **Libraries**: NumPy, Pandas, Seaborn, Matplotlib, Scikit-Learn  
- **Algorithm**: Logistic Regression  

---

## 🔄 **Data Preprocessing**
### **1️⃣ Handle Missing Data**
- Removed any rows containing **missing values** to maintain data integrity.

### **2️⃣ Encoding Categorical Variables**
- Converted **crop names** into numerical format using **Label Encoding**.

### **3️⃣ Feature Scaling**
- Applied **StandardScaler** to normalize feature values.

### **4️⃣ Dimensionality Reduction**
- Used **Principal Component Analysis (PCA)** to reduce the dataset to **5 key features**.

---

## 📈 **Model Training & Optimization**
### **1️⃣ Logistic Regression**
- A **classification model** trained to predict the most suitable crop based on soil & climatic factors.

### **2️⃣ Hyperparameter Tuning**
- Used **GridSearchCV** to optimize:
  - **Regularization Strength (C)**
  - **L1 (Lasso) vs L2 (Ridge) Regularization**

### **3️⃣ Model Evaluation**
- Achieved **high accuracy (~95%)** using:
  - **Confusion Matrix**
  - **Classification Report**

---

## 📊 **Results**
| Model | Accuracy |
|--------|---------|
| **Optimized Logistic Regression** | `~97%` |
