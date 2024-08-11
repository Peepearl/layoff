### Business Understanding
Objective:
The goal of this project is to analyze layoff trends across various industries, locations, and stages of company growth. By identifying patterns in layoffs, stakeholders can gain insights into economic conditions, company performance, and industry stability.

The key questions include:
- What industries are most affected by layoffs?
- Are there specific regions with higher layoff rates?
- How does company stage (e.g., Pre-IPO vs. Post-IPO) correlate with layoff events?
### Data Understanding
Data Overview:
The dataset contains 2361 records with 9 columns, including:
- company: The name of the company where layoffs occurred.
- location: The geographical location of the company.
- industry: The industry in which the company operates.
- total_laid_off: The total number of employees laid off.
- percentage_laid_off: The percentage of the company's workforce that was laid off.
- date: The date when the layoffs were announced.
- stage: The stage of the company (e.g., Series A, Post-IPO).
- country: The country where the layoffs occurred.
- funds_raised_millions: The amount of funds raised by the company in millions of dollars.

### Exploratory Data Analysis (EDA):
The dataset has missing values in columns like total_laid_off, percentage_laid_off, stage, funds_raised_millions, and industry.
The total_laid_off column has a wide range of values, from as low as 3 to as high as 12,000 employees.
The percentage_laid_off has some missing values and varies widely across companies.

### Data Preparation
Steps Taken:
- Handling Missing Values:
- For total_laid_off, missing values were filled with the median value (80) to avoid skewing the data.
- Missing values in percentage_laid_off, stage, and other relevant columns were carefully considered for imputation or exclusion based on their impact on the analysis.
### Data Transformation:
The date column was converted to a datetime format for time-based analysis.
Categorical variables like industry and location were encoded for easier analysis.

