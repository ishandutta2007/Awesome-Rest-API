# Awesome-Rest-API

## Top REST API Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on HTTP API Design, OpenAPI Tooling & Self-Hosted API Frameworks*  

**Last updated: October 2026**



This repository tracks notable **commercial REST API platforms** and **open-source projects** that provide well-designed HTTP APIs, OpenAPI specifications, documentation, and server/client frameworks — from developer-first SaaS APIs to self-hosted API gateways and code generators.



**Examples** include Salesforce REST API, Stripe API, Twilio REST API, Shopify REST API, GitHub REST API, SendGrid API, Slack Web API, Plaid API, Algolia REST API, and Contentful REST API (the category leaders).



**Open-source emphasis**: REST API tooling is one of the strongest open-source domains. **OpenAPI Specification** is the de facto standard for describing REST APIs with 30,000+ GitHub_Stars . **FastAPI**, **Express**, **Django REST Framework**, and **Spring Boot** dominate server frameworks. **Swagger UI**, **Redoc**, and **Scalar** deliver documentation. **OpenAPI Generator** and **Swagger Codegen** automate client/SDK generation across 50+ languages. **Postman**, **Bruno**, and **Hoppscotch** provide API clients. **Kong**, **Traefik**, and **Apache APISIX** handle gateway concerns. **JSON Schema** validates payloads. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Starting Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Stripe API](https://stripe.com/docs/api)** | The gold standard for REST API design — predictable resource-oriented URLs, form-encoded request bodies, JSON responses, idempotency keys, and comprehensive error handling. Best for payments and financial infrastructure. | Pay-as-you-go at 2.9% + $0.30 per transaction (standard domestic card processing); $0 monthly platform fee | Free forever testing in full-featured Test/Sandbox mode with unlimited simulated API calls; $0 upfront cost |
| **[Twilio REST API](https://www.twilio.com/docs/usage/api)** | Communications API — SMS, voice, video, and email with consistent REST conventions, pagination, and webhooks. Best for programmable communications. | Pay-as-you-go starting at $0.0083 per SMS segment (US domestic) | 30-day free trial with 100 free SMS messages (limited to 5 verified recipient phone numbers) |
| **[Salesforce REST API](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)** | Enterprise CRM API — SOQL queries, composite requests, bulk operations, and OAuth 2.0 authentication. Best for Salesforce integrations. | Enterprise Edition starts at $175/user/month (billed annually) with API access included | Free forever Developer Edition org with 15,000 API calls per rolling 24-hour window (or 30-day standard evaluation trial) |
| **[Shopify REST API](https://shopify.dev/docs/api/admin-rest)** | E-commerce API — products, orders, customers, inventory, and fulfillment with cursor-based pagination and rate limiting. Best for Shopify app development. | Basic Plan starts at $29/month (billed annually) or $39/month (billed monthly) | Free forever partner development stores with full Admin REST API access for app testing; 3-day merchant trial for live stores |
| **[GitHub REST API](https://docs.github.com/en/rest)** | Developer platform API — repositories, issues, pull requests, actions, and webhooks with extensive documentation. Best for GitHub integrations. | Team plan starts at $4/user/month ($48/user/year) | Free forever plan with 5,000 authenticated requests/hour (or 60 unauthenticated requests/hour per IP) |
| **[SendGrid API](https://docs.sendgrid.com/api-reference/)** | Email API — transactional and marketing email with templates, scheduling, and analytics. Best for email delivery. | Essentials 50K plan starts at $19.95/month for up to 50,000 emails/month | 60-day free trial with 100 emails per day |
| **[Slack Web API](https://api.slack.com/web)** | Messaging API — channels, messages, users, and workflows with Web API, Events API, and Socket Mode. Best for Slack apps. | Pro plan starts at $7.25/user/month (billed annually) or $8.75/user/month (billed monthly) | Free forever plan with standard Tier rate limits (~1 msg/sec per channel, 30,000 event deliveries/hr/workspace) and up to 10 app integrations |
| **[Plaid API](https://plaid.com/docs/api/)** | Financial data API — bank account linking, transactions, identity verification, and balance checks. Best for fintech applications. | Pay-as-you-go starting with product fees (e.g. Auth one-time connection fee, Balance per-request fee) with $0 monthly minimum | Free forever Sandbox environment with unlimited mock testing; Free Production Trial plan with up to 10 live connected Items |
| **[Algolia REST API](https://www.algolia.com/doc/rest-api/)** | Search API — indexing, search, and recommendations with multi-language SDKs and real-time updates. Best for search and discovery. | Grow plan (Pay-as-you-go) at $0.50 per 1,000 additional search requests after monthly free allowance | Free forever Build plan with 10,000 search requests/month and 50,000 records |
| **[Contentful REST API](https://www.contentful.com/developers/docs/references/content-delivery-api/)** | Content management API — content delivery, management, and preview APIs for headless CMS. Best for content-driven applications. | Lite plan starts at $300/month for up to 1,000,000 API calls/month and 100 GB CDN bandwidth | Free forever plan with 100,000 API calls/month, 50 GB CDN bandwidth, and 10,000 content records |



## Open-Source GitHub Projects



### Specifications & Standards



- **[OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification)**  

  **The world's most widely used API description format**, Apache-2.0 licensed with **30,000+ GitHub_Stars** . **Language-agnostic interface to HTTP APIs** — allows both humans and computers to discover and understand service capabilities without access to source code, documentation, or network traffic inspection . **Machine-readable format** for documentation, code generation, testing, and automation . **Best for standardizing REST API descriptions** .



- **[JSON Schema](https://github.com/json-schema-org/json-schema-spec)**  

  **The standard for validating JSON data structures**, open-source . **Vocabulary that allows annotation and validation of JSON documents** . **Essential for request/response validation in REST APIs** . **Best for payload validation** .



- **[API Blueprint](https://github.com/apiaryio/api-blueprint)**  

  **Powerful high-level API description language**, MIT licensed with **8,700+ GitHub_Stars** . **Markdown-based API documentation format** . **Best for human-readable API specs** .



- **[RAML](https://github.com/raml-org/raml-spec)**  

  **RESTful API Modeling Language**, open-source . **YAML-based language for describing RESTful APIs** . **Best for API-first design** .



### Server Frameworks



- **[FastAPI](https://github.com/fastapi/fastapi)**  

  **Modern, fast web framework for building APIs with Python**, MIT licensed with **85,000+ GitHub_Stars** . **Automatic OpenAPI documentation, type validation with Pydantic, async support, dependency injection, and OAuth2/JWT security** . **The fastest-growing Python API framework** . **Best for Python REST APIs** .



- **[Express](https://github.com/expressjs/express)**  

  **Fast, unopinionated, minimalist web framework for Node.js**, MIT licensed with **65,000+ GitHub_Stars** . **The de facto standard for Node.js REST APIs** . **Best for Node.js REST APIs** .



- **[Django REST Framework](https://github.com/encode/django-rest-framework)**  

  **Powerful and flexible toolkit for building Web APIs**, BSD-3-Clause licensed with **30,000+ GitHub_Stars** . **Serialization, authentication, permissions, pagination, and browsable API** . **Best for Django-based REST APIs** .



- **[Spring Boot](https://github.com/spring-projects/spring-boot)**  

  **Java framework for building production-ready REST APIs**, Apache-2.0 licensed with **75,000+ GitHub_Stars** . **Spring Web, Spring Data REST, and Spring HATEOAS** . **Best for Java REST APIs** .



- **[NestJS](https://github.com/nestjs/nest)**  

  **Progressive Node.js framework for building efficient, scalable server-side applications**, MIT licensed with **70,000+ GitHub_Stars** . **TypeScript-first with decorators, dependency injection, and modular architecture** . **Best for TypeScript REST APIs** .



- **[Fiber](https://github.com/gofiber/fiber)**  

  **Express-inspired web framework for Go**, MIT licensed with **35,000+ GitHub_Stars** . **High performance, low memory, and familiar API** . **Best for Go REST APIs** .



- **[Gin](https://github.com/gin-gonic/gin)**  

  **HTTP web framework written in Go**, MIT licensed with **80,000+ GitHub_Stars** . **Fast, with middleware, routing, and JSON validation** . **Best for Go REST APIs** .



- **[Actix Web](https://github.com/actix/actix-web)**  

  **Powerful, pragmatic, and extremely fast web framework for Rust**, MIT/Apache-2.0 licensed with **22,000+ GitHub_Stars** . **Best for Rust REST APIs** .



- **[Axum](https://github.com/tokio-rs/axum)**  

  **Ergonomic and modular web framework built with Tokio, Tower, and Hyper**, MIT licensed with **20,000+ GitHub_Stars** . **Best for Rust REST APIs** .



- **[Laravel](https://github.com/laravel/framework)**  

  **PHP web framework with comprehensive API tooling**, MIT licensed with **33,000+ GitHub_Stars** . **Laravel Sanctum for API tokens and Passport for OAuth2** . **Best for PHP REST APIs** .



- **[Rails API](https://github.com/rails/rails)**  

  **Ruby on Rails in API-only mode**, MIT licensed with **56,000+ GitHub_Stars** . **Fast JSON APIs with ActiveModel::Serializers or Jbuilder** . **Best for Ruby REST APIs** .



### Documentation & Code Generation



- **[Swagger UI](https://github.com/swagger-api/swagger-ui)**  

  **Visual documentation for OpenAPI specs**, Apache-2.0 licensed with **26,000+ GitHub_Stars** . **Interactive API documentation from OpenAPI specs** . **Best for OpenAPI documentation** .



- **[Redoc](https://github.com/Redocly/redoc)**  

  **OpenAPI-generated documentation with beautiful three-panel design**, MIT licensed with **23,000+ GitHub_Stars** . **Best for beautiful API reference docs** .



- **[Scalar](https://github.com/scalar/scalar)**  

  **Modern open-source API client and documentation generator**, MIT licensed with **7,000+ GitHub_Stars** . **Beautiful API reference from OpenAPI specs** . **Best for modern API documentation** .



- **[OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)**  

  **Generate clients, servers, and documentation from OpenAPI specs**, Apache-2.0 licensed with **22,000+ GitHub_Stars** . **50+ languages and frameworks supported** . **Best for SDK generation** .



- **[Swagger Codegen](https://github.com/swagger-api/swagger-codegen)**  

  **Generate server stubs and client SDKs from OpenAPI specs**, Apache-2.0 licensed with **17,000+ GitHub_Stars** . **Best for legacy code generation** .



- **[swagger-editor](https://github.com/swagger-api/swagger-editor)**  

  **Design, describe, and document APIs in YAML or JSON**, Apache-2.0 licensed . **Best for OpenAPI authoring** .



- **[Stoplight Studio](https://github.com/stoplightio/studio)**  

  **Open-source API design and documentation editor**, Apache-2.0 licensed . **Best for API-first design** .



### API Clients & Testing



- **[Postman](https://github.com/postmanlabs)**  

  **The most widely used API client** (open-source components) . **Collections, environments, testing, and monitoring** . **Best for API development and testing** .



- **[Bruno](https://github.com/usebruno/bruno)**  

  **Fast, Git-friendly, open-source API client**, MIT licensed with **30,000+ GitHub_Stars** . **Collections stored as plain text for version control** . **Best for offline-first API testing** .



- **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)**  

  **Open-source API development ecosystem**, MIT licensed with **70,000+ GitHub_Stars** . **Lightweight, web-based API client** . **Best for quick API testing in browser** .



- **[Insomnia](https://github.com/Kong/insomnia)**  

  **Open-source API client with GraphQL and REST support**, Apache-2.0 licensed with **35,000+ GitHub_Stars** . **Best for cross-platform API testing** .



- **[Newman](https://github.com/postmanlabs/newman)**  

  **Command-line collection runner for Postman**, Apache-2.0 licensed . **Best for CI/CD API testing** .



- **[Dredd](https://github.com/apiaryio/dredd)**  

  **Language-agnostic HTTP API testing tool**, MIT licensed with **4,200+ GitHub_Stars** . **Tests API against API Blueprint or OpenAPI** . **Best for contract testing** .



- **[Schemathesis](https://github.com/schemathesis/schemathesis)**  

  **Property-based testing for OpenAPI and GraphQL APIs**, MIT licensed with **2,600+ GitHub_Stars** . **Automatic test generation from OpenAPI specs** . **Best for automated API testing** .



### Gateways & Middleware



- **[Kong Gateway](https://github.com/Kong/kong)**  

  **The most widely adopted open-source API gateway**, Apache-2.0 licensed with **40,000+ GitHub_Stars** . **API management, rate limiting, authentication, and plugins** . **Best for API gateway** .



- **[Apache APISIX](https://github.com/apache/apisix)**  

  **High-performance API gateway**, Apache-2.0 licensed with **15,000+ GitHub_Stars** . **Dynamic routing, plugins, and observability** . **Best for high-performance API gateway** .



- **[Traefik](https://github.com/traefik/traefik)**  

  **Cloud-native application proxy**, MIT licensed with **50,000+ GitHub_Stars** . **Automatic service discovery and Let's Encrypt** . **Best for Kubernetes ingress** .



- **[Envoy Gateway](https://github.com/envoyproxy/gateway)**  

  **Kubernetes-native gateway**, Apache-2.0 licensed . **Gateway API implementation based on Envoy** . **Best for Kubernetes Gateway API** .



- **[Tyk Gateway](https://github.com/TykTechnologies/tyk)**  

  **Open-source API gateway**, MPL-2.0 licensed . **Analytics, rate limiting, and authentication middleware** . **Best for API management** .



- **[KrakenD](https://github.com/krakend/krakend-ce)**  

  **Ultra-fast API gateway**, Apache-2.0 licensed . **API composition and aggregation** . **Best for API composition** .



### Additional Strong Open-Source Options



- **API Platform** — PHP framework for building REST and GraphQL APIs, Symfony-based .

- **LoopBack** — Node.js framework for building REST APIs, IBM-originated .

- **Hapi** — Node.js framework for building applications and services .

- **Restify** — Node.js framework for building REST APIs, optimized for production .

- **Lumen** — Micro-framework by Laravel for building fast APIs .

- **Slim** — PHP micro-framework for building REST APIs .

- **Falcon** — Minimalist Python web framework for building REST APIs .

- **Bottle** — Fast, simple, lightweight WSGI micro-framework for Python .

- **Koa** — Next-generation web framework for Node.js by Express creators .

- **Fastify** — Fast and low overhead web framework for Node.js .



**Frameworks for building custom REST API solutions**: Combine **OpenAPI Specification** for API description and **OpenAPI Generator** for SDK generation across 50+ languages . Use **FastAPI** or **Express** for Python/Node.js APIs with automatic documentation . Deploy **Swagger UI**, **Redoc**, or **Scalar** for API documentation . Integrate **Bruno** or **Hoppscotch** for API testing . Use **Schemathesis** for property-based testing against OpenAPI specs . Choose **Kong** or **Apache APISIX** for API gateway concerns . Note that true enterprise REST API platforms with global infrastructure, managed rate limiting, and vendor-supported SLAs (Stripe, Twilio, Salesforce) remain primarily commercial territory; open-source stacks provide strong specification, framework, documentation, and gateway foundations that require integration for complete REST API operations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- REST API platforms handle sensitive application data and must comply with data privacy regulations (GDPR, CCPA) and security standards (OAuth 2.0, TLS). Self-hosted solutions require proper security hardening, access controls, and rate limiting.

- **API design consistency matters** — Stripe's API is considered the gold standard for predictable resource-oriented URLs, idempotency, and error handling. Follow established conventions for pagination, versioning, and error responses .

- **OpenAPI is the standard** — every modern REST API should have an OpenAPI specification for documentation, code generation, and testing .

- **License considerations**: OpenAPI Specification uses Apache-2.0 , FastAPI uses MIT , Express uses MIT , Kong uses Apache-2.0 , and Bruno uses MIT . Verify licensing against your use case before committing.

- The open-source ecosystem provides strong specification, framework, documentation, and gateway foundations, but **global infrastructure, managed rate limiting, and vendor-supported SLAs** remain primarily commercial offerings.
