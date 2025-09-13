<!-- Banner -->
<h1 align="center">Structured-Equation-Modeling</h1>
<p align="center">
  <b>Understanding the Use of Social Media in Medical Education — An Exploratory SEM Study</b>  
</p>
This repository contains all files, data, and analysis used for an exploratory study investigating how medical students use social media and whether social media usage relates to academic performance. The analysis uses **Structural Equation Modeling (SEM)** implemented in Python (Jupyter Notebook).

---

## 📌 Project Overview

The study aims to understand the different uses of social media by medical students, motivations for sharing and seeking information, awareness of misinformation, and how social media may be leveraged for improving access to reliable academic resources.

Key components in this repo:
- survey questionnaire
- cleaned dataset for SEM
- Jupyter notebook with SEM pipeline and results
- exported fit statistics and parameter estimates

---

## 🎯 Objectives & Hypotheses

**Objectives (short):**
1. Investigate use of different social networking sites by medical students.  
2. Analyze social media usage for enhancing academic performance.  
3. Identify motivations for sharing and seeking information on social media.  
4. Determine reasons for excessive social media use vs. traditional sources.  
5. Check students' awareness of information disorders (misinformation/disinformation).  
6. Suggest methods to harvest information effectively from social platforms.  
7. Recommend ways to help students access reliable resources and services on social media.

**Hypotheses (tested using SEM):**
- H1: Perceptions and experiences with social media differ by gender and age.  
- H2: Students have not yet leveraged social networking sites for academic/scholarly communication.  
- H3: There is demand for harnessing social media to access library resources and services.  
- H4: Medical mis/disinformation is prevalent on social media and students are not fully aware.  
- H5: Students show no concern about the reliability and authenticity of information shared/consumed.

> (Objectives and hypotheses are taken from the project documentation.)

---

## 📂 Repository Structure
```bash
├── Objectives of the Study.docx
├── questionaire.pdf
├── sem_data.xlsx
├── Sem_Model.ipynb
├── sem_fit_statistics.csv
├── sem_parameter_estimates.csv
├── requirements.txt
├── README.md
└── LICENSE
```


**What each file contains**
- `Objectives of the Study.docx` — Project objectives & hypotheses.  
- `questionaire.pdf` — The survey instrument used to collect responses.  
- `sem_data.xlsx` — Collected & preprocessed dataset used for SEM.  
- `Sem_Model.ipynb` — Jupyter Notebook: data preparation, SEM specification, model fitting, evaluation, and plots.  
- `sem_fit_statistics.csv` — Fit statistics exported from the SEM run (ex: CFI, RMSEA, χ², SRMR, etc.).  
- `sem_parameter_estimates.csv` — Parameter estimates (factor loadings, regression weights, standardized estimates).

---

## 🧰 Requirements & Setup

> Create a virtual environment and install dependencies:

```bash
# from within the repo folder
python -m venv venv
# activate
# Linux / Mac
source venv/bin/activate
# Windows (PowerShell)
venv\Scripts\Activate.ps1

# install requirements
pip install -r requirements.txt
```

**requirements.txt** 
```bash
pandas
numpy
openpyxl
matplotlib
seaborn
jupyter
semopy 
scipy
statsmodels
```

**▶️ Running the analysis**

Activate your virtual environment (see above).
```bash
Start Jupyter Notebook / Lab: Jupyter notebook or Jupyter lab

Open 'Sem_Model.ipynb' and run the cells top-to-bottom. 

The notebook: loads 'sem_data.xlsx' preprocesses & encodes variables (scales, reverse-coded items if any) builds the SEM model (measurement model + structural paths) fits the model using semopy (or the SEM library used) saves fit statistics to sem_fit_statistics.csv and parameter estimates to 'sem_parameter_estimates.csv' includes interpretation/plots for loadings, standardized effects, and fit indices
```

## ✅ What to check in results

- Model fit indices: χ², df, p-value, CFI, TLI, RMSEA (with 90% CI), SRMR.
- Factor loadings — check for significance and magnitude (>0.50 desirable).
- Standardized path coefficients — interpret effect sizes and significance.
- Modification indices (if used) — to consider theoretically-justified modifications only.
- Reliability & validity tests — Cronbach’s alpha / composite reliability, AVE.

## 📝 Reporting & Outputs

sem_fit_statistics.csv contains the main fit indices you will report in the Results section.

sem_parameter_estimates.csv contains factor loadings, regression weights, standard errors, z-values, and p-values for interpretation.

Use the notebook cells (already included) to copy plots and tables directly into your report.

## 🤝 Contributors
Rishi Sahu 

## 📜 License

This project "Structured-Equation-Modeling" is made available for academic and educational purposes only. 