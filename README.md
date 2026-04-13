# Dempsey Center Client Survey Analysis (2022–2025)

## Overview
This project analyzes client survey data from the Dempsey Center across four years (2022–2025). The goal is to understand client satisfaction, service usage patterns, and key factors that influence outcomes.

The analysis goes beyond descriptive statistics by applying machine learning and statistical methods to identify drivers of satisfaction and uncover hidden client segments.

---

## Key Findings
- Visit frequency is the strongest predictor of satisfaction
- Demographics do not significantly impact satisfaction
- Three distinct client segments were identified using clustering
- A small group of clients shows low benefit and requires targeted intervention

---

## Repository Structure

Dempsey-Project/
│
├── data/                # Survey data (2022–2025)
├── notebook/            # Jupyter notebook for analysis
├── report/              # Final written report (PDF)
├── slides/              # Presentation slides
├── requirements.txt     # Python dependencies
└── README.md

---

## How to Run

1. Clone the repository:
   git clone <your-repo-link>
   cd Dempsey-Project

2. Install dependencies:
   pip install -r requirements.txt

3. Open the notebook:
   jupyter notebook

4. Run all cells to reproduce results.

---

## Methods
- Correlation Analysis
- Decision Tree
- K-Means Clustering (k=3)
- Chi-Square Test

---

## Reproducibility
All results can be reproduced by running the notebook with the provided dataset.  
Data preprocessing, modeling, and analysis steps are included.

---

## Limitations
- No unique client ID (cannot track individuals across years)
- Binary encoding of service usage (no intensity)
- Class imbalance in satisfaction levels
- Survey-based self-selection bias

---

## Future Work
- Build predictive models for client retention
- Introduce longitudinal tracking
- Test intervention strategies (A/B testing)
- Integrate operational data (e.g., wait times)

---

## Authors
- Yuchen Kuang
- Lingyun Chen

---

## Course
Northeastern University CS5100