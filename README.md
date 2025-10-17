# Breast Cancer Prognosis-AI Campus

This project goes over **survival prediction** using real-world **cancer registry data**, by using techniques in data cleaning, feature selection, and advanced machine learning modeling tailored for **time-to-event data**.

---

## Project Description

Breast cancer remains a leading cause of cancer-related death. Identifying patients at high risk of poor outcomes is vital for personalized clinical intervention and improving survival rates.

This project focuses on predicting **breast cancer survival** using clinical data derived from the **Surveillance, Epidemiology, and End Results (SEER) cancer registry**. The dataset includes crucial prognostic factors such as **age, tumor size, lymph node status, and hormone receptor status (ER/PR status)**.

Unlike traditional classification, **survival prediction** is a distinctive and complex machine learning task that estimates the **time to an event**, represented by `(outcome, time)` pairs (e.g., survival status and survival months).

The primary objectives are:

1.  Develop a robust prognostic model using advanced machine learning techniques, such as **survival XGBoost** and **survival random forest**, to accurately predict survival probabilities at various time points.
2.  Interpret the models and findings, with feature importance explained using state-of-the-art methods like **survSHAP**.

---

## Dataset Information

The data utilized in this project is sourced from the **SEER program** of the National Cancer Institute, which provides comprehensive information on cancer statistics in the United States.

| Metric | Detail |
| :--- | :--- |
| **Source** | SEER Cancer Registry |
| **Patients** | 400,000+ |
| **Features** | 28 |
| **Included Features** | Demographic (age, race, marital status) and Prognostic factors (T/N/A stages, tumor grade/size, differentiation, ER/PR status, number of nodes examined/positive) |
| **Outcomes** | Survival status and Survival months |

**Dataset Source:**

* For the original, comprehensive SEER data, access can be requested through: `https://seerdataaccess.cancer.gov/seer-data-access`


---

## References and Suggested Reading

### Original Publications

* Grootes, Isabelle, et al. "An updated PREDICT breast cancer prognostic model including the benefits and harms of radiotherapy." *NPJ Breast Cancer* 10.1 (2024): 6.
* Sonabend, Raphael, et al. "mlr3proba: an R package for machine learning in survival analysis." *Bioinformatics* 37, no. 17 (2021): 2789-2791.

### Other Useful Publications/Materials

* PREDICT Breast cancer website: `https://breast.predict.cam/`
* The mlr3 R package: `https://mlr3.mlr-org.com/`
* Spooner, Annette, et al. "A comparison of machine learning methods for survival analysis of high-dimensional clinical data for dementia prediction." *Scientific reports* 10.1 (2020): 20410.
* Krzyziński, M., et al. "SurvSHAP (t): time-dependent explanations of machine learning survival models." *Knowledge-Based Systems*, 262, p.110234 (2023).

---

## Project Prepared By

* **Pei-Chen Peng, PhD** - Assistant Professor of Computational Biomedicine, Cedars Sinai Medical Center
* **Yi-Wen Hsiao, PhD (he/him)** - Postdoctoral Scientist of Computational Biomedicine, Cedars Sinai Medical Center
