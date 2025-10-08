```markdown
# Mental Health in Tech: Big Data & Machine Learning Insights

Data-driven insights aren’t just numbers—they’re the key to unlocking better mental well-being for tech professionals worldwide. 🧠

---

## Overview

Mental health challenges are widespread in the tech industry, yet often under-discussed. This project analyzes a large-scale mental health survey of 1,200+ tech professionals using big data analytics and machine learning to uncover critical insights about burnout, anxiety, and workplace well-being.

### Highlights
- 🔹 PySpark & MLlib — Scaled data processing and built classification models to identify risk factors based on workplace pressure, demographics, and remote work effects.
- 🔹 Pandas & NumPy — Cleaned and engineered features from diverse survey data for effective model training.
- 🔹 Tableau Visualizations — Interactive dashboards illustrating correlations between work culture, stigma, and mental health outcomes.
- 🔹 Data-Driven Recommendations — Actionable strategies for improving mental health support tailored to tech employees’ unique needs.

> “Data-driven insights aren’t just numbers—they’re the key to unlocking better mental well-being for tech professionals worldwide.”

---

## Tech Stack

- Big Data Analytics, Machine Learning
- PySpark (Spark MLlib), Pandas, NumPy
- Tableau for interactive dashboards
- Python 3.10+

---

## Repository Structure

```
.
├─ data/
│  ├─ raw/                 # Original survey data (anonymized)
│  ├─ processed/           # Cleaned & feature-engineered datasets
│  └─ README.md            # Data dictionary / source notes (add here)
├─ notebooks/              # EDA, feature engineering, experiments
├─ src/
│  ├─ data_prep.py         # Ingestion & cleaning (PySpark / Pandas)
│  ├─ features.py          # Feature engineering & encoding
│  ├─ train.py             # Model training (MLlib)
│  ├─ evaluate.py          # Metrics & explainability
│  └─ utils.py             # Helpers & config
├─ dashboards/
│  └─ tableau/             # .twb/.twbx files, exports, images
├─ reports/
│  ├─ figures/             # Plots & exports
│  └─ findings.md          # Key insights & recommendations
├─ requirements.txt
├─ config.yaml             # Paths, model params, feature flags
└─ README.md
```


---

## Methodology

- Data processing at scale with PySpark (null handling, deduplication, outlier rules).
- Feature engineering:
  - Encoded workplace pressure, managerial support, stigma perception, remote work patterns, and demographics.
  - Generated workload intensity and work-life boundary indices.
- Modeling (Spark MLlib):
  - Baselines and tree-based classifiers (Logistic Regression, Random Forest, GBT).
  - Imbalanced learning strategies (class weights, sampling).
  - Cross-validation with stratified folds and AUC/PR metrics.
- Interpretability:
  - Feature importances, SHAP-like approximations, partial dependence-style plots.
- Visualization:
  - Tableau dashboards to explore correlations, cohort differences, and trend slices.

---

## Dashboards

- Interactive Tableau
- Exports (PNGs/PDFs): see `dashboards/tableau/` and `reports/figures/`.

---

## Results & Insights

- Models surface patterns between workplace pressure, stigma, and mental health outcomes.
- Remote work effects appear nuanced; team culture and manager support moderate risk.
- The visual dashboards help leaders pinpoint high-risk cohorts and target interventions.


---

## Recommendations (Actionable Examples)

- Strengthen manager training for mental health conversations and accommodations.
- Promote flexible schedules and clear work-life boundaries.
- Offer confidential access to mental health resources and normalize usage.
- Measure stigma reduction through periodic pulse checks and policy clarity.


---

## Ethics, Privacy, and Scope

- This project is for research and organizational well-being strategy only and is not medical advice.
- All data should be anonymized; review privacy and consent before analysis.
- Monitor for bias across demographic groups; validate fairness of models and recommendations.

---

## Skills

Big Data Analytics · Machine Learning · PySpark · Pandas · NumPy · Tableau · Data Visualization · Mental Health Awareness
