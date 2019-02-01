# Kafka Procesing

## Example code used from the API

https://kafka.apache.org/documentation/#introduction

## Producer, Consumer, Streams APIs

With a producer you can publish one or more stream of records to a kafka topic. With a Consumer you can subscribe to one or more topics and process a stream of records. Streams transforms input to output streams.

## Protocol Language Access

Done through language agnostic TCP protocol
`Kafka uses a binary protocol over TCP`

- No handshake is required on connection or disconnection
- The client initiates a socket connection
- server gaurantees FIFO processing.

### Topics and Logs

In a queue, a pool of consumers may read from a server and each record goes to one of them; in publish-subscribe the record is broadcast to all consumers.
Topic is

- The Kafka cluster durably persists all published records—whether or not they have been consumed—using a configurable retention period.
