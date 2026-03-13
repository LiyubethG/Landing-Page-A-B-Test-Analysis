📊 Landing Page A/B Test Analysis
📌 Project Overview
This project analyzes the results of an A/B experiment on a landing page to evaluate how different page versions influence user behavior and business performance.
The analysis focuses on identifying which version of the page performs better in terms of:
•	Conversion rate
•	Average spending per converted user
•	Traffic source effectiveness
•	Differences between new and returning users
The goal is to translate statistical results into actionable business insights that can help optimize marketing strategy and user acquisition.

🎯 Business Questions
The analysis aims to answer the following key questions:
•	Which page version (A or B) generates a higher conversion rate?
•	Which version generates a higher average spend per converted user?
•	Which traffic channels are most effective at generating conversions?
•	Are there significant differences between new and returning users?
•	What business recommendations can improve marketing performance?

🧪 Experiment Design
An A/B test was conducted where users were randomly exposed to one of two landing page versions:
•	Page A → Original version
•	Page B → Alternative version with design/content variations
User interactions were tracked including:
•	Page version viewed
•	Conversion (purchase or desired action)
•	Amount spent
•	Traffic source
•	User type (new vs returning)

📂 Dataset
The dataset includes user-level observations with variables such as:
Variable	Description
user_id	Unique user identifier
page_version	Landing page version (A or B)
converted	Whether the user completed the desired action
amount_spent	Amount spent by converted users
traffic_source	Acquisition channel (Organic, Ads, Referral)
user_type	New or Returning user

🔎 Methodology
The analysis includes several steps:
1️⃣ Data Cleaning
•	Handling missing values
•	Validating data consistency
•	Preparing variables for analysis
2️⃣ Exploratory Data Analysis (EDA)
•	Conversion rate by page version
•	Average spending analysis
•	Traffic source segmentation
•	User type comparison
3️⃣ Statistical Testing
To validate whether observed differences are statistically significant:
•	Two-proportion Z-test → Compare conversion rates between page versions
•	T-test for independent samples → Compare average spending between page versions
These tests help determine whether differences are due to actual effects or random variation.

📊 Key Findings
Page Performance
•	Page B generated a higher average spending per converted user compared to Page A.
•	Statistical testing suggests this difference is statistically significant, indicating that page design may influence purchase value.
Conversion Rate
•	Conversion rates differ between the two page versions.
•	The statistical test indicates that page design impacts the likelihood of conversion.
Traffic Sources
•	Organic traffic produced the highest number of conversions, suggesting strong user intent.
•	Paid ads also contributed significantly, while referral traffic showed lower conversion impact.
User Type
•	Conversion rates between new and returning users showed only minor differences.
•	Statistical testing suggests the difference is not significant, meaning both user groups behave similarly in this experiment.

💡 Business Recommendations
Based on the analysis, the following strategic recommendations can be made:
1️⃣ Consider implementing Page B
Page B shows stronger revenue potential due to higher average spending per converted user.
2️⃣ Invest in organic acquisition channels
Organic traffic demonstrates strong conversion potential, suggesting SEO and content marketing should be prioritized.
3️⃣ Optimize paid advertising campaigns
Paid traffic contributes meaningfully to conversions and may benefit from improved targeting and campaign optimization.
4️⃣ Continue experimentation
Further A/B testing could explore:
•	Page layout improvements
•	Messaging optimization
•	Personalized experiences for different traffic sources

🛠 Tools & Technologies
•	Python
•	Pandas
•	NumPy
•	Matplotlib / Seaborn
•	SciPy
•	Jupyter Notebook

