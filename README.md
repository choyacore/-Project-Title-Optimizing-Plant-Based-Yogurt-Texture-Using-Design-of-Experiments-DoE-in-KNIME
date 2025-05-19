# BioYogurt+: Ingredient Optimization for Glycemic Control

**Project Goal:**  
To simulate and analyze how ingredient ratios in plant-based yogurt formulations affect product qualities like viscosity, taste, and glycemic index — using both Python (Jupyter) and KNIME Analytics Platform.

---

## 🧠 Background

This project was inspired by New-Food Innovation’s case study on increasing starch resistance in legumes to reduce glycemic load. In a simulated R&D setting, we investigate how starch, protein, and probiotic content influence the health and sensory profile of a yogurt prototype.

---

## 📊 Dataset

The synthetic dataset includes 20 yogurt samples with:

- `Starch_%` – Simulated legume-based starch content  
- `Protein_%` – Plant protein source (e.g., pea, chickpea)  
- `Probiotic_%` – Functional bacteria concentration  
- `pH` – Final product acidity  
- `Viscosity_Pa_s` – Simulated texture reading  
- `Taste_Score_10` – Predicted consumer rating  
- `Glycemic_Index` – Modeled using nutritional impact formulas

📥 [Download the dataset](bioyogurt_nfi_gi_dataset.csv)

---

## ⚙️ Tools Used

| Tool | Purpose |
|------|---------|
| **Python (Jupyter Notebook)** | Data preprocessing, regression modeling, coefficient analysis |
| **scikit-learn** | Multivariate regression |
| **Seaborn / Matplotlib** | Data visualization |
| **KNIME Analytics Platform** | Visual workflow replication (File Reader, Regression, Correlation) |

---

## 📈 Workflow

### In Python (Jupyter)
1. Load and preview dataset  
2. Visualize variable relationships  
3. Train regression models for:
   - Viscosity
   - Taste Score
   - Glycemic Index  
4. Analyze coefficients to identify most influential ingredients  
5. Visualize findings and summarize insights

### In KNIME
- File Reader → Correlation Matrix → Linear Regression Learner  
- Quick visual interface for non-programmatic replication

---

## 🔬 Key Findings

- **Protein** had a positive impact on **taste** and helped reduce **glycemic index**  
- **Starch** improved **viscosity**, but increased **GI**  
- **Probiotics** helped reduce **GI** and contributed to sensory scores

---

## 🧠 Reflection

This project helped me explore how to simulate product optimization in a food science context. It also allowed me to bridge my skills in biomedical data analysis with agri-food innovation.

I practiced:
- Design of Experiments logic  
- Multivariate regression  
- Data storytelling  
- Translating analysis between code-based (Jupyter) and visual (KNIME) tools

---

## 🚀 Future Work

- Expand dataset with real-world sensor data or open food composition data  
- Try advanced models like Ridge/Lasso regression  
- Explore taste prediction models using machine learning  
- Deploy with a Streamlit or Dash UI for R&D demo

---

## 🙋‍♀️ Author

**Sehba Samman**  
Biomedical Engineering @ University of Calgary  
📧 sehba.samman@ucalgary.ca  
🔗 [LinkedIn](https://www.linkedin.com/in/sehbasamman/)
