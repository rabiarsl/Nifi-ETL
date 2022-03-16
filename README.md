# Nifi-ETL (PostgreSQL/API - Kafka - ElasticSearch)

This is a pipeline that fetches data from PostgreSQL and API (fake rest used), then publishes to Kafka topics. The subscribed content updates elasticsearch indices.


# Packages needed

Download and install NiFi: https://nifi.apache.org/download.html

Download and install PostgreSQL: https://www.postgresql.org/download

Download and install Kafka 2.6: https://kafka.apache.org/downloads

Download and install ElasticSearch: https://www.elastic.co/downloads/elasticsearch


# Overall Pipeline

## PostgreSQL/API to Kafka

![image](https://user-images.githubusercontent.com/30345527/158668228-1a0da0b5-2dc5-4726-add4-00db8131c338.png)

## Kafka to Elasticsearch
