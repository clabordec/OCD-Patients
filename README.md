# OCD-Patients

## Overview
The **OCD-Patients** repository is designed to facilitate the analysis and visualization of healthcare data related to patients with Obsessive-Compulsive Disorder (OCD). The goal of this project is to provide actionable insights for stakeholders, including healthcare providers and researchers, by leveraging advanced business intelligence tools and methods.

## Key Features
- **Data Management**: Efficient retrieval and manipulation of large datasets using **MySQL**.
- **Data Analysis**: Comprehensive analysis performed to uncover trends, correlations, and patterns in the data.
- **Data Visualization**: Creation of intuitive and interactive dashboards using **Power BI** and **Excel** for clear communication of insights to stakeholders.

## Tools and Technologies

### 1. MySQL
- **Purpose**: To store, manage, and query patient data efficiently.
- **Key Use Cases**:
  - Retrieving data related to patient demographics, symptoms, and treatment outcomes.
  - Performing complex queries to identify trends and anomalies.

### 2. Power BI
- **Purpose**: To create visually appealing and interactive dashboards for stakeholders.
- **Key Use Cases**:
  - Developing trend analysis dashboards to monitor patient improvement over time.
  - Visualizing geographic distribution of patients for regional insights.

### 3. Excel
- **Purpose**: For quick analysis and visualization of smaller datasets.
- **Key Use Cases**:
  - Creating pivot tables and charts for ad-hoc reporting.
  - Conducting scenario analysis and sharing results in a portable format.

## Repository Structure
```
OCD-Patients/
|
├── data/                     # Raw and processed data files
│   ├── raw/                  # Original datasets
│   └── processed/            # Cleaned and transformed datasets
|
├── queries/                  # MySQL scripts for data retrieval
│   ├── patient_analysis.sql
│   └── treatment_patterns.sql
|
├── visuals/                  # Power BI and Excel visualization files
│   ├── dashboards.pbix       # Power BI dashboards
│   └── reports.xlsx          # Excel reports
|
├── docs/                     # Documentation and reports
│   ├── data_dictionary.md    # Explanation of data fields
│   └── project_summary.pdf   # Executive summary for stakeholders
|
├── scripts/                  # Python scripts for data processing
│   └── data_cleaning.py      # Script for cleaning raw data
|
└── README.md                 # Repository overview
```

## Getting Started

### Prerequisites
To run the analyses and visualizations, ensure you have the following installed:
- **MySQL** (v8.0 or higher)
- **Power BI Desktop** (latest version)
- **Microsoft Excel**
- **Python** (v3.8 or higher) with necessary libraries (e.g., pandas, numpy, sqlalchemy)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/OCD-Patients.git
   ```
2. Navigate to the repository:
   ```bash
   cd OCD-Patients
   ```
3. Set up the MySQL database by importing the provided schema and data:
   ```bash
   mysql -u username -p < data/raw/ocd_schema.sql
   ```

## How to Use

### Step 1: Data Retrieval
- Use the SQL scripts in the `queries/` folder to extract relevant datasets from MySQL.
  Example:
  ```bash
  mysql -u username -p < queries/patient_analysis.sql > output/patient_analysis.csv
  ```

### Step 2: Data Cleaning
- Use the Python script in `scripts/` to clean the extracted data:
  ```bash
  python scripts/data_cleaning.py
  ```

### Step 3: Visualization
- Load the cleaned data into Power BI or Excel to generate visualizations. Templates are provided in the `visuals/` folder.

## Deliverables
- **Interactive Dashboards**: Delivered through Power BI for live updates and stakeholder presentations.
- **Reports**: Generated in Excel for portability and quick distribution.
- **Insights**: Data-driven recommendations to improve patient outcomes and resource allocation.

## Contributing
Contributions are welcome! Please follow the steps below:
1. Fork the repository.
2. Create a new branch (`feature/your-feature-name`).
3. Commit your changes.
4. Push to the branch and submit a pull request.

## License
This repository is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions, feedback, or collaboration opportunities, please contact:
- **Name**: Chaanyah Laborde
- **Email**: chaanyahlaborde@gmail.com
- **LinkedIn**: [Your LinkedIn Profile URL]

---
**Empowering healthcare providers and researchers with actionable insights.**

