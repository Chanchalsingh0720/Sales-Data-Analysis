# Power BI Retail Data Analysis

## Overview
This project involves analyzing retail data using Power BI. It encompasses loading and managing data from multiple sources, defining relationships, and creating insightful reports and dashboards.

## Tasks Completed
1. **Data Loading**: Imported four disparate files into the Power BI model.
2. **Data Cleaning**: Removed records with missing values from specific tables.
3. **Relationship Management**: Established and validated relationships between tables.
4. **DAX Calculations**:
   - Created `Net_Units` by subtracting `Cancelled_Units` from `Units`.
   - Added `OrderDayOfWeek` for weekday names.
   - Added `OrderWeekStart` to mark the start of the week, formatted as 'Nov 06'.
5. **Field Restructuring**: Renamed and restructured the `City` field for clarity.
6. **Reporting**: Developed reports and metrics on total revenue, quantity, cancellations, and other key metrics.
7. **Dashboard**: Designed a high-level dashboard to visualize the data and insights.

## Files
- **Data Files**: Contains the raw data files used in the project.
- **Power BI File**: The `.pbix` file with the data model, DAX formulas, and dashboard.

## Usage
1. Load the provided data files into Power BI.
2. Ensure that all relationships are correctly defined.
3. Use the Power BI file to explore the dashboard and reports.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
