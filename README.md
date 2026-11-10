# Awesome Cloudflare [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/sponsors/brandonhimpfen) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for the Cloudflare ecosystem, Cloudflare Workers, Pages, KV, Durable Objects, D1, Vectorize, Zero Trust, and edge compute primitives.

Cloudflare provides a global edge network platform delivering web performance, serverless compute, distributed storage, Zero Trust security, and developer tooling. By executing V8 isolate-based workloads across hundreds of edge locations worldwide, Cloudflare enables developers to build low-latency serverless APIs, full-stack applications, and secure global infrastructure. This list is intended for cloud software architects, edge computing engineers, full-stack developers, and DevOps leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Edge Compute & Serverless Runtimes](#edge-compute--serverless-runtimes)
- [Distributed Storage & Databases](#distributed-storage--databases)
- [Edge AI & Machine Learning](#edge-ai--machine-learning)
- [Developer Tooling & Framework Integrations](#developer-tooling--framework-integrations)
  - [CLI & Deployment Tooling](#cli--deployment-tooling)
  - [Framework Adapters & Libraries](#framework-adapters--libraries)
- [Related Awesome Lists](#related-awesome-lists)

## Edge Compute & Serverless Runtimes

Core compute platforms, isolate runtimes, and distributed state abstractions executing code at the network edge.

- [Cloudflare Workers](https://github.com/cloudflare/workers-sdk) — Serverless execution environment allowing developers to run V8 JavaScript, TypeScript, and WebAssembly code globally.
- [Cloudflare Pages](https://github.com/cloudflare/pages-action) — Jamstack and full-stack platform for deploying static sites and server-side rendered web applications directly to the edge.
- [workerd](https://github.com/cloudflare/workerd) — Open-source JavaScript/WebAssembly serverless runtime that powers Cloudflare Workers locally and in production.
- [Durable Objects](https://developers.cloudflare.com/durable-objects/) — Strongly consistent in-memory compute primitives providing localized state coordination and real-time multiplayer capabilities.

## Distributed Storage & Databases

Key-value stores, relational databases, object storage, and event streaming built for low-latency access.

- [Cloudflare D1](https://developers.cloudflare.com/d1/) — Serverless relational SQL database built on SQLite distributed across Cloudflare's global edge network.
- [Workers KV](https://developers.cloudflare.com/kv/) — Low-latency, globally distributed key-value storage system engineered for high-read throughput.
- [Cloudflare R2](https://developers.cloudflare.com/r2/) — S3-compatible, zero-egress fee object storage engine for media, assets, and data archives.
- [Hyperdrive](https://developers.cloudflare.com/hyperdrive/) — Database acceleration service making existing regional databases (PostgreSQL) feel local from global edge workers.
- [Cloudflare Queues](https://developers.cloudflare.com/queues/) — Message queuing service enabling asynchronous task processing and batching across Workers pipelines.

## Edge AI & Machine Learning

Hardware-accelerated inference pipelines and vector databases for building AI applications at the edge.

- [Workers AI](https://developers.cloudflare.com/workers-ai/) — Serverless GPU-powered inference platform for running open LLMs, embeddings, and diffusion models on Cloudflare's global network.
- [Vectorize](https://developers.cloudflare.com/vectorize/) — Distributed vector database for storing and querying vector embeddings directly from Workers applications.

## Developer Tooling & Framework Integrations

Command-line utilities, local emulators, framework adapters, and open-source libraries tailored for Cloudflare.

### CLI & Deployment Tooling

- [Wrangler](https://github.com/cloudflare/workers-sdk/tree/main/packages/wrangler) — Official command-line interface for configuring, developing locally, and deploying Cloudflare Workers and Pages projects.
- [Miniflare](https://github.com/cloudflare/workers-sdk/tree/main/packages/miniflare) — Fully-featured local simulator for Cloudflare Workers powered by `workerd` for rapid offline testing.

### Framework Adapters & Libraries

- [Hono](https://github.com/honojs/hono) — Fast, lightweight, standards-based web framework designed specifically for Cloudflare Workers and edge runtimes.
- [@astrojs/cloudflare](https://github.com/withastro/astro) — Official SSR deployment adapter for serving Astro applications from Cloudflare Pages and Workers.
- [toucan-js](https://github.com/robertcepa/toucan-js) — Sentry client SDK designed specifically for error tracking within Cloudflare Workers environments.

## Related Awesome Lists

- [Awesome Astro](https://github.com/brandonhimpfen/awesome-astro) — Island Architecture, SSG/SSR web frameworks, and edge deployment adapters.
- [Awesome React](https://github.com/brandonhimpfen/awesome-react) — Component frameworks, SSR engines, state management tools, and JSX ecosystems.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — Web runtimes, frontend frameworks, and asynchronous event pipelines.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
