# Hotel No-Show Prediction Project

## Overview

This project implements a machine learning solution for predicting hotel no-shows to help reduce expenses from no-show customers.

## Project Structure

```
AISG/
├── data/
│   └── noshow.db          # SQLite database (119,391 records)
├── eda.ipynb              # Exploratory Data Analysis notebook
├── requirements.txt       # Python dependencies
└── README.md             # This file
```

## Setup Instructions

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Run EDA Notebook

```bash
jupyter notebook eda.ipynb
```

## Dataset Information

- **Database**: SQLite format with 1 table ('noshow')
- **Records**: 119,391 booking records
- **Features**: 15 columns including booking details, customer info, and target variable
- **Target**: `no_show` (0 = Show, 1 = No-Show)

## EDA Notebook Features

The EDA notebook provides comprehensive analysis including:

- Data structure and quality assessment
- Missing value analysis
- Target variable distribution
- Feature correlation analysis
- Categorical vs target relationships
- Statistical significance testing
- Outlier detection
- Data independence verification

## Next Steps

1. Complete the EDA analysis by running all cells
2. Use EDA insights to build the ML pipeline
3. Implement feature engineering based on findings
4. Develop and evaluate multiple models

## Requirements Met

✅ Python 3.13 compatible dependencies  
✅ SQLite database connection  
✅ Comprehensive EDA notebook  
✅ Statistical analysis and visualizations  
✅ Business-focused insights and recommendations
