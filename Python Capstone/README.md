# Python Capstone Project – SkilloVilla  

This repository contains my **Python Capstone Project** completed as part of the SkilloVilla program. The project is focused on **data wrangling, transformation, and analysis** using multiple datasets.  

The goal is to simulate real-world business scenarios where multiple tables must be joined, cleaned, and analyzed to extract actionable insights.  

---

## 📊 Dataset Overview  

The project involves three different datasets:  

1. **Projects Table**  
   - Project Head ID  
   - Gender  
   - Project Name  
   - Active Status  
   - Budget  
   - Deadline  

2. **Employee Table**  
   - Emp ID  
   - Employee Name  
   - Employee Salary  
   - Joining Date  
   - Department  

3. **Employee Project Allocation Table**  
   - Emp ID  
   - Project Head ID  

---

## 📝 Problem Statements  

The project involves solving the following problems using Python and Pandas:  

- Load the three datasets into Pandas DataFrames and join them using keys (`Emp ID`, `Project Head ID`), while handling missing values appropriately.  
- Split the `Employee Name` column into **First Name** and **Last Name**.  
- Merge all datasets into a single unified DataFrame called `Final`.  
- Add a new column in the Final DataFrame to provide a **5% bonus** for employees handling active projects, based on the project budget.  
- Derive **employee experience level** (in years) from the `Joining Date` and classify them into:  
  - **Fresher** (< 5 years)  
  - **Experienced** (5–20 years)  
  - **Veteran** (> 20 years)  
- Calculate the **gender ratio** (male-to-female) for project heads and include it in the Final DataFrame.  
- Count the number of projects each employee has handled and add it as a new column.  
- Extract employees whose **first names start with 'S' or 's'**.  

---

## 🧮 Performance Evaluation  

This project tests key skills in:  
- Data loading and cleaning  
- Data joining and merging across multiple DataFrames  
- String manipulation in Pandas  
- Date-time handling for calculating experience  
- Feature engineering (e.g., bonus calculation, gender ratio, project counts)  

---

## ⚙️ Tools & Technologies  

- **Python**  
- **Pandas**  
- **NumPy**  
- **Jupyter Notebook**  

---

## 📌 Learning Outcomes  

- Efficiently handling multiple datasets in Python.  
- Applying **data wrangling techniques** for real-world scenarios.  
- Using Pandas for **data transformation, feature creation, and analysis**.  
- Strengthened my problem-solving ability with structured tasks.  

---

## 🧑‍💻 Author  

**Piyush Jain**  
- Data Analyst | Python | SQL | Power BI | Excel  
- Passionate about leveraging data to solve business problems  
