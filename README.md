# Relay MQ

English | [Русский](README.ru.md)

`Relay MQ` is an event broker for asynchronous communication between services.
The project is inspired by systems like Kafka and Redis Streams, with a focus on low latency, reliability, and horizontal scaling.

## Description

Relay MQ helps build event-driven architecture where producers publish events and consumers process them independently.

Main use cases:
- service-to-service event exchange
- asynchronous command and job processing
- event fan-out to multiple consumers
- reliable message delivery in distributed systems

## Project Goals

- predictable message delivery under load
- convenient horizontal scaling by adding nodes
- fault tolerance and restart recovery
- a clear and compact protocol for clients
- practical operation in development and production

## Key Capabilities

- publish/subscribe model
- support for consumer groups
- configurable delivery semantics
- clustering and data replication
- durable storage for recovery
- admin and observability endpoints

## Development Status

The project is under active development.
Core broker functionality is already implemented, but APIs and behavior may evolve.

## Quick Start

```bash
python3 main.py
```

By default, Relay MQ starts:
- broker server
- event stream endpoint

## Roadmap (High-Level)

- stabilize protocol and client contracts
- improve production hardening and test coverage
- expand tooling and operational documentation
- prepare official client SDK examples

## License

This project is licensed under Apache License 2.0. See [LICENSE](LICENSE).
