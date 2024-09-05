# Simple Application using: 

Spring Boot Reactive and Apache Kafka

## Summary:

    Producer Client: Pulls data from Wikimedia and sends it to Kafka.
    Kafka Broker: Acts as a message broker, storing and managing the messages.
    Consumer Client: Retrieves the data from Kafka for processing or further use.

## Commands for windows

Start the zookeeper

```bash
bin\windows\zookeeper-server-start.bat config\zookeeper.properties
```

Start Kafka server

```bash
bin\windows\kafka-server-start.bat .\config\server.properties
```

To list topics

```bash
bin\windows\kafka-topics.bat --bootstrap-server localhost:9092 --list
```

**N.B:** These commands are for windows users
