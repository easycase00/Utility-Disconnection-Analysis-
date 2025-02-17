# 📌 Overview
The **Utility Disconnection project** was developed in collaboration with the **Energy Justice Lab** to analyze **state-wide utility disconnections**. The goal was to conduct **Exploratory Data Analysis (EDA)** and uncover insights on **how the COVID-19 pandemic affected disconnection rates**.

By analyzing datasets spanning **1996-2024**, I identified **state-level trends**, performed **statistical significance testing**, and evaluated the effectiveness of **state protections and policies**.

---

## 🎯 Purpose
Utility disconnections disproportionately impact **low-income communities**, leading to:
- **Health risks**
- **Housing instability**
- **Financial hardship**

This project aims to:
- Identify **state-wise trends** and disparities in disconnections.
- Provide **data-driven insights** for stakeholders.
- Assist policymakers and advocacy groups in developing **fair energy policies**.

---

## 🏗 Methodology

### **📂 Data Sources**
I analyzed multiple datasets:
- **Service Territory Data**: Disconnections at the **state and utility provider level (1996-2024)**.
- **Protections Data**: Policies related to **weather-based and regulatory protections**.
- **Zip Code Level Data**: Granular **disconnection data** at the local level.
- **SP Territory Data**: Utility-specific **financial and customer** data.

### **🛠️ Technologies Used**
- **Python (Pandas, Matplotlib, SciPy, Seaborn)** for analysis and visualization.
- **SQL/Python/Excel** for data exploration.
- **Statistical Tests**: **ANOVA, Kruskal-Wallis H Test, Dunn’s Test, and T-tests**.

### **📈 Analytical Methods**
#### ✅ **State-Wise Trend Analysis**
- Compared **year-over-year** changes in disconnection rates.
- **Key Findings:**
  - States like **California, New York, and Michigan** saw major declines during COVID.
  - **Texas, Idaho, and Utah** had minimal changes.

#### ✅ **Nationwide Statistical Testing**
- **Used ANOVA & Kruskal-Wallis H Tests** to compare **Pre-COVID, COVID, and Post-COVID disconnection rates**.
- **Key Findings:**
  - **Disconnections dropped significantly during COVID** due to **moratoriums**.
  - **Post-COVID rates rebounded** but remained **lower than pre-pandemic levels**.

#### ✅ **State-Level Statistical Testing**
- **Performed T-tests, ANOVA, and Dunn’s Test** to compare **Pre-COVID, COVID, and Post-COVID periods**.
- **Key Findings:**
  - **California, Michigan, Maryland, and New York** showed **significant decreases** due to **strong protections**.
  - **Texas, Idaho, and Utah** had **no significant changes**, indicating **weaker interventions**.

#### ✅ **Utility Type Statistical Testing**
- Compared **Investor-Owned, Municipal, and Cooperative utilities**.
- **Key Findings:**
  - **Municipal utilities had the highest disconnection rates**.
  - **Investor-Owned utilities showed the most fluctuation**.

#### ✅ **Raw Disconnection Numbers Analysis**
- Evaluated **total number of disconnections** instead of rates.
- **Key Findings:**
  - **Disconnections plummeted during COVID** but increased post-pandemic.
  - **North Dakota showed a sharp increase post-COVID** due to policy rollbacks.

---

## 📢 Key Findings & Visuals

### 📊 **Disconnection Rates Before, During, and After COVID**
- **Pre-COVID:** Higher rates due to lack of protections.
- **COVID:** **Sharp decline** in disconnections due to **moratoriums**.
- **Post-COVID:** Partial rebound, but **still below pre-COVID levels**.

### 📍 **State-Level Disconnection Variability**
- **California & Michigan:** Significant **decline** in disconnections.
- **Texas & Utah:** Minimal impact, showing **weaker protections**.

### 🔍 **Utility Type Analysis**
- **Municipal utilities had the highest disconnection rates**.
- **Investor-Owned utilities showed the most fluctuation**.

### 🚨 **State-Wise Percentage Change in Disconnection Rates**
- **North Dakota had the sharpest post-COVID increase**.
- **States with strong protections had more controlled rebounds**.

---


## 📜 Detailed Report
A **more detailed report** containing in-depth statistical analysis, methodology, charts, and policy insights is included in the project files.

📄 **Read the full report here:** 

---

## 🔎 Future Recommendations
🚀 **1. Deep Dive into Policy Data**  
- Analyze **state policies affecting disconnection rates**.

📈 **2. Update Analysis with New Data**  
- Include **2023+ data** to track new trends.

🔄 **3. Comparative State Analysis**  
- Compare states with **different policy approaches**.

📊 **4. Incorporate Socioeconomic Data**  
- Merge data with **income levels, employment rates, and demographics**.

🌍 **5. Expand Utility-Specific Testing**  
- Apply analysis to **all U.S. states and utility providers**.

---

