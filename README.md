# Microservice template [![Build](https://github.com/Covid-Alert-Microservices/Microservice-template/actions/workflows/build.yaml/badge.svg)](https://github.com/Covid-Alert-Microservices/Microservice-template/actions/workflows/build.yaml)

This repository aims to provide a starter template for our microservices.
It provides the base configuration to integrate with other microservices as Keycloak.

## Currently shipped in the template

- Configuration of Spring Security to only accept authenticated request on `/api/**`
- Authentication of requests with Keycloak
- Listening and publishing of Kafka topics
- CI to build the application

## Environment variables

The following environment variables can be configured:
- `KEYCLOAK_URL`: the URL to the Keycloak instance (default: `http://localhost:5000`)
- `KAFKA_URL`: the URL to the Kafka node (default: `http://localhost:29092`)