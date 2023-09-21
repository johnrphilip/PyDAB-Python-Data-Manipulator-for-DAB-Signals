# PyDAB-Python-Data-Manipulator-for-DAB-Signals
A Python application for data manipulation tasks related to Digital Audio Broadcasting (DAB) signals.


## Table of Contents
1. [About](#about)
2. [Features](#features)
3. [Technical Highlights](#technical-highlights)
4. [What This Project Demonstrates](#what-this-project-demonstrates)
5. [Report](#report)

---

## About

DABMaster is a Python application developed to efficiently manage and process datasets related to Digital Audio Broadcasting (DAB) signals. The application is capable of loading, transforming, cleaning, and statistically analyzing CSV data through a Graphical User Interface (GUI). It runs in a Jupyter Notebook and only requires two CSV files for its operation.

---

## Features

- GUI designed with Tkinter for intuitive data operations.
- Data cleaning, transformation, and statistical analysis.
- Optimized operations, including considerations for concurrency.
- Comprehensive report accompanying the project.

---

## Technical Highlights

- **Concurrency**: To speed up data encoding and cleaning, the `load_data()` and `clean_data()` functions are designed for concurrent execution. Concurrency is a valuable feature for reducing processing time, particularly for large datasets.
  
- **GUI with Tkinter**: Tkinter provides a simple yet robust framework for developing the GUI. It is rich in features, offering a seamless way to interact with the application.

- **Data Containers**: Implemented efficient data structures like Pandas dataframes for data storage and manipulation, benefiting from Python's dynamic typing and flexibility.

- **JSON Handling**: Utilized JSON for data storage to offer hierarchical data structures, easily handled by Pandas in Python.

- **Statistical Calculations**: Used Pandas for statistical operations like mean, mode, and median, and SciPy for a chi-square test of independence, highlighting Python's strengths in statistical computing.

- **Data Visualization**: Employed Seaborn API and Matplotlib for generating client-requested visualizations integrated into the Tkinter GUI.

---

## What This Project Demonstrates

1. **Advanced Python Programming**: From concurrency to dynamic typing, this project is a demonstration of Python's capabilities in building robust data analysis tools.

2. **Data Science Skills**: Through data cleaning, transformation, and statistical analysis, I've showcased essential data science practices.

3. **GUI Development**: The use of Tkinter for GUI shows my understanding of user interface design, focusing on ease of use and real-time feedback.

4. **Comparative Analysis**: In the report, I've compared Python with Java in the context of data manipulation, diving deep into the advantages and disadvantages of each.

5. **Statistical Analysis**: Application of chi-square tests, and other statistical measures like mean, mode, and median to the dataset demonstrates my grasp of statistical methods.

6. **Ethical Awareness**: The accompanying report contains a section discussing the ethical implications of software engineering, revealing a comprehensive understanding of the subject matter beyond just coding.

---

## Report

For a deeper understanding of the design decisions, technologies used, and the expertise demonstrated, refer to the [16-page report](link_to_report.pdf). The report is divided into three sections:

1. Theory and application of programming techniques.
2. Design decisions for data manipulation.
3. Reflection on ethical, moral, and legal aspects in computing.

---

Feel free to reach out with any questions or for further clarifications.
