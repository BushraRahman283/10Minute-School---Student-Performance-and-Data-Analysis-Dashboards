# 10Minute-School---Student-Performance-and-Data-Analysis-Dashboards
📊 10Minute School - Student Performance and Data Analysis Dashboards
This Power BI project presents a comprehensive data analysis of student performance on the 10 Minute School platform. The goal was to uncover patterns in student engagement, academic trends, and rank movement through interactive and insight-driven dashboards. The project highlights the effectiveness of data-driven strategies for improving educational outcomes.

🧠 Project Objective
The objective of this project was to design and build four interactive dashboards that visualize and analyze:

Attendance trends across exams and over time

Rank distribution and frequency of top performers

Performance improvement or decline patterns

Exam-wise pass rates and student growth metrics

This analysis provides actionable insights for both educators and administrators to make informed decisions regarding student support and academic planning.

📁 Data Sources
The project used multiple structured tables containing:

Exam metadata and schedules

Student scores and pass/fail status

Top 5 ranked students per exam

Attempt-wise performance for each student

The data model involved relationships between student IDs, exam names, and attempt records to ensure accurate aggregation and filtering across all visuals.

📊 Dashboards Overview
1. Attendance Trend Dashboard
Visualizes attendance counts over time and across exam types.

Identifies peak and low participation periods.

Helps highlight engagement patterns and potential drop-off points.

Used time-based visualizations and custom DAX measures for attendance aggregation.

2. Top 5 Ranks Dashboard
Highlights students who consistently place in the top 5 across different exams.

Measures the frequency of top 1 rankings to track elite performance.

Calculates the number of students who are not receiving ranks, signaling a need for academic support.

Utilized calculated measures to quantify rank distribution.

3. Performance Trend Dashboard
Analyzes student performance trends: improved, declined, or unchanged.

Visualizations break down these trends by exam name and performance status.

Identifies exams where a large portion of students are declining.

Measures performance shifts and aggregates them into categorized insights.

4. Rank Analysis Dashboard
Tracks improvement between exam attempts for individual students.

Displays pass rates by exam date and exam name to monitor consistency.

Highlights the maximum improvement made by any student across all attempts.

Reveals the top improver (student with the greatest positive score change).

Combines time-series analysis with student-level progression metrics.

🧮 Key Technical Work
Developed a relational data model with multiple tables connected through student and exam identifiers.

Created custom DAX measures to track performance trends, rank distributions, improvements, and attendance dynamics.

Used KPI cards, bar/line/pie charts, tables, and filters/slicers for dynamic, drillable dashboard experiences.

Applied row-level filtering, aggregate functions, and logical conditions to extract deeper insights from raw data.

📌 Insights Uncovered
A significant drop in attendance and pass rate was observed from February to April.

A small group of students consistently achieve top ranks; others require intervention.

Over half of the students experienced a performance decline across multiple exams.

Some students show strong improvement across attempts, signaling the effectiveness of retries or revised study strategies.

🚀 Recommendations & Next Steps
Introduce intervention plans for students showing consistent decline.

Gamify progress and create peer mentorship around top performers.

Use attendance data to redesign academic calendars and reduce fatigue.

Expand dashboards to include learning content interaction and quiz analytics.

This project demonstrates how Power BI can transform raw educational data into actionable academic intelligence. By leveraging DAX and data modeling, this analysis equips 10 Minute School with tools to make performance-driven decisions and improve student outcomes at scale.
