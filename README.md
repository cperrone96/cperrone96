# Hi, I'm Christina 👋

**Data scientist with a lab-science background.** I build machine learning models, statistical analyses and marketing measurement systems in Python, R and SQL. Before data science I spent six years in clinical and research labs, including Phase I–III assay development at Pfizer, and contributed to four peer-reviewed neuroscience papers.

I run [Data Design Dynamics](https://datadesigndynamics.org), a data, analytics and AI studio, where I build GA4 and BigQuery reporting, Google Ads measurement and AI agent workflows with human-in-the-loop review. Before that I led operations and analytics for a medical device distributor, helping grow gross sales from $2M to $8M.

### ⭐ Flagship projects

- **[CKD Launch Intelligence](https://github.com/cperrone96/ckd-launch-intelligence)**: chronic kidney disease analysis on public NHANES, MEPS, and ClinicalTrials.gov data. It covers survey-weighted prevalence (13.9% of US adults show the CKD lab marker), a risk model selected by a declared rule inside nested cross-validation (ROC-AUC 0.779; screening the top 10% finds cases at 3.1× the base rate), and a spending analysis, served through typed APIs with a dashboard. Adding 22 more predictors, including HbA1c and hemoglobin, raises plain logistic regression from 0.771 to 0.792 (paired 95% CI +0.014 to +0.027).
- **[Marketing Measurement Decision Studio](https://github.com/cperrone96/marketing-measurement)**: GA4 funnel, cohort and multi-touch attribution analysis on Google's public ecommerce sample, with self-referral correction and a buyer-propensity model validated forward in time (ROC-AUC 0.811 vs 0.720 for a returning-visitor rule), served through an evidence dashboard.

### 📈 Machine learning and forecasting

- **[Hospital Readmission Prediction](https://github.com/cperrone96/hospital-readmission-prediction)**: 30-day readmission risk on 99,343 encounters from 130 US hospitals with a patient-disjoint split. Gradient boosting (ROC-AUC 0.675) beats logistic regression (0.664), is well calibrated, and drives a decision-curve-based triage rule for care-management calls. On the same test patients it beats a LACE-style clinical readmission score (0.553) by +0.122 (95% CI +0.106 to +0.137).
- **[Medical-Sales Churn & Revenue Forecasting](https://github.com/cperrone96/medical-sales-churn-forecasting)**: account churn model (ROC-AUC 0.79; top decile at 2.9× the base churn rate) with a retention-value analysis, and a revenue forecast chosen by rolling-origin backtest (6.2% holdout MAPE), on synthetic B2B medical-device data.
- **[Weather Time-Series Forecasting](https://github.com/cperrone96/weather-time-series-forecasting)**: SARIMAX on seven years of NOAA data, tested on 359 forecast origins. It cuts one-day-ahead error 17% against climatology and beats persistence at every horizon.
- **[SpaceX Falcon 9 Landing Prediction](https://github.com/cperrone96/Space-Race-Project)**: IBM capstone rebuilt with leaky features removed, nested cross-validation and a next-flight test.
- **[Laptop Pricing Analysis](https://github.com/cperrone96/Laptop-Pricing-Analysis)**: price model with grouped nested cross-validation (random forest RMSE $348 vs a $576 baseline) and conformal prediction intervals.

### 🧫 Biostatistics and life sciences

- **[Clinical-Trial Survival Analysis](https://github.com/cperrone96/clinical-trial-survival-analysis)**: Kaplan-Meier, log-rank and Cox models with time-varying effects on the GBSG2 breast-cancer trial (686 patients), plus external validation of a model built on 1,546 Rotterdam patients (Uno's C 0.680, observed/expected risk 1.03). Hormone therapy HR 0.71 (95% CI 0.55–0.92); Python and R agree to six significant digits.
- **[Differential Gene Expression](https://github.com/cperrone96/differential-gene-expression)**: PyDESeq2 and Welch testing benchmarked on simulated RNA-seq experiments with known truth at 3, 6 and 12 replicates per group, with a recommended configuration at each sample size that keeps false discoveries under 5%.
- **[Dose-Response IC50 Analysis](https://github.com/cperrone96/dose-response-ic50-analysis)**: four-parameter logistic fits whose 95% intervals cover the true IC50 95.0% of the time across 100 simulated plates, with matching Python and R implementations.
- **[Experimental Design & Inference](https://github.com/cperrone96/experimental-design-inference)**: power analysis, ANOVA and Holm, Dunnett and Tukey comparisons, with error rates checked across 10,000 simulated studies.

### 🗺️ Other projects

- **[Geospatial Crime Mapping](https://github.com/cperrone96/geospatial-crime-mapping)**: interactive Folium maps and incident-level summaries of San Francisco crime data.
- **[Web Design Demos](https://github.com/cperrone96/web-design-demos)**: responsive multi-page marketing sites for three demo local-service businesses.

### 🔧 Tools

`Python` · `pandas` · `NumPy` · `scikit-learn` · `statsmodels` · `SciPy` · `PyDESeq2` · `R` · `SAS` · `SQL` · `BigQuery` · `Google Analytics 4` · `Google Ads` · `Jupyter` · `matplotlib` · `Plotly / Dash` · `Folium` · `pytest` · `Git`

### 🎓 Certifications and education

- [Google Ads Search Certification](https://www.credential.net/0ddccc03-29ff-4fe1-9c92-a6f40ef8ac0e) (2026)
- [Google Analytics Certification](https://www.credential.net/aca85107-be71-45f2-b952-16666f420b9c) (2026)
- [Google Cloud skill badges](https://www.credly.com/users/christina-perrone.776ce583): Implement Cloud Security Fundamentals on Google Cloud, Secure Software Delivery, Develop Serverless Applications on Cloud Run (2026)
- IBM Data Science Professional Certificate (2025)
- BS in Neurobiology, University of California, Irvine
- Google Developer Program member

📫 [LinkedIn](https://www.linkedin.com/in/christina-perrone-) · **admin@datadesigndynamics.org**
