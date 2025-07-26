This is a Research project that I completed during CS 212 Data Science Ethics at UC Riverside. It focuses on reducing the prevalent bias in COMPAS Dataset. Following is the resume description.

## 🧠 Purpose

Analyze and reduce algorithmic bias in the COMPAS dataset—used in criminal justice risk assessment—through responsible data science practices, including:
Ethical auditing of risk prediction outcomes
SMOTE for resampling underrepresented groups
Threshold tuning for parity in predictions
Fairness-aware training using Exponentiated Gradient Reduction

## 🔄 Steps:

Bias Identification
Analyzed COMPAS predictions across race and gender groups.
Identified significant disparities in false positive rates and predictive parity.
Class Imbalance Handling (SMOTE)
Applied SMOTE to synthetically balance classes.
Improved minority group representation in training data by 12%.
Threshold Adjustment
Tuned decision thresholds separately per demographic group.
Reduced the false positive gap across groups by 10%.
Fairness-Aware Optimization
Used Exponentiated Gradient Reduction to optimize for fairness.
Achieved 5% boost in demographic parity with <1% accuracy loss.
Post-Mitigation Monitoring
Evaluated and tracked fairness metrics:
Equalized Odds
Predictive Parity
Ensured ethical compliance throughout the pipeline.

## 🧰 Tech Stack

Python – Data processing & model development
Jupyter Notebook – Experimentation & visualization
Pandas, NumPy, Scikit-learn – Data wrangling & ML
Imbalanced-learn – SMOTE resampling
Fairlearn – Fairness optimization & evaluation
Matplotlib / Seaborn – Visualizations

## 📈 Impact

⚖️ Significantly reduced racial bias in risk predictions
📉 Lowered false positive rate disparity by 10%
📊 Improved demographic parity without sacrificing model performance
🔍 Reinforced accountability in criminal justice AI tools

## 🧩 Future Improvements

Incorporate counterfactual fairness analysis
Build real-time fairness dashboards
Extend research to other high-stakes domains like hiring or lending



