**Project Overview**

This project was designed as an end-to-end simulation of an Inside Sales Information System. It covers the full workflow from SQL Server database design and data structuring to Power BI dashboard development, SharePoint integration, and scheduled refresh through Power BI Service.

The goal of the project was not simply to build a dashboard, but to understand how transactional sales data can be structured, validated, transformed into business-facing KPIs, and delivered through an automated reporting workflow.


**Project Overview**

This project was designed as an end-to-end simulation of an Inside Sales Information System. It covers the full workflow from SQL Server database design and data structuring to Power BI dashboard development, SharePoint integration, and scheduled refresh through Power BI Service.

The goal of the project was not simply to build a dashboard, but to understand how transactional sales data can be structured, validated, transformed into business-facing KPIs, and delivered through an automated reporting workflow.

**What Problem This Project Solves**

This project solves several common business reporting issues:

Reduces dependency on manually updated spreadsheets for reporting
Creates a structured SQL-based data architecture for sales operations
Improves visibility over quotations, orders, and KPI performance
Enables a more repeatable and scalable reporting workflow
Demonstrates how reporting can move from fragmented manual work to a connected BI process

**Data Structure Designed**

To simulate a realistic inside sales environment, I designed the database from the ground up in SQL Server.

The data model included:

Database creation in SQL Server
Schema design for better logical organization
Table creation for core operational entities
Data insertion and validation
KPI views created for reporting purposes

The structure was designed around sales-related business objects such as:

Customers
Products
Salespersons
Quotations
Orders
Order lines

I also created SQL views to support reporting logic for quotation and order analysis, which allowed Power BI to consume cleaner and more business-ready datasets.

**Why These KPIs Were Built**

The KPIs were selected to reflect the most relevant performance indicators in an inside sales workflow.

The dashboard includes:

Total Sales to track overall revenue performance
Total Orders to monitor order volume
Total Quotes to measure quotation activity
Gross Profit to evaluate margin performance
Quote Conversion Rate to understand how effectively quotations are converted into actual business
Quote Status Analysis to track whether quotations are won, pending, or lost

These KPIs were chosen because they provide a practical view of sales efficiency, operational activity, and business performance in a quotation-to-order process.

Tools and Workflow Integration

This project connects multiple tools across the workflow.

**Main tools used:**
[ Hidden ]

**Personal Summary**
I developed an end-to-end workflow from the ground up, starting with database creation in SQL Server and continuing through schema design, table creation, data insertion, data validation, and KPI view development for orders and quotations. In Power BI, I created DAX measures within the data model and built KPI cards for Total Sales, Total Orders, Total Quotes, Gross Profit, and Quote Conversion Rate, along with interactive charts and slicers to support business analysis. I also published the dashboard to SharePoint.

This process took time, as I had to work through each step independently and understand how a Power BI dashboard and semantic model function in practice. I also came to understand that, in a corporate environment where a gateway is already provided, connecting data source credentials and setting up scheduled refreshes would be much more straightforward than building and configuring an on-premises gateway myself through Power BI Service for publishing and automated refresh purposes.

Overall, this project was designed to simulate an inside sales information system from the ground up by structuring transactional data in SQL Server, creating Excel-based operational files for business use, building KPI-driven Power BI dashboards, and automating report refresh workflows with ----Great Automation Tool. Through this work, I developed a solid understanding of SQL Server and SQL Server Management Studio (SSMS), and I would be eager to apply these skills in an industrial setting, preferably within a Dubai-based consumer electronics company handling quotations, orders, CRM-related operations, and similar workflows. My goal would be to reduce manual tasks and reporting burdens by building a more efficient SQL-based data architecture supported by clear and actionable Power BI dashboards.

**Manual Work Reduced**

Although this project was built as a simulation, the intended business value is clear.

Compared with a manual reporting process, this structure helps reduce time spent on:

manually consolidating sales data
checking quotation and order records one by one
rebuilding Excel summaries repeatedly
manually updating dashboard visuals
distributing updated reporting files across teams

In a real business environment, this type of workflow could significantly reduce repetitive reporting effort and improve reporting consistency.

If deployed with live operational data, the process could save hours of recurring manual work each reporting cycle.

**Technical Challenges and Constraints**

One of the main technical challenges in this project was understanding how Power BI semantic models interact with data sources after publishing.

A particularly important challenge was configuring the on-premises gateway required to connect Power BI Service to a local SQL Server data source. Since the source database was hosted locally, publishing the report alone was not enough. I had to understand:

how the semantic model works after publishing
why scheduled refresh fails without proper gateway configuration
how to connect data source credentials
how gateway mapping affects refresh behavior
how service-side connection issues differ from desktop-side development

This part of the project was especially valuable because it provided practical insight into how reporting works beyond dashboard design.

**What I Learned**

Through this project, I developed practical understanding of:

SQL Server database creation and structure
schema and table design
data insertion and validation logic
SQL views for reporting
Power BI data modeling and DAX measures
KPI dashboard design
semantic model behavior in Power BI Service
gateway-based publishing and refresh setup
SharePoint-based file management for reporting assets

Most importantly, I learned how BI reporting is not only about visuals, but also about data structure, workflow reliability, and system connectivity.

**Sharepoint Link**

https://audubai-my.sharepoint.com/my?id=%2Fpersonal%2Fhyunmin%5Fpark%5Fmymail%5Faud%5Fedu%2FDocuments%2FSales%20Dashboard%20Demo&viewid=87ca6c56%2Dcd2c%2D4170%2Db1bb%2Dd721c5396b8e

Will be refreshed every sunday at UTC + 4 ( UAE Time )
