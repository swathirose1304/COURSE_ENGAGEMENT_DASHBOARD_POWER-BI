# COURSE_ENGAGEMENT_DASHBOARD_POWER-BI

![image](https://github.com/user-attachments/assets/2354d064-f0bd-40e6-9fb7-247afa676ff7)

![image](https://github.com/user-attachments/assets/aaea7dc5-0d8a-4aa2-837d-08db5e520995)

# 📊 Employee Training Analytics Dashboard

This project provides an interactive dashboard to analyze employee training completion rates, quiz performance, and engagement trends. The goal is to identify stores with poor completion rates, highlight challenging courses, and pinpoint specific quiz sections that need improvement.

## 🚀 Features

### 🔹 Store-Level Analysis
- **Identifying Stores with Poor Course Completion Rates**  
  - A table visual filters stores where `avg_completion_percentage < 50%`.
  - Drill-through functionality on `store_id` dynamically displays the corresponding `manager_name`, enabling targeted interventions.

### 🔹 Course Difficulty Analysis
- **Detecting Difficult Courses**  
  - A bar chart visualizes `course_name` vs. `course_completion_percentage`.
  - Tooltips classify courses into `"Easy"`, `"Moderate"`, or `"Tough"` based on calculated difficulty.
  - Helps in adjusting course content to enhance learning experiences.

### 🔹 Quiz Performance & Engagement
- **Finding the Most Challenging Quiz Sections**  
  - Quiz data is parsed from JSON format for detailed insights.
  - A column chart plots `CorrectAnswerPercentage` for `course_name` and `quizcard_id` to detect difficult sections.
  - Another chart tracks `HighAttemptsPercentage` to identify confusing quiz cards.
  - Engagement trends are analyzed using `time_to_complete_in_days`, helping detect boring or difficult sections.

## 🛠️ Technologies Used
- **Power BI** for data visualization
- **SQL** for data extraction and transformation
- **Python**  for JSON parsing and data processing
- **ETL Pipelines** to preprocess training data

