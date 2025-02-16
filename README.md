# 🚢 Titanic AWP (Analysis With Python)  

## 📌 Overview  
**Titanic AWP (Analysis With Python)** is a data analysis project that explores the **Titanic dataset**. The project focuses on:  
- **Cleaning and preprocessing** the dataset  
- **Exploratory Data Analysis (EDA)**  
- **Visualizing key trends**  
- **Statistical insights into passenger survival rates**  

⚠️ **No machine learning is used**—this project is purely for **data analysis and visualization**.  

---

## 📊 Dataset Overview  
The dataset contains **418 rows** and **11 columns** with details about Titanic passengers.  

### **Key Columns:**
- `Pclass`: Passenger class (1st, 2nd, 3rd)  
- `Sex`: Male or Female  
- `Age`: Passenger age (with missing values)  
- `SibSp`: Number of siblings/spouses aboard  
- `Parch`: Number of parents/children aboard  
- `Fare`: Ticket fare  
- `Embarked`: Port of embarkation (C, Q, S)  
- `Cabin`: Cabin number (mostly missing)  

---

## 📉 Data Cleaning  
### **Handling Missing Values**  
- **Age**: Missing values were **filled with the median age** based on `Pclass` and `Sex`.  
- **Fare**: One missing value was **filled with the median fare**.  
- **Cabin**: Most values were missing, so it was **dropped from analysis**.  

---

## 📊 Analysis & Insights  

### **1️⃣ Survival Rate by Passenger Class**  
- **1st Class** passengers had the **highest survival rate**.  
- **3rd Class** passengers had the **lowest survival rate**.  

#### 📌 Graph: Survival Rate by Class  
*(Bar Chart: Survival Rate vs. Pclass)*  

---

### **2️⃣ Gender-Based Survival Rate**  
- **Females had a much higher survival rate** than males.  
- The survival rate for **males was significantly lower**.  

#### 📌 Graph: Survival Rate by Gender  
*(Bar Chart: Male vs. Female Survival Rate)*  

---

### **3️⃣ Age Distribution of Survivors vs. Non-Survivors**  
- **Children (under 10)** had a higher chance of survival.  
- **Elderly passengers** had lower survival rates.  

#### 📌 Graph: Age Distribution (Histogram)  
*(Histogram: Age distribution for survivors vs. non-survivors)*  

---

### **4️⃣ Fare Distribution by Class**  
- **1st Class passengers paid higher fares** compared to 2nd and 3rd class.  
- **Survivors generally had higher fares** than non-survivors.  

#### 📌 Graph: Fare Distribution  
*(Boxplot: Fare comparison for different classes)*  

---

### **5️⃣ Embarkation Port & Survival**  
- **Passengers from Cherbourg (C) had higher survival rates**.  
- **Southampton (S) had the lowest survival rate**.  

#### 📌 Graph: Survival Rate by Embarkation Port  
*(Bar Chart: Survival Rate vs. Embarked Port)*  

---

## 📝 Conclusion  
📌 **Key Takeaways:**  
✅ **Class and gender** played a major role in survival.  
✅ **Women and children** had higher chances of survival.  
✅ **Higher fare prices correlated with survival**.  
✅ **Cabin information was mostly missing** and not useful for analysis.  


---

## 🎯 Future Improvements  
- **More detailed feature engineering**  
- **Interactive visualizations**  
- **Additional statistical tests**  

