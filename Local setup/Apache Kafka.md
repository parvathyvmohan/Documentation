# Summary
This document provides links and steps to be followed to get local kafka running

## Steps followed
1.  Download the binaries from http://kafka.apache.org/downloads  
2.  Make changes as listed in https://www.goavega.com/install-apache-kafka-on-windows/
3.  Remember to run the server and zookeeper as admin
4.  Follow steps as per article. For consuming messages use this command instead
  - kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic [topic name] --from-beginning --partition 0
