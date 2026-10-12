# Awesome-Developer-Tooling-API

## Top Developer Tooling API Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on API Management, Gateway Infrastructure & Developer Experience*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Tooling APIs**. These tools enable teams to manage API lifecycles, build gateways, test endpoints, generate documentation, and integrate with CI/CD pipelines — powering modern API-first development workflows.



**Examples** include Salesforce Tooling API, GitHub REST API, GitLab API, Bitbucket Cloud API, Docker Hub API, Vercel API, Netlify API, Postman API, CircleCI API, and Travis CI API (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom gateway infrastructure, and open API tooling — ideal for platform engineers, DevOps teams, and developers seeking transparent, vendor-independent API management.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global API management and developer tooling market is estimated at approximately **$8.6B to $10.5B** and projected to surpass **$30B+ by the early 2030s** (growing at an ~18–22% CAGR). The sector exhibits a **dual dynamic**: it is **moderately concentrated** at the enterprise infrastructure layer (where hyperscalers and incumbents like Microsoft/GitHub, Salesforce/MuleSoft, and Google Cloud command over 50% of market share), yet **highly fragmented** in specialized developer experience niches (such as API testing, edge platforms, and collaborative API design) where product-led, developer-first startups compete vigorously.



## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Paid Tier Pricing | Free Tier / Free Trial Limits | API Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Tooling API](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/)** | ~$280B Market Cap (~$38B ARR) | $25/user/month (Starter Suite) | 30-day full-feature trial (includes REST/Tooling API access) or free Developer Edition org (lifetime sandbox with 5MB data / 20MB file storage, max 15,000 API calls/24 hrs) | REST API for managing metadata about Apex classes, triggers, Visualforce pages, and development artifacts. Endpoints for querying/mutating tooling objects (`ApexClass`, `ApexTrigger`, `ApexLog`, `MetadataContainer`). Base URL: `https://{instance}.salesforce.com/services/data/v59.0/tooling`. |
| **[GitHub REST API](https://docs.github.com/rest)** | ~$100B+ Implied Value (Part of Microsoft $3T+ Cap; ~$2B+ ARR) | $4/user/month (Team plan) | $0 Free forever plan: unlimited public/private repositories, 2,000 GitHub Actions CI/CD minutes/month, 500MB Packages storage, and 5,000 API requests/hour authenticated (60 requests/hour unauthenticated). | Comprehensive REST API (version 2026-03-10) for managing repositories, issues, pull requests, actions, packages, and organization governance with OpenAPI descriptions and granular PAT permissions. |
| **[Bitbucket Cloud API](https://developer.atlassian.com/cloud/bitbucket/)** | ~$50B Market Cap (Atlassian; ~$4.4B ARR) | $3/user/month (Standard plan) | $0 Free forever plan: up to 5 user seats, 50 CI/CD build minutes/month, 1GB Git LFS storage, and unlimited private repositories with REST API access (1,000 requests/hr rate limit). | 2.0 REST API supporting Bitbucket Query Language (BBQL) for query filtering, partial field responses, and API proxy authentication. Built on OpenAPI Specification 2.0. |
| **[Vercel API](https://vercel.com/docs/rest-api)** | $9.3B Valuation (~$200M+ ARR) | $20/month per seat (Pro plan) | $0 Free Hobby plan (personal/non-commercial): 100GB fast data transfer/month, 1M Edge Requests/month, 1M Serverless Function invocations/month, 4 CPU-hours compute, and 1GB Blob storage. Hard-paused upon limit exhaustion. | REST API for managing deployments, project environments, custom domains, Edge/Serverless functions, Secure Compute networks, PrivateLink endpoints, and third-party integrations. |
| **[GitLab API](https://docs.gitlab.com/api/)** | ~$9B Market Cap (~$700M+ ARR) | $29/user/month (Premium plan) | $0 Free forever plan: up to 5 users/namespace, 400 CI/CD compute minutes/month, 5GB storage, 10GB transfer/month, and API rate limit of 2,000 requests/minute authenticated. | REST API (v4) managing projects, CI/CD pipelines, merge requests, container registries, and enterprise issue tracking. Supports offset/keyset pagination and token authentication. |
| **[Postman API](https://learning.postman.com/docs/)** | $5.6B Peak Valuation (~$313M ARR) | $9/user/month billed annually ($12 monthly - Solo plan) | $0 Free forever plan: 1 user seat, 50 Postman AI credits/month, unlimited collection runs, mock servers, and 1,000 Postman API requests/month. | REST API for programmatically managing workspace collections, environments, monitors, mock servers, and API definitions to integrate into automated CI/CD pipelines. |
| **[Travis CI API](https://docs.travis-ci.com/api/)** | ~$3B Valuation (Idera; ~$500M+ ARR) | $69/month (Core 1-concurrent job plan) | 14-day free trial with 10,000 trial build credits (~1,000 Linux build minutes) valid for trial duration; free credits pool renewable upon request for qualified open-source repositories. | API V3 for managing repositories, triggering builds, inspecting jobs, controlling environment variables, setting cron schedules, and validating `.travis.yml` files. |
| **[Docker Hub API](https://docs.docker.com/reference/api/hub/)** | $2.1B Valuation (~$207M ARR) | $9/user/month billed annually ($11 monthly - Pro plan) | $0 Docker Personal forever plan (organizations <250 employees and <$10M revenue): 200 image pulls per 6 hours (authenticated), unlimited public repositories, and 1 private repository. | API v2 for programmatic management of container repositories, webhooks, tags, teams, and access tokens, coupled with Registry HTTP v2 API and Docker Scout CVE analysis endpoints. |
| **[CircleCI API](https://circleci.com/docs/api/)** | $1.7B Valuation (~$55M+ ARR) | $15/month (Performance plan, includes 30k credits + 5 seats) | $0 Free forever plan: 30,000 credits/month (~3,000 Linux medium build minutes), up to 5 user seats, and unlimited VCS integrations. | REST API for triggering pipelines, inspecting workflows/jobs, managing contexts and environment variables, and querying performance and test insights. |
| **[Netlify API](https://docs.netlify.com/api-and-cli-guides/api-guides/get-started-with-api/)** | $2.0B Valuation (~$45M ARR) | $9/month (Personal plan, includes 1,000 credits) | $0 Free forever plan: 300 credits/month (e.g., 20 credits/GB outbound transfer, 15 credits/production deploy, 2 credits/10k web requests), 1-day analytics retention, hard cap when monthly pool is consumed. | REST API for site deployments (including raw ZIP upload), DNS/domain automation, serverless and edge functions management, and form submissions. |



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
