# Interconnect

Interconnect provides a configurable interface between Kafka and MQTT. 
Interconnect strives to be:

* Reliable - Delivery guarantees provided by both Kafka and the MQTT broker
should be honored
* Fast - Performance metrics are TBD, but this project should provide high
throughput with very low overhead
* Secure - Data access can be restricted through client-based access control  
* Scalable - The service should scale horizontally
  * Ideally, it should be possible to scale dynamically with load
* Simple - Configuration should be straightforward
  * External dependencies should be minimized

## Status

This project is very early development.