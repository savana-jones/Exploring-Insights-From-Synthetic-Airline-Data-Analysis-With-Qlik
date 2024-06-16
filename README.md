# Exploring-Insights-From-Synthetic-Airline-Data-Analysis-With-Qlik

1. Introduction
 1.1 Overview
The project "Exploring Insights from Synthetic Airline Data Analysis with Qlik" utilizes a synthetic airline dataset from Kaggle to extract valuable insights using Qlik, a powerful business intelligence and data visualization tool. The dataset includes various aspects of airline operations such as passenger information, airport details, flight schedules, and flight status. By employing Qlik’s advanced analytical capabilities, the project aims to uncover patterns, trends, and correlations within the data to support decision-making processes for airlines, airports, and related stakeholders.

 1.2 Purpose
The purpose of this project is to:
- Optimize Revenue: Analyze historical ticket sales data to identify peak travel times, popular destinations, and effective pricing strategies.
- Enhance Operational Efficiency: Evaluate flight schedules, passenger flows, and luggage handling processes to identify and address operational bottlenecks.
- Improve Customer Experience: Understand customer preferences and satisfaction levels to enhance service quality, personalize offerings, and tailor marketing campaigns.

1.3 Technical Architecture
The technical architecture of the project includes:
- Data Source: Synthetic airline data from Kaggle stored in CSV files.
- Data Ingestion: Importing data into Qlik Sense using built-in connectors.
- Data Processing: Cleaning, transforming, and preparing the data for analysis within Qlik Sense.
- Visualization: Creating interactive visualizations and dashboards in Qlik Sense.
- Analysis: Using Qlik Sense’s analytical tools to derive insights and generate reports.

 2. Define Problem/Problem Understanding
 2.1 Specify the Business Problem
The business problems addressed by this project include:
- Revenue Leakage: Identifying and mitigating factors leading to suboptimal revenue generation.
- Operational Inefficiencies: Detecting and resolving inefficiencies in flight operations, passenger handling, and luggage processing.
- Customer Dissatisfaction: Recognizing and addressing factors contributing to customer dissatisfaction and enhancing the overall passenger experience.

2.2 Business Requirements
The business requirements for this project are:
- Data Integration: Seamless integration of synthetic airline data into Qlik Sense.
- Interactive Dashboards: Creation of interactive dashboards that allow stakeholders to explore data insights dynamically.
- Actionable Insights: Generation of actionable insights to inform strategic decision-making.

2.3 Literature Survey
A review of existing literature and case studies related to airline data analysis, revenue management, operational efficiency, and customer satisfaction will provide context and best practices for the project.

 3. Data Collection
 3.1 Collect the Dataset
The synthetic airline dataset from Kaggle includes various components such as:
- Passenger Information: Passenger ID, names, gender, age, nationality.
- Airport Details: Airport name, country code, country name, continent.
- Flight Schedules: Departure date, arrival airport, pilot name.
- Flight Status: Status of flights such as on-time, delayed, or cancelled.

 3.2 Connect Data with Qlik Sense
To connect the data with Qlik Sense:
1. Open Qlik Sense: Start Qlik Sense and navigate to the Data Load Editor.
2. Add Data: Click on “Add Data” and select the CSV file from the dataset.
3. Load Data: Load the synthetic airline data into Qlik Sense for further processing.

4. Data Preparation
 4.1 Prepare the Data for Visualization
Data preparation steps include:
- Cleaning: Removing duplicates, handling missing values, and correcting data inconsistencies.
- Transformation: Aggregating data, creating calculated fields, and formatting data appropriately for visualization.
- Validation: Ensuring data accuracy and consistency before creating visualizations.

 5. Data Visualizations
 5.1 Visualizations
Various visualizations are created to explore and analyze the data:
- Bar Graphs: Plotting flight status (on-time, delayed, cancelled) against months.
- Line Charts: Analyzing trends in ticket sales over time.
- Pie Charts: Displaying the distribution of passenger demographics.

6. Dashboard
 6.1 Responsive and Design of Dashboard
The dashboard design includes:
- User-Friendly Interface: Intuitive and easy-to-navigate layout.
- Responsive Design: Ensuring compatibility across different devices and screen sizes.
- Interactive Elements: Filters, drill-down options, and dynamic updates for enhanced user interaction.

7. Report
7.1 Report Creation
To create a report:
1. Select Insights: Choose key insights and visualizations from the dashboard.
2. Format Report: Arrange the selected insights in a logical sequence, adding explanatory text and context.
3. Export Report: Generate the report in a suitable format for distribution to stakeholders.

 8. Performance Testing
 8.1 Amount of Data Rendered: 97739 rows of cleaned data.
 8.2 Qlik Sense Script: Added a snippet to remove the null values from the "Arrival Airport" column.
 8.3 Utilization of Data Filters
Filtered the dataset to obtain meaningful insights and to create new columns for further utilization.
 8.4 No. of Visualization/Graphs: 16 graphs and visualizations have been included to provide better insights of the dataset.

## A quick demo link of the dashboard is attached
https://drive.google.com/file/d/1BWwPFIRYTMZK1TdULUvlXDin8tEsk0YW/view?usp=drive_link

