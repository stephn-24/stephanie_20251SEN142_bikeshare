# Research Log

**Project:** Bike-Sharing Demand Analysis and Operational Decision Support System  
**Student:** Uwakowe Stephanie  
**Student ID:** 20251SEN142  
**Course:** INSY 8311 – Database Development with PL/SQL

## 1. Research Sources

### 1. Kim et al. (2019)
- **Type:** Research paper
- **Reference:** Kim, T. S., Lee, W. K., & Sohn, S. Y. (2019). Graph convolutional network approach applied to predict hourly bike-sharing demands considering spatial, temporal, and global effects. *PLOS ONE, 14*(9), e0220782.
- **Link:** https://doi.org/10.1371/journal.pone.0220782
- **Key finding:** Bike-sharing demand is influenced by time patterns, weather and relationships between stations.
- **Research gap:** This project uses aggregated historical data and focuses on Oracle-based demand analysis rather than station-level prediction.

### 2. Sathishkumar et al. (2020)
- **Type:** Research paper
- **Reference:** Sathishkumar, V. E., Park, J., & Cho, Y. (2020). Using data mining techniques for bike sharing demand prediction in metropolitan city. *Computer Communications, 153*, 353–366.
- **Link:** https://doi.org/10.1016/j.comcom.2020.02.007
- **Key finding:** The researchers compared five prediction models. Gradient Boosting Machine achieved the best test performance among the models evaluated.
- **Research gap:** This project focuses on database management and PL/SQL-based historical demand analysis rather than machine-learning prediction.

### 3. Bean et al. (2021)
- **Type:** Research paper
- **Reference:** Bean, R., Pojani, D., & Corcoran, J. (2021). How does weather affect bikeshare use? A comparative analysis of forty cities across climate zones. *Journal of Transport Geography, 95*, 103155.
- **Link:** https://doi.org/10.1016/j.jtrangeo.2021.103155
- **Key finding:** The study found that time of day and precipitation are important factors influencing bike-sharing usage.
- **Research gap:** This project focuses on one historical dataset and presents its findings through an Oracle dashboard.

### 4. NACTO (2024)
- **Type:** Industry report
- **Reference:** National Association of City Transportation Officials. (2024). *Shared micromobility report: 2023*.
- **Link:** https://nacto.org/publication/shared-micromobility-report-2023/
- **Key finding:** The report recorded 157 million shared micromobility trips in the United States and Canada in 2023, including bicycle and scooter trips.
- **Research gap:** This project focuses on analysing historical rental records rather than general industry statistics.

### 5. Capital Bikeshare
- **Type:** Existing system
- **Reference:** Capital Bikeshare. (n.d.). *How it works*.
- **Link:** https://capitalbikeshare.com/how-it-works
- **Key finding:** Capital Bikeshare provides a real-world example of a public bicycle rental system.
- **Research gap:** This project focuses on historical demand analysis and database-based decision support.

### 6. Fanaee-T (2013)
- **Type:** Dataset
- **Reference:** Fanaee-T, H. (2013). *Bike Sharing* [Dataset]. UCI Machine Learning Repository.
- **Link:** https://doi.org/10.24432/C5W894
- **Key finding:** The dataset contains historical daily and hourly rental counts with weather, seasonal and user-type information.
- **Research gap:** It does not contain individual trip histories, station locations or real-time bicycle availability.

### 7. Oracle (2026)
- **Type:** Technical documentation
- **Reference:** Oracle. (2026). *Oracle AI Database: Database PL/SQL Language Reference, 26ai*.
- **Link:** https://docs.oracle.com/en/database/oracle/oracle-database/26/lnpls/
- **Key finding:** Oracle PL/SQL supports procedures, functions, packages, triggers and exception handling.
- **Research gap:** This project will apply these database programming features to bike-sharing rental data.

## 2. Research Summary

The reviewed sources show that bike-sharing demand is influenced by factors such as time, weather and seasonal conditions. The UCI dataset provides historical rental information suitable for analysis.

This project will use Oracle Database and PL/SQL to organise, process and analyse the data, while Oracle APEX will provide an interactive dashboard for presenting historical demand patterns.

## 3. Proposed Contribution

The project will:
- Organise historical rental data in relational tables.
- Validate and process records using PL/SQL.
- Analyse demand by time, season, weather and user type.
- Identify historical high- and low-demand periods.
- Present results through an Oracle APEX dashboard.

**Limitation:** The proposed application analyses historical demand. It does not provide live bicycle availability or station tracking.
