# Spark-ClickStream-Application

This is spark application developed using scala with lambda architecture.  When it comes to big data, Lamda arch is designed to address
fault tolerance of Big Data systems. It makes use of both Batch layer processing and Stream/Speed processing in spark.

Steps to run application :
This application is built using Spark, Kafka, Cassandra. Make sure to setup all these in your VM box along with Hadoop.
Update Maven to include all dependencies in IDE.

To generate log files run logproducer.scala. Batch job is run from batchjob.scala and streaming job is run using streamingjob.scala. 
