# NYC-Project
NYC Taxi Emissions Analysis
This project analyzes the environmental impact of NYC taxi rides by estimating the total carbon emissions generated from taxi trips. Using Azure Databricks and PySpark, the project processes taxi trip data, calculates CO2 emissions for each ride based on the trip distance and fuel efficiency, and identifies trends in emissions based on the number of passengers and other factors.

Project Overview
Objective: Estimate CO2 emissions from taxi rides and analyze patterns in emissions.
Data Source: NYC Taxi & Limousine Commission trip data.
Tools Used: PySpark, Azure Databricks, Matplotlib, Pandas.
Key Features
Carbon Emissions Calculation: Uses the formula (Distance / 22) * 8.89 to estimate CO2 emissions per trip, where 22 MPG is the average fuel efficiency and 8.89 kg of CO2 is emitted per gallon of gasoline burned.
Passenger Group Analysis: Compares emissions from rides with 1-2 passengers versus rides with 3 or more passengers.
Daily Emissions Visualization: Plots total CO2 emissions per day to identify patterns in taxi emissions.
Instructions
Clone the repository:
bash
Copy code
git clone https://github.com/YourUsername/NYC-Taxi-Emissions-Analysis.git
Run the Databricks notebook: Follow the instructions in the notebook to process the data and generate emissions insights.
Visualize results: The notebook includes plots comparing emissions across different passenger groups.
Technologies Used
PySpark for big data processing.
Matplotlib for visualizations.
Azure Databricks for cloud-based data processing.
