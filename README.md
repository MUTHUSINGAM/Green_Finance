# ![ESG Logo](https://your-logo-url.com/logo.png)

# ESG Data Analysis & Optimization Platform

## 📌 Overview
The **ESG Data Analysis and Optimization Platform** is a comprehensive tool that integrates **machine learning, statistical analysis, and linear programming** to evaluate, predict, and optimize **Environmental, Social, and Governance (ESG)** metrics. This platform enables data-driven decision-making for businesses and policymakers to enhance sustainability strategies.

---

## 🔥 Key Features
✅ **Data Processing & Cleaning**: Handles missing data, normalizes values, and merges multiple datasets for accurate analysis.  
✅ **Machine Learning Models**:
   - **Regression Model** for ESG Score Prediction
   - **Random Forest Classifier** for ESG-based Categorization
✅ **Optimization using Linear Programming**: Allocates resources efficiently to maximize ESG impact under budget constraints.
✅ **Data Balancing with SMOTE**: Mitigates class imbalance for better classification accuracy.
✅ **Automated ESG Ranking System**: Ranks projects based on predicted ESG impact.
✅ **Interactive Visualizations**: Engaging dashboards powered by **Streamlit** and **Plotly**.

---

## 🛠 Technologies Used
- **Programming Language**: Python 🐍
- **Libraries**: `pandas`, `numpy`, `sklearn`, `pulp`, `imblearn`, `streamlit`, `plotly`
- **Machine Learning Models**: Linear Regression, Random Forest Classifier
- **Optimization Algorithm**: Linear Programming (**pulp**)
- **Web Framework**: Streamlit

---

## 📂 ESG Datasets Used
This project leverages multiple datasets for ESG analysis:
- `ESGCountry.csv`
- `ESGSeries.csv`
- `ESGSeries-Time.csv`
- `ESGData.csv`
- `ESGFootNote.csv`
- `ESGCountry-Series.csv`

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository:
```bash
git clone https://github.com/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install Dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App:
```bash
streamlit run app.py
```

---

## 📊 Model Training & Evaluation
- **Regression Model**: Trained using `LinearRegression()` on ESG time-series data.
- **Random Forest Classifier**: Tuned using `RandomizedSearchCV` for optimal ESG classification.
- **Performance Metrics**:
  - ✅ Mean Squared Error (MSE)
  - ✅ Accuracy Score
  - ✅ F2 Score
  - ✅ Confusion Matrix

---

## 🔍 ESG Optimization Approach
The platform employs **Linear Programming (LP)** to allocate budgets efficiently while maximizing ESG impact.
- **Constraints Considered**:
  - Budgetary Limits 💰
  - Risk Factors ⚠️
  - Predicted ESG Score 📊

---

## 📈 Data Visualization
The platform provides **interactive analytics** with various charts:
- **Scatter Plot**: Projected Impact vs. Predicted ESG Score
- **Bar Chart**: Top 10 ESG Projects by Score
- **Pie Chart**: ESG Investment Distribution

---

## 🔮 Future Enhancements
🔹 Implement advanced **deep learning models** for ESG predictions.  
🔹 Enhance **risk analysis** with probabilistic models.  
🔹 Extend platform to support **real-time ESG data streaming**.  

---

## 📜 License
This project is **open-source** and available under the **MIT License**. Feel free to contribute and enhance the platform! 🎉

---

### 📧 Contact
For any questions or collaborations, reach out via **[your.email@example.com](mailto:muthusingam539@gmail.com)** or visit the **[GitHub Repository]([https://github.com/your-repo-name](https://github.com/MUTHUSINGAM))**.


