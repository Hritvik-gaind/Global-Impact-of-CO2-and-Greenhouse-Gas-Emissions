# Global-Impact-of-CO2-and-Greenhouse-Gas-Emissions

## **Project Overview**

This project examines the global impact of CO₂ and greenhouse gas (GHG) emissions, focusing on their environmental and societal consequences. Through data analysis, the study investigates patterns of emissions by source, sector, and region, exploring their correlation with global life expectancy trends and evaluating the effectiveness of international environmental policies like the Paris Agreement.

## **Objectives**

**Data Integration**:

   - Combine datasets on CO₂ emissions, GHG emissions, and life expectancy.
   - Establish SQL tables for efficient querying and analysis.

**Guiding Questions**:
   
   - How do emissions differ across continents and sectors?
   - How have emissions per capita evolved over decades?
   - What is the correlation between emissions and life expectancy?
   - Have international policies impacted emissions reductions?

**Impact Analysis**:
   - Evaluate the effectiveness of the Paris Agreement, Kyoto Protocol, and other policies.

## **Datasets**

Datasets were sourced from [Our World in Data](https://ourworldindata.org):

- **Per capita CO₂ emissions**
- **Per capita GHG emissions**
- **GHG emissions by sector**
- **GHG emissions by composition**
- **Life expectancy**

All datasets are licensed under Creative Commons, with modifications including column standardization and data cleaning.

## **Tools & Technologies**

- **Programming Languages**: Python, SQL
- **Libraries**: Pandas, Matplotlib, MySQL Connector
- **Database**: MySQL
- **Visualization**: Matplotlib, Seaborn

## **Methodology**

**Data Preprocessing**:
   - Cleaned datasets to address missing values and standardize formats.
   - Established relationships between tables using a unique `Code_Year` identifier.

**Data Analysis**:
   - Built SQL queries to explore emissions trends by sector, region, and year.
   - Calculated emissions ratios (e.g., CO₂/GHG) to analyze sectoral contributions.

**Policy Impact Evaluation**:
   - Compared emissions before and after policy enactments.
   - Focused on changes during key periods (e.g., 2010-2015 vs. 2015-2020).

## **Key Findings**

**Regional Trends**:
   - Developed comprehensive tables linking emissions data to continents and countries.
   - Highlighted countries with the most significant reductions in emissions.

**Policy Effectiveness**:
   - Countries adhering to the Paris Agreement showed measurable reductions in CO₂ and GHG emissions per capita.
   - Quantified the percentage change in emissions before and after policy implementation.

**Sectoral Contributions**:
   - Identified transportation and energy production as the largest contributors to emissions.
   - Detailed emissions breakdown by type (e.g., methane, nitrous oxide).

**Correlation Analysis**:
   - Revealed inverse relationships between emissions and life expectancy in several regions.
