# pyspark project
Tasks Performed 

Create SparkSession and SparkContext
Load & Preview – Read the CSV into Spark and inspect the shape of the data.
Clean – Remove duplicates, null customer IDs, and any non‑positive quantities.
Enrich – Add an order_value column and extract year/month/day info from the timestamp.
Country Revenue Summary – Compute total sales per country.
Top Customer per Country – Rank customers and keep the biggest spender in each country.
Region Join & Summary – Join the country‑to‑region lookup and roll sales up by region.
Monthly Category Pivot – Produce a table of monthly sales per product category.
Price Band Counts – Bucket orders into price ranges and count how many fall in each.
Partition Tuning Check – Repartition the data and compare job performance.
Cache vs. Recompute – Measure the speedup gained by caching intermediate results.
Write Gold Output – Save curated revenue tables as compressed Parquet files

