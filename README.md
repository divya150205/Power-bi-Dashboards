# Power BI Dashboard: Data Professional Survey Reports

This dashboard is created using data from the **Survey_Data** file, which contains responses from professionals in the data field. Below is a detailed description of the key components:

## Dashboard Components

### 1. Survey Taker's Average Age
- **Metric Displayed**: 29.87 years (average age of survey respondents).
- **Data Source**: Column `Q10 - Current Age` from the dataset.

### 2. Count of Survey Takers
- **Metric Displayed**: 630 total survey participants.
- **Data Source**: Total rows in the dataset (excluding null values).

### 3. Survey Takers by Programming Language
- **Visualization**: Stacked bar chart.
- **Breakdown**: Programming languages preferred by survey respondents (e.g., Python, R, C/C++, Java).
- **Data Source**: Column `Q5 - Which Programming Language do you primarily use?`.
- **Job Roles**: Segmented by job titles such as Data Scientist, Data Analyst, and others.

### 4. Happy Work/Life Balance and Salary
- **Visualization**: Gauge charts.
- **Metrics Displayed**:
  - Work-life balance satisfaction: 5.74/10.
  - Salary satisfaction: 4.27/10.
- **Data Source**: Columns `Q6 - How Happy are you in your Current Position with the following? (Work/Life Balance)` and `Q6 - How Happy are you in your Current Position with the following? (Salary)`.

### 5. Average Salary by Job Role
- **Visualization**: Horizontal bar chart.
- **Breakdown**: Average salary categorized by roles like Data Scientist, Data Engineer, and others.
- **Data Source**: Column `Q4 - What is your annual salary (in USD)?` combined with `Q2 - Job Role`.

### 6. Difficulty to Break into Data Field
- **Visualization**: Doughnut chart.
- **Breakdown**: Survey respondents' ratings of how difficult it was to enter the data field (e.g., Very Difficult, Easy).
- **Data Source**: Column `Q7 - How difficult was it for you to break into Data?`.

### 7. Country of Survey Takers
- **Visualization**: Treemap.
- **Breakdown**: Distribution of respondents by country (e.g., United States, India, Canada).
- **Data Source**: Column `Q11 - Which Country do you live in?`.

## Insights Provided by the Dashboard
1. **Programming Language Preference**: Python is the most widely used programming language, with significant representation across job roles.
2. **Work-Life Balance and Salary Satisfaction**: Survey takers rate their work-life balance higher than their salary satisfaction.
3. **Challenges in the Field**: A considerable portion of professionals found it challenging to break into the data field.
4. **Geographic Distribution**: The majority of survey respondents are from the United States and India.

## Data Cleaning and Transformation
To create this dashboard, the following steps were performed:
1. Removed duplicate entries and null values from key columns.
2. Aggregated data for visualizations such as average age, salary, and difficulty ratings.
3. Standardized job titles and programming language entries for consistency.

## Tools and Techniques Used
- **Data Source**: Excel file (`Survey_Data.xlsx`).
- **Dashboard Platform**: Microsoft Power BI.
- **Visualization Types**: Bar charts, gauge charts, doughnut charts, and treemaps.

This dashboard provides a comprehensive overview of survey data, aiding in understanding trends and challenges in the data field.
