# Distributed Systems – Energy Data Project

A university project developed for the "Distributed Systems" course.

## Overview
This system simulates energy consumption and production, using message queues and persistent storage. It consists of **six independent components**, communicating via RabbitMQ and persisting data in PostgreSQL.

## Features
- Local deployment using Docker (RabbitMQ and PostgreSQL)
- Two producer components:
  - **Energy User** and **Energy Producer** send messages to specific RabbitMQ queues
- Data persistence via PostgreSQL
- REST API for retrieving current and historical energy data
- JavaFX GUI for visualizing energy statistics through the REST API

## Tech Stack
- Java (Spring Boot, JavaFX)
- RabbitMQ (via Docker)
- PostgreSQL (via Docker)
- REST API (JSON responses)
