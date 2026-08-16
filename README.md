# real-time-stock-market

Architecture & Data Pipeline :

Data Ingestion: Continuously fetch live or simulated stock data via Python scripts calling APIs (e.g., Yahoo Finance, Finnhub).

Message Broker: Use Apache Kafka or AWS Kinesis to handle high-throughput, low-latency streaming queues.

Stream Processing: Process, clean, and transform data on the fly using Apache Spark Streaming, Flink, or AWS Lambda.

Storage & Catalog: Store raw and transformed payloads in Amazon S3 and catalog meta-data using AWS Glue.

Query Engine: Perform SQL queries over real-time and historical datasets using AWS Athena or Snowflake.

Visualization: Connect PowerBI, Grafana, or a custom web app to display real-time stock dashboards and metrics.

Key Technical Features :

Sub-second latency for live ticker updates

Scalable distributed cluster architecture for high message volume

Seamless integration between batch historical data and live streaming feeds
