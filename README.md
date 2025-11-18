# Exploratory-Data-Analysis-Project-Done-by-Juoyter-Notebook
Comprehensive Exploratory Data Analysis project using Python in Jupyter Notebook to examine data quality, uncover trends, visualize patterns, and explore feature relationships. Includes data cleaning, statistical summaries, correlations, and insightful charts to guide deeper analysis and future modeling.

# Diwali Sales Analysis

## Project Overview
This project analyzes Diwali sales data to uncover customer purchasing patterns, demographic insights, and sales trends during the festive season. The analysis helps understand customer behavior, product preferences, and sales performance across different demographic segments.

## Dataset Information
- **File Name**: Diwali Sales Data.csv
- **Records**: 11,251 initial entries
- **Columns**: 15 original columns
- **Final Dataset**: 11,239 records after data cleaning

## Data Columns
The dataset contains the following columns after preprocessing:
- User_ID: Unique customer identifier
- Cust_name: Customer name
- Product_ID: Unique product identifier
- Gender: Customer gender (M/F)
- Age Group: Age category (0-17, 18-25, 26-35, 36-45, 46-50, 51-55, 55+)
- Age: Customer age
- Marital_Status: Marital status (0=Unmarried, 1=Married)
- State: Customer's state
- Zone: Geographical zone
- Occupation: Customer's occupation
- Product_Category: Product category
- Orders: Number of orders placed
- Amount: Total purchase amount

## Data Preprocessing Steps

### 1. Data Loading and Initial Inspection
- Imported necessary libraries (pandas, numpy, matplotlib, seaborn)
- Loaded the CSV file with proper encoding
- Checked dataset shape and structure
- Displayed first few records to understand data format

### 2. Data Cleaning
- **Removed unnecessary columns**: 'Status' and 'unnamed1' (both contained only null values)
- **Handled missing values**: Dropped 12 records with null values in 'Amount' column
- **Data type conversion**: Converted 'Amount' column from float to integer

### 3. Data Quality Checks
- Verified no remaining null values
- Checked data types for consistency
- Renamed columns for better readability (e.g., 'Marital_Status' to 'Shaadi')

## Exploratory Data Analysis

### Gender Analysis
**Key Findings:**
- **Customer Distribution**: More female customers than male customers
- **Purchasing Power**: Female customers show higher total purchase amounts compared to male customers
- **Insight**: Females are both the majority of buyers and have greater purchasing power during Diwali sales

### Age Group Analysis
**Visualizations Created:**
- Count plot showing customer distribution across age groups by gender
- Bar chart analyzing purchase amounts by age group

**Key Insights:**
- Age group 26-35 shows the highest purchasing activity
- Different age groups exhibit varying purchasing patterns
- Gender distribution varies across different age segments

## Tools and Technologies Used
- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Jupyter Notebook**: Interactive development environment

## Key Business Insights
1. **Target Audience**: Females in the 26-35 age group are the primary customers
2. **Sales Strategy**: Focus marketing efforts on female customers aged 26-35
3. **Product Planning**: Stock products preferred by the identified target demographic
4. **Regional Analysis**: Data includes state and zone information for geographical insights

## Future Analysis Directions
- Occupation-based purchasing patterns
- State/zone-wise sales performance
- Product category preferences
- Marital status impact on purchasing behavior
- Seasonal trends and peak shopping periods

## How to Run the Analysis
1. Ensure required Python libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
