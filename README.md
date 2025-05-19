# BioYogurt+: Sensor-Based Quality Optimization in Plant-Based Yogurt

**Project Goal:**  
To simulate and optimize the formulation of plant-based yogurt using a synthetic dataset, multivariate statistical analysis, and design of experiments (DoE). This project bridges food science, data science, and sensor analytics.

---

## 💡 Problem Statement

In the agri-food industry, optimizing product quality—like yogurt texture, pH, and taste—requires a deep understanding of how ingredient ratios influence key sensory and physical properties. This project simulates that process using synthetic sensor data to model, predict, and enhance product performance.

---

## 🧪 Dataset

The dataset includes 20 synthetic yogurt samples with the following variables:

- `Starch_%` – Plant-based starch content (%)
- `Protein_%` – Plant-based protein content (%)
- `Probiotic_%` – Functional bacteria content (%)
- `pH` – Final product acidity level
- `Viscosity_Pa_s` – Simulated viscosity readings from sensor
- `Taste_Score_10` – Simulated consumer sensory score (0–10)

👉 [Download dataset](bioyogurt_plus_synthetic_dataset.csv)

---

## ⚙️ Workflow Overview

1. **Data Loading & Exploration** – Preview and summarize trends
2. **Design of Experiments (DoE)** – Generate formulation variations
3. **PLSR Modeling** – Predict yogurt quality from ingredient inputs
4. **Pareto Analysis** – Identify most influential factors
5. **SQL (Optional)** – Query high-performing samples
6. **Results Visualization** – Scatter plots, bar charts, prediction accuracy
7. **Reflection & Learnings** – Summary of insights, limitations, future work

---

## 🧰 Tools & Skills Used

| Area             | Tools/Methods                          |
|------------------|----------------------------------------|
| Programming      | Python (Jupyter Notebook)              |
| Data Wrangling   | pandas, numpy                          |
| DoE              | pyDOE2, statsmodels                    |
| Regression       | scikit-learn (PLSR, Linear Regression) |
| Visualization    | matplotlib, seaborn                    |
| SQL (Optional)   | sqlite3, pandasql                      |
| Documentation    | Markdown, GitHub                       |

---

## 🔍 Learning Outcomes

- Applied DoE and PLSR to a simulated food-tech scenario
- Explored multivariate relationships between formulation and output quality
- Practiced scientific documentation and reproducibility using Jupyter and Git
- Gained insight into how statistical models can drive product optimization in biotech and agri-food industries

---

## 🚀 Future Work

- Apply model to real-world open-source datasets (e.g., FAO or Kaggle food science data)
- Integrate machine learning models for deeper insight (Random Forest, XGBoost)
- Extend project with KNIME or JMP workflows for no-code version
- Add real-time dashboard or UI with Plotly Dash or Streamlit

---

## 🙋‍♀️ Author

**Sehba Samman**  
Biomedical Engineering @ University of Calgary  
🔗 [LinkedIn](https://www.linkedin.com/in/sehbasamman/)  
📬 sehba.samman@ucalgary.ca  

