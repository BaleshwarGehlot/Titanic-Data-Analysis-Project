# 🚢 Titanic Survival Analysis: End-to-End Data Project

### 📝 Project Overview
This project performs a comprehensive analysis of the Titanic dataset to identify factors influencing passenger survival. It demonstrates an end-to-end data workflow, from raw data cleaning to interactive dashboard creation.

### 🛠️ Tech Stack & Tools
* **Data Cleaning:** Python (Pandas, NumPy)
* **Visualization:** Power BI Desktop
* **Analysis:** DAX (Data Analysis Expressions)
* **Data Source:** Titanic Dataset (CSV)

### 🚀 Key Steps Taken

#### 1. Data Cleaning & Pre-processing (Python)
* Handled **Missing Values** for key columns like Age and Cabin.
* Performed **Feature Engineering** to create a 'FamilySize' column for deeper insights.
* Cleaned and formatted data types for seamless integration with Power BI.

#### 2. Data Visualization (Power BI)
* Developed an interactive dashboard with custom **DAX Measures**:
    * `Total Survivors`
    * `Survival Rate (%)`
    * `Gender-wise Distribution`
* Implemented **Gauge charts, Donut charts, and Slicers** for dynamic filtering by Passenger Class and Gender.

### 📊 Key Insights Discovered
* **Overall Survival Rate:** The analysis shows a survival rate of approximately **36%**.
* **Gender Impact:** Female passengers had a significantly higher survival rate compared to males.
* **Class Correlation:** First-class passengers had a higher probability of survival, showing a strong correlation between Pclass and survival outcomes.

### 📂 Repository Structure
* `Data/`: Contains the original and processed CSV files.
* `Scripts/`: Python Jupyter Notebook used for data cleaning.
* `Dashboard/`: The `.pbix` Power BI project file.
