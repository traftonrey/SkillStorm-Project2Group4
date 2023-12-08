# ETL Pipeline for GitHub REST API Archive Data
- An ETL Pipeline to ingest Archived GitHub data in monthly batches.
- The archived data sourced from GitHub Archives are in .json format 
compressed into a .gzip. 

### Goals for Pipeline:
- Visualize the data 
  |Use Case # | Case Study|
  |----------- |----------- |
  |1.| Data aggregated by Type of GitHub Event by Hour|
  |2. |Push Events aggregated by the committed branch|
  |3. |Summary of each Event Type|
  |4. |Breakdown of User Activity by week/month|
  |5. |Activity breakdown- automated or not: Bots vs Users|
  
### Team:
- Alvin Lin
- Erin Burgess
- Timothy Buchak
- Trafton Reynolds

### Cloud Storage
- Microsoft Azure

### Technologies
- Databricks
- Apache Spark (PySpark)

