# Loan Approval EDA

## Overview
This project explores a **loan approval dataset** to figure out what really matters when banks decide who gets approved. By digging into applicant details like **income, credit score, age, marital status, education, and occupation**, the analysis highlights the trends and key drivers behind approvals and rejections.

---

## Problem Questions
Some of the real-world questions explored in this project:

- What percentage of applicants actually get approved?  
- Does earning more money increase your chances of approval?  
- How much does a **credit score** really matter?  
- Are older applicants more likely to be approved than younger ones?  
- Do factors like **education level, marital status, or gender** influence approval?  
- What combinations of factors (e.g., low credit score + low income) make applicants more likely to be denied?  

---

##  Tools & Libraries
- **Python** for analysis  
- **NumPy & Pandas** for data wrangling  
- **Matplotlib & Seaborn** for visualizations  
- **Google Colab** as the working environment  

---

##  What I Did
1. Data Preprocessing  
   - Cleaned the dataset, handled missing values, and generated descriptive stats.  
   - Explored numeric features like **age, income, credit score** and categorical ones like **gender and education**.  

2. Exploratory Analysis  
   - Looked at overall loan approval rates.  
   - Compared approved vs. denied applicants across multiple factors.  
   - Grouped data to see approval trends by gender, marital status, occupation, and education.  

3. Visual Insights 
   - Plotted approval rates across different categories.  
   - Analyzed **credit score bins** and income levels vs. approval.  
   - Checked correlations between numeric features and loan status.  

---

## Key Insights
- **Credit score is king**: Approved applicants had an average score of **745**, while denied ones had around **610**.  
- **Income matters**: Approved applicants earned about **92k** on average vs. **39k** for denied ones.    
- **Top 3 approval drivers**: **Credit Score > Income > Age**.  

