# Kafka-AWS-Streaming-Stock
## Purpose
This project is thank to "Darshil Parmar" that I am able to create it, you can watch more on https://www.youtube.com/watch?v=KerNf0NANMo&ab_channel=DarshilParmar

The purpose of this project is to learn creating streaming data (stock-market) using Apache Kafka in Python to Amazon Web Services (Amazon S3, Glue, Athena). We use EC2 machine to install tool to perform the task and learn more about the AWS. Here is the building structure of this project 

![Architecture](https://user-images.githubusercontent.com/99011504/218926703-9c3d754c-403e-4d84-8125-7f9b4ad854d3.jpg)
## Register AWS
First, you need to register your account and provide credit card information to AWS. It is fairly simple by following AWS instruction or watch YouTube on how to create account in AWS.

After that, search EC2 -> click on "Instances" -> click "Lanuch instances" -> provide "Name" at Name and tags -> choose "Amazon Machine Image" you want -> select "Instance type", for learning should choose Free tier eligible such as "t2.micro" -> create "Key pair" by provide name t -> you can reseach the other option, or leave it default -> then "Launch instance" to create EC2

You can now click Instance Name that you just create, click on "Start instance" to start or "Stop instance" to stop
## Install tool
Now, it is time to install Apache Kafka and other tools on EC2 machine to continue your project. 

First, open cmd, then type "wget https://downloads.apache.org/kafka/3.4.0/kafka_2.13-3.4.0.tgz" or you can go to kafka.apache.org to download lastest version. NOTED: Please download at Binary section: Scala {version}.   
