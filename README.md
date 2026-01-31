# HR Analytics dashboard for AtliQ
## Project Objectives
- Monitor overall Presence %, WFH %, and SL %
- Analyze attendance trends across time and days of the week
- Enable employee-level and date-level drill-down
- Support strategic HR, event, and infrastructure planning

## Dataset used
- <a href="https://github.com/Nawal-U/HR-Analytics-PowerBI/blob/main/Dataset">Dataset</a>

## Tools & Techniques
- Power BI Desktop
- DAX for dynamic KPIs and aggregations
- Power Query (M) for data cleaning and transformation
- Reusable Power Query template for monthly data refresh
- Excel as the source system

## Data Preparation & Automation
All monthly attendance files followed an identical Excel structure. Therefore, data cleaning and transformation were performed once using Power Query and converted into a reusable template. This approach allows new monthly data to be refreshed without reapplying transformations, ensuring consistent data quality, reduced manual effort, and scalable report maintenance.

## Dashboard
- <a href="https://github.com/Nawal-U/HR-Analytics-PowerBI/blob/main/PowerBI-dashboard.png)>Dashboard</a>

## Key Insights & Business Value
- The dashboard helps identify days with maximum employee presence, allowing HR to schedule trainings, meetings, and engagement activities when participation is likely to be highest.
- A clear pattern shows higher WFH adoption toward the end of the week, particularly on Fridays. This insight enables facilities teams to schedule maintenance, electrical work, or office upgrades with minimal disruption.
- The increasing trend in WFH usage indicates that the organization could benefit from a structured hybrid work model, balancing in-office collaboration with remote flexibility.
- Understanding attendance patterns helps HR and management optimize workspace utilization, reduce unnecessary facility costs, and plan resources more efficiently.
- The dashboard empowers HR leaders to move from intuition-based decisions to evidence-based workforce planning.

## Disclaimer
The dataset used in this project was sourced from a YouTube learning project, while the dashboard design, data modeling, and insights were independently developed.

