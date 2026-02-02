# Household Income and Expenditure Survey (HIES) – Econometrics I  
**Problem Set 1 | Questions 5–8**

This notebook contains the solutions to Questions 5–8 of Problem Set 1 for the *Econometrics I* course.  
The analysis uses microdata from the **Household Income and Expenditure Survey (HIES)** to study income, expenditure patterns, and education-related household behavior.

---

## File Description

- **Metrics_HIES_403201483.ipynb**  
  Python notebook for descriptive statistics, expenditure decile construction, and household-level analysis.

---

## Datasets

- Source: Statistical Center of Iran – HIES (Year 1401)
- Formats:
  - Excel (`.xlsx`) – household summary data
  - Stata (`.dta`) – education expenditure data
- Coverage: Urban and rural households

---

## Questions Overview

### Question 5  
Descriptive statistics by:
- Province
- Urban / rural status  

Variables analyzed:
- Household income
- Family size
- Education level of household head  

Outputs include means, standard deviations, minimums, maximums, and education shares.

---

### Question 6  
- Construction of **total household expenditure** as the sum of:
  - Food expenditure
  - Non-food expenditure
- Households are classified into **expenditure deciles**
- Results exported as an Excel file

---

### Question 7  
- Average household expenditure by:
  - Expenditure decile
  - Urban / rural status  
- Results visualized using bar charts

---

### Question 8  
- *(Incomplete)*  
- Intended analysis:
  - Share of household income spent on education per child
  - Comparison across expenditure deciles and urban/rural areas  
- This section requires further data preparation and variable definition.

---

## How to Run

1. Place all HIES data files in a local `data/` directory.
2. Ensure Excel and Stata files are correctly named.
3. Update file paths in the notebook if needed.
4. Run all cells sequentially.

---

## Dependencies

```bash
pip install pandas numpy matplotlib openpyxl
