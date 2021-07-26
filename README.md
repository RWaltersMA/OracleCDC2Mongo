#Oracle to MongoDB via Kafka

This repo is part of the MongoDB blog post, "Data movement from Oracle to MongoDB made easy with Apache Kafka".  The docker compose will spin up a local MongoDB database, Apache Kafka, Kafka Conenct and Confluent KSQL and Schema Registry.  With this platform you can configure the environment to read data with the Confluent Oracle CDC connector, transform it using KSQL and write it into MongoDB using the MongoDB Connector for Apache Kafka.

Note: If you do not already have an Oracle environment, you can pull one from docker via `docker pull store/oracle/database-enterprise:12.2.0.1-slim`

Launch the environment by issuing: `docker-compose up -d build`

Refer to the blog post (link TBD) for specific tutorial steps.

