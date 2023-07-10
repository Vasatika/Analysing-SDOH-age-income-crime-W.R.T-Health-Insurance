# Project Title: Analysing Social Determinants of Health – Age, Income, Crime with respect to Health Insurance

## Importance
"Social determinants of health (SDOH) are the conditions in the environments where people are born, live, learn, work, play, worship, and age that affect a wide range of health, functioning, and quality-of-life outcomes and risks." This project aims to analyze the impact of social determinants of health, such as age, income, and crime, on health insurance. Understanding these factors is crucial for health insurance companies to design effective plans and coverage that cater to the needs of different demographic groups.

## Business Questions
1. Determine the groups at risk based on social determinants of health (SDOH) that can be targeted for providing insurance.
2. Understand target audience groups and ideate ways to provide health insurance for vulnerable groups and determine appropriate coverage.

## Data
The following datasets were used for this analysis:
1. SDOH Data: [Link to SDOH Data](https://www.ahrq.gov/sdoh/data-analytics/sdoh-data.html#download)
   - Description: Variables in the data are related to five main SDOH domains, including social context, economic context, education, physical infrastructure, and healthcare context.
   - Type of Data: Secondary Data collected by AHRQ.
   - Data Collection process: Drawn from multiple sources (original data documents, codebooks, surveys, and environmental scan)

2. CRIME Data: [Link to Crime Data](https://www.kaggle.com/datasets/michaelbryantds/crimedata)
   - Description: Types of crimes, percentages of crime, demographic groups like age, race, and police force. This data includes metrics according to states and counties.
   - Type of Data: Secondary Data taken from Kaggle.
   - Data Collection process: Data collection process is unknown and not mentioned in the main Kaggle file. Data dictionary source was used to understand the columns.

## Information Quality
- The datasets used are publicly available from government websites and reputable sources.
- Some datasets contain missing or null values, requiring data preprocessing.
- Data wrangling processes are needed to integrate and clean the datasets.
- Data profiling was performed to identify outliers, null values, and data quality issues.
- Adequate data is available to address the business questions, but further data wrangling and processing may be necessary.

## Methods and Tools
The following methods and tools were used for this analysis:
- Data Discovery
- Data Formatting
- Data Profiling
- Data Pre-processing/Cleaning
- Data Enrichment
- Data Integration

The main tools used:
- Python (Jupyter Notebook)
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
- Excel

## Data Wrangling Process
The data wrangling process involved the following steps:
1. Data Discovery: Conducted thorough research to find relevant datasets and understand their contents.
2. Data Formatting: Selected relevant columns, performed data type conversions, and cleaned the data.
3. Data Preprocessing: Handled missing and null values, created common columns for merging, and formatted the data.
4. Data Enrichment: Created subset dataframes for detailed analysis, generated visualizations, performed correlation analysis, and merged datasets.
5. Data Profiling: Conducted data profiling to identify outliers, null values, and data quality issues.
6. Data Visualization in Python: Used pandas and seaborn libraries to plot charts and regression plots for data visualization.

## Validation Rules
- Validated missing and null values during data entry.
- Validated the relevance of columns during the data formatting process.
- Validated changes in data cases, splitting, and formatting during data preprocessing.

## Analysis and Outputs
The analysis aimed to:
- Identify groups at risk based on social determinants of health (SDOH) that can be targeted for providing insurance.
- Understand target audience groups and ideate ways to provide health insurance for vulnerable groups and determine appropriate coverage.

The additional analysis involved:
- Developing regression models to generate risk scores considering various SDOH indices.
- Expanding the analysis to other SDOH factors and geographic regions.

## External Material
External websites and articles were researched to support the project objective. These sources provide additional insights into social determinants of health, health insurance, and the impact of SDOH on health outcomes.

## Additional Notes
- Detailed information on the data wrangling process, analysis steps, and visualizations can be found in the final report.
- The project focuses on analyzing the impact of social determinants of health on health insurance, providing insights for insurance companies to design effective plans and coverage.
