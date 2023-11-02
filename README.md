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

Key Insights from the XGBoost Model:

1.OverTime: Frequent overtime may lead to employee burnout and higher attrition.
2.Total Working Years: Longer working years might indicate career stagnation or a desire for change.
3.Environmental Satisfaction: Workplace alignment with employee values boosts retention.
4.Job Satisfaction & Role: Specific roles may be stressful, and overall job dissatisfaction can lead to attrition.
5.Work-Life Balance: Employees seeking better work-life balance might consider changing jobs.
6.Training and Development: Inconsistent training can either overwhelm or make employees feel neglected.
7.Stock Options & Job Involvement: Better stock options can retain employees, and their connection to their role affects retention.
8.Age & Manager Tenure: Longer tenure with a manager or age might spur a desire for change.
9.Other Factors: Departments, travel frequency, education, and marital status can subtly influence retention decisions.

Employee Engagement and Retention Recommendations:

1. OverTime: Implement flexible hours and compensate for overtime. Regular well-being check-ins for those working extra.
2. Total Working Years: Facilitate career growth or role changes for tenured employees. Hold internal "career exploration" events.
3. Environment: Seek continuous feedback on workspace. Empower committees for environment enhancement.
4. Job Satisfaction & Role: Regular role satisfaction checks. Offer job rotation for those seeking diversity.
5. Work-Life Balance: Foster a culture of balance. Introduce remote or flexi-hours.
6. Training: Customize training frequency. Ensure relevance to current roles.
7. Stock Options & Involvement: Review stock plans for competitiveness. Reinforce company vision regularly.
8. Age & Manager Tenure: Propose mentorship for experienced employees. Rotate teams for diverse managerial experiences.
9. Other Factors: Balance business travel. Foster inter-departmental collaborations. Host preference-based workshops.
    
For the dashboard, please refer to:
https://public.tableau.com/app/profile/kaixin.yang/viz/HRAttritionAnalysisDashboard_16987962110410/HRAnalyticsDashboard
