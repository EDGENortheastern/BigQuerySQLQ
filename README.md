# BigQuery SQL

BigQuery introduction to SQL questions

## Accessing BigQuery public data sets

1. Log in to Google Cloud Console with a Gmail (Google) account:

[https://console.cloud.google.com/](https://console.cloud.google.com/)

2. Find BigQuery (you may have to search for `BigQuery`)

3. Find the public datasets (you may have to search data sets for `bigquery-public-data`)

## Part 1. Evaluate expressions

> use BigQuery (yes, you absolutely must use an enterpirse data warehouse for those advanced calculations 😀) and Standard SQL (`SELECT`) to calculate the following:

1. Raise 25 to the power of 12 ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#pow))
2. Find the remainder of 25 divided by 2 ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#mod))
3. How many whole times can 12 fit into 25 (integer division) ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#div))
4. What is the FLOOR of 3.77? ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#floor))
5. What is the absolute value of -230? ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#abs)
6. What is the ceil of 2.111? ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#ceil)
7. Round 2.34567837 to 3 decimal places. ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#round))
8. Turn DATA to lower case ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#lower))
