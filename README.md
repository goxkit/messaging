# Gokit Messaging

<p align="center">
  <a href="https://github.com/goxkit/messaging/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  </a>
  <a href="https://pkg.go.dev/github.com/goxkit/messaging">
    <img src="https://godoc.org/github.com/goxkit/messaging?status.svg" alt="Go Doc">
  </a>
  <a href="https://goreportcard.com/report/github.com/goxkit/messaging">
    <img src="https://goreportcard.com/badge/github.com/goxkit/messaging" alt="Go Report Card">
  </a>
  <a href="https://github.com/goxkit/messaging/actions">
    <img src="https://github.com/goxkit/messaging/actions/workflows/action.yml/badge.svg?branch=main" alt="Build Status">
  </a>
</p>

The `messaging` package provides an abstraction layer for integrating with various messaging systems, including RabbitMQ, MQTT, and Kafka. It defines a unified interface for publishing and consuming messages, enabling developers to switch between messaging systems with minimal code changes.

## Features

- **Unified Messaging Interface**:
  - Abstracts the differences between RabbitMQ, MQTT, and Kafka.
  - Provides a consistent API for publishing and consuming messages.

- **Extensibility**:
  - Easily extendable to support additional messaging systems.
  - Implement custom messaging backends by adhering to the provided interfaces.

- **Decoupled Design**:
  - Simplifies switching between messaging systems without modifying business logic.
  - Promotes clean and maintainable code.
