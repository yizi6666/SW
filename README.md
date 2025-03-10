# Data Usage Explanation

This study utilizes multiple data sources to analyze the evolution, regional disparities, influencing factors, and policy recommendations related to private education in China. Below is an overview of the data types used, their primary purposes, and relevant data source links.

## 1. Overview of Data Used

### (1) Statistical Yearbooks and Government Reports
- **Data Sources**: Ministry of Education (MOE) Statistical Yearbooks (1987-2022), Provincial Education Bureau Reports, National and Regional Socioeconomic Development Statistical Bulletins
- **Primary Uses**:
  - Tracking the changes in the number of private educational institutions at the national and provincial levels
  - Analyzing regional distribution differences across different educational stages (preschool, compulsory education, high school, and higher education)
  - Assessing government financial investments and policy support for private education

- **Data Link**:
  - Official Statistics from the Ministry of Education: [MOE Website](http://www.moe.gov.cn/jyb_sjzl/moe_560/2022/)

### (2) Geospatial Data
- **Data Sources**: National Bureau of Statistics, Provincial Statistical Bureaus
- **Primary Uses**:
  - Visualization using Python's `geopandas` and `matplotlib` to map the geographic distribution of private educational institutions across provinces
  - Combining economic data (GDP, population density, etc.) to analyze regional disparities

### (3) Policy Documents and Literature Review
- **Data Sources**: National People's Congress (NPC), Ministry of Education policies, *Private Education Promotion Law* and its amendments
- **Primary Uses**:
  - Studying the evolution of private education policies
  - Analyzing the impact of the classification of “for-profit” and “non-profit” schools on private school operations
  - Examining the effects of the "Double Reduction" policy on the private education market

## 2. Data Processing Methods
- **Time Series Analysis**: Comparing changes in the number of private educational institutions from 2000 to 2020 to assess the impact of policies on private education development.
- **Regional Comparison**: Comparing the number of private educational institutions in southeastern coastal areas versus western regions to evaluate the influence of economic development on education.
- **Category Analysis**: Differentiating between preschool, compulsory education, high school, and higher education to explore the unique challenges and opportunities of each sector within private education.

## 3. Data Visualization and Storage
- **Code and Data Repository**: [GitHub Repository](https://github.com/yizi6666/SW)
- **Map Visualization**: Using Python to process data and generate visual representations of the distribution of private education in China.
