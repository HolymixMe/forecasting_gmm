# 📊 Forecasting Malang City’s Regional Revenue (PAD) Using the Grey–Markov (1,1) Model

## 🧠 Overview
This project focuses on forecasting the **Regional Original Revenue (Pendapatan Asli Daerah — PAD)** of **Malang City, Indonesia**, using a hybrid **Grey–Markov (1,1)** model.  
The Grey–Markov model combines the strengths of **Grey System Theory (GM(1,1))**, which is effective for small and uncertain datasets, with **Markov Chain correction**, which enhances accuracy by considering probabilistic state transitions in residuals.

---

## 🎯 Objectives
- To model and forecast Malang City’s PAD based on historical data.
- To improve the accuracy of the standard GM(1,1) model using Markov state transition adjustments.
- To provide an interpretable and data-efficient forecasting method suitable for regional financial planning.

---

## 🧩 Methodology

### 1. **Data Collection**
- The dataset consists of **annual PAD data** from Malang City’s financial reports published by the local government or Kementerian Keuangan.  

### 2. **Grey Model GM(1,1)**
- GM(1,1) constructs a first-order differential equation based on cumulative generation (AGO).
- It is suitable for forecasting systems with limited or incomplete information.

### 3. **Residual Correction using Markov Chain**
- The residuals from the GM(1,1) model are classified into several states (e.g., low, medium, high deviation).
- Transition probabilities are estimated using historical residuals.
- Future forecast values are adjusted based on the most probable Markov state transitions.

---

## ⚙️ Workflow
1. Import and preprocess PAD time series data  
2. Fit the **GM(1,1)** model and generate initial forecasts  
3. Compute residuals and construct **Markov transition matrix**  
4. Adjust forecasts using **Markov chain probabilities**  
5. Evaluate model performance with metrics such as:
   - Mean Absolute Percentage Error (MAPE)
   - Posterior Variance Test (PVT)

---

## 📈 Results Summary
- The hybrid **Grey–Markov (1,1)** model provides more stable and accurate forecasts than the standalone GM(1,1) model.  
- Residual fluctuation patterns are better captured using Markov state transitions.  
- Forecast results show consistent growth trends in Malang’s PAD, supporting long-term fiscal planning.

---

## 🧮 Tools & Libraries
- **Python**  
- **Libraries:**
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `statsmodels` (optional, for comparison)

---

## 🧾 Conclusion
The **Grey–Markov (1,1)** model demonstrates high effectiveness for **forecasting short-term economic indicators** with limited data.  
This method can be applied not only to local revenue forecasting but also to other regional financial indicators and socio-economic planning models.

---

## 👨‍💻 Author
**Muhammad Fahmi Hussain**  
🎓 Mathematics Department, Universitas Brawijaya  
📧 [fahmisajaa@gmail.com](mailto:fahmisajaa@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/muhammad-fahmi-hussain)

---
