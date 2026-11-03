# Enterprise Business Intelligence & Executive Performance Analytics

An enterprise retail BI project designed to integrate business data and support
executive decision-making using SQL, Power Query, Power BI, and Excel.

## Business Objective

Create a centralized executive dashboard that helps leadership monitor sales,
profitability, customers, inventory, and operational performance across regions.

## Stakeholders

- CEO: business health, risks, and strategic opportunities
- CFO: revenue, profit, margins, and financial performance
- Sales Director: sales trends, products, customers, and regions
- Operations Manager: inventory, suppliers, and shipping
- Department leaders: team-specific performance and KPI monitoring

## Data and Tools

**Data sources:** [list source systems or dataset name]  
**Reporting period:** [start date] to [end date]  
**Tools:** SQL ([MySQL/PostgreSQL]), Power Query, Power BI Desktop, Excel  
**Dataset grain:** [e.g., one row per order line]

Expected business entities include Orders, Customers, Products, Categories,
Suppliers, Inventory, Employees, Regions, Shipping, and a Calendar table.

## Project Workflow

1. Document business requirements and KPI definitions.
2. Design the relational structure and ERD.
3. Extract and analyze data using SQL.
4. Clean and transform data using Power Query.
5. Build a star-schema model and date dimension.
6. Create DAX measures for business KPIs.
7. Build interactive executive dashboards.
8. Validate results, summarize findings, and recommend actions.

## Dashboard Pages

1. **Executive Overview** — revenue, profit, orders, customers, margins,
   growth, and regional performance.
2. **Sales Performance** — monthly and quarterly sales, product and category
   rankings, and regional comparisons.
3. **Customer Analytics** — customer segments, repeat purchases, estimated
   lifetime value, and customer growth.
4. **Inventory Analytics** — stock status, low-stock products, turnover, and
   supplier performance.
5. **Executive Scorecard** — KPI status, target vs. actual, risks, and actions.

## Key Findings

- Revenue: [verified result and comparison]
- Profit and margin: [verified result]
- Strongest region/category: [finding]
- Product or inventory concern: [finding]
- Customer insight: [finding]
- Main business risk: [finding]

## Repository Structure

- `README.md`
- `documentation/Business_Requirements_Document.md`
- `documentation/Data_Dictionary.md`
- `documentation/Dashboard_User_Guide.md`
- `documentation/Technical_Documentation.md`
- `presentation/Executive_Summary_Presentation.pptx`
- `sql/` — queries and scripts
- `powerbi/` — Power BI report, if shareable
- `data/` — only data approved for sharing
- `screenshots/` — report images

## Limitations

Project findings depend on the source data’s accuracy and completeness.
Estimated lifetime value, repeat purchase, and inventory metrics require clear
definitions and appropriate historical coverage. Document any unavailable
fields, assumptions, and known data-quality issues.

