# Awesome-Developer-Tooling-API

# Top Developer Tooling API Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on API Management, Gateway Infrastructure & Developer Experience*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Tooling APIs**. These tools enable teams to manage API lifecycles, build gateways, test endpoints, generate documentation, and integrate with CI/CD pipelines — powering modern API-first development workflows.

**Examples** include Salesforce Tooling API, GitHub REST API, GitLab API, Bitbucket Cloud API, Docker Hub API, Vercel API, Netlify API, Postman API, CircleCI API, and Travis CI API (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom gateway infrastructure, and open API tooling — ideal for platform engineers, DevOps teams, and developers seeking transparent, vendor-independent API management.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Tooling API](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/)**  
  REST API for accessing metadata about Apex classes, triggers, Visualforce pages, and development artifacts. Provides endpoints for querying, creating, updating, and deleting tooling objects such as ApexClass, ApexTrigger, ApexLog, and MetadataContainer. Base URL: `https://{instance}.salesforce.com/services/data/v59.0/tooling` .

- **[GitHub REST API](https://docs.github.com/rest)**  
  Comprehensive API (version 2026-03-10) for managing repositories, issues, pull requests, actions, packages, and more. Features OpenAPI descriptions, granular PAT permissions, and extensive endpoint coverage across users, orgs, and enterprise features .

- **[GitLab API](https://docs.gitlab.com/api/)**  
  REST API (v4) for projects, pipelines, merge requests, and CI/CD management. Supports offset and keyset pagination, authentication via PRIVATE-TOKEN header, and comprehensive endpoint coverage for GitLab features .

- **[Bitbucket Cloud API](https://developer.atlassian.com/cloud/bitbucket/)**  
  2.0 REST API with Bitbucket Query Language (BBQL) for filtering, partial responses, and API proxy module for authentication and parameter substitution. Built on OpenAPI Specification 2.0 .

- **[Docker Hub API](https://docs.docker.com/reference/api/hub/)**  
  API v2 (beta) for managing repositories, tags, organizations, teams, and access tokens. Includes Registry HTTP API v2 for manifests, blobs, and multi-arch inspection, plus Docker Scout for CVE/SBOM intelligence .

- **[Vercel API](https://vercel.com/docs/rest-api)**  
  REST API for deployments, projects, domains, and networking. Features check runs, Secure Compute networks, PrivateLink endpoints, and connector management for integrations .

- **[Netlify API](https://docs.netlify.com/api-and-cli-guides/api-guides/get-started-with-api/)**  
  REST API for site deployment, functions, and form handling. Supports ZIP file deploys, async requests for large deploys, and OpenAPI reference .

- **[Postman API](https://learning.postman.com/docs/)**  
  API for managing collections, environments, mocks, and monitors. Enables programmatic access to Postman workspace for CI/CD integration and team collaboration .

- **[CircleCI API](https://circleci.com/docs/api/)**  
  REST API for pipelines, workflows, jobs, and insights. Provides programmatic access to trigger builds, manage contexts, and retrieve pipeline metadata including VCS and trigger information .

- **[Travis CI API](https://docs.travis-ci.com/api/)**  
  API V3 for repositories, builds, jobs, and CI settings. Supports build triggering, environment variable management, cron schedules, cache management, and `.travis.yml` validation .

## Open-Source GitHub Projects

- **[Kong](https://github.com/Kong/kong)**  
  Leading open-source microservice API gateway and platform (Apache-2.0). Features plugin ecosystem, rate limiting, authentication, and observability. Deployable via Docker, Kubernetes, or bare metal. 40k+ GitHub stars.

- **[Tyk](https://github.com/TykTechnologies/tyk)**  
  Fast and scalable open-source API gateway (MPL-2.0). Out-of-the-box API Management Platform with gateway, analytics, developer portal, and dashboard. Go-based with Docker/K8S deployment .

- **[Hasura](https://github.com/hasura/graphql-engine)**  
  Instant GraphQL and REST APIs on Postgres (Apache-2.0). Features fine-grained access control, webhooks on database events, and real-time subscriptions. 31k+ GitHub stars.

- **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)**  
  Fast and beautiful open-source API request builder (MIT). Alternative to Postman with lightweight browser-based UI, collections, environments, and team collaboration. 70k+ GitHub stars .

- **[Fusio](https://github.com/apioo/fusio)**  
  Open-source API management platform (AGPL-3.0). Helps build and manage REST APIs with a backend, developer portal, and analytics .

- **[DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory)**  
  Turns any SQL/NoSQL/structured data into RESTful APIs (Apache-2.0). Auto-generates APIs for databases with role-based access control, API keys, and user management .

- **[Yaade](https://github.com/EsperoTech/yaade)**  
  Open-source, self-hosted, collaborative API development environment (MIT). Lightweight alternative to Postman/Insomnia with team collaboration features .

- **[Tainha Gateway](https://github.com/lusqua/tainha-gateway)**  
  Lightweight open-source API gateway written in Go (license varies). Features routing with path params, JWT auth (HS256 or delegation), response mapping with parallel service aggregation, SSE passthrough, rate limiting, OpenTelemetry traces, and Prometheus metrics. Single YAML config .

- **[webscope](https://gitlab.com/manabug/webscope)**  
  Lightweight API documentation tool (license varies). Generates static HTML from markdown and OpenAPI files with separate pages for spec, documentation, and changelog. CLI and HTTP server modes .

- **[AAT (Adaptive API Toolkit)](https://github.com/gburgyan/aat)**  
  CLI tool for testing API workflows end-to-end (license varies). Defines APIs as graphs, executes test plans with data dependency resolution, and produces detailed request/response archives. LLM-assisted test plan generation and MCP server for IDE integration .

- **[api-client-tui](https://github.com/nutcas3/api-client-tui)**  
  Terminal-based API client built with Bubble Tea (license varies). Fast alternative to GUI tools with multi-panel TUI, request history, environment variables, and collections .

- **[Lura](https://github.com/luraproject/lura)**  
  High-performance API Gateway framework (license varies). Extensible with middleware and plugins for custom API management .

- **[Graphweaver](https://github.com/exogee-technology/graphweaver)**  
  Turn multiple data sources into a single GraphQL API (MIT). Features automatic schema generation, data source connectors, and admin UI .

- **[Para](https://github.com/erudika/para)**  
  Flexible and modular backend framework/server for object persistence, API development, and authentication (Apache-2.0). Java-based with Docker support .

- **[Svix](https://github.com/svix/svix-webhooks)**  
  Open-source webhooks as a service (MIT). Makes it easy for API providers to send webhooks with retry logic, signatures, and monitoring .

- **[Opik](https://github.com/comet-ml/opik)**  
  Open-source LLM observability and evaluation toolkit (Apache-2.0). Evaluate, test, and ship LLM applications with observability tools across dev and production lifecycle .

- **[form.io](https://github.com/formio)**  
  REST API building platform with drag-and-drop form builder (MIT). Application framework agnostic with open-source and enterprise versions .

### Additional Strong Open-Source Options

- **[Insomnia](https://github.com/Kong/insomnia)** — Open-source API client (Apache-2.0) for REST, GraphQL, and gRPC.
- **[Bruno](https://github.com/usebruno/bruno)** — Fast, Git-friendly API client (MIT) storing collections as plain files.
- **[Swagger UI](https://github.com/swagger-api/swagger-ui)** — Visual documentation for OpenAPI specs (Apache-2.0).
- **[Redoc](https://github.com/Redocly/redoc)** — OpenAPI documentation generator (MIT).
- **[Postwoman/Hoppscotch](https://github.com/hoppscotch/hoppscotch)** — Already listed above.
- **[Mockoon](https://github.com/mockoon/mockoon)** — Desktop API mocking tool (MIT).
- **[WireMock](https://github.com/wiremock/wiremock)** — HTTP mock server (Apache-2.0).
- **[Pact](https://github.com/pact-foundation/pact-js)** — Contract testing framework (MIT).
- **[K6](https://github.com/grafana/k6)** — Load testing tool (AGPL-3.0) for API performance.
- Community **OpenAPI Generator** projects for SDK generation from specs.

**Frameworks for building custom systems**: Combine **Kong** or **Tyk** as the API gateway with **Hoppscotch** for API development and testing, **webscope** for documentation generation, **AAT** for workflow testing, and **Svix** for webhooks — creating a fully self-hosted, enterprise-grade developer tooling API platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- API management platforms handling authentication and data must comply with security regulations (SOC 2, GDPR, etc.).
- Self-hosted open-source solutions require proper security hardening, rate limiting configuration, and ongoing maintenance for production reliability.

---

**Made for platform engineers, DevOps teams, backend developers, and organizations building transparent API tooling solutions.**  
Let's make Developer Tooling APIs more open, data-driven, and efficient.
