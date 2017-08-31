# Spark Streaming with Kafka

This repository contains experimentation and examples of doing Streaming in Spark (2.2 onwards) with Kafka as Source

# How to Run
To run the StreamingApp example, first start up Kafka brokers and create a topic and publish some data. Then to run the
streaming job execute the following command:

```
spark-submit --packages org.apache.spark:spark-sql-kafka-0-10_2.11:2.2.0
kafka-streaming-1.0-SNAPSHOT.jar <list_of_brokers> subscribe <kafka_topic>
```
