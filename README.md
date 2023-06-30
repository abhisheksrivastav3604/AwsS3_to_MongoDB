# How to Fetch objects from S3 and load them into MongoDB using Apache Nifi

## Aim

The Aim is to Fetch objects from S3 and load them into MongoDB using Apache Nifi

## References

Link: `https://medium.com/@evanescence1106/fetch-object-from-s3-using-apache-nifi-660c314e96b1`

## Prerequisites

To run this project, you need the following prerequisites:

Apache NiFi: You need Apache NiFi installed on your system. If you don't have it, you can follow the instructions on `https://nifi.apache.org/docs/nifi-docs/html/getting-started.html#downloading-and-installing-nifi` to install it.

User and Password: You need  user and password to login the Apache NiFi. 

We need the access key ID and Secret Access Key of AWS 

MongoDB: You need MongoDB installed on your system. If you don't have it, you can follow the instructions on `https://www.geeksforgeeks.org/how-to-install-mongodb-on-windows/` to install it.

Full flow in NiFi involves fetching the CSV file, converting it to JSON, changing the file type, and storing the data in MongoDB given below:

![Screenshot (338)](https://github.com/abhisheksrivastav3604/AwsS3_to_MongoDB/assets/117782915/671e0ee1-9592-4995-a7fb-f09f51b36e81)



## How to Run

To run the project:
Draw The process Flow or import template into Apache NiFi and, 
Click the "Run" button in Apache NiFi to execute the flow.

