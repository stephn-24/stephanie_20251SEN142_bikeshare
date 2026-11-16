# Bike-Sharing Demand Analysis and Operational Decision Support System

**Student Name:** Uwakowe Stephanie  
**Student ID:** 20251SEN142  
**Course:** INSY 8311 – Database Development with PL/SQL  
**Instructor:** Eric Maniraguha  
**Academic Year:** 2026–2027


## 1. Project Overview

The Bike-Sharing Demand Analysis and Operational Decision Support System is a proposed database application for analysing historical bike-sharing rental demand.

The project will use historical rental data to identify patterns and understand how factors such as time, season and weather relate to bicycle rentals.

Oracle Database and PL/SQL will be used to store and analyse the data, while Oracle APEX will provide an interactive dashboard for presenting the results.

## 2. Problem Statement

Bike-sharing rental demand changes depending on different factors, including the time of day, season, working days and weather conditions.

Understanding these patterns can help bike-sharing operators identify periods of high and low demand and make better operational decisions.

However, historical rental data needs to be properly organised and analysed before it can provide useful information.

This project addresses this problem by proposing an Oracle database application that analyses historical rental records and presents meaningful insights.

## 3. Project Objectives

The main objective is to design a database application that analyses historical bike-sharing demand and supports operational decision-making.

The specific objectives are to:

1. Design a relational database for storing bike-sharing rental information.
2. Import and validate the selected dataset.
3. Use PL/SQL to process and analyse rental records.
4. Identify rental patterns based on time, season, weather and user type.
5. Generate indicators for historical periods of high and low demand.
6. Present analytical results through an interactive dashboard.

## 4. Proposed Solution

The proposed solution is an Oracle database application that will organise historical bike-sharing data and process it using PL/SQL.

The application will analyse rental patterns, calculate useful indicators and present the results through an Oracle APEX dashboard.

This will allow users to explore the historical data and understand changes in rental demand.

## 5. Data Source

**Dataset:** Bike Sharing Dataset  
**Source:** UCI Machine Learning Repository  
**Author:** Hadi Fanaee-T  
**DOI:** 10.24432/C5W894  
**Licence:** Creative Commons Attribution 4.0 International (CC BY 4.0)

**Dataset link:** https://archive.ics.uci.edu/dataset/275/bike-sharing-dataset

The dataset contains historical daily and hourly rental information collected by the Capital Bikeshare system in Washington, D.C., during 2011 and 2012.

It includes:
- Date and hour of rental.
- Season and weather conditions.
- Holiday and working-day information.
- Temperature, humidity and wind speed.
- Casual, registered and total rental counts.

**Dataset limitation:** The dataset contains aggregated rental counts. It does not provide individual customer records, individual trip histories, station locations or real-time bicycle availability. Therefore, the project focuses on historical demand analysis.

## 6. Planned Database Tables

The following tables are proposed for organising the database:

| Table | Purpose |
|---|---|
| `DIM_DATE` | Stores date and calendar information. |
| `DIM_HOUR` | Stores hour-of-day information. |
| `DIM_WEATHER` | Stores weather categories. |
| `FACT_HOURLY_RENTAL` | Stores hourly rental records and measurements. |
| `STG_HOURLY_RENTAL` | Temporarily stores imported data before validation. |
| `DEMAND_ALERT` | Stores historical demand indicators. |
| `AUDIT_LOG` | Records selected database activities. |

These are proposed tables. Their final structure and relationships will be established during database design.

## 7. Planned PL/SQL Features

The project will use the following PL/SQL features:

- **Procedures:** To validate and load data, generate summaries and identify demand patterns.
- **Functions:** To calculate rental indicators and classify demand levels.
- **Cursors:** To retrieve and process rental information.
- **Packages:** To organise related procedures and functions in `PKG_BIKE_ANALYTICS`.
- **Triggers:** To record selected database changes.
- **Exception Handling:** To manage invalid data, duplicate records and data consistency problems.

The main business rules and data-processing logic will be implemented in PL/SQL.

## 8. Innovation

The proposed innovation is an **Oracle APEX interactive dashboard** connected to the Oracle database.

The dashboard will provide:

- Summary indicators for total, casual and registered rentals.
- Charts showing hourly and seasonal rental patterns.
- Comparisons of rental demand under different weather conditions.
- Filters for exploring historical rental records.
- Configurable indicators for identifying historical high- and low-demand periods.

The dashboard will allow users to interact with information stored in the database, while PL/SQL will handle the main business rules and processing.

The demand indicators will be based on historical data rather than live bicycle availability.

## 9. References

1. Kim, T. S., Lee, W. K., & Sohn, S. Y. (2019). Graph convolutional network approach applied to predict hourly bike-sharing demands considering spatial, temporal, and global effects. *PLOS ONE, 14*(9), e0220782. https://doi.org/10.1371/journal.pone.0220782

2. Sathishkumar, V. E., Park, J., & Cho, Y. (2020). Using data mining techniques for bike sharing demand prediction in metropolitan city. *Computer Communications*. https://doi.org/10.1016/j.comcom.2020.02.007

3. Bean, R., Pojani, D., & Corcoran, J. (2021). How does weather affect bikeshare use? A comparative analysis of forty cities across climate zones. *Journal of Transport Geography, 95*, 103155. https://doi.org/10.1016/j.jtrangeo.2021.103155

4. National Association of City Transportation Officials. (2024). *Shared Micromobility Report: 2023*. https://nacto.org/publication/shared-micromobility-report-2023/

5. Capital Bikeshare. (n.d.). *How it works*. https://capitalbikeshare.com/how-it-works

6. Fanaee-T, H. (2013). *Bike Sharing Dataset*. UCI Machine Learning Repository. https://doi.org/10.24432/C5W894

7. Oracle. (n.d.). *PL/SQL Language Reference – Oracle AI Database 26ai*. https://docs.oracle.com/en/database/oracle/oracle-database/26/lnpls/

---

**GitHub Repository:** https://github.com/stephn-24/stephanie_20251SEN142_bikeshare
