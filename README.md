# Poultry Mortality & Disease Tracking – Power App Solution

Built for: Organo Group Poultry Company
Developed by: Aya Tarek
Technology Stack: Power Apps (Canvas App), Microsoft Dataverse, Power Fx, Power BI-ready backend

📍 Overview

This project is a Dataverse-powered Power App designed to digitalize the collection, validation, and monitoring of poultry mortality and disease records across multiple farms.
The app enables field workers to submit daily records, while managers can instantly review, verify, and analyze data — all through a centralized cloud environment.

🧠 Core Features
✔ 1. Dataverse-Centric Architecture

The heart of the project is a fully structured Dataverse backend:

Relational tables

Hierarchical category → condition tables

Lookup dependencies

Searchable fields

Conditional & calculated columns

Custom views for optimized filtering and analytics

Dataverse ensures reliability, scalability, and enterprise-level data consistency.

✔ 2. Power Apps Canvas App (4 Main Pages)
1. Welcome Screen

Simple UI with two main paths:

Death Records Tracking

Diseases Records Tracking

2. Death Records Module

Gallery view that loads Dataverse records in real time

Full record editing, validation, and deletion

"Add New" feature for inserting new rows

Power Apps Accordion Component used to separate death categories

Each accordion panel displays conditions based on Dataverse hierarchy

3. Disease Records Module

Category selection leading into condition drill-down

Driven entirely by Dataverse hierarchical tables

Allows dynamic viewing of changing condition values

Clean, intuitive data-entry form

4. Success Screen

Displayed after:

Submitting new entries

Updating existing records

Deleting records

Provides clear and positive confirmation of action.

⚙️ Technical Details
Backend (Dataverse)

Multiple interconnected tables

Hierarchical relationships for categories and conditions

Calculated columns based on other fields

Data types assigned properly (text, date, number, lookup, choice)

Business rules applied for validation

Centralized views for Power BI reporting

Frontend (Canvas App)

Power Fx logic for navigation, validation, conditional visibility

Accordion control to break down categories

Gallery search & filter

Editable forms with color-coded indicators

Icons and UI optimized for mobile usage

Success screen and confirmation logic implemented

🚀 Business Benefits

Real-time synchronization from farms → management

Higher accuracy due to structured Dataverse design

Faster reaction to disease outbreaks

Visibility across all farms and cycles

Can easily be extended to:

Vaccine tracking

Feed consumption

Cycle performance

Growth metrics

Ready for Power BI live dashboards

📊 Power BI Integration (Optional Expansion)

Because the system is fully built on Dataverse, it can be connected directly to Power BI to create dashboards for:

Mortality trends

Disease patterns

Farm performance

Cycle analysis

Geographical distribution

📱 Screenshots

(Add your images here)

Welcome Screen

Death Records Gallery

Death Entry Form

Diseases Drill-Down Screen

Success Screen

🏁 Conclusion

This app modernizes poultry health data management by combining the power of Microsoft Dataverse with the flexibility of Power Apps.
It provides a reliable, scalable, and user-friendly solution that supports Organo Group’s digital transformation goals.
