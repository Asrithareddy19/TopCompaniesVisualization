# TopCompaniesVisualization

This project involves analyzing the Top 1000 Companies dataset using Python for data cleaning and Tableau for data visualization. The goal is to uncover insights like funding trends, growth rates, and industry dominance across countries.

##DataSet: From Kaggle [Link Text]([https://example.com](https://www.kaggle.com/datasets/vedantkhapekar/top-10000-companies-dataset/data))
The dataset contains 1000 companies with the following key columns:
- `Company Name`, `Country`, `Industry`, `Total Funding`, `Growth Percentage`, and more.


Key Features:
- Data cleaning using Python (Pandas) to handle missing values, inconsistent data, and standardize columns.
- Interactive Tableau dashboard to visualize insights, including:
  - Funding distribution by industry.
  - Growth percentage by country.
  - Top 10 companies in funding and job openings.
 
Technologies Used:
- **Python (Pandas)**: For exploratory data analysis (EDA) and data cleaning.
- **Tableau**: For interactive dashboards and visualizations.

Data Cleaning:
The raw dataset had issues such as:
- Missing values in columns like `State`, `Country`, and `Job Openings`.
- Inconsistent formatting for `Total Funding` (e.g., "$11B", "€365").
- Duplicate entries (e.g., `USA` and `United States` as separate values).

Steps performed:
1. Handled missing values using strategies like:
   - Filling with median for numeric columns (e.g., `Estimated Revenues`).
   - Filling with mode or placeholder for categorical columns (e.g., `Industry`).
2. Standardized and converted `Total Funding` to numeric format.
3. Removed duplicates and inconsistent values (e.g., unified `USA` and `United States`).
4. Exported the cleaned dataset for use in Tableau.

Tableau Dashboard:
Key Visualizations:
1. **Bar Chart**: Total funding by industry.
2. **Pie Chart**: Company distribution by country.
3. **Summary Table**: Grouped metrics for top industries and countries.
4. **Line Chart**: Growth percentage trends over time.

### Screenshots:
| **Visualization**      | **Description**                |
|-------------------------|--------------------------------|
| ![Bar Chart](tableau/screenshots/bar_chart.png) | Total funding by industry. |
| ![Pie Chart](tableau/screenshots/pie_chart.png) | Company distribution by country. |
| ![Table](tableau/screenshots/summary_table.png) | Summary of funding and growth. |

Download the full Tableau workbook: [TopCompanies.twbx](tableau/TopCompanies.twbx)

