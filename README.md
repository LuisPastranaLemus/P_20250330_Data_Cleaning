# 🧹 Data Cleaning Project - Sprint 1

This notebook is part of the first part in a multi-stage data analytics project. The focus here is on **data quality assessment and preprocessing**, preparing raw customer data from Store 1 for further analysis.

## 📘 Project Context

As a new member of the analytics team, the initial task is to review and clean a sample dataset provided by the client.

The dataset is structured as a list of users, where each entry contains:

- `user_id`: User’s unique identifier (string).
- `user_name`: Full name with formatting issues (e.g. underscores, inconsistent spacing).
- `user_age`: User's age (should be an integer).
- `fav_categories`: List of category names in uppercase.
- `total_spendings`: Integer list matching the categories.

## 🔍 Key Objectives

- Evaluate the data structure for inconsistencies.
- Apply the appropriate transformations:
  - Clean string formats.
  - Normalize category names.
  - Convert types (e.g. `user_id` from string to integer).
- Validate the transformed data for further use.

## 🛠 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- No external libraries required (standard Python data structures and functions used)

## 📁 Notebook Structure

1. **Project Overview**  
   Introduction to the business need and data context.

2. **Raw Data Review**  
   Inspection of sample user data and identification of potential issues.

3. **Data Cleaning Steps**  
   Each issue is addressed individually (e.g. type conversion, string normalization).

4. **Validation**  
   The cleaned user data is reconstructed into a standard format for further analysis.

---

## 📌 Notes

This project is part of a personal learning portfolio focused on developing strong skills in data analysis, statistical thinking, and communication of insights. Constructive feedback is welcome.

---

## 👤 Author   
##### Luis Sergio Pastrana Lemus   
##### Engineer pivoting into Data Science | Passionate about insights, structure, and solving real-world problems with data.   
##### [GitHub Profile](https://github.com/LuisPastranaLemus)   
##### 📍 Querétaro, México     
##### 📧 Contact: luis.pastrana.lemus@engineer.com   
---

