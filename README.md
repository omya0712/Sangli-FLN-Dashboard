# Sangli Student Performance Dashboard

## 📊 Project Overview

The **Sangli Student Performance Dashboard** is an interactive Tableau dashboard developed to analyze student assessment data across multiple months. It provides insights into student enrollment, assessment coverage, and learning levels across different subjects.

The dashboard helps users compare student performance across assessment periods and understand learning progress in reading, writing, and mathematics.

## 🎯 Project Objectives

- Analyze student assessment data across multiple months.
- Monitor student enrollment and assessment coverage.
- Compare learning levels between selected assessment months.
- Analyze performance in the regional language, English, and Mathematics.
- Present student performance data through interactive visualizations.
- Support data-driven monitoring and educational decision-making.

## 🛠️ Tools and Technologies

- **Tableau Desktop:** Dashboard development and data visualization.
- **Microsoft Excel:** Data preparation and storage.
- **CSV:** Data storage and exchange.
- **Data Analysis:** Student assessment analysis and month-wise comparisons.

## 📈 Dashboard Features

The dashboard includes the following features:

### 1. Student Enrollment Analysis
- Displays student enrollment information.
- Provides an overview of the student population.

### 2. Student Assessment Analysis
- Tracks the number of assessed students.
- Displays assessment information for the selected periods.
- Supports comparisons between assessment months.

### 3. Month-wise Performance Comparison
- Compares learning levels across different assessment months.
- Supports the selection of starting and ending months.
- Helps identify changes in student learning levels over time.

### 4. Subject-wise Learning Analysis

The dashboard analyzes student learning levels across the following subjects:

- **First Language:** Reading and Writing
- **English:** Reading and Writing
- **Mathematics:** Numeracy and learning levels

### 5. Interactive Visualizations
- Interactive dashboard views.
- Month-selection parameters.
- Comparative charts for learning levels.
- KPI cards for key student assessment indicators.

## 📂 Project Structure

```text
Sangli-Dashboard/
│
├── README.md
│
├── Sangli_Dashboard.twb
│
├── data/
│   ├── san_dashboard_data.xlsx
│   ├── san_dashboard_data_v4.xlsx
│   ├── san_all_students_basic_info.xlsx
│   └── san_student_wise_levels_multi_month.csv
│
└── screenshots/
    └── dashboard_preview.png
```

*Note: The filenames and folders above are suggested for organizing the repository. Rename the files or update the README to match your final GitHub folder structure.*

## 🗃️ Dataset Description

The project uses student assessment and school information datasets.

### Student Assessment Dataset

The assessment dataset contains fields such as:

- `student_id` — Student identifier.
- `test_date` — Assessment date.
- `class_name` — Student's class.
- `udise` — School identifier.
- `school_name` — School name.
- `medium_name` — Medium of instruction.
- `cluster_name` — School cluster.
- `marathi/kannada/urdu reading` — First-language reading level.
- `marathi/kannada/urdu writing` — First-language writing level.
- `english reading` — English reading level.
- `english writing` — English writing level.
- `maths` — Mathematics learning level.

### School Information Dataset

The school information dataset includes:

- Student identifier
- Medium of instruction
- Class
- School identifier
- School name
- School bit
- School block

These fields support the analysis of assessment results alongside school-related information.

## 🚀 How to View the Dashboard

1. Clone or download this GitHub repository.
2. Install Tableau Desktop or use a compatible Tableau application.
3. Download the project files.
4. Open the Tableau workbook (`.twb`).
5. If prompted, reconnect the data source to the Excel or CSV file in the downloaded repository.
6. Refresh the data connection if required.
7. Open the dashboard sheets and interact with the available filters and month-selection parameters.

**Important:** The workbook may contain local file paths. Update the data source connections after downloading the repository to ensure the dashboard works on your computer.

## 💡 Key Takeaways

This project demonstrates how Tableau can be used to transform student assessment data into interactive visualizations for educational monitoring.

It highlights the importance of tracking enrollment, assessment coverage, and subject-wise learning levels over time to support evidence-based decisions.

## 🔒 Data Privacy

Student assessment and school datasets may contain sensitive or confidential information. Only publish datasets that you are authorized to share.

If the data is confidential, keep the original files private and upload only approved, anonymized, or synthetic sample data.

## 👨‍💻 Author

**Omm Tharkude**

Data Analytics | Tableau | SQL | Python | Power BI

---

*This project was developed for student assessment analysis and educational data visualization.*
