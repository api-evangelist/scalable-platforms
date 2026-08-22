# Scalable Platforms (scalable-platforms)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A subject-matter collection covering APIs, tools, and platforms for building and deploying scalable platform infrastructure. This topic encompasses Platform-as-a-Service (PaaS) providers, developer experience platforms, deployment automation, serverless computing, container platforms, and the tools that abstract infrastructure management so teams can focus on application delivery. Covers Railway, Render, Fly.io, Heroku, Vercel, Netlify, and Cloudflare Workers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scalable-platforms/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scalable-platforms/refs/heads/main/apis.yml)

## Tags

- Cloud Infrastructure
- Deployment
- Developer Experience
- DevOps
- PaaS
- Platform
- Scalability
- Serverless

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-02

## APIs

### Vercel REST API

Vercel is the frontend cloud platform for deploying Next.js, React, and other JavaScript frameworks with zero configuration. The Vercel REST API manages deployments, projects, domains, environment variables, edge functions, and team access. Provides global edge network with automatic scaling.

#### Tags

- CDN
- Deployment
- Edge Computing
- Frontend
- Next.js
- Serverless
- Vercel

#### Properties

- [Documentation](https://vercel.com/docs/rest-api)
- [OpenAPI](https://openapi.vercel.sh/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://vercel.com/docs)
- [Pricing](https://vercel.com/pricing)
- [SDK](https://github.com/vercel/sdk)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Netlify API

Netlify is a web platform for building, deploying, and serving modern web projects. The Netlify API manages sites, deploys, environment variables, build hooks, functions, forms, identity, and DNS records. Features atomic deploys and instant rollbacks.

#### Tags

- CDN
- CI/CD
- Deployment
- Frontend
- JAMstack
- Netlify
- Serverless

#### Properties

- [Documentation](https://docs.netlify.com/api/get-started/)
- [OpenAPI](https://open-api.netlify.com/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://docs.netlify.com/)
- [Pricing](https://www.netlify.com/pricing/)
- [SDK](https://github.com/netlify/js-client)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudflare API

Cloudflare's platform API manages DNS, CDN, Firewall rules, Workers (serverless edge functions), Pages (JAMstack deployments), R2 (object storage), D1 (serverless SQLite), KV, and Durable Objects. Powers globally distributed scalable applications at the edge.

#### Tags

- CDN
- Cloudflare
- DNS
- Edge Computing
- Security
- Serverless
- Workers

#### Properties

- [Documentation](https://developers.cloudflare.com/api/)
- [OpenAPI](https://raw.githubusercontent.com/cloudflare/api-schemas/main/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developers.cloudflare.com/)
- [Pricing](https://www.cloudflare.com/plans/)
- [SDK](https://github.com/cloudflare/cloudflare-typescript)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Heroku Platform API

Heroku pioneered the "git push" deployment model and remains a leading PaaS for rapid application deployment. The Heroku Platform API manages apps, dynos, config vars, add-ons, pipelines, review apps, spaces (private networking), and team access. Owned by Salesforce.

#### Tags

- Deployment
- Dynos
- Heroku
- PaaS
- Pipelines
- Salesforce

#### Properties

- [Documentation](https://devcenter.heroku.com/articles/platform-api-reference)
- [OpenAPI](https://devcenter.heroku.com/api-docs) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://devcenter.heroku.com/start)
- [Pricing](https://www.heroku.com/pricing)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fly.io Machines API

Fly.io deploys Docker containers globally on its own hardware, with low-latency routing to the nearest region. The Machines API manages apps, machines (VMs), volumes, networks, secrets, and certificates. In 2026, Fly.io supports managed Postgres, GPU instances, Kubernetes, object storage, and scale-to-zero.

#### Tags

- Containers
- Deployment
- Edge Computing
- Fly.io
- Global Deployment
- Scale To Zero

#### Properties

- [Documentation](https://fly.io/docs/machines/api/)
- [OpenAPI](https://raw.githubusercontent.com/superfly/fly-openapi/refs/heads/main/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://fly.io/docs/getting-started/)
- [Pricing](https://fly.io/docs/about/pricing/)
- [SDK](https://github.com/superfly/fly-go)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Railway API

Railway is a modern deployment platform with usage-based pricing and arguably the best developer experience of any deployment platform. Launched in 2020, by 2026 it has matured with support for persistent volumes, private networking, cron jobs, TCP proxy, and one-click database deployments. The API manages projects, services, deployments, environments, and variables.

#### Tags

- Containers
- Deployment
- Developer Experience
- PaaS
- Railway
- Usage-Based Pricing

#### Properties

- [Documentation](https://docs.railway.app/reference/public-api)
- [Getting Started](https://docs.railway.app/)
- [Pricing](https://railway.app/pricing)
- [SDK](https://github.com/railwayapp/cli)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Render API

Render positioned itself as the modern Heroku with a free tier, managed databases, background workers, cron jobs, and static sites. The Render API manages services, deploys, environment groups, and custom domains. By 2026, Render supports auto-scaling, private networking, and managed Redis.

#### Tags

- Containers
- Deployment
- Managed Databases
- PaaS
- Render
- Serverless

#### Properties

- [Documentation](https://api-docs.render.com/reference/)
- [OpenAPI](https://raw.githubusercontent.com/renderinc/openapi-specs/main/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://render.com/docs/)
- [Pricing](https://render.com/pricing)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Northflank API

Northflank is a DevOps platform providing container deployment, managed databases, job scheduling, preview environments, and full Kubernetes-based infrastructure. The Northflank API manages projects, services, databases, secrets, and pipelines. Supports BYOC (Bring Your Own Cloud) for running on AWS, GCP, or Azure.

#### Tags

- BYOC
- CI/CD
- Containers
- Deployment
- Kubernetes
- Managed Databases
- Northflank
- PaaS

#### Properties

- [Documentation](https://northflank.com/docs/v1/api/overview)
- [OpenAPI](https://api.northflank.com/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://northflank.com/docs/)
- [Pricing](https://northflank.com/pricing)
- [Postman Collection](collections/scalable-platforms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-platforms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer  Experience  Comparison](https://thesoftwarescout.com/heroku-vs-railway-vs-render-vs-fly-io-2026-which-platform-should-you-deploy-on/)
- [Paa S  Alternatives](https://northflank.com/blog/best-cloud-hosting-platforms)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/scalable-platforms/main/json-schema/scalable-platforms-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/scalable-platforms/main/json-schema/scalable-platforms-serverless-function-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/scalable-platforms/main/json-ld/scalable-platforms-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/scalable-platforms/main/vocabulary/scalable-platforms-vocabulary.yml)

## Maintainers

**FN:** API Evangelist
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
