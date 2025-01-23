Personalized Student Recommendations

Project Overview
This project aims to provide personalized recommendations for students to improve their quiz preparation. Using historical and current quiz performance data, we identify weak areas, analyze performance trends, and propose actionable steps for improvement. The solution also highlights specific strengths and weaknesses while creating student personas based on data insights.

The project is built to analyze quiz data, generate detailed insights, and recommend tailored learning strategies for students preparing for competitive exams like NEET.

Dataset Description
We worked with two datasets:

Current Quiz Data:

Details of a user’s most recent quiz submission.
Includes information about questions, topics, responses, and scores.
Historical Quiz Data:

Performance data from the last five quizzes for each user.
Contains scores, response accuracy, and a response map linking question IDs to selected options.
The data allowed us to examine student performance by topics, accuracy, and trends over time.

Steps for Setup and Execution
Prerequisites
Python 3.10 or above.
Libraries required: pandas, matplotlib, and other dependencies listed in the requirements.txt file.

Outputs will include:
Detailed insights into performance.
Visualizations of weak areas and trends.
Personalized recommendations for students.
Approach to Analysis, Insights, and Recommendations
Analysis
Data Cleaning: Handled missing values and converted data types for accurate analysis.
Schema Exploration: Examined relationships between quizzes, topics, and responses.
Performance Trends: Analyzed cumulative performance over time and identified patterns.
Insights
Weak Areas: Topics with below-average accuracy or scores.
Trends: Identified topics and response accuracy improvements over time.
Performance Gaps: Highlighted areas where students consistently underperform.
Recommendations
Suggested topics to focus on, based on weak areas.
Proposed improvements for response accuracy.
Identified areas of strength to boost student confidence.
Key Takeaways
Actionable Insights: The project provides clear recommendations tailored to each student's performance.
Student Personas: Based on data, students are classified into personas like "Accuracy Focused" or "Time-Efficient" to personalize strategies further.
Data-Driven Decisions: Visualization and analysis make the recommendations easy to understand and implement.

Screenshots are in repo itself.

Performance by Topics:

User Trends Over Time:

Weak Topics Insights:
Overall Accuracy: 72.21%
Overall Score: 60.29

Weak Topics:
                                      topic  Avg_Accuracy  Avg_Score  \
2                        Human Reproduction          38.0       40.0   
3                       Reproductive Health          43.0       52.0   
4              Respiration and Gas Exchange          66.0       24.0   
7  principles of inheritance and variation           30.0       12.0   

Contribution
Contributions and suggestions are welcome! Please feel free to raise an issue or create a pull request.

License
This project is licensed under the MIT License.

