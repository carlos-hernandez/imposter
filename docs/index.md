---
layout: default
title: Documentation
description: Imposter Mock Engine
---

## Welcome

Imposter is a mock server for REST APIs, OpenAPI (and Swagger) specifications, SOAP web services (and WSDL files), Salesforce and HBase APIs.

- Run **standalone** mock servers in Docker, Kubernetes, AWS Lambda or on the JVM.
- **Embed** mocks within your tests (JVM or Node.js) to remove external dependencies.
- Script **dynamic** responses using JavaScript, Groovy or Java.
- **Capture** data from requests, then store it or return a **templated** response.
- **Proxy** an existing endpoint to replay its responses as a mock.

## Getting started

To begin, check out the [Getting started](getting_started.md) guide. See the _User documentation_ section below, or read a [product summary](./summary.md).

## User documentation

- [Getting started](getting_started.md)
- [Configuration guide](configuration.md)
- [Response templates](templates.md)
- [Scripting](scripting.md)
- [Security](security.md)

### Data capture and storage

- [Data capture](data_capture.md)
- [Stores](stores.md)
- [GraphQL](stores_graphql.md)

### Advanced

- [Advanced request matching](request_matching.md)
- [OpenAPI validation](openapi_validation.md)
- [Template queries](template_queries.md)
- [Performance simulation](performance_simulation.md)
- [Metrics, logs and telemetry](metrics_logs_telemetry.md)
- [Proxy an endpoint](proxy_endpoint.md)
- [Scaffolding configuration](scaffold.md)
- [Fake data](fake_data.md)
- [CORS](cors.md)
- [Performance tuning](./performance_tuning.md)
- [Plugins](./plugins.md)
- [Usage (arguments and environment variables)](usage.md)
- [Features](./features.md)
- [Groovy scripting tips](groovy_tips.md)

### Other

- [Tips and tricks](tips_tricks.md)
- [Benchmarks](./benchmarks.md)

## Mock types

Imposter provides specialised mocks for the following scenarios:

- **[OpenAPI](openapi_plugin.md)** - Support for OpenAPI (and Swagger) API specifications.
- **[REST](rest_plugin.md)** - Mocks RESTful or plain HTTP APIs.
- **[SOAP](soap_plugin.md)** - Support for SOAP web services (and WSDL files).
- **[HBase](hbase_plugin.md)** - Basic HBase mock implementation.
- **[SFDC (Salesforce)](sfdc_plugin.md)** - Basic Salesforce mock implementation.
- **[WireMock](wiremock_plugin.md)** - Support for WireMock mappings files.

> Learn more about [plugins](plugins.md).

## Developers

- [Build](build.md)
- [Roadmap](roadmap.md)
- [Github](https://github.com/outofcoffee/imposter)

## Tutorials

- [Mocking APIs with OpenAPI and Imposter](https://medium.com/@outofcoffee/mocking-apis-with-swagger-and-imposter-3694bd1733c0)
- [Mocking REST APIs with Imposter](https://medium.com/@outofcoffee/mocking-apis-with-imposter-53bd908632e5)
- [Mocking SOAP web services with Imposter](https://medium.com/@outofcoffee/mocking-soap-web-services-with-imposter-da8e9666b5b4)
