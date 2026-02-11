# DataScience Project

A comprehensive data analysis project featuring two case studies with Tableau visualizations and datasets.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Case Studies](#case-studies)
  - [Case Study 1: Titanic Survival Analysis](#case-study-1-titanic-survival-analysis)
  - [Case Study 2: Coffee Chain Business Analysis](#case-study-2-coffee-chain-business-analysis)
- [Datasets](#datasets)
- [Tableau Dashboards](#tableau-dashboards)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Project Timeline](#project-timeline)

## 🎯 Project Overview

This repository contains two comprehensive data analysis case studies focused on exploratory data analysis (EDA), business insights, and interactive visualizations using Tableau. The project demonstrates skills in data cleaning, statistical analysis, and data visualization.

## 📁 Project Structure

```
DataScience/
├── data/                           # Raw datasets
│   ├── Coffee.csv                  # Coffee chain sales and inventory data (462 KB)
│   └── titanic.xlsx                # Titanic passenger data (65 KB)
├── Info/                           # Case study documentation
│   ├── CASE_STUDY_1_TITATNIC_students.docx
│   └── CASE_STUDY_2_COFFEE_CHAIN_students.docx
├── tableau/                        # Tableau workbooks
│   ├── Coffee Data 137.twbx        # Coffee chain analysis dashboard
│   └── TITANIC DATA 137.twbx       # Titanic survival analysis dashboard
└── README.md                       # This file
```

## 📊 Case Studies

### Case Study 1: Titanic Survival Analysis

**Objective:** Analyze the Titanic passenger dataset to understand survival patterns and factors that influenced passenger outcomes during the disaster.

**Key Analysis Areas:**
- Survival rates by passenger class
- Gender and age distribution analysis
- Family size impact on survival
- Fare analysis and correlation with survival
- Embarkation port analysis
- Socioeconomic factors affecting survival

**Dataset:** `data/titanic.xlsx`
- Contains passenger information including demographics, ticket class, fare, cabin, and survival status

**Documentation:** `Info/CASE_STUDY_1_TITATNIC_students.docx`

**Visualization:** `tableau/TITANIC DATA 137.twbx`

### Case Study 2: Coffee Chain Business Analysis

**Objective:** Perform comprehensive business intelligence analysis on a coffee chain's operations, focusing on sales performance, inventory management, and profitability across different markets.

**Key Analysis Areas:**
- Sales performance across different markets (Central region analysis)
- Product line profitability (Beans vs. Leaves, Coffee vs. Tea)
- Budget vs. actual performance comparison
- Inventory management and COGS (Cost of Goods Sold)
- Marketing effectiveness and ROI
- Market size segmentation (Major Market performance)
- Geographic distribution (State-wise analysis)
- Product type analysis (Regular vs. Decaf)

**Dataset:** `data/Coffee.csv`
- Contains 20+ columns including:
  - Geographic data: Area Code, State, Market, Market Size
  - Product information: Product, Product Line, Product Type
  - Financial metrics: Sales, COGS, Profit, Margin, Budget figures
  - Operations: Inventory, Marketing expenses, Total Expenses

**Documentation:** `Info/CASE_STUDY_2_COFFEE_CHAIN_students.docx`

**Visualization:** `tableau/Coffee Data 137.twbx`

## 📈 Datasets

### 1. Titanic Dataset (`titanic.xlsx`)
- **Size:** 65 KB
- **Format:** Excel (.xlsx)
- **Description:** Passenger manifest data from the RMS Titanic including survival outcomes
- **Key Fields:** PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

### 2. Coffee Chain Dataset (`Coffee.csv`)
- **Size:** 462 KB
- **Format:** CSV
- **Description:** Comprehensive sales and operations data for a coffee chain business
- **Key Fields:**
  - **Geographic:** Area Code, State, Market, Market Size
  - **Product:** Product, Product Line, Product Type, Type
  - **Financial:** Sales, COGS, Profit, Margin, Budget Sales, Budget COGS, Budget Margin, Budget Profit
  - **Operations:** Inventory, Marketing, Total Expenses
  - **Temporal:** Date

## 🎨 Tableau Dashboards

### TITANIC DATA 137.twbx
- Interactive dashboard for exploring Titanic survival patterns
- Visualizations include survival rates, demographic breakdowns, and correlation analysis
- File size: 103 KB

### Coffee Data 137.twbx
- Comprehensive business intelligence dashboard for coffee chain operations
- Includes sales trends, profitability analysis, market comparisons, and inventory insights
- File size: 236 KB

## 🚀 Getting Started

### Prerequisites

To work with this project, you'll need:

1. **Tableau Desktop or Tableau Reader** (to open .twbx files)
   - Download from: https://www.tableau.com/products/reader
   
2. **Excel or compatible spreadsheet software** (for .xlsx files)
   - Microsoft Excel, LibreOffice Calc, or Google Sheets

3. **Text editor or IDE** (for .csv files)
   - Any text editor, VS Code, or data analysis tools like Python/Pandas, R

4. **Microsoft Word or compatible word processor** (for documentation)
   - Microsoft Word, LibreOffice Writer, or Google Docs

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd DataScience
```

2. Navigate to the project directory:
```bash
cd D:\Projects\DataScience
```

## 💻 Usage

### Viewing Tableau Dashboards

1. Install Tableau Desktop or Tableau Reader
2. Navigate to the `tableau/` directory
3. Double-click on either:
   - `TITANIC DATA 137.twbx` for Titanic analysis
   - `Coffee Data 137.twbx` for Coffee Chain analysis

### Working with Datasets

**For Python/Pandas:**
```python
import pandas as pd

# Load Titanic data
titanic_df = pd.read_excel('data/titanic.xlsx')

# Load Coffee data
coffee_df = pd.read_csv('data/Coffee.csv')

# Basic exploration
print(titanic_df.head())
print(coffee_df.describe())
```

**For R:**
```r
# Load Titanic data
library(readxl)
titanic <- read_excel("data/titanic.xlsx")

# Load Coffee data
coffee <- read.csv("data/Coffee.csv")

# Basic exploration
head(titanic)
summary(coffee)
```

### Accessing Documentation

1. Navigate to the `Info/` directory
2. Open the relevant case study document:
   - `CASE_STUDY_1_TITATNIC_students.docx` - Titanic analysis guidelines
   - `CASE_STUDY_2_COFFEE_CHAIN_students.docx` - Coffee Chain analysis guidelines

## 📅 Project Timeline

- **Initial Commit:** October-November 2025
- **Dataset Collection:** September - October 2025
- **Tableau Dashboards Completed:** November 13, 2025

## 🔍 Key Insights & Analysis Focus

### Titanic Case Study Insights
- Survival correlation with socioeconomic status (passenger class)
- Gender disparities in survival rates
- Impact of traveling with family members
- Geographic and demographic patterns

### Coffee Chain Case Study Insights
- Performance metrics: Budget vs. Actual analysis
- Profitability drivers across different product lines
- Market size impact on sales and margins
- Inventory efficiency and cost management
- Marketing spend effectiveness

## 📝 Notes

- All Tableau workbooks are packaged (.twbx) files containing both the workbook and data extracts
- Case study documentation files provide detailed analysis requirements and guidelines
- The project uses real-world datasets for educational and analysis purposes
- Git repository is initialized and connected to remote origin

## 🤝 Contributing

This is an educational project. If you'd like to extend the analysis:

1. Fork the repository
2. Create a feature branch
3. Add your analysis or visualizations
4. Submit a pull request with clear documentation

## 📧 Contact

For questions or collaboration opportunities, please refer to the repository owner.

---

**Last Updated:** November 13, 2025
**Version:** 1.0.0
**Status:** Active Development
