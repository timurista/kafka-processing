## Kafka notes

Setup notes on how kafka works

## Commands

## Zookeeper

`> bin/zookeeper-server-start.sh config/zookeeper.properties`

### Server Kafka

`> bin/kafka-server-start.sh config/server.properties`

## Create a Topic

`> bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic test`

`> bin/kafka-topics.sh --list --zookeeper localhost:2181`
