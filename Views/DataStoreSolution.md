# Datastore Solution

1. _To store and process CCTV recordings_, we suggest using **Azure Data Factory**, a fully managed cloud-based ETL service with data integration that automates data movement and transformation by collecting raw information and transforming it into ready-to-use information using special services . 

 **Azure Blob** storage provides scalable and cost-effective object storage in the cloud, which provides the ability to store and access unstructured data for the most demanding workloads. 

  **Azure Analysis Services** is a fully managed platform as a service (PaaS) that provides enterprise-grade data models in the cloud. With advanced combining and modeling features, you can combine data, define metrics, and secure data in one trusted semantic tabular data model. The Data Model helps you perform ad hoc data analysis faster with tools like Power BI. 

  **Azure Active Directory** provides an identity platform with advanced security features, access control, scalability, and reliability. For data visualization, we suggest using Power BI


![image](https://user-images.githubusercontent.com/58341842/151186813-3989ed15-cb1f-47ad-98d4-79c36fb2c345.png)

2. _To collect IoT data_, we suggest using the **Azure IoT Hub** - an IoT managed services platform that enables message routing of all IoT devices and applications to transfer data through the cloud. 

  **Event Hub** is an event processing service used to provide cloud events and introduce telemetry with low latency and high reliability. 
  
  **The Event Center** provides messaging processing functionality, and its characteristics differ from traditional enterprise messaging. The Event Center feature is built on high throughput and event handling solutions. 

  We suggest using **Kafka and Haddop (HDFS)** for data storage. Kafka collects data from applications, stores it in its distributed storage, grouping it by topic, and gives it to application components by subscription. At the same time, messages are stored on different broker nodes, which ensures high availability and fault tolerance. Hadoop Distributed File System is a distributed file system designed to store large files distributed block by block between the nodes of a computing cluster. For data processing, we will use **Haddop MapReduce** - is a framework using which we can write applications to process huge amounts of data, in parallel, on large clusters of commodity hardware in a reliab. **Spark** is also suitable for data processing - a framework for cluster computing and large-scale data processing.

  As a database, Apache Hbase and Hadoop (HDFS) are suitable for us. **Apache HBase** is an open source NoSQL database. HBase provides direct access and strong consistency for large amounts of data in a schemaless database. To create a machine learning model (for predicting weather changes and its impact), we will use Azure ML. 
**Microsoft Azure Machine Learning** is a set of predictive analytics cloud services that allows you to predict various events in the future. 
We will use **Mahout** as our data mining framework, which typically works in conjunction with the Hadoop framework in the background to manage massive amounts of data. For data visualization and predictive models, we will use **Power BI**

![image](https://user-images.githubusercontent.com/58341842/151187082-82e554fa-ac2e-4050-8775-a64f44c96801.png)

[Back to contents](../README.md)
