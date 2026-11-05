# GCP-Batch-Data-Pipeline
Batch Data Pipeline using Google Cloud Storage and BigQuery to process CSV website traffic data.

# GCP Batch Data Pipeline – CSV to BigQuery

## Project Overview
This project demonstrates a simple batch data pipeline using Google Cloud Platform (GCP).

The pipeline processes website pageview data stored in a CSV file and loads transformed results into BigQuery for analysis.

## Technologies Used
- Google Cloud Storage
- Google BigQuery
- SQL
- CSV

## Dataset Details
The sample dataset contains the following columns:
- user_id
- page_url
- timestamp

## Project Workflow
1. Created a public Cloud Storage bucket.
2. Uploaded a sample website traffic CSV file.
3. Created a BigQuery dataset.
4. Created an external table connected to the CSV file in Cloud Storage.
5. Executed a SQL query to count pageviews per URL.
6. Stored the transformed results in a native BigQuery table.

## Transformation
The SQL query groups website pageviews by page URL and calculates the total pageviews for each URL.

## Project Output
A native BigQuery table containing transformed pageview counts.

## Screenshots
Project screenshots are available in the `screenshots` folder.

## Author
Jeya Vidhya
