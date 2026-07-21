# Pico (pico-trading)

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
