# Data Science Project: California Housing Price Analysis & Prediction

## 1. Problem / Research Question
The primary objective of this project is to analyze the socioeconomic and geographic determinants of housing prices in California. Specifically, this project aims to answer the following research question:
> **What are the key geographic and economic indicators driving median house values, and how effectively can a regression model predict housing prices?**

---

## 2. Dataset Source & Usage Permissions
- **Source**: The dataset used in this analysis is the classic California Housing dataset (`housing.csv`), sourced from the StatLib repository and made available for data science benchmarking[cite: 3].
- **Usage Permissions**: Publicly available for educational, research, and non-commercial machine learning analysis.
- **Privacy Notice**: This dataset contains aggregated block-group level census data. No private or personal identifiable information (PII) is included.

---

## 3. Methods & Tools Used
- **Programming Language**: Python 3.10+
- **Libraries & Packages**: 
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- **Environment**: Jupyter Notebook (`practice09.ipynb`)

---

## 4. Key Findings & Limitations

### Key Findings
1. **Median Income Impact**: Median income showed the strongest positive correlation with median house values, acting as the most dominant predictor in the analysis[cite: 3].
2. **Location & Proximity**: Geographic coordinates and spatial distribution significantly impact pricing, reflecting strong coastal and urban premiums[cite: 3].

### Project Limitations
- **Data Age**: The dataset represents historical census data, which may not fully capture modern, post-pandemic real estate market dynamics and inflation patterns.

---

## 5. Instructions for Running the Analysis

Follow these steps to reproduce the analysis locally:

### Step 1: Clone the Repository
```bash
git clone [https://github.com/你的GitHub用户名/data-science-project.git](https://github.com/你的GitHub用户名/data-science-project.git)
cd data-science-project
