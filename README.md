# Financial-analyze-tool

## 1. Project Purpose and the Target Users
The target audience of this project is professional financial data analysts or business students at universities. This project provides a convenient way to filter data, perform calculations based on financial formulas, and generate simple comments based on the calculated results. 

## 2. Data Source
The sources are from WRDS database.

## 3. Methods (Python Workflow)
1. Import Pandas for financial data filtering, table processing, data cleaning, and calculations, and import WRDS to directly pull corporate financial statement data from the database.
2. Using the calculate_ratio() function, we standardize the calculation logic, handle exceptional cases (such as division by zero), and ensure a standardized output format.
3. Interact with the user to input the company and the year to be analyzed.
4. Connect with WRDS database. Using the user's own account.
5. Using SQL to precisely extract the corporate financial statement data required for analysis from the WRDS database.
6. Using the predefined calculate_ratio() function and the extracted financial data, we compute and display key financial ratios.
7. Based on the calculated data and market average benchmarks, we provide a brief evaluation.
