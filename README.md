# 🔬 Breast Cancer Survival Analysis Using Gene Expression Data
### *Kaplan–Meier • Cox Proportional Hazards • Pathway Enrichment*
#### This is the project page for Youth Bioinformatics Summit 2024, International Society for Computational Biology (ISCB) attended remotely.
---

## 🔗 Youtube Link

- [Relevance of Genes on survival of Breast cancer patients YBS 2024](https://youtu.be/ZD1atpsdUWs?si=7Y2aHo-_fjtbbj8y)

---

This repository contains a complete analysis pipeline to understand how **gene expression** impacts **overall survival** in Breast Cancer (BRCA) patients.

The project includes:

- Kaplan–Meier survival analysis  
- Univariate Cox proportional hazards modeling  
- Identification of risk vs. protective genes  
- Pathway enrichment analysis  
- All workflows implemented in Jupyter Notebook  

Reference presentation: **Gungun_Surana_BRCA_Survival.pptx**  
Primary notebook: **Survival_Analysis.ipynb**

---

## 📌 Project Overview

Breast cancer remains one of the most common cancers globally. Gene expression patterns can help identify biomarkers that influence survival.

This project analyzes breast cancer microarray data (e.g., GSE7390) to determine:

- Which genes increase patient mortality?  
- Which genes are protective?
- Which biological pathways are enriched?
- How ER+ vs ER– status relates to outcomes? 

---

## 🧬 Methods

### **1️⃣ Kaplan–Meier Survival Analysis**

Compares survival between high‑ and low‑expression patient groups.

### **2️⃣ Univariate Cox Proportional Hazards Model**

	h(t|X) = h0(t) exp(βX)

- **HR > 1** → Higher risk (poor survival)  
- **HR < 1** → Protective (better survival)  
- p‑values and CI used for ranking  

### **3️⃣ Pathway Enrichment Analysis**

Top significant genes tested via GO/KEGG.

Key pathways:

- Cytoplasmic translation  
- Ribosome assembly  
- Nucleoplasm processes  
- Translation initiation  

---

## 📁 Repository Structure

```
├── data/
│   ├── gene_enrich_results.csv
│   ├── gene_enrich_results_top10.csv
│   ├── gene_survival_analysis_results.csv
│   ├── gene_survival_analysis_results_significant.csv
│   ├── gene_survival_analysis_results_significant_decrease_hazard.csv
│   ├── gene_survival_analysis_results_significant_increase_hazard.csv
│   ├── GSE7390_transbig2006affy_README
├── code/
│   ├── Survival_Analysis.ipynb
├── presentation
│   ├── Gungun_Surana_BRCA_Survival.pptx
├── README.md
```

---

## 🚀 How to Run

### **1. Clone the repository**
```bash
git clone https://github.com/your-username/BRCA-Survival-Analysis.git
cd BRCA-Survival-Analysis
```

### **2. Run the notebook**
```bash
jupyter notebook Survival_Analysis.ipynb
```

---

## 🏆 Key Results

### 🔥 Top 10 High‑Risk Genes  
Genes with **HR > 1** associated with decreased survival.

### 🛡️ Top 10 Protective Genes  
Genes with **HR < 1** associated with improved survival.

### 📊 Pathway Insights  
Cancer progression linked to:

- Altered protein translation  
- Ribosome dysfunction  
- Nucleoplasm irregularities  

---

## 📧 Contact

**Gungun**
GitHub: GungunSurana
