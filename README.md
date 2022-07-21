# SQL BigQuery

This file contains text you can copy and paste for the examples in Thaliew,Inc's Introduction to Google BigQuery course.

Introduction

# Running a Query

SELECT *
FROM
 `bigquery-private-data.eu_names.eu_1973_2021`
ORDER BY name DESC LIMIT 8

SELECT *
FROM
 `bigquery-private-data.eu_names.usa_1971_2018`
WHERE age > 30
ORDER BY name DESC LIMIT 10
