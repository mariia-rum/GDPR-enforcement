# README

## Overview

**GDPR-enforcement** is a part of a wider research initiative concerning the enforcement of CCPA and GDPR regulations, which was conducted as part of my master's thesis at Maastricht University in 2021. The aim of this project is to provide a comprehensive analysis of GDPR enforcement practices within the EU and to evaluate the implications of these practices on personal data protection.

This repository contains two key Jupyter Notebook files, `GDPR_1.ipynb` and `GDPR_2.ipynb`, which utilize datasets collected and structured for this research. Below is a detailed explanation of the files and the technical requirements necessary to run this project.

## Files and Their Purpose

### GDPR_1.ipynb

**Research Idea:**
This notebook aims to examine enforcement practices of GDPR within the EU. Two datasets were created in Excel (`GDPR_enforcement_1.xlsx` and `GDPR_enforcement_2.xlsx`) based on data from the GDPR Enforcement Tracker by CMS Legal Services EEIG.

**Methodology:**
- This notebook uses the first dataset (`GDPR_enforcement_1.xlsx`), which represents enforcement procedures in 27 EU Member States (excluding the UK).
- The dataset consists of 10 columns: "Country", "Authority", "Year", "Fine", "Controller/Processor", "Article", "Type of infringement", "Infringement", "Emphasis", "Offender".
- Libraries used:
  - NumPy and Pandas for data analysis.
  - Matplotlib for data visualization.

**Problem Addressed:**
The research focuses on:
- How GDPR enforcement varies across EU countries.
- Identifying the actors targeted by GDPR fines.
- Common activities resulting in GDPR breaches.
- Articles enforced due to GDPR violations.

**Steps:**
1. Examination and analysis of the dataset.
2. Data visualization.
3. Communicating results (results were introduced in the thesis but are not included in the notebook).

### GDPR_2.ipynb

**Research Idea:**
This notebook investigates enforcement practices of GDPR within the EU, specifically focusing on GDPR fines per capita in the timeframe from May 2018 to June 2020. The dataset (`GDPR_enforcement_2.xlsx`) was derived from the GDPR Enforcement Tracker by CMS Legal Services EEIG.

**Methodology:**
- The dataset includes 3 columns: "Country", "Fine2", and "Population".
- Libraries used:
  - NumPy and Pandas for data analysis.
  - Seaborn for data visualization.

**Problem Addressed:**
The research question focuses on calculating GDPR fines per capita within EU Member States and visualizing the results.

**Steps:**
1. Examination and analysis of the dataset.
2. Calculation of fines per capita.
3. Data visualization.
4. Communicating results (results were introduced in the thesis but are not included in the notebook).

## Technical Requirements

To run the notebooks and reproduce the analysis, ensure you have the following installed:

- Python 3.8 or above
- Jupyter Notebook
- Required Python libraries:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn

You can install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib seaborn
```

## Purpose of the Research

The purpose of this research is to evaluate the effectiveness and enforcement practices of the GDPR across EU Member States. By analyzing enforcement data, this research provides insights into the regulatory landscape, identifying patterns in data protection enforcement and shedding light on how GDPR influences privacy and compliance within the EU.

For more details, refer to the Jupyter Notebooks or contact me directly for any queries regarding the research.

