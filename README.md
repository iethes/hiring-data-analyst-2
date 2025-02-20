# **Technical Test - Data Analyst Position at Magpie**

Welcome to the **Data Analyst Technical Test** at **Magpie**! This test is designed to evaluate your **Python coding, SQL analysis, and analytical thinking skills**.

## **Test Structure**

This test consists of **two main sections**, both included in a single Jupyter Notebook:

1. **Python Coding Challenge** 
2. **SQL Analytical Challenge** 

The provided dataset is structured as follows:

```bash
.
├── dataset/
│   ├── beauty_brand_gmv.db      # SQLite database for SQL tasks
│   ├── brand_refinement.csv     # CSV file for data analysis tasks
├── python_sql_coding.ipynb  # Jupyter Notebook for Python & SQL coding
```

If any files or structure differ from this, **please contact us immediately**.

---

## **Setup Instructions**

We recommend using **VSCode** (with the **Pylance** extension) or **Jupyter Notebook** for this test. The test should be completed using **Python 3.8 or later** within a virtual environment.

### **1. Set Up a Virtual Environment**

To ensure consistency, set up a virtual environment using `venv` (recommended) or any other tool like `conda`:

```bash
python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate      # For Windows
pip install -r requirements.txt  # Install dependencies
```

### **2. Working on the Test**

- Open `python_sql_coding.ipynb` and follow the instructions inside.
- Complete **both Python and SQL tasks** within the same notebook.
- Ensure your code is well-structured, efficient, and documented.

### **3. Required Dependencies**

The test requires the following Python libraries:

```
ipython-sql
pandas
matplotlib
```

These dependencies are already listed in `requirements.txt`. If you install additional libraries, update `requirements.txt` using:

```bash
pip freeze > requirements.txt
```

---

## **Submission Instructions**

Once you have completed the test:

1. **Commit and push** your solutions to a **private GitHub repository**.
2. **Grant access** to the following reviewers:
   - **[ichsan@adskom.com](mailto:ichsan@adskom.com)**
   - **[bima@magpie.co.id](mailto:bima@magpie.co.id)**
3. **Send us an email** confirming your submission.

---

## **Additional Notes**

- Ensure your **SQL queries are optimized** and return meaningful insights.
- Your Python code should be **efficient, well-documented, and follow best practices**.
- If you face any issues (missing files, unclear instructions, etc.), **reach out to us as soon as possible**.

Good luck! 🚀
