# Metabolic Health Analysis

## Overview

This repository contains the data analysis process and findings for the study titled *"Exploring Metabolic Health: Impacts on Body Composition and Immunity via PCA and Regression Analysis."* The study aims to investigate the relationship between dietary intake, metabolic markers, and anthropometric measures such as BMI, arm circumference, and waist circumference.

Key components:
- **PDF Report**: [Metabolic_Health_Report.pdf](./Metabolic_Health_Report.pdf) — Comprehensive documentation of the study, including background, methodology, and conclusions.
- **Jupyter Notebook**: [Metabolic_Health_Analysis.ipynb](./Metabolic_Health_Analysis.ipynb) — Step-by-step Python code for data preprocessing, PCA, and regression modeling.

## Project Details

### Objective
To understand how dietary and metabolic health markers correlate with body composition metrics using advanced statistical techniques such as Principal Component Analysis (PCA) and Multiple Linear Regression (MLR).

### Key Features
- **Dimensionality Reduction**: Applied PCA to retain variables explaining 95% of the variance while reducing complexity.
- **Predictive Models**: Built regression models to identify significant predictors of anthropometric measures.
- **Key Findings**:
  - Copper and vitamin D intake are significant dietary predictors.
  - Inflammatory markers (e.g., monocyte and white blood cell counts) correlate with body composition.

### Tools and Techniques
- **Data Cleaning**: Addressed missing values using K-Nearest Neighbors (KNN).
- **Feature Scaling**: Standardized variables for PCA.
- **Data Visualization**: Used heatmaps and plots to interpret PCA loadings and regression results.
- **Programming Languages**: Python (pandas, scikit-learn, matplotlib, seaborn).

## File Structure

- **Metabolic_Health_Analysis.ipynb**: The notebook with all the analysis steps, including data preprocessing, PCA, and regression modeling.
- **Metabolic_Health_Report.pdf**: The written report summarizing the study’s purpose, methods, results, and conclusions.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/luiscarlosmarrufo/Metabolic-Health-Analysis.git
   ```

2. **Install Dependencies**: Ensure you have Python installed and run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**:
   Open `Metabolic_Health_Analysis.ipynb` in Jupyter Notebook or JupyterLab to explore the analysis.

## Results Summary

The study highlights the critical role of dietary and metabolic factors in influencing body composition. The regression models achieved high adjusted R² values, indicating strong predictive power:
- **BMI Model**: Adjusted R² = 0.945
- **Arm Circumference Model**: Adjusted R² = 0.978
- **Waist Circumference Model**: Adjusted R² = 0.973

These insights are valuable for designing interventions to improve health outcomes.

## Acknowledgments

This project utilized data from the National Health and Nutrition Examination Survey (NHANES) and Python libraries for statistical analysis. Special thanks to the research team for their contributions.
