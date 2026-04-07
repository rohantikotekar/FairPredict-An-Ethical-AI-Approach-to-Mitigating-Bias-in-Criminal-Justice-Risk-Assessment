# FairPredict
### An Ethical AI Approach to Mitigating Bias in Criminal Justice Risk Assessment

---

## Problem

AI tools like COMPAS are used across the U.S. criminal justice system to predict recidivism risk — influencing bail, sentencing, and parole decisions. Studies have shown these tools disproportionately flag Black defendants as high-risk, even when controlling for actual reoffending rates. The root cause is historical training data that encodes decades of systemic bias. When that data feeds a model, the model doesn't just reflect bias — it amplifies it at scale.

---

## Solution

FairPredict is a fairness-aware machine learning pipeline built to detect and reduce racial and demographic bias in recidivism prediction. Rather than treating accuracy as the only goal, it explicitly optimizes for both predictive performance and fairness — measuring outcomes across demographic groups using established metrics like **demographic parity**, **equalized odds**, and **disparate impact**.

---

## Implementation

- **Dataset:** COMPAS recidivism dataset (ProPublica)
- **Bias Detection:** Disparate impact analysis across race and gender subgroups
- **Mitigation Techniques:**
  - Pre-processing: Dataset reweighing and resampling
  - In-processing: Fairness-constrained model training
  - Post-processing: Threshold adjustment per demographic group
- **Fairness Metrics:** Demographic parity, equalized odds, equal opportunity
- **Models:** Logistic Regression, Random Forest, evaluated with fairness-accuracy tradeoff analysis
- **Toolkit:** IBM AI Fairness 360 (AIF360), scikit-learn, Python

---

## Future Goals

- Extend bias mitigation to intersectional subgroups (e.g., race × gender)
- Benchmark against additional criminal justice datasets beyond COMPAS
- Build an explainability layer so predictions are interpretable by judges and attorneys
- Explore real-time bias monitoring for deployed models
- Contribute findings toward policy recommendations for ethical AI use in public sector decisions

---

> *FairPredict is a research project. It is not intended for deployment in real-world criminal justice settings without extensive legal, ethical, and domain expert review.*
