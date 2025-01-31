# BANK CHURN ANALYSIS

### Report Link: [https://app.powerbi.com/groups/me/reports/cff8eb01-1803-4a29-86e2-7ac535fdb058?experience=power-bi]
### Dashboard Link : [https://app.powerbi.com/home?experience=power-bi]

## Problem Statement

This dashboard helps banks to analyze customer churn and retention. It provides information about the total customers and the list of customers that are active and the list of customers that are inactive and also it gives further information like the number of users having credit cards or with no credit cards and the number of customers that retained successfully and number of customers that exited from services.
	
So in this report I created multiple dropdowns to filter based on the year and the month and geographic location and even gender.
	
So finally I did multiple analysis like did churn analysis in which it displays the percentage of churn based on year and month And also I compared between the retention rate and churn analysis by percentage in every year and also I displayed a report showing the data about the customers by geographic location.


### Steps Followed

- Load Data into Power BI Desktop : The dataset was sourced from various tables: Active Customer, Bank_Churn, CreditCard, CustomerInfo, ExitCustomer, Gender, and Geography.

- Data Cleaning & Preparation: Opened Power Query Editor to profile the dataset. Ensured data quality by checking column distribution, column quality, and column profiling.

- Missing values in non-critical columns (e.g., Bank DOJ) were ignored as they had minimal impact.

- Data Transformation: Merged and related data from multiple sources using Fact table. Created calculated columns for metrics like Active customer list and exit customer list

- Data Modeling: Relationships between tables were established to ensure seamless filtering and calculation.

- Visualizations Created: pie charts, slicers, and card visuals were added to highlight churn rates, customer demographics, and factors affecting churn.
    - Heatmaps were used to analyze the impact of geography on churn.
    - Pie charts visualized segments like active/inactive members, score distributions.
- Published to Power BI Service: The report was published for wider accessibility and collaboration.
- Key Metrics and Calculations
  Churn Rate: (Total Customers at the Start of the Period Number of Customers Lost in a Period)*100

![Snap_Count](https://github.com/user-attachments/assets/b9cfe474-a435-4ec6-946c-223af6876274)



### Final Report
A comprehensive report was created and published to Power BI Service. The dashboard provides actionable insights for the bank for churn analysis based on gender region and also it provide all slicers to filter data accordingly like(Year, Month, Geography, Gender, Active, Inactive) and also assigned Roles for RLS(Row-Level Security based on geography Location).

![Snap_Count](https://github.com/user-attachments/assets/84b3be27-c1ee-4bef-8333-33aede1b74e0)





