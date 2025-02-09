---
title: REST API
category: Integrations
chapter: 6
order: 8
---

Dependency-Track is built using a *thin server architecture* and an *API-first design*. APIs are simply at the heart
of the platform. Every API is fully documented via OpenAPI v3.

> http://{hostname}:{port}/api/openapi.json  
> http://{hostname}:{port}/api/openapi.yaml

**Note:** The OpenAPI endpoints are only available on the backend server, not on the frontend server.
If you run Dependency Track with the default Docker Compose file, this is port `8081` and *not* port `8080`.

The Swagger UI Console (not included) can be used to visualize and explore the wide range of possibilities. Chrome and
Firefox extensions can be used to quickly use the Swagger UI Console.

![Swagger UI Console](/images/screenshots/swagger-ui-console.png)

Prior to using the REST APIs, an API Key must be generated. By default, creating a team will NOT create an API key. A team may have multiple keys.

![Teams - API Key](/images/screenshots/teams.png)
