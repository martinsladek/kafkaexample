## Kafka Example

## Clone:
```
git clone https://github.com/martinsladek/kafkaexample.git
```

## Build:
```
mvn clean install
```

## Run:
```
mvn spring-boot:run
```

## Example usage:

Open terminal:
```
cd src\test\resources\bin
```

Start Kafka Docker container:
```
001-kafka-start.cmd
```

Send message to Kafka:
```
002-kafka-send.cmd
```

Stop Kafka Docker container:
```
003-kafka-stop.cmd
```

Remove Kafka Docker container:
```
004-kafka-delete.cmd
```

