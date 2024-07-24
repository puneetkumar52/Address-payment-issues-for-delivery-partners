GoLogistics: Address Payment Issues for Delivery Partners
Introduction

GoLogistics, a third-party logistics (3PL) company, manages various supply chain functions for e-commerce clients. This includes warehousing, transportation, order fulfillment, and more. A core aspect of GoLogistics' service is collaborating with delivery partners across specific regions within cities.

Problem Statement

A recent payment issue with delivery partners has raised concerns about potential overpayments. The finance team has suspended payments while the situation is investigated.

Your Role

You are tasked with analyzing payment data to:

Verify claims of overpayment.
Identify the underlying causes of these discrepancies.
Propose solutions that address the concerns of both operations and finance teams.
Objective

Our primary objective is to:

Rectify payment discrepancies.
Ensure fair compensation for our delivery partners.
Foster improved collaboration between internal teams and external vendors.
Enhance sustained operational effectiveness.
Approach

We will analyze data from the following sources to achieve our objectives:

payouts_table: Partner per kg rates and weight delivered (December 2018)
business_partners: Partner information (vehicles, purchase year, ownership)
locations: Delivery station information (branch name, city, region)
vehicle_details: Vehicle data (type, capacity, price)
maintenance: Driver expenses per vehicle type
Expected Deliverables

A comprehensive presentation or report for senior leadership.
The report will compile all research, analysis, findings, and recommendations.
Data Description

The downloaded workbook contains several tabs with detailed information:

payouts_table:
bp_id (Unique partner ID)
bp_name (Partner name)
branch_name (Delivery station/branch)
per_kg_rate (Contracted rate per kg for deliveries)
kg_delivered (Weight delivered in December 2018)
business_partners:
bp_id (Unique partner ID)
bp_code (Partner alphanumeric code)
bp_name (Partner name)
bp_joining_date (Partner joining date)
branch_id (Delivery station ID)
vehicle_type_id (ID of the vehicle)
ownership_type (Vehicle purchase/ownership type)
vehicle_purchase_year (Year of vehicle purchase)
locations:
branch_id (Primary key for location data)
branch_name (Delivery station name)
cluster_code (Cluster/city/region code)
city (City of the delivery station)
vehicle_details:
vehicle_type_id (Unique ID for vehicle type)
vehicle_type (Type of vehicle owned)
vehicle_mileage (Mileage for vehicles in the Ahmedabad region)
vehicle_capacity_tons (Maximum vehicle capacity in tons)
ex_showroom_price (Vehicle price at retail including dealer margins)
insurance_rto (Insurance and RTO costs)
maintenance:
vehicle (Vehicle name)
driver_expenses (Monthly driver expenses in rupees)
Dataset Schema

A diagram will be included in the final report to illustrate the relationships between the tables in the provided data set.

Getting Started

This project will involve data cleaning, exploration, analysis, and visualization to identify the root causes of payment discrepancies. The final report will present our findings and propose solutions to ensure accurate and fair partner compensation while maintaining operational efficiency.
