# 📊 EDA Case Study: Stack Overflow Annual Developer Survey 2020

## 👨‍💻 Author
**L Hareesh**  
(With assistance from ChatGPT)

---

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Stack Overflow Annual Developer Survey 2020 dataset**.  
The dataset contains responses from **65,000+ developers worldwide**, where they shared details about their age, countries, education, jobs, salaries, programming languages, and preferences.

The main goal is to analyze and visualize the data to understand **global developer trends in 2020**.

---

## 📝 Understanding the Title

### 🔹 What is Stack Overflow?
A popular website where programmers ask and answer coding questions.

### 🔹 What is the Annual Developer Survey?
Every year, Stack Overflow collects responses from developers worldwide about their demographics, skills, and work.

### 🔹 What are Responses?
Each respondent (developer) provides answers. Example:

* Question: *What programming languages do you use?*  
* Response: *Python, JavaScript, SQL*

### 🔹 What does Analyzing Responses mean?
Studying those answers to find insights like:

* Most popular programming languages  
* Average salaries by country  
* Work preferences during COVID-19 (2020)

### 🔹 Where does the Data come from?
Published by **Stack Overflow**, freely available on their research page or Kaggle.

---

## 💡 What You Can Do with the Data

1. **Demographics** – Age, gender, countries of developers.  
2. **Programming Languages & Tools** – Most popular languages, databases, frameworks.  
3. **Job & Salary Analysis** – Salary by country, experience, education.  
4. **Learning & Education** – University vs self-taught vs bootcamp.  
5. **Work Preferences** – Remote work, job satisfaction, working hours.  
6. **Trends & Patterns** – Younger vs older developers, technology shifts.  
7. **Advanced Analysis** – Correlations, clustering, deeper insights.  

---

## 🚀 Roadmap for EDA

### **Step 1: Load the Data**
* Import libraries (`pandas`, `matplotlib`, `seaborn`)  
* Load dataset with `pd.read_csv()`  
* Check shape (rows, columns) and first few rows  

---

### **Step 2: Understand the Data**
* `df.info()` → Column names & datatypes  
* `df.describe()` → Summary stats  
* `df.isnull().sum()` → Missing values  

---

### **Step 3: Clean the Data**
* Remove irrelevant columns (IDs, metadata)  
* Handle missing values (drop/fill)  
* Rename columns (e.g., `YearsCodePro → Years_Professional`)  
* Convert text into numeric values where needed  

---

### **Step 4: Demographics**
* Age distribution (histogram)  
* Top countries by respondents  
* Gender distribution  

---

### **Step 5: Programming Languages & Tools**
* Most popular programming languages (bar chart)  
* Databases, frameworks, cloud platforms analysis  

---

### **Step 6: Job & Salary**
* Salary distribution (boxplot)  
* Salary by country  
* Salary vs years of experience  
* Salary vs education level  

---

### **Step 7: Learning & Education**
* Coding learning methods (bootcamp, university, self-taught)  
* Education level vs salary  
* Education level vs languages used  

---

### **Step 8: Work Preferences**
* Remote work preference (important in 2020 – pandemic)  
* Job satisfaction levels  
* Weekly working hours  

---

### **Step 9: Correlation & Multivariate Analysis**
* Correlation heatmap (experience, age, salary)  
* Salary vs Experience scatterplot  
* Grouping developers by skills (optional clustering)  

---

### **Step 10: Summarize Insights**
* Top 3 languages: **JavaScript, Python, SQL**  
* **US developers** earn highest salaries; **India** has more developers but lower median salary  
* Younger developers → Python; Older developers → Java, C#  
* Rise of self-taught developers  

---

## 🔑 Final Summary

This project analyzes the **Stack Overflow 2020 Developer Survey** to uncover:

* Who the developers are  
* What tools they use  
* How much they earn  
* How they learn coding  
* How their preferences changed in 2020 (COVID-19 year)  

It helps us **understand global trends in software development**.  

---

## 🙌 Acknowledgements
* Dataset Source: [Stack Overflow Developer Survey 2025](https://insights.stackoverflow.com/survey)  
* Analysis & Documentation: **L Hareesh**  
* AI Assistance: **ChatGPT**  **Gemini Pro** 

---

## 📚 References & Resources

* [Google Colab](https://colab.research.google.com/) – Cloud-based Python environment used for running the analysis.  
* [Pandas Documentation](https://pandas.pydata.org/) – Python data analysis library.  
* [NumPy Documentation](https://numpy.org/) – Numerical computing library.  
* [Matplotlib Documentation](https://matplotlib.org/) – Visualization library.  
* [Seaborn Documentation](https://seaborn.pydata.org/) – Statistical data visualization.  
* [YouTube Playlist: Pandas & NumPy Tutorials](https://www.youtube.com/watch?v=GPVsHOlRBBI&list=PLyMom0n-MBrpr1Q3OQC5Od1o1zczHEO0u) – Helpful for learning data manipulation and analysis.  

---
