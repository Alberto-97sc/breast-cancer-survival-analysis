# Breast Cancer Survival Analysis

This project focuses on the **survival analysis of breast cancer patients treated with breast-conserving surgery**, using real-world clinical data and standard statistical survival techniques.

The project is developed as:
- a **collaboration with a clinical researcher** for a scientific publication, and
- a **data science portfolio project** demonstrating applied survival analysis skills.

---

## 🎯 Objectives

- Analyze overall and disease-free survival in breast cancer patients
- Identify clinical and pathological factors associated with survival outcomes
- Apply and interpret classical survival analysis methods
- Produce reproducible, well-documented analytical workflows

---

## 📊 Data Description

- **Domain**: Clinical oncology (breast cancer)
- **Population**: Patients treated with breast-conserving surgery
- **Data source**: Provided by a medical collaborator
- **Data characteristics**:
  - Retrospective observational data
  - Patient-level clinical and pathological variables
  - Time-to-event outcomes with censoring

> ⚠️ The dataset is **not publicly shared** due to confidentiality and ethical considerations.  
> All analyses are performed on anonymized data.

---

## 🧪 Methodology

The analysis follows a standard survival analysis workflow:

1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Definition of:
   - Time-to-event variable
   - Event indicator
   - Censoring mechanism  
4. Kaplan–Meier survival estimation  
5. Group comparisons using log-rank tests  
6. Cox proportional hazards modeling  
7. Model interpretation and validation  

---

## 📈 Techniques & Tools

### Statistical Techniques
- Kaplan–Meier survival curves
- Log-rank tests
- Cox proportional hazards models
- Hazard ratio interpretation

### Tools
- Python
- pandas, numpy
- matplotlib / seaborn
- lifelines
- statsmodels
- Jupyter Notebooks

---

## 📁 Repository Structure

```
breast-cancer-survival-analysis/
│
├── data/
│   ├── raw/            # original data (not tracked if sensitive)
│   └── processed/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_survival_analysis.ipynb
│   └── 03_cox_model.ipynb
│
├── figures/
├── src/
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/breast-cancer-survival-analysis.git
   cd breast-cancer-survival-analysis
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Register the Jupyter kernel (optional but recommended):
   ```bash
   python -m ipykernel install --user \
     --name breast-cancer-survival-analysis \
     --display-name "Python (breast-cancer-survival-analysis)"
   ```

5. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 📌 Results

Key results and visualizations are presented within the Jupyter notebooks, including:
- Survival curves stratified by relevant clinical variables
- Estimated hazard ratios with confidence intervals
- Statistical interpretation of findings

---

## ⚠️ Limitations

- Limited sample size
- Observational (non-randomized) data
- Potential unmeasured confounders
- Results should be interpreted in a clinical research context

---

## 🔮 Future Work

- Multivariable model refinement
- Assessment of proportional hazards assumptions
- Inclusion of additional clinical endpoints
- External validation with independent cohorts

---

## 👤 Author

**Alberto**  
Data Scientist  
🌍 Open to remote opportunities  

---

## 📄 License

This project is licensed under the MIT License.
