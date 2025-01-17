# Hotel Bookings Data Analysis

## Project Description
This project focuses on the analysis of the `HotelBookingDemandDatasets.pdf` article and the `hotel_bookings.csv` dataset, providing insights through a rigorous analysis and visualization process.

## Contents
1. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
2. [Conceptual Diagram Design](#conceptual-diagram-design)
3. [Table Creation](#table-creation)
4. [Star Schema Implementation](#star-schema-implementation)
5. [Dashboard Design and Development](#dashboard-design-and-development)
6. [PDF Analysis](#pdf-analysis)

## PDF Analysis
The detailed analysis of the `HotelBookingDemandDatasets.pdf` article can be found [here](HotelBookingDemandDatasets.pdf).

## Exploratory Data Analysis (EDA)
The EDA was performed in Python, analyzing the variables into `hotel_bookings.csv` dataset. This initial analysis helps identify patterns and prepare the data for further modeling.
![EDA](images/correlation-matrix.png)

## Conceptual Diagram Design
Once on the EDA was completed, a conceptual diagram was designed to facilitate understanding and organizing the relationships between different variables into dataset.
![Conceptual Diagram](images/conceptual_model.png)

## Table Creation
Several tables were created to efficiently structure the data:
- **Dimension Tables**: Using Python to extract and define dimensions.
  ![Python - Dim Table](images/dim_python_1.png) 
  ![Python - Dim Table](images/dim_python_2.png) 
- **Fact Table**: Created with Talend to join dimensions and load fact table.
  ![Talend - Fact Table](images/talend_fact.png) 

## Star Schema Implementation
The star schema was implemented on two data tools:
- **Microsoft SQL Server Database**: For data storage and management.
- **Power BI**: For reporting and dashboard creation.
Additionally, Power Query was used to optimize the data transformation process.

## Dashboard Design and Development
The interactive dashboard was designed and developed in Power BI, using advanced techniques such as:
- **Bookmarks**
- **Field Parameters**
- **Calculation Groups**
- **DAX for creating advanced measures**
![Dashboard](images/dashboard.png)
![Dashboard_Menu](images/dashboard_menu.png)
![Slicer_Measure](images/dashboard_measure_slicer.png)

This approach provides a dynamic and detailed visualization of the data, allowing users analyze the information interactively.

---

I hope this project provides valuable insights and a greater understanding of patterns in hotel bookings!
