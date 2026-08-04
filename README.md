# Pico (pico-trading)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Pico (pico.net) is a trading-infrastructure and financial market data company - not the creator-CRM company of the same name - providing global exchange connectivity, colocation and managed infrastructure in 55+ data centers, Redline trading software (InRush ticker plant feed handlers and Execution Gateway, acquired 2021), RedlineFeed normalized market data from 230+ venues, and Corvil network and trading analytics (acquired 2019). Market data is delivered to entitled customers via multicast feeds and an embedded InRush software API rather than public HTTP endpoints, and Corvil exposes analytics via a REST API, SDK, and streaming to Kafka, Splunk, and Elastic. Privately held; everything is sales-gated - there is no public developer portal, no self-serve signup, and no public API reference, with product documentation and the Corvil API docs behind the login-gated customer portal at portal.pico.net.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pico-trading/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pico-trading/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Trading
- Real-Time
- Low Latency
- Feed Handlers
- Order Execution
- Network Analytics
- Exchange Connectivity

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

No public, documented API products are cataloged. Pico's API surface is real but customer-only: the Redline "single API for market data and order execution" is a software library (InRush ticker plant receivers deployed on customer servers, plus Bloomberg and Reuters API bridges), RedlineFeed is delivered as normalized multicast from a managed publishing hub, and the Corvil API/SDK (REST plus streaming connectors to Kafka, Splunk, and Elastic) is documented only behind the customer portal. There is no self-serve signup, public API reference, or downloadable OpenAPI/AsyncAPI specification.

## Common Properties

- [Website](https://www.pico.net/)
- [Portal](https://portal.pico.net/) (login-gated customer portal; support.corvil.com redirects here)
- [Blog](https://www.pico.net/blog/)
- [GitHub Organization](https://github.com/corvil) (org named "Pico"; only website tooling public — legacy org [picotrading](https://github.com/picotrading) holds infrastructure Ansible roles)
- [LinkedIn](https://www.linkedin.com/company/picotrading/)
- [Support / Contact](https://www.pico.net/company/contact/)
- [Terms of Service](https://www.pico.net/terms-and-conditions)
- [Privacy Policy](https://www.pico.net/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
