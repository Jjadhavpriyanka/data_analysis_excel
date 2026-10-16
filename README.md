# Employee Wage Analysis and Dashboard (Excel)

## Project Overview
This project analyses a global workforce dataset containing employee demographics, occupations, education levels, countries, and wages.The objective was to clean and prepare the data, perform statistical analysis, test a wage-related hypothesis, and create an interactive Excel dashboard to uncover insights into salary distribution and wage disparities.
The project involved data cleaning, handling missing values, statistical analysis, hypothesis testing, and the creation of an interactive dashboard to identify wage trends, salary distributions, and gender pay disparities across different countries and occupations. The workflow included data preparation, exploratory analysis, inferential statistics, and business-focused visualisation. The project findings indicated no statistically significant difference between average wages in the US and the rest of the world on a two-sample t-test (t = 1.64, p = 0.099).

## Objectives
1. Import and clean raw workforce data.
2. Handle missing and inconsistent values.
3. Analyse wage distributions across different groups.
4. Perform hypothesis testing on employee wages.
5. Identify wage disparities by gender, occupation, education level, and country.
6. Develop an interactive dashboard for stakeholders.

## Business Problem
Organisations operating across multiple countries require visibility into workforce compensation patterns to ensure fair pay practices and support strategic decision-making.

This project answers key business questions:
1. Are employee wages significantly different between the US and the rest of the world?
2. Which countries have the highest and lowest average wages?
3. Are there notable gender pay gaps?
4. How do occupation and education levels influence earnings?
5. What trends can be identified through interactive reporting?

## Dataset
The dataset contains approximately 10,000 employee records and includes:
1. Country
2. Occupation
3. Employer Type
4. Gender
5. Education level
6. Marital Status
7. Ethnic Group
8. Wage Information

## Dataset Disclaimer
The dataset used in this project was provided as part of an academic assessment by Arden University. The original dataset is not included in this repository due to ownership and educational usage restrictions. The analysis, methodology, dashboard design, and findings presented in this repository are my own work.

## Data Cleaning Process
The dataset was cleaned using Excel through the following steps:
1. Imported data
2. Applied Clean and Proper functions to standardise text values
3. Corrected data types for each column
4. Removed invalid characters and inconsistent entries.
5. Identified missing values using conditional formatting.
6. Removed duplicate records.
7. Used deletion and imputation techniques where appropriate.
8. Replaced missing categorical values using mode-based methods.
9. Protected worksheets to preserve data integrity.

## Exploratory Data Analysis
Descriptive statistical analysis was conducted to understand wage distributions.
Metrics analysed included:
1. Mean
2. Median
3. Standard Deviation
4. Range
5. Skewness
6. Kurtosis

Additional visualisations included:
1. Histograms
2. Pivot Charts
3. Wage Distribution Analysis
4. Country Comparison Analysis
5. Occupation Comparison Analysis

## Hypothesis Testing

### Research Question
Do employees in the US earn significantly higher wages than employees in the rest of the world?

### Hypotheses
#### Null Hypothesis (H₀):
There is no significant difference in average wages between the US and the rest of the world.

#### Alternative Hypothesis (H₁):
Employees in the US earn significantly higher wages than employees in the rest of the world.

### Method
A two-sample t-test (unequal variances) was conducted to compare average wages between employees in the United States and employees in the rest of the world.

### Result:
t-statistics = 1.64
p-value = 0.099

### Conclusion
The analysis failed to reject the null hypothesis at a 5% significance level, indicating no statistically significantly difference between average wages in the US and the rest of the world.

## Dashboard Features
The dashboard was developed entirely in Microsoft Excel using Pivot Tables, Pivot Charts, KPI calculations, and slicers.

### Interactive Features
1. Gender Filter
2. Education Filter
3. Occupation Filter
4. Country Filter
5. Dynamic KPI Cards
6. Interactive Charts

### Dashboard Metrics
1. Average Wage by Gender
2. Average Wage by Occupations
3. Average Wage by Countries
4. Gender Wage Differential
5. Top Paying Countries
6. Lowest Paying Countries
7. Top occupations by earnings

### Key Insights
1. Wage gaps vary across education levels, countries, and occupations.
2. Higher education levels generally correspond with higher earnings.
3. Some countries show substantial differences in average wages between genders.
4. Protective Services and Technical Support roles demonstrated notable wage differences.
5. Interactive analysis revealed varying wage trends across global regions.

## Tools Used
1. Microsoft Excel
2. Pivot Tables
3. Pivot Charts
4. Slicers
5. Conditional Formatting
6. Descriptive Statistics ToolPack
7. T-Test Analysis

## Skills Demonstrated
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Data Validation
4. Missing Data Handling
5. Statistical Analysis
6. Hypothesis Testing
8. Dashboard Design
9. Business Insight Generation

## Future Improvements
1. Rebuild dashboard in Power BI
2. Add advanced statistical testing
3. Create predictive wage analysis models
4. Integrate automated data refresh workflows
