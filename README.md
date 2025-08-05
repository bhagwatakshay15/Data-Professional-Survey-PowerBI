# 📊 Data Professional Survey Breakdown

## 📄 Project Overview  
This Power BI project provides a comprehensive breakdown and analysis of a survey conducted among data professionals. The dashboard aims to offer insights into various aspects of data professionals' careers, including their geographical distribution, perceived difficulty in entering the data field, work/life balance, salary satisfaction, preferred programming languages, and average salaries across different job titles.

---

## ✨ Features  
The interactive dashboard allows users to explore key trends and metrics:

- **Geographical Distribution**: Visualizes the country of survey takers, highlighting major regions like the United States and India.
- **Difficulty to Break into Data**: A donut chart illustrating the perceived difficulty levels (Easy, Difficult, Very Difficult, Neither easy nor difficult) in entering the data field.
- **Key Performance Indicators (KPIs)**: Displays the total count of survey takers and their average age.
- **Satisfaction Scores**: Gauges Work/Life Satisfaction and Salary Satisfaction through intuitive gauge visuals.
- **Favorite Programming Language**: A stacked bar chart showing the distribution of preferred programming languages among respondents.
- **Average Salary by Job Title**: A bar chart presenting the average salary for various data-related job titles such as Data Scientist, Data Engineer, Data Architect, Data Analyst, and more.
- **Interactive Filtering**: All visuals are interconnected, allowing cross-filtering by clicking on any data point.

---

## 💾 Data Sources  
The data for this Power BI project is sourced from a survey dataset. This is a structured dataset (file type- xlsx) containing the survey responses and can be accessed [here.](https://github.com/bhagwatakshay15/Data-Professional-Survey-PowerBI/blob/main/DataProfessionalSurvey.xlsx)

---

## 🛠️ Setup and Usage  

### Prerequisites  
- Power BI Desktop (latest version recommended)

### Opening the Report  
1. Download the `.pbix` file (e.g., [`DataProfessionalSurvey.pbix`)](https://github.com/bhagwatakshay15/Data-Professional-Survey-PowerBI/blob/main/DataProfessionalSurvey.pbix) 
2. Open the file using Power BI Desktop

### Interacting with the Dashboard  
- Click on any visual element (e.g., a country in the tree map, a bar in the programming language chart) to filter the entire dashboard and see related insights.  
- Observe the KPIs and satisfaction scores for overall trends.

---

## 📈 Dashboard Overview  
The dashboard is designed as a single, comprehensive view, presenting various facets of the survey data:

- **Top Left**: Country of Survey Takers (Tree Map)  
- **Top Center**: Difficulty to Break into Data (Donut Chart)  
- **Top Right**: Key Performance Indicators (Count of Survey Takers, Average Age) and Satisfaction Scores (Work/Life, Salary)  
- **Bottom Left**: Favorite Programming Language (Stacked Bar Chart)  
- **Bottom Right**: Average Salary by Job Title (Bar Chart)

---

## 🔑 Key Metrics and Definitions  

- **Count of Survey Takers**: The total number of individuals who completed the survey.  
- **Average Age of Survey Takers**: The average age of all respondents.  
- **Work/Life Satisfaction Score**: An aggregated score representing respondents' satisfaction with their work-life balance (likely on a scale, e.g., 1-10).  
- **Salary Satisfaction Score**: An aggregated score representing respondents' satisfaction with their current salary (likely on a scale, e.g., 1-10).  
- **Average Salary**: The calculated average annual salary for each specified job title.

---

## 🔄 Data Transformation and Cleaning  

Significant effort was put into transforming and cleaning the raw survey data to ensure accuracy and usability within the Power BI model. Key steps included:

- **General Data Transformation**: Applied various transformations in Power Query to reshape the data into a suitable format for analysis. This involved standardizing text fields, adjusting data types, and ensuring consistency across columns.  
- **Cleaning of Dataset**: Addressed inconsistencies, duplicates, and irrelevant entries to improve data quality.  
- **Yearly Salary Fix**: The 'Yearly Salary' column was specifically processed. This involved splitting columns (e.g., if salary ranges were in a single text field, they were split into separate minimum and maximum columns) and then transforming these values into a consistent numerical format for accurate calculations.  
- **Replacing Null Values**: Identified and handled missing data points (nulls) across various columns. Null values were replaced with appropriate defaults (e.g., zero for numerical fields, "Unknown" or "N/A" for categorical fields) to prevent errors in calculations and visualizations.
