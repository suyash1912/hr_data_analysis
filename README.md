#  HR Data Analysis & Cleaning

This project focuses on cleaning, preparing, and visualizing HR employee data to make it analysis-ready. The dataset was loaded directly from a GitHub release and processed using Python (pandas, seaborn, matplotlib).

---

##  Problem Statement

**HR Data Cleaning for Analysis**  
Prepare raw HR employee data by:
- Handling missing values
- Correcting typos
- Standardizing formats
- Encoding categorical variables

---

##  Dataset Source

- **GitHub Release URL**: [Download Dataset](https://github.com/suyash1912/hr_data_analysis/releases/tag/data)
- **File**: `hr_analysis_data.csv`

---

##  Cleaning Steps Performed

1. **Missing Values**  
   - Numeric: Filled with median  
   - Categorical: Filled with mode

2. **Text Normalization**  
   - Trimmed whitespaces
   - Standardized capitalization
   - Fixed common typos (e.g., `"Sixty Thousand"` → `60000`)

3. **Data Type Fixes**  
   - Converted `Age`, `Salary`, `Experience` to numeric
   - Converted `EmployeeID` to string

4. **Categorical Encoding**  
   - Label encoded: `Department`, `Gender`, `Attrition`, `Education`

---

##  Visualizations

The following charts were generated to understand the dataset:

-  Attrition Count
-  Gender-wise Attrition
-  Department Distribution
- Experience vs Salary (scatterplot)
-  Age Distribution

All visualizations were built using `seaborn` and `matplotlib`.

---

##  Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn (for label encoding)

---


---

## ✅ Output Example

Cleaned dataset preview:

| EmployeeID | Age | Department | Attrition | Salary | Experience | Gender | ... |
|------------|-----|------------|-----------|--------|------------|--------|-----|
| 1001       | 28  | HR         | Yes       | 60000  | 3          | Male   | ... |

---

##  Future Work

- Build a machine learning model to predict employee attrition
- Create an interactive dashboard with Plotly or Streamlit

---

## 🙌 Contributions

Feel free to fork the repo, open issues, or suggest improvements!

---



