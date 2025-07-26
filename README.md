# FairPredict- An Ethical AI Approach to Mitigating Bias in Criminal Justice Risk-Assessment

This is a Research project that I completed during CS 212 Data Science Ethics at UC Riverside. It focuses on reducing the prevalent bias in COMPAS Dataset. Following is the resume description.

## 🧠 Purpose

Analyze and reduce algorithmic bias in the COMPAS dataset—used in criminal justice risk assessment—through responsible data science practices, including:
  1. Ethical auditing of risk prediction outcomes
  2. SMOTE for resampling underrepresented groups
  3. Threshold tuning for parity in predictions  
  4. Fairness-aware training using Exponentiated Gradient Reduction

## 🔄 Steps:

  1. Bias Identification
  2. Analyzed COMPAS predictions across race and gender groups.
  3. Identified significant disparities in false positive rates and predictive parity.
  4. Class Imbalance Handling (SMOTE)
  5. Applied SMOTE to synthetically balance classes.
  6. Improved minority group representation in training data by 12%.
  7. Threshold Adjustment
  8. Tuned decision thresholds separately per demographic group.
  9. Reduced the false positive gap across groups by 10%.
  10. Fairness-Aware Optimization
  11. Used Exponentiated Gradient Reduction to optimize for fairness.
  12. Achieved 5% boost in demographic parity with <1% accuracy loss.
  13. Post-Mitigation Monitoring
  14. Evaluated and tracked fairness metrics:
  15. Equalized Odds
  16. Predictive Parity
  17. Ensured ethical compliance throughout the pipeline.



## 🧰 Tech Stack

  1. Python – Data processing & model development
  2. Jupyter Notebook – Experimentation & visualization
  3. Pandas, NumPy, Scikit-learn – Data wrangling & ML
  4. Imbalanced-learn – SMOTE resampling
  5. Fairlearn – Fairness optimization & evaluation
  6. Matplotlib / Seaborn – Visualizations

## 📈 Impact

  1. ⚖️ Significantly reduced racial bias in risk predictions
  2. 📉 Lowered false positive rate disparity by 10%
  3. 📊 Improved demographic parity without sacrificing model performance
  4. 🔍 Reinforced accountability in criminal justice AI tools

## 🧩 Future Improvements

  1. Incorporate counterfactual fairness analysis
  2. Build real-time fairness dashboards
  3. Extend research to other high-stakes domains like hiring or lending



