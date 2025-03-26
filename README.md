# Excel Customer Care Centre Dashboard

## 1. Project Overview
This dashboard provides highly informative insights into a Customer Care Centre's sales performance by analyzing sales data across multiple regions, representatives and periods of time.  
It provides a simple, interactive, and intuitive layout to aid stakeholders track useful key performance indicators (KPIs), identify trends, reveal context and support informed decision making.

## 2. Features
- **Interactive Visualizations**  
  See specific data and highlight relevant information using conditional formatting options. 

- **Data Filters**  
  Interact with charts and graphs through the slicers.

- **Pivot Tables**  
  Aggregated information, grouped by specific attributes represented using Pivot Tables and DAX built Measures allowing for detailed analysis.

- **Formulas**  
  Excel formulas like =SUM(), =IF(), =XLOOKUP(), COUNTA(), etc. used in calculating and representating key information.

- **Performance Metrics**  
  Displays insightful KPIs like: % of Calls, Amount Rank, Call Rank.  
  These add crucial context while gauging performance.

- **Report**
  Contains the Dashboard displaying the various charts visualising key performance metrics that update in responce to the slicer.  

## 3. Installation
To use this Excel dashboard:

1. Download the following files from the repository:
   - **Customer Care Centre Dashboard.xlsx**
2. Open **Excel**.
3. Load the File:
   - Open the **"Customer Care Centre Dashboard.xlsx"** file in Excel.

## 4. Data Sources

### Source 1: `Customer Care Centre Dashboard.xlsx` (1.0 MB)
An .xlsx file with 4 Sheets:
1. **Data** - Contains the tabular data used in the dashboard. It contains 3 tables.
     - **calls** - The facts table containing information on Call ID, Duration, Customer ID, Representative ID, Date, Purchase Amount, Satisfaction Rating for each sale.
     - **customers** - Table containing information on Customer ID, Gender, Age, City.
       
2. **Assets** - Contains the Call Centre Representative information like Representative ID and Image used in the dashboard.

3. **Pivots** - Contains all the Pivot Tables that were used in building this Dashboard and analysing the data further.
   - **Summary Pivot** - Represents the Number of Calls, Duration, Average rating and Total Revenue collectively for the business.
   - **Rep Pivot** - Represents the Number of Calls, Duration, Average rating and Total Revenue for each individual or group of representatives selected using the slicer.
   - **Monthlytrend** - Represents Monthly call figures for each individual or group of representatives selected using the slicer.
   - **weeklytrend** - Represents weekly call figures for each individual or group of representatives selected using the slicer.
     ...

4. **Customer Centre Report** - Contains the Dashboard displaying the various charts visualising key performance metrics that update in responce to the slicer.  

## 5. How to Use

### Navigating the Dashboard:
- Use the tabs at the bottom to switch between sheets.
- Interactive visuals allow you to:
  - Filter using slicers to see individual representative's performance or combined performance for selected representatives.
