# BigQuery SQL

BigQuery introduction to SQL questions

## Accessing BigQuery public data sets

1. Log in to Google Cloud Console with a **Gmail (Google)** account:

[https://console.cloud.google.com/](https://console.cloud.google.com/)

2. Find BigQuery (you may have to search for `BigQuery`)

3. Find the public datasets (you may have to search data sets for `bigquery-public-data`)

## Part 1. Evaluate expressions

The main idea of this task is to run soome BigQuery queries written in [Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/syntax). So, you *do not have* to save your queries on GitHub. However, if you want to, make a copy of this README and use backticks to make codeblocks, e.g.,:

```sql
SELECT LEFT("Hello world", 2); --selects the left two characters of "Hello world": "He"
```

> use BigQuery (yes, you absolutely must use an enterpirse data warehouse for those advanced calculations 😀) and Standard SQL (`SELECT`) to calculate the following:

1. Raise 25 to the power of 12 ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#pow))
2. Find the remainder of 25 divided by 2 ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#mod))
3. How many whole times can 12 fit into 25 (integer division) ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#div))
4. What is the FLOOR of 3.77? ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#floor))
5. What is the absolute value of -230? ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#abs)
6. What is the ceil of 2.111? ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#ceil)
7. Round 2.34567837 to 3 decimal places. ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#round))
8. Turn DATA to lower case ([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#lower))
9. Selects the last three characters of "SQL is life😀" and alias as last_three([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/string_functions#right))
10. Convert your name into all capitals and alias as name_in_caps([docs](https://cloud.google.com/bigquery/docs/reference/standard-sql/string_functions#upper))

## Part 2. `SELECT DISTINCT`

1. Get names of London boroughs from `bigquery-public-data.london_crime.crime_by_lsoa`. Make sure boroughs do not repeat.
2. What are the distinct values from the column gender in the table `bigquery-public-data.new_york.citibike_trips`?

## Part 3. `COUNT`

1. How many distinct birth_year values are there in the `bigquery-public-data.new_york.citibike_trips` data set?
2. How many genders are there in the data set `bigquery-public-data.usa_names.usa_1910_current`?
3. How many distinct american names are there in the data set `bigquery-public-data.usa_names.usa_1910_current`?

## Part 4. `LIMIT`

1. Get names of 5 London boroughs from `bigquery-public-data.london_crime.crime_by_lsoa`. Make sure boroughs do not repeat.

## Part 5. `WHERE`

1. Get all male names from `bigquery-public-data.usa_names.usa_1910_current`
2. Get all female names from `bigquery-public-data.usa_names.usa_1910_current`
3. Count male names from `bigquery-public-data.usa_names.usa_1910_current`
4. Count female names from `bigquery-public-data.usa_names.usa_1910_current`
5. Get all **male** American names that begin with "X"


