# -Project-Title-Optimizing-Plant-Based-Yogurt-Texture-Using-Design-of-Experiments-DoE-in-KNIME
🎯 Objective
Use KNIME to perform multivariate statistical analysis (e.g., PLSR, Pareto optimization) on a simulated dataset of plant-based yogurt formulations to optimize for desirable texture and consistency, simulating a realistic agri-food R&D setting.

🧠 Skills & Tools Highlighted
Skill/Gap	How It’s Addressed
KNIME	Learn and use it for data wrangling + workflow design
SQL (Optional)	Integrate SQL queries in KNIME workflows for data pulls
JMP Pro (Alternative)	Mention plan to compare with KNIME if tools available
Agri-Food Exposure	Focus on texture (emulsification, thickening, etc.)
Multivariate Stats	Apply PLSR, DoE, and visualize via Pareto charts
AI/ML	Add a basic regression model to predict optimal texture

🛠️ Dataset (Options)
Synthetic data — You can generate a dataset in Excel with variables like:

Ingredient ratios (starch, protein, emulsifier)

Mixing time, homogenization speed, pH

Output parameters: Viscosity, firmness (from a texturometer), consumer rating

Open-source data — Use Kaggle or FAO agri-food datasets (I can help you find one if you want a real dataset).

🔁 Workflow Outline
📥 Import Data → (CSV or SQL through KNIME)

🧹 Preprocess → Normalize ingredient % and output variables

📊 Design of Experiments → Use KNIME DoE nodes to simulate trials

🔬 PLSR → Link input ingredients to output properties

📈 Pareto Optimization → Maximize texture and consumer rating

🤖 (Optional) Add Linear Regression / Decision Tree for prediction

📤 Export results to Google Sheets (or Excel) and automate report
