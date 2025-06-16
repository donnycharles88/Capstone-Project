# 🎓 Capstone Project: Student Social Media Addiction Analysis

> *A data analysis project to explore patterns, behaviors, and impacts of social media usage among students using real-world dataset and AI-powered insights.*

---

## 📌 Project Overview

This project focuses on analyzing the extent and effects of social media addiction among students based on a comprehensive dataset that includes variables such as daily usage hours, mental health scores, academic performance, most-used platforms, and more. The goal is to uncover trends, correlations, and actionable insights to help educators, researchers, and policymakers understand digital behavior in educational environments.

Key components of this project include:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Statistical modeling
- AI-assisted interpretation using Granite from IBM via Replicate API

---

## 📁 Raw Dataset Link

The dataset used in this project can be accessed here:

🔗 [Students Social Media Addiction Dataset (CSV)](https://github.com/donnycharles88/Capstone-Project/raw/main/Students%20Social%20Media%20Addiction.csv) 

This dataset contains over 700 entries with detailed attributes such as:
- `Student_ID`, `Age`, `Gender`, `Academic_Level`
- `Country`, `Avg_Daily_Usage_Hours`, `Most_Used_Platform`
- `Mental_Health_Score`, `Addicted_Score`, and more

---

## 🔍 Insight & Findings

### Key Discoveries:
1. **High Usage Among Younger Students**
   - Students aged 18–20 show the highest average daily usage (>6 hours/day).
   - TikTok and Instagram dominate platform preference in this age group.

2. **Correlation Between Addiction and Mental Health**
   - There's a strong negative correlation (`r ≈ -0.73`) between Addicted Score and Mental Health Score.
   - Increased social media use correlates with lower sleep quality and higher stress levels.

3. **Platform Influence**
   - Users of visually-driven platforms like Instagram and TikTok report higher addiction scores compared to LinkedIn or Facebook users.

4. **Academic Impact**
   - Over 60% of respondents agree that social media negatively affects their academic performance.

5. **Regional Trends**
   - Students from Bangladesh, India, and UAE report significantly higher daily usage than those from Europe or East Asia.

---

## 🤖 AI Support Explanation

To enhance interpretability and provide deeper insight, we integrated the **IBM Granite 3.3 8B Instruct** model via **Replicate API**. This AI model was used to:
- Summarize complex findings into human-readable narratives
- Interpret statistical outputs and suggest implications
- Generate suggestions for future research or interventions

---
