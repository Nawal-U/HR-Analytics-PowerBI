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
- <a href="https://github.com/Nawal-U/HR-Analytics-PowerBI/blob/main/PowerBI-dashboard.png">Dashboard</a>

## Key Insights & Business Value
- The data indicates an average 91.83% presence rate, with 9.18% of WFH usage, reflecting strong attendance and growing WFH trends.
- Fridays showed the highest WFH usage (11.7%), making them optimal for scheduling office maintenance or low attendance activities.
- An upward WFH trend highlights the opportunity for executives to adopt a hybrid work model, supporting operational cost reduction.

## Disclaimer
The dataset used in this project was sourced from a YouTube learning project, while the dashboard design, data modeling, and insights were independently developed.

