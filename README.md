# BI-Developer-Assignment
## 1 round_pdf
**Scenario: You are given a dataset containing information about global temperatures and CO2 emissions**.
**Table name: country_pollution**
**Columns name :** Country, Temperature, CO2, Date(Year)


**1. Question:** Write a query to find the countries with the highest temperatures in the dataset?
**ANS** Select country, temperature from country_pollution where temperature = (select max(temperature) from country_pollution);
