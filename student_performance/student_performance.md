# 🎓 Student Performance Prediction & Analysis

## 📘 Overview
This project focuses on analyzing and predicting **students’ academic performance** based on various social, behavioral, and academic factors.  
Using advanced data preprocessing, exploratory data analysis (EDA), and machine learning modeling, this study reveals the most significant factors influencing students’ exam scores.

The goal is to provide data-driven insights that can help educators and institutions better understand what truly impacts student success.

---

## 📊 Dataset Description
**Total Records:** 6,607  
**Total Features:** 20  

### 🧮 Numerical Features:
- Hours_Studied  
- Attendance  
- Sleep_Hours  
- Previous_Scores  
- Tutoring_Sessions  
- Physical_Activity  
- Exam_Score  

### 🧩 Categorical Features:
- Parental_Involvement  
- Access_to_Resources  
- Extracurricular_Activities  
- Motivation_Level  
- Internet_Access  
- Family_Income  
- Teacher_Quality  
- School_Type  
- Peer_Influence  
- Learning_Disabilities  
- Parental_Education_Level  
- Distance_from_Home  
- Gender  

---

## 🔧 Data Preparation
Before performing the analysis and modeling, the dataset was carefully cleaned and prepared:
- Removed **missing (NaN)** values.  
- Encoded categorical variables into numerical form.  
- Scaled numerical features for better model performance.  
- Checked and handled **outliers** using the IQR method.  

This ensured that the data was balanced, normalized, and ready for accurate predictive modeling.

---

## 📈 Exploratory Data Analysis (EDA)
Comprehensive visual analysis was performed using **Matplotlib** and **Seaborn**, including:

- **Distribution plots** for key numeric variables.  
- **Boxplots** to identify and visualize outliers.  
- **Correlation heatmap** to find relationships between features.  
- **Comparative visualizations** for gender, school type, and extracurricular involvement.

### 🔍 Key Observations:
- A strong positive correlation between **Attendance**, **Hours_Studied**, and **Exam_Score**.  
- Students with higher **Motivation Levels** and **Parental Involvement** tend to achieve higher scores.  
- Balanced sleep and moderate physical activity also contribute positively.

---

## 🤖 Machine Learning Model
A **Gradient Boosting Regressor** was used to predict students’ exam scores based on their behavioral and academic attributes.

### 🧠 Model Performance:
| Metric | Training | Testing |
|:--------|:----------|:---------|
| RMSE | 0.877 | 0.941 |
| R² Score | 0.948 | **0.930** |

### ⚡ Interpretation:
- The model achieved an **excellent predictive performance** with **93% accuracy** (R² = 0.93).  
- Very small difference between training and testing performance → **no overfitting**.  
- **Hours_Studied** and **Attendance** were the most influential features, followed by **Previous_Scores**.

---

## 🧩 Tools & Libraries
- **Python 3.x**  
- **pandas**, **numpy** – data manipulation  
- **matplotlib**, **seaborn** – visualization  
- **scikit-learn** – model training and evaluation  

---

## 💡 Key Insights
- Consistent studying and attendance have the highest impact on exam performance.  
- Proper sleep and motivation levels contribute significantly to academic success.  
- Machine learning can reliably predict academic outcomes and identify weak areas for intervention.


---

## ⭐ Future Enhancements
- Deploy the model using a web interface for real-time prediction.  
- Extend analysis with psychological and socio-economic factors.  
- Compare different ML algorithms for performance benchmarking.

---

## 🏁 Conclusion
This project demonstrates how data analytics and machine learning can uncover valuable insights about **student performance**.  
The Gradient Boosting model achieved **94% accuracy**, confirming that academic success can be effectively predicted based on behavioral and educational factors.


## 🧑‍💻 Author
**Abdelrhman Khalil Abdullah**  
Faculty of Computers and Artificial Intelligence, Fayoum University  
Specialization: Machine Learning  

---