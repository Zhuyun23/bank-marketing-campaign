# Bank Marketing Campaign Analysis

## Overview
This project analyzes a Portuguese bank's marketing campaign dataset to optimize customer targeting for term deposit subscriptions. The analysis combines data processing, visualization, and machine learning to provide actionable insights for marketing strategy improvement.

## Target Audience
- Marketing and sales teams
- Financial analysts  
- Decision makers within Portuguese banks or financial institutions

## Project Objectives
1. Optimize Customer Targeting:
  - Identify high-probability term deposit subscribers
  - Develop customer profiling for better targeting
  - Analyze impact of demographic factors (marital status, education)

2. Enhance Campaign Effectiveness:
  - Analyze timing factors (including special holidays)
  - Improve resource allocation
  - Increase subscription success rates

3. Develop Predictive Models:
  - Build machine learning models for subscription prediction
  - Provide data-driven decision support tools

## Data Source
- Source: [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)  
- Dataset: bank-additional-full.csv
- Records: 41,188 examples
- Features: 20 input variables
- Time Period: May 2008 to November 2010

## Technical Details

### Technologies Used
1. Data Processing:
  - Python
  - SQL 
  - Key Libraries: pandas, numpy

2. Data Visualization:
  - Tableau

3. Machine Learning:
  - Logistic Regression
  - Random Forest

### Data Processing Methodology
1. Data Cleaning Steps:
  - Duplicate value removal
  - Missing data handling 
  - Irrelevant data removal
  - Structural error correction
  - Outlier filtering
  - Data validation

2. Analysis Methods:
  - Time Series Analysis
  - User Profiling (Customer Segmentation)
  - Predictive Modeling

## Key Features Analyzed
1. Customer Demographics:
  - Marital status
  - Education level
  - Age
  - Occupation

2. Temporal Factors:
  - Campaign timing
  - Special holiday periods
  - Seasonal patterns

## Project Structure
```text
project/
├── data/
│   ├── raw/          # Original bank marketing dataset
│   └── processed/    # Cleaned and processed data
├── notebooks/        # Jupyter notebooks for analysis
├── scripts/          # Python and SQL scripts
├── visualization/    # Tableau workbooks
└── results/          # Analysis outputs and model results


## Analysis Results

### 1. Machine Learning Performance
- Model Accuracy: 90.5%
- Successfully predicts customer subscription behavior for term deposits

### 2. Customer Segment Analysis
#### Demographic Insights
- Married individuals without housing loans show higher subscription rates
- Age group 30-50, especially those in their 30s, demonstrate higher engagement
- High-income audiences, including retirees and housemaids, show strong potential
- Secondary education holders form the majority of loan and deposit users
- Blue-collar workers, technicians, and management are primary loan users
- Married individuals constitute the majority of both loan and deposit users

#### Campaign Response Patterns
- Existing customers show a remarkable 50% conversion rate
- Previous campaign success strongly correlates with future subscription likelihood
- Middle-aged customers form the core loan product user base

### 3. Temporal Analysis
#### Seasonal Patterns
- May and October show highest campaign effectiveness
- Public holidays, especially Halloween, significantly impact campaign outcomes

## Recommendations

### 1. Customer Targeting Strategy
#### Primary Focus Groups
- Married individuals without housing loans
- Professionals aged 30-50
- High-income segments (retirees and housemaids)
- Existing customers with positive past interactions
- Secondary education holders
- Blue-collar workers, technicians, and management professionals

### 2. Campaign Timing Optimization
#### Schedule major campaigns during:
- May and October (peak effectiveness months)
- Around Halloween and other significant public holidays
- Periods aligned with target segment availability

### 3. Segment-Specific Approaches
#### Develop tailored campaigns for:
- Retirees with specific interest-aligned strategies
- Existing customers with personalized offers
- Age-specific marketing messages for the 30-50 demographic
- Education level-appropriate communication strategies

### 4. Resource Allocation
#### Prioritize:
- Marketing to existing customer base (50% conversion potential)
- Segments with proven high response rates
- Campaigns during optimal timing windows
- Demographic-specific campaign materials

## Implementation Guidelines
### 1. Customer Segmentation
- Implement detailed customer profiling
- Develop segment-specific marketing materials
- Regular monitoring of segment response rates

### 2. Campaign Scheduling
- Create an annual campaign calendar highlighting optimal periods
- Plan holiday-specific marketing initiatives
- Coordinate timing with resource availability

### 3. Performance Monitoring
- Track conversion rates by segment
- Monitor campaign timing effectiveness
- Regular model performance evaluation
