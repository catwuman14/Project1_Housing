# Project1_Housing
Title: **Housing Affordability in Germany**

**Introduction**
Housing is one of the largest expenses for any household, and as cities continue to grow, housing affordability becomes an increasing concern for residents and policymakers alike. Which begs us all to think about, How much should a person's salary go towards rent?We want to analyse this problem 1) investigating factors that influence rental prices and 2) exploring the relationship between wages and rent based off both region and sex.

**Data you are using (and comments, main challenges, strengths & weaknesses, etc…)**
    - income dataset: https://www.statistischebibliothek.de/mir/receive/DESerie_mods_00000301
    - inflation webscraping: https://www.inflation.eu/es/tasas-de-inflacion/alemania/inflacion-historica/ipc-inflacion-alemania-2018.aspx
    - [https://www.notion.so/1824b707679180b09545c1de84f5ef9c?v=1824b707679180e4bab4000c18cfa13a&p=1824b707679180ceb3bfe37dba1c506b&pm=s](https://www.notion.so/update-readme-file-1824b707679180ceb3bfe37dba1c506b?pvs=21)
    - was not able to pull 2021/2022/2023/2024 housing data from immmoscout (tried both via APIs and webscraping)

**Questions you want to answer (maybe divided by different topics). Each question should include a conclusion written in a markdown cell.**

    1. The larger the living space the cheaper the rent per meter squared.
    2. Inflation is positively correlated to rental prices.
    3. Rent as a proportion of salary is higher in more urban regions.
    4. Females pay a higher percentage of their income on rent in comparison to men.

**Describe the methodology you are using, explaining the steps you took for data cleaning, analysis, etc.**
    1. Chose the data set
    2. Cleaned the data set
        1. removed duplicate columns
        2. standardised data values where related
        3. checked % of null values in every column
        4. removed outliers (i.e. living space and price per square meter)
        5. bucketed condition values
    3. Formulated Hypotheses
    4. Merged the data sets
    5. Wrangled the new data set
        1. created new data frame with aggregations for average income 
        2. created new data frame with aggregations for price per square metre
        3. created new data frame with aggregation by sex and price per rental property
        4. created various graphs to support our hypotheses
    6. Chose the data set
    7. Cleaned the data set

**Conclusions:**
    1. The larger the living space the cheaper the rent per meter squared. - FALSE
    2. Inflation is positively correlated to rental prices. - TRUE
    3. Rent as a proportion of salary is higher in more urban regions. - TRUE
    4. Females pay a higher percentage of their income on rent in comparison to men. -TRUE

Links to data sources
    - housing dataset: https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany
    - income dataset: https://www.statistischebibliothek.de/mir/receive/DESerie_mods_00000301
    - inflation webscraping: https://www.inflation.eu/es/tasas-de-inflacion/alemania/inflacion-historica/ipc-inflacion-alemania-2018.aspx
    - [https://www.notion.so/1824b707679180b09545c1de84f5ef9c?v=1824b707679180e4bab4000c18cfa13a&p=1824b707679180ceb3bfe37dba1c506b&pm=s](https://www.notion.so/update-readme-file-1824b707679180ceb3bfe37dba1c506b?pvs=21)
