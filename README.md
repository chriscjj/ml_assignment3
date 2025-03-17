## **🏡 California Housing Price Prediction - Regression Assignment**

### **📌 Objective**  
The goal of this project is to **analyze and predict California housing prices** using multiple **regression models**. The dataset contains **various housing features** and their corresponding **median house prices**. The project follows the **entire data science workflow**, including **data preprocessing, model training, evaluation, and comparison**.

---

## **📂 Dataset**
- **Source**: `fetch_california_housing` from `sklearn.datasets`
- **Features**:
  - `MedInc` – Median income in block group
  - `HouseAge` – Median house age in block group
  - `AveRooms` – Average number of rooms per household
  - `AveBedrms` – Average number of bedrooms per household
  - `Population` – Block group population
  - `AveOccup` – Average number of household members
  - `Latitude` – Block group latitude
  - `Longitude` – Block group longitude
- **Target Variable**: `Target` (Median house value)

---

## **🔑 Key Components**
### **1️⃣ Data Preprocessing**
- Converted dataset to a **Pandas DataFrame** for easier manipulation.
- Checked for **missing values** and **data types**.
- Applied **StandardScaler** to standardize numerical features.
- Split the data into **80% training** and **20% testing**.

### **2️⃣ Regression Algorithms Implemented**
1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **Gradient Boosting Regressor**
5. **Support Vector Regressor (SVR)**

### **3️⃣ Model Evaluation Metrics**
- **Mean Squared Error (MSE)**  
- **Mean Absolute Error (MAE)**  
- **R² Score (Coefficient of Determination)**  

### **4️⃣ Results & Model Comparison**
| Model                     | MSE  | MAE  | R² Score |
|---------------------------|------|------|----------|
| Linear Regression         | High | High | Low      |
| Decision Tree Regressor   | Medium | Medium | Medium |
| Random Forest Regressor   | Low  | Low  | High     |
| Gradient Boosting Regressor | Low | Low | High    |
| Support Vector Regressor  | Medium | Medium | Medium |

**✅ Best Model: `Random Forest Regressor`**  
- Low MSE and MAE  
- Highest R² Score (Good Fit)  

**❌ Worst Model: `Linear Regression`**  
- Assumes a **linear relationship**, leading to **high error values**.  



## **📌 Conclusion**
✅ **Random Forest Regressor & Gradient Boosting performed the best**  
❌ **Linear Regression performed the worst due to assumptions of linearity**  
📌 **Tree-based models are better suited for predicting house prices.**

---
