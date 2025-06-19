# PROJECT-
	Title: Return Rate Dashboard Project
	Introduction
In this project, I tried to analyze and visualize the return rates of the products in order to understand customer behavior, product performance, and operational problems. The dashboard gives insights into return percentages based on categories, reasons for returns, regional distribution of orders, and monthly trends. Through this analysis, areas where quality control, logistics, and customer satisfaction strategies can be improved can be determined.

	Abstract
Product returns are a metric that is critical to revenue and customer loyalty. From analyzing return data by category, geography, and reason, we derive useful insights into root causes such as product flaws, fit issues, or customer dissatisfaction. The dashboard further identifies top-performing product categories and geographies, which help decision-makers create action plans.

	Tools Used
 	Microsoft Excel – for preliminary data cleaning and formatting

 	Power BI (Power Query Editor) – for:

 	Data transformation

 	DAX measures & calculated columns

 	Building interactive visualizations and KPIs

	Steps Involved in Building the Project
 	Step 1: Data Cleaning & Structuring (Excel)
Cleaned out missing/null values

Normalized date and category formats

Confirmed numeric consistency in return and order columns

 	Step 2: Importing and Transforming Data (Power BI - Power Query Editor)
Imported Excel file into Power BI

Utilized Power Query Editor to:

Rename columns

Eliminate invalid rows

Develop clean schema for analysis

 	Step 3: Creating New Columns & DAX Measures
Calculated metrics:

Return % = (Total_Returns / Total_Orders) * 100

Total_Returns, Total_Orders – using SUM

Segmented returns by product category and date

 	Step 4: Building the Dashboard (Visualizations)
Return % by Product Category – Bar chart of category-wise returns

Donut Chart by Return Reason – Visualizes proportion of defective, wrong items, etc.

Map by User Location – Picks up order density by geography

KPI Cards – Shows total return %, order count, and return count

Tabular view – Monthly breakdown for trend analysis

 	Conclusion
The dashboard presents an overall summary of return trends by products and regions. Home and Clothing products have the most return rates, with defective products constituting approximately 50% of total returns. Dynamic interaction with return information through the use of Power BI facilitated finding problems in customer satisfaction and quality control. The project provides actionable recommendations that can be implemented by supply chain teams, product managers, and customer service to decrease return rates and enhance overall performance.
