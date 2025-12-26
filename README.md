# customer-support-ticket-triage
Week-1 Internship Project
# Project Title: Customer Support Ticket Triage System

## DescriptionThis project focuses on analyzing and processing customer support ticket data using Python. 
The dataset is first loaded and explored to understand the number of rows, columns, missing values, and to view sample ticket messages.
Ticket messages are then cleaned by converting text to lowercase, removing special characters, and eliminating extra spaces to ensure consistency for further analysis.
A rule-based classification approach is used to categorize each ticket.

Based on specific keywords present in the ticket messages, priority levels are assigned
Service Level Agreement (SLA) hours are calculated for each ticket according to its priority, and the due time is determined using the ticket creation time and SLA hours.
Finally, a support manager report is generated to summarize ticket details, priorities, SLA status, and due times. The processed data and report are exported as a CSV file for further use and reporting.

## Tools Used
- Google Colab
- Python
- Pandas
- NumPy
- Matplotlib 

## Files in this Repository
- `Week1_Customer_Support_Triage.ipynb` – Google Colab notebook
- `final_support_tickets(3)` – Processed output data

## How to Run
Open the notebook in Google Colab and run all cells.

