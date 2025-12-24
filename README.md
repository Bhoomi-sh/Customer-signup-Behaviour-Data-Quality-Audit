# Customer Sign-Up Behaviour & Data Quality Audit

## 📌 Project Overview
This project analyzes customer sign-up behaviour and evaluates data quality for a fast-growing SaaS organization (Rapid Scale). The objective is to support the Business Intelligence (BI) team by identifying data quality issues and uncovering actionable insights related to customer acquisition, subscription preferences, and marketing engagement.

The analysis focuses on improving reporting reliability and enabling better decision-making for marketing, onboarding, and customer engagement teams.

---

## 🎯 Project Objectives
- Conduct a **data quality audit** to identify missing values, inconsistencies, and duplicate records
- Analyze **customer sign-up patterns** across acquisition sources, regions, age groups, and subscription plans
- Provide **business insights and recommendations** to improve data capture and marketing effectiveness

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- CSV datasets
- Data Cleaning & Exploratory Data Analysis (EDA)

---

## 📂 Datasets Used
- **Customer Sign-Up Dataset**  
  Includes demographics, sign-up date, acquisition source, region, subscription plan, and marketing opt-in status
- **Support Tickets Dataset** (contextual reference)

---

## 🧹 Data Cleaning Summary
The datasets were cleaned to ensure accuracy and consistency before analysis:
- Converted `signup_date` into proper date format for time-based analysis
- Standardized categorical fields such as source, region, gender, and plan_selected
- Removed duplicate customer records based on `customer_id`
- Handled missing values by replacing blanks with consistent labels (e.g., “Unknown”)
- Aligned subscription plans into standardized categories (Basic, Pro, Premium)

Although data quality improved significantly, some missing demographic data remains and is addressed in the recommendations.

---

## 📊 Key Findings & Insights
- **User Acquisition**: YouTube and Google are the strongest acquisition channels, driving the majority of new sign-ups
- **Regional Trends**: The North and East regions show high sign-up volume, but the East region has the highest proportion of incomplete records
- **Subscription Preferences**: The Premium plan is the most popular subscription choice
- **Age & Marketing Opt-in**:
  - Older users are more likely to opt in to marketing communications
  - Younger users rely more on social media and peer-driven discovery
- **Data Quality**: Missing demographic fields and inconsistent plan labels pose risks to reporting accuracy

---

## ❓ Business Questions Answered
1. **Which acquisition source brought in the most users last month?**  
   Google was the top-performing source in the most recent full month.

2. **Which region shows signs of missing or incomplete data?**  
   The East region had the highest proportion of incomplete records (~21%).

3. **Are older users more or less likely to opt in to marketing?**  
   Older users are more likely to opt in compared to younger users.

4. **Which plan is most commonly selected, and by which age group?**  
   The Premium plan is most popular, especially among the 25–34 age group.

---

## 💡 Business Recommendations
- Increase investment in high-performing channels such as YouTube and Google
- Improve data capture by enforcing mandatory fields and validation rules, especially in regions with high missing data
- Segment marketing strategies by age group:
  - Use email and newsletters for older users
  - Use social media, app notifications, and influencers for younger users
- Standardize data entry through controlled dropdowns and validation checks

---

## ⚠️ Data Risks & Limitations
- Inconsistent plan naming can cause misreporting if not standardized
- Missing demographic data limits accurate segmentation
- Marketing opt-in data may underrepresent younger users

---

## 📁 Repository Contents
- Jupyter Notebook (`.ipynb`) – data cleaning and analysis
- Cleaned datasets (`.csv`)
- Project Report (`.pdf`)
- Visualizations and charts

---

## 👤 Author
**Bhoomi Sharma**  
Data Analytics Project – Week 1  
Customer Sign-Up Behaviour & Data Quality Audit
