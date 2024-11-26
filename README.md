# dataEngFlow

Creating a simple poc dataflow 

Create data using Faker
Producers publish to Kafka 
Consume and Transform using PySpark
Use PySpark Structured Streaming to Wrie to GCP BigQuery 

Infastructure with Terraform

resources:

https://dev.to/ankitmalikg/python-generate-fake-data-with-faker-1ecj

https://www.geeksforgeeks.org/how-to-install-and-run-apache-kafka-on-windows/

https://www.svix.com/guides/kafka/python-kafka-producer/

https://medium.com/google-cloud/streaming-events-to-bigquery-using-spark-structured-streaming-96cf541de4ed

https://www.terraform.io/

Run Locally:

cd \
cd Kafka
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
.\bin\windows\kafka-server-start.bat .\config\server.properties