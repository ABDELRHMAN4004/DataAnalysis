# Global Cybersecurity Threats (2015–2024)

## 📑 Table of Contents
- [Introduction](#-introduction)  
- [Dataset Description](#-dataset-description)  
- [Analysis Questions](#-analysis-questions)  
  - [General Questions](#general-questions)  
  - [Advanced Questions](#advanced-questions)  
- [Methods](#️-methods)  
- [Visualizations](#-visualizations)  
- [Key Findings](#-key-findings)  
- [Future Work](#-future-work)  
- [How to Run](#️-how-to-run)  
- [Author](#-author)  

---

## 📌 Introduction
This project analyzes global cybersecurity threats from 2015 to 2024.  
The dataset contains detailed information about countries, attack types, target industries, financial losses, affected users, vulnerabilities, defense mechanisms, and incident resolution times.  
The goal is to uncover insights, trends, and relationships between different features to better understand the evolving cyber threat landscape.

---

## 📊 Dataset Description
The dataset contains **3,000 rows** with the following columns:

1. **Country** – The country where the cyberattack occurred  
2. **Year** – The year of the incident (2015–2024)  
3. **Attack Type** – Type of cyberattack (e.g., Phishing, Ransomware, DDoS)  
4. **Target Industry** – The industry targeted (e.g., Finance, Healthcare, Education)  
5. **Financial Loss (in Million $)** – The estimated financial damage caused  
6. **Number of Affected Users** – Number of people affected by the incident  
7. **Attack Source** – Origin of the attack (e.g., Hacker Group, Nation-State, Insider)  
8. **Security Vulnerability Type** – The exploited vulnerability (e.g., Zero-day, Weak Passwords)  
9. **Defense Mechanism Used** – Security control applied to defend against the attack  
10. **Incident Resolution Time (in Hours)** – Time taken to resolve the incident  

---

## ❓ Analysis Questions

### General Questions
1. Which countries are most targeted by cyberattacks?  
2. How has the number of attacks changed over the years?  
3. What are the most common types of attacks globally?  
4. Which industries are the most frequently targeted?  
5. What is the average financial loss per country or attack type?  
6. What is the relationship between the number of affected users and the financial loss?  
7. What are the most common attack sources?  
8. Which vulnerabilities contribute the most to attacks?  
9. Do certain defense mechanisms reduce incident resolution time?  
10. Are there differences between countries in how quickly incidents are resolved?  

### Advanced Questions
11. Is there a relationship between attack type and target industry?  
12. Do attacks from nation-states cause higher financial losses compared to others?  
13. Are some industries more affected in terms of the number of users?  
14. How do average financial losses change over the years?  
15. Which defense mechanism proves to be most effective in reducing losses?  
16. Are certain countries more prone to specific attack types?  
17. Is there a relationship between the number of affected users and the resolution time?  
18. Do zero-day attacks take longer to resolve compared to weak password attacks?  
19. Which years recorded the highest total financial losses?  
20. Can we predict future attack types based on country and industry?  

---

## 🛠️ Methods
- **Data Cleaning**: Handling missing values, encoding categorical features, and formatting columns  
- **Exploratory Data Analysis (EDA)**: Using descriptive statistics, distributions, and relationships  
- **Visualizations**: Bar charts, line plots, pie charts, heatmaps, boxplots, and scatter plots  
- **Encoding Techniques**: Label Encoding, One-Hot Encoding, and Frequency Encoding (for categorical variables)  
- **Correlation Analysis**: Identifying patterns between financial loss, users affected, and resolution time  
- **Hypothesis Testing**: Comparing losses and resolution times across different attack types and countries  

---

## 📈 Visualizations
- Cyberattack distribution by country  
- Trend of attacks over time (2015–2024)  
- Attack type frequency across industries  
- Financial loss per country and per attack type  
- Relationship between affected users and financial losses  
- Defense mechanisms vs. incident resolution time  
- Heatmap of correlations among numerical features  

---

## 📌 Key Findings
- Certain countries (e.g., USA, India, Brazil) are consistently high-target regions.  
- Financial losses have generally increased over the years, with spikes during major ransomware waves.  
- Nation-state attacks tend to cause greater losses compared to hacker groups.  
- Healthcare and Finance industries are among the most affected sectors.  
- Zero-day vulnerabilities lead to longer resolution times than weak passwords.  
- Effective defense mechanisms (e.g., Multi-factor Authentication, Advanced Firewalls) significantly reduce both losses and resolution times.  

---

## 🚀 Future Work
- Build **predictive models** to forecast the likelihood of attack types by industry and country.  
- Develop an **anomaly detection system** for early identification of unusual attack patterns.  
- Apply **clustering techniques** to group countries/industries with similar threat profiles.  
- Create an **interactive dashboard** (using Plotly/Dash or Power BI) for real-time threat monitoring.  

---

## 📌 Author

**Abdelrahman Khalil Abdullah**
