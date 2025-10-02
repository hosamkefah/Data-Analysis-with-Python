# Employee Data ETL

## Project Overview
Data preprocessing and analysis pipeline for employee data, handling missing values, data quality improvements, and generating departmental insights through aggregation.

## Dataset
- **Records**: 1,000 employees
- **Features**: 14 columns (demographics, compensation, employment dates, location)
- **Time Period**: 1992-2022

## Technologies Used
- Python 3.x, pandas, numpy
- Google Colab

## Project Structure
Employee Sample Data - A.xlsx    # Raw data
employee_summary1.xlsx           # Processed output


## Key Features

### Data Cleaning
- Missing value imputation (mean/median for numeric, mode for categorical)
- Removed duplicate entries
- Created `Still Working` flag from Exit Date
- Type conversions and data validation

### Analysis & Aggregations
- Department-level salary and age statistics
- Multi-level groupings (Department × Ethnicity)
- Salary range calculations
- Employee filtering and segmentation

## Key Findings
- **Highest Salary**: $258,498 (Vice President, Sales, Manufacturing)
- **Department Salary Ranges**: Between $195K-$217K spread
- **Average Employee Age**: 44.4 years
- **Active Employees**: 913 out of 998 (91.5%)

## Data Modifications Made
Sample manual updates for demonstration:
- Updated employee names (rows 0, 2)
- Modified department assignments (row 1)
- Adjusted age values (row 3)
- Changed gender classifications (row 4)

## Output
- **employee_summary1.xlsx** with two sheets:
  - Cleaned Data (998 records)
  - Grouped Summary (30 aggregated records)

## How to Run
1. Clone this repository
2. Install required packages: `pip install pandas numpy openpyxl`
3. Open `employee-data-etl.ipynb` in Jupyter/Colab
4. Run all cells sequentially


## Business Applications
- **HR Analytics**: Workforce demographics and compensation analysis
- **Diversity Reporting**: Ethnicity and gender distribution insights
- **Retention Analysis**: Employment duration and exit patterns
- **Compensation Planning**: Salary benchmarking by role and department

## Future Enhancements
- Time-series hiring trend analysis
- Employee attrition prediction modeling
- Interactive visualization dashboard
- Automated data quality monitoring

## Author
Hussam Alsayahien
