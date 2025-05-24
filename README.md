# AI-Developer-Productivity
Quantify developer productivity by tracking behavior, caffeine, sleep and AI Use

About Dataset
This dataset simulates the productivity of AI developers over 500 days, capturing the subtle interaction between deep work, distractions, caffeine intake, and code quality. Designed to push the limits of machine learning, this data blends behavioral, physiological, and productivity indicators to allow for advanced predictive modeling, regression, clustering, and time-series analysis.

💡 Suggested ML Tasks
Binary classification (task_success)
Regression (e.g., predicting cognitive_load)
Clustering of work patterns
Correlation analysis & feature importance
Time series simulation & rolling averages (useful with synthetic date column)
Exploratory Data Analysis (EDA)


🧠 Inspiration
How does caffeine impact bugs in code?
Can you predict if a dev will succeed today based on distractions and AI tool use?
What’s the optimal balance between AI usage and raw coding time?

📊 Column Descriptions
Column Name	- Description
hours_coding	- Total focused hours spent on software development work (0–12 hours).
coffee_intake_mg	- Daily caffeine intake in milligrams (0–600 mg).
distractions	- Number of distractions (e.g., meetings, Slack notifications) (0–10).
sleep_hours	- Number of hours of sleep the previous night (3–10 hours).
commits	- Number of code commits pushed during the day (0–20).
bugs_reported	- Number of bugs reported in code written that day (0–10).
ai_usage_hours	- Number of hours spent using AI tools (e.g., ChatGPT, Copilot) (0–12).
cognitive_load	- Self-reported mental strain on a scale of 1 to 10.
task_success	- Target column — whether the daily productivity goal was achieved (0/1).
