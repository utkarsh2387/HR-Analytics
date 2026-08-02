# HR-Analytics
### End-to-end HR analytics solution built on Power BI and Microsoft Fabric — with enterprise-grade column-level security on sensitive compensation data.

Every company loses people. Few can tell you who, from where, and why fast enough to act on it — and fewer still can do that without exposing sensitive compensation data to everyone who opens the report.

This project simulates that gap — an HR analytics dashboard that lets a business/HR stakeholder go from "attrition feels high" to "attrition is highest among overtime employees in Sales, in the ₹[X] salary band" in under 3 clicks, with zero SQL knowledge required — while ensuring only authorized roles can see individual compensation figures.

The semantic model is hosted and managed in Microsoft Fabric, with the Power BI report connected live to it — the same setup used in enterprise environments where the data model, security, and reporting layers are deliberately separated.

## Dashboard Preview
![Dashboard Overview](https://github.com/utkarsh2387/HR-Analytics/blob/main/images/Overview.png)
![Dashboard Overview](https://github.com/utkarsh2387/HR-Analytics/blob/main/images/Deepdive.png)


## What's inside

### Page 1 — Overview
Component	            Purpose
5 KPI cards	          Headcount, Avg Monthly Income, Attrition Rate, Employees Left, Avg Tenure of Leavers
Treemap	              Left vs. Stayed employee split at a glance
Decomposition Tree	  Drills Total Attrition → Department → Job Role → Salary Band
Bar Chart	            Attrition Rate by Department
Pivot Tables (x2)	    Headcount/Attrition by Education Field and by Age Group
Slicers	              Cross-filter the entire page by Department, Gender, and more

Page 2 — Deep Dive
Component	             Purpose
4 Bar Charts	         Attrition Rate by OverTime, Business Travel, Marital Status, and Gender
Pivot Tables (x2)	     Headcount/Attrition breakdowns by Education Field and Age Group
Navigation	           One-click return to Overview page

Scope at a glance: 2 dashboard pages · 5 KPIs · 9 dimensional breakdowns · 1 drill-down hierarchy · fully cross-filtered
