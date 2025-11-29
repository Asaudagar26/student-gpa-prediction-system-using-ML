# 🎓 Student GPA Prediction System  
A Machine Learning + Flask web application that predicts a student’s GPA and Percentage based on demographic, academic, and behavioral factors.  
This project uses a real Kaggle dataset and a Linear Regression model integrated with a clean, modern UI.

---

## 🚀 Demo  
🔮 Enter student details → 🧠 ML model predicts GPA → 📊 Shows percentage.

---

## 🧠 Project Overview  
Students perform differently based on various factors such as study habits, absences, parental support, tutoring, and extracurricular involvement.  
This project uses Machine Learning to **predict GPA early**, helping educators and parents:

- Identify weak or at-risk students  
- Understand what affects performance  
- Provide early support or interventions  
- Improve decision-making with data  

---

## 🧩 Features  
### ✔ Machine Learning Model  
- Trained using Linear Regression  
- Uses multiple features:
  - Age  
  - Gender  
  - Ethnicity  
  - Parental Education  
  - Study Time Weekly  
  - Absences  
  - Tutoring  
  - Parental Support  
  - Extracurricular Activities  
  - Sports  
  - Music  
  - Volunteering  

### ✔ Modern Web App (Flask + HTML + CSS)  
- Clean and attractive user interface  
- Dropdown-based input fields  
- Predicts GPA + Percentage  
- User-friendly front-end  
- Smooth animations and modern styling  

---

## 🛠️ Tech Stack  
**Frontend:** HTML, CSS  
**Backend:** Python, Flask  
**ML Model:** Linear Regression  
**Libraries:** Pandas, NumPy, Scikit-Learn, Joblib  
**Tools:** Git, GitHub  

---

## 📂 Project Structure
student_gpa_prediction/
│── app.py
│── train_model.py
│── student_gpa_model.pkl
│── Student_performance_data _.csv
│
├── templates/
│ ├── index.html
│ └── result.html
│
└── static/
└── style.css


---

## 🧪 How to Run the Project

### 1️⃣ Install dependencies


pip install flask pandas numpy scikit-learn joblib


### 2️⃣ Train the Machine Learning model


python train_model.py

This will create:  
✔ `student_gpa_model.pkl`

### 3️⃣ Run the Flask app


python app.py


### 4️⃣ Open the browser


http://127.0.0.1:5000/

he dataset used includes the following columns:

- StudentID  
- Age  
- Gender  
- Ethnicity  
- ParentalEducation  
- StudyTimeWeekly  
- Absences  
- Tutoring  
- ParentalSupport  
- Extracurricular  
- Sports  
- Music  
- Volunteering  
- GPA  
- GradeClass  

---

## 🎯 Purpose of the Project  
This project is designed to help:

### 👩‍🏫 Teachers  
Early detection of low-performing students.

### 🏫 Schools  
Improve academic planning and student success rate.

### 👨‍👩‍👦 Parents  
Understand performance factors and support their children.

### 🎓 Students  
Self-evaluation and study improvement.

### 🤖 Researchers / Data Scientists  
Analyze factors affecting student academic performance.
