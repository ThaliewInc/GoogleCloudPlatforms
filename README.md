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


https://cloud.google.com/free


# Loading Data



Baby names
[foo]: /url1
https://www.ssa.gov/OACT/babynames/names.zip

Jeopardy Data
https://datascienceplus.com/wp-content/uploads/2015/08/JEOPARDY_CSV.csv

Google Cloud SDK installation instructions
https://cloud.google.com/sdk/docs/install

Instructions
bq mk public
bq load --autodetect public.jeopardy JEOPARDY_CSV.csv

#Streaming Data
Bigquery documentation
https://cloud.google.com/bigquery/docs/reference/rest/v2/tabledata/insertAll

Exporting Data
bq extract
gs://ca-example/games*.csv.gz

#Review
https://cloud.google.com/bigquery/docs
customercare@thaliew.com








