# Structured-Equation-Modeling

> **Understanding the Use of Social Media in Medical Education — An Exploratory SEM Study**

This repository contains all files, data, and analysis used for an exploratory study investigating how medical students use social media and whether social media usage relates to academic performance. The analysis uses **Structural Equation Modeling (SEM)** implemented in Python (Jupyter Notebook).

---

## 📌 Project Overview

The study aims to understand the different uses of social media by medical students, motivations for sharing and seeking information, awareness of misinformation, and how social media may be leveraged for improving access to reliable academic resources.

Key components in this repo:
- Survey questionnaire  
- Cleaned dataset for SEM  
- Jupyter notebook with SEM pipeline and results  
- Exported fit statistics and parameter estimates  

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

Structured-Equation-Modeling/
├── Objectives of the Study.docx # Project objectives & hypotheses
├── questionaire.pdf # Survey instrument used to collect responses
├── sem_data.xlsx # Collected & preprocessed dataset for SEM
├── Sem_Model.ipynb # Jupyter Notebook: SEM pipeline & analysis
├── sem_fit_statistics.csv # Exported SEM fit statistics
├── sem_parameter_estimates.csv # Exported SEM parameter estimates
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── LICENSE # License file (MIT)

yaml
Copy code

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
requirements.txt
nginx
Copy code
pandas
numpy
openpyxl
matplotlib
seaborn
jupyter
semopy
scipy
statsmodels
▶️ Running the Analysis
Activate your virtual environment.

Start Jupyter Notebook / Lab:

bash
Copy code
jupyter notebook
# or
jupyter lab
Open Sem_Model.ipynb and run all cells. The notebook will:

Load sem_data.xlsx

Preprocess & encode variables

Build the SEM model (measurement model + structural paths)

Fit the model using semopy (or the SEM library used)

Save results to sem_fit_statistics.csv and sem_parameter_estimates.csv

Generate plots and interpretation

✅ What to Check in Results
Model fit indices: χ², df, p-value, CFI, TLI, RMSEA (with 90% CI), SRMR

Factor loadings: check significance and magnitude (>0.50 desirable)

Standardized path coefficients: interpret effect sizes and significance

Modification indices: only consider theoretically-justified modifications

Reliability & validity: Cronbach’s alpha, composite reliability, AVE

📝 Reporting & Outputs
sem_fit_statistics.csv → Fit indices to report in results section

sem_parameter_estimates.csv → Factor loadings, regression weights, SE, z-values, p-values

Use plots & tables from the notebook in your research paper/report

🤝 Contributors
Priyanshu Chouhan

Krishna Gupta

Prateek Batham

Pratham Hande

📜 License
This project is released under the MIT License — see LICENSE for details.

yaml
Copy code

---

✅ Just copy–paste this into `README.md` inside your `Structured-Equation-Modeling` folder.  

Do you also want me to generate a **ready-to-paste `requirements.txt` and `.gitignore`** file code in the same way?






You said:
give me ready to paste readme.md code


ChatGPT said:
Got it 👍
Here’s the final, clean, ready-to-paste README.md code for your project. Just copy this as-is into your README.md file inside the Structured-Equation-Modeling folder:

markdown
Copy code
# Structured-Equation-Modeling

> **Understanding the Use of Social Media in Medical Education — An Exploratory SEM Study**

This repository contains all files, data, and analysis used for an exploratory study investigating how medical students use social media and whether social media usage relates to academic performance. The analysis uses **Structural Equation Modeling (SEM)** implemented in Python (Jupyter Notebook).

---

## 📌 Project Overview

The study aims to understand the different uses of social media by medical students, motivations for sharing and seeking information, awareness of misinformation, and how social media may be leveraged for improving access to reliable academic resources.

Key components in this repo:
- Survey questionnaire  
- Cleaned dataset for SEM  
- Jupyter notebook with SEM pipeline and results  
- Exported fit statistics and parameter estimates  

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

Structured-Equation-Modeling/
├── Objectives of the Study.docx # Project objectives & hypotheses
├── questionaire.pdf # Survey instrument used to collect responses
├── sem_data.xlsx # Collected & preprocessed dataset for SEM
├── Sem_Model.ipynb # Jupyter Notebook: SEM pipeline & analysis
├── sem_fit_statistics.csv # Exported SEM fit statistics
├── sem_parameter_estimates.csv # Exported SEM parameter estimates
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── LICENSE # License file (MIT)

yaml
Copy code

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
requirements.txt
nginx
Copy code
pandas
numpy
openpyxl
matplotlib
seaborn
jupyter
semopy
scipy
statsmodels
▶️ Running the Analysis
Activate your virtual environment.

Start Jupyter Notebook / Lab:

bash
Copy code
jupyter notebook
# or
jupyter lab
Open Sem_Model.ipynb and run all cells. The notebook will:

Load sem_data.xlsx

Preprocess & encode variables

Build the SEM model (measurement model + structural paths)

Fit the model using semopy (or the SEM library used)

Save results to sem_fit_statistics.csv and sem_parameter_estimates.csv

Generate plots and interpretation

✅ What to Check in Results
Model fit indices: χ², df, p-value, CFI, TLI, RMSEA (with 90% CI), SRMR

Factor loadings: check significance and magnitude (>0.50 desirable)

Standardized path coefficients: interpret effect sizes and significance

Modification indices: only consider theoretically-justified modifications

Reliability & validity: Cronbach’s alpha, composite reliability, AVE

📝 Reporting & Outputs
sem_fit_statistics.csv → Fit indices to report in results section

sem_parameter_estimates.csv → Factor loadings, regression weights, SE, z-values, p-values

Use plots & tables from the notebook in your research paper/report

🤝 Contributors
Priyanshu Chouhan

Krishna Gupta

Prateek Batham

Pratham Hande

📜 License
This project is released under the MIT License — see LICENSE for details.