# Decision-Tree-Ensemble-Trading-Models-with-Exploratory-Tip-Analytics
Weekly-Return Classification & Trading

Decision Tree: Train on 2021 weekly features (μ, σ), predict 2022 labels, report accuracy, confusion matrix, TPR/TNR, and compare a label-based trading strategy to buy-and-hold.

Random Forest: Grid-search N (1-10) and depth d (1-5), plot 2022 error rates, select the optimal model, evaluate confusion matrix plus TPR/TNR, and assess its trading performance.

AdaBoost: For λ = 0.5 and 1, pair three base estimators, vary learners N (1-15), plot error curves, identify the best estimator/ N*, measure accuracy, and contrast an AdaBoost-driven strategy with buy-and-hold.

Tip-Behavior Exploration (tips.csv)

Compute tip percentages by meal time and by weekday.

Identify the highest-tipping day/time.

Quantify correlations: meal price vs tip, group size vs tip, and smoker status effects.

Examine temporal tip trends within each day.
