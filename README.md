# IBM_Attrition_Analysis

Employees are the cornerstone of any organization. The organization's success heavily relies on its workforce's caliber. Challenges arising from employee attrition include:

1. The financial and time cost of training new hires.
2. Departure of seasoned professionals.
3. A dip in productivity.
4. Impact on profits.

Before delving into the data, it's essential to define the business objectives clearly. A well-articulated problem statement is key to ensuring the solutions developed are relevant and effective.

Key business questions to consider:

1. Which factors contribute most to employee attrition?
2. What strategies should the company adopt to retain its staff?
3. What is the tangible business value provided by the model?
4. Which department or unit is most affected by attrition?
   
I began by addressing missing values and redundant features in the dataset to uphold data quality. An in-depth exploratory data analysis revealed intricate patterns. Utilizing the Chi-Square Test, I discerned the impact of categorical features on employee attrition.

To counteract the data's imbalance, I applied the SMOTE technique, emphasizing oversampling the minority class, and optimized model parameters. Knowing that relying solely on accuracy might be deceptive, I turned to metrics such as Precision, Recall, F-1 Score and AUC ROC for a comprehensive assessment. The finalized model achieved an 87% accuracy and an AUC score of 0.70. Using feature importance, I derived key insights and formulated actionable recommendations to proactively address employee attrition.

For the dashboard, please refer to:
https://public.tableau.com/app/profile/kaixin.yang/viz/HRAttritionAnalysisDashboard_16987962110410/HRAnalyticsDashboard
