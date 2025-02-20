# Capstone-Project---Python

This project focuses on data processing, transformation, and analysis using Python. It involves working with multiple datasets, handling missing values, restructuring data, and applying business logic to employee roles, project costs, and designations.


📊 Project Objectives<br/>

--Create and save structured dataframes from raw datasets.<br/>
--Handle missing values in project costs using a running average.<br/>
--Split full names into first and last names for better organization.<br/>
--Merge multiple datasets into a single consolidated DataFrame.<br/>
--Assign bonuses based on project completion and update employee roles accordingly.<br/>
--Promote and demote employees based on project success or failure.<br/>
--Filter employee records based on city names for targeted analysis.<br/>


📂 Datasets Used

The project is based on three datasets:

--Employee Data: Contains details about employees, their ID, name, gender, city, and age.<br/>
--Seniority Level Data: Tracks designation levels of employees.<br/>
--Project Data: Stores information about projects, costs, and their status (Finished, Ongoing, Failed).<br/>


📌 Key Tasks & Implementations

✅ Data Cleaning & Storage: Created dataframes and saved them as .csv files.<br/>
✅ Handling Missing Values: Replaced NaN values in project costs using a running average with a loop.<br/>
✅ Data Transformation: Split full names into First Name and Last Name, removing the original column.<br/>
✅ Merging DataFrames: Combined employee, seniority level, and project datasets into a unified DataFrame.<br/>
✅ Business Logic Implementation:<br/>
Assigned 5% bonus for completed projects.<br/>
Demoted employees for failed projects and removed ineligible records.<br/>
Promoted employees above age 29 by one designation level.<br/>
✅ Data Filtering: Extracted employees from cities containing 'o' in their name.


🛠️ Technologies Used

--Python – Core programming language.<br/>
--Pandas – Data manipulation and transformation.<br/>
--NumPy – Numerical operations and missing value handling.<br/>
--Jupyter Notebook – For interactive execution of code.<br/>


🚀 Future Enhancements

--Automate data processing pipeline for real-time updates.<br/>
--Integrate Matplotlib/Seaborn for visualizing insights.<br/>
--Expand business logic rules to track employee performance over time.<br/>
