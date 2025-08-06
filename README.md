# FUTURE_DS_03
Task 3 of Future Intern: Student Feedback Analysis

This repository hosts the Student Feedback Analysis Dashboard for FutureIntern Internship Task 3, built in a Jupyter Notebook using Python (pandas, matplotlib, seaborn). It analyzes student_feedback.csv to visualize course satisfaction, dissatisfaction areas, event type differences, and course structure impacts.

Dataset

File: student_feedback.csv (~1001 rows)

Columns: Student ID, 8 ratings (1–10): Well versed with subject, Explains concepts, Use of presentations, Assignment difficulty, Solves doubts, Course structure, Support for advanced students, Course recommendation

Key Metrics

Avg Satisfaction: Mean of all ratings per course
Low Ratings: Count of ratings ≤4 per metric
High Recommendations: Courses with recommendation ≥8
Correlation: Pearson correlation between metrics

Visualizations

Top 3 Courses (Bar Chart): Top 3 courses by avg satisfaction.
Dissatisfaction Areas (Bar Chart): Frequency of low ratings (≤4).
Recommendation by Event Type (Bar & Scatter): Compares Seminar-like (presentations ≥7) vs. Workshop-like (<7) recommendations.
Course Structure Impact (Pie Chart): High recommendations by course structure (department proxy).
Satisfaction Distribution (Histogram): Spread of avg satisfaction scores.
Rating Distribution (Box Plot): Variability and outliers per metric.
Metric Correlations (Heatmap): Pairwise correlations between ratings.
High vs. Low Recommendations (Stacked Bar): Proportions by event type.
Recommendation Distribution (Violin Plot): Score distributions by event type.

Assumptions

Courses identified by Student ID
Low ratings (≤4) proxy for complaints
Use of presentations ≥7 for Seminar-like, <7 for Workshop-like
Course structure proxies for department
