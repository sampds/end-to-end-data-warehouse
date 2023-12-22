# End-to-End Data Warehouse

## Description

The IST 722 project was a comprehensive, intense group effort completed over the course of a week to develop a data warehouse, integrating Fudgeflix and Fudgemart for enhanced business intelligence. This involved creating an intricate ETL process, crucial for staging, transforming, and loading data into the warehouse. We then created dashboards in PowerBI.

### Motivation

Driven by intellectual curiosity and the desire to apply the skills learned in class, we worked morning until late into the night for a week to plan, build, load, and analyze our data warehouse.

## Business Problems Addressed

Scope of the project encompassed various business aspects, including sales, inventory, customer service, and order fulfillment. We chose to make our key goal to analyze order fulfillment for Fudgemart and Fudgeflix from a unified data source, focusing on product lead times, departmental performance, and shipping destinations.

### Learning Experience

- This project was a foundational learning experience in database design and data management. It honed my skills in SQL and R, particularly in the context of real-world application.
- I learned to work with stakeholders throughout the business and ask the right questions to learn relationship among data and the right business cases to address.
- I gained valuable insights into the ethical aspects of data management, especially concerning privacy and security in handling personal information.

## Impact and Results

- Successfully established a robust and efficient ETL process, facilitating effective data management in a warehouse environment.
- Enhanced data accessibility and reliability, supporting informed decision-making.
- Empowered the business with analytics capabilities, providing tools for data visualization and decision-making. This included dashboards for monitoring fulfillment health and order fulfillment processes.
- Derived insights to address customer issues: reducie lead times for movie orders by capturing received dates, offer promotional discounts for high lead-time orders, and transform Fudgeflix into a full-fledged streaming service.

## Installation

To set up and use the data warehouse, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have the requisite programs, including the versions, which are outlined in the requirements.txt.
3. Follow instructions in the dimensional model documents and ETL documentation.
4. Connect the data warehouse to PowerBI, as we did, or another program of your choice, to work with the model. 

## Usage

### Business Intelligence

Use PowerBI, Tableau, etc. to examine the MOLAP cube; create KPIs and metrics to monitors, and carry out exploratory data analysis.

### Programming and Implementation 
Building the ETL pipeline in Visual Studio is fun, but also time-consuming, so if you want to see the end result without building out the control flows, look at our dashboard.

### Data Integration and Cleaning
The biggest challenge is integrating data from the two fictional companies, which have different business rules and data dictionaries.

## Credits

Developed with Daniel Caley, Michael Johnson and Jennifer Lammers Zimmer in IST 722, Data Warehouse.