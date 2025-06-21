# 🧪 Week 03 – Lab Assignment 02 | MAD 01 (BSCCS2003) – IITM BS

This folder contains the complete solution for **Week 03 Lab Assignment 02** of the **MAD 01: Modern Application Development I** course from **IIT Madras B.S. in Data Science and Applications**.

---

## 📌 Problem Statement Summary

You are provided with a CSV file named `data.csv` containing marks of students across various courses. Your task is to create a Python script (`app.py`) that processes this data and generates:

- ✅ An **HTML output file (`output.html`)** that displays the result in a table based on the command line arguments  
- ✅ A **histogram image** (when querying by course ID)  
- ✅ Proper error handling and output formatting

---

## 📁 CSV File Format

The input CSV `data.csv` contains the following fields:

```
Student ID,Course ID,Marks
101,201,89
102,201,75
101,202,92
...
```

---

## 🧠 Expected Behavior

Your script should handle two kinds of input:

### 1. `python app.py -s <student_id>`  
Generates a table titled **"Student Details"** with:

- Student ID  
- Course ID  
- Marks  
- A total row at the bottom showing the sum of marks  

### 2. `python app.py -c <course_id>`  
Generates a table titled **"Course Details"** with:

- Average Marks  
- Maximum Marks  

Also includes a **histogram image** showing the distribution of marks for that course.

---

## ❌ Invalid Input Handling

If input format is incorrect or the ID doesn't exist in `data.csv`, generate an HTML page with the message:

> "No data available for the given input."

---

## 📋 Instructions

- ✅ Name your main file as `app.py`  
- ✅ Submit a `.zip` file named `<rollnumber>.zip`  
- ✅ Use only **relative paths** (e.g., `"data.csv"` not `"C:/data.csv"` or `"./Week3/data.csv"`)  
- ✅ The output must be **HTML5 compliant**  
- ✅ Use only allowed packages: `pyhtml`, `jinja2`, `matplotlib`, or standard `Python3` libraries  
- ❌ Do not use HTML code generators

---

## 🗂 Folder Structure

```
week 03 (Lab 02)/
├── app.py                # Your Python script
├── data.csv              # Input file with student/course data
├── output.html           # Generated output HTML (dynamic)
├── course_histogram.png  # Histogram image for course-based output
├── README.md             # This file
```

---

## ▶️ How to Run

Use the following commands in the terminal:

```bash
python app.py -s 101
```

or

```bash
python app.py -c 201
```

---

## ✅ Example Output

### Student Query (`-s 101`)

| Student ID | Course ID | Marks   |
| ---------- | --------- | ------- |
| 101        | 201       | 89      |
| 101        | 202       | 92      |
| **Total**  |           | **181** |

---

### Course Query (`-c 201`)

| Average Marks | Maximum Marks |
| ------------- | ------------- |
| 82.33         | 98            |

🖼️ Includes `course_histogram.png` showing mark distribution.

---

### Invalid Input Example

If ID is not found or incorrect flag is used:

> ❗ No data available for the given input.

---

## 📩 Connect with Me

* 📺 YouTube: [AI By IITian](https://www.youtube.com/@AIByIITian)
* 💻 GitHub: [github.com/Irshadanwar](https://github.com/Irshadanwar)
* 🔗 LinkedIn: [MD Irshad Anwar](https://www.linkedin.com/in/mdirshadanwar)

---

## ⭐ Give this repo a star if it helped you!
