# 🏥 SQL Practice - Patient Insurance Data

This repository contains **SQL practice queries** on a sample patient insurance dataset.  
The queries help practice **filtering, aggregation, update, and delete operations**. 💻✨

---

## 📂 Table Name

`insurance_data_campusx`

**Columns (example structure):**  
- 🆔 `PatientID` : Unique ID of each patient  
- 👨‍👩‍👧‍👦 `gender` : Male / Female  
- 🌍 `region` : Region of patient (e.g., southwest, southeast)  
- 🎂 `age` : Age in years  
- ⚖️ `bmi` : Body Mass Index  
- 💓 `bloodpressure` : Blood pressure of patient  
- 🩺 `diabetic` : Yes / No  
- 🚬 `smoker` : Yes / No  
- 👶 `children` : Number of children  
- 💰 `claim` : Insurance claim amount  

---

## 📝 Queries Included

1. 📋 Show all records and total record count  
2. 👨 Male patients from southwest region  
3. ⚖️ Patients with BMI in range 30–45  
4. 💓 Minimum and maximum blood pressure for diabetic smokers  
5. 🆕 Count of unique patients not from southwest  
6. 💰 Total claim amount from male smokers  
7. 🌍 Select all patients from south regions  
8. 🩺 Count of patients with normal blood pressure [90-120]  
9. 🎂 Patients below 17 years with dynamic blood pressure formula  
10. 💻 Average claim for non-smoking diabetic female patients  
11. ✏️ Update claim amount for a specific patient  
12. 🗑️ Delete all records for smokers with no children  

---

## ⚠️ Notes

- ⚗️ Some formulas (e.g., blood pressure for age <17) are **for practice only**.  
- 🔍 Always verify string values for case-sensitivity (`Yes` vs `yes`) and trailing spaces (`'no '` vs `'no'`).  
- ✅ Before running `UPDATE` or `DELETE`, always use `SELECT` to verify affected rows.  

---

## 📌 How to Use

1. ⬇️ Download or clone this repository.  
2. 📂 Open `practice_queries.sql` in your SQL client (MySQL, PostgreSQL, etc.).  
3. ▶️ Execute queries section by section to practice filtering, aggregation, and data manipulation.  

---

Made for learning SQL efficiently with a **sample patient dataset**. 💡💻  
