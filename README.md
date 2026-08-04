# BMLL Technologies (bmll-technologies)

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

BMLL is a London-based provider of harmonised historical Level 3, 2, and 1 order book data and analytics for capital markets, covering global equities, ETFs, futures, and options. Acquired by Nordic Capital in October 2025 (with Optiver as minority shareholder), BMLL sells its data through the BMLL Data Lab hosted Python environment, the BMLL Data Feed file product, and entitlement-gated REST APIs (Reference Data, Time-Series, Market Data, and an async query APIv2) documented publicly via the bmll Python SDK on PyPI, with delivery over API, S3, SFTP, and Snowflake. There is no self-serve signup - access is sales-led with key-pair credentials issued per account.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bmll-technologies/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bmll-technologies/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Order Book
- Stocks
- Trading
- Reference Data
- Historical Data
- Analytics
- ETF
- Futures
- Options

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### BMLL Reference Data API

Query reference data for the instruments, listings, and markets in the BMLL universe (equities, ETFs, futures, options), including availability by data type (LOB, listing/instrument/market-level metrics, DataFeed) and ETF constituent data. Documented publicly through the bmll Python SDK (ReferenceDataClient); the host is live but requires entitled key-pair credentials (probed 403 without auth).

- **Human URL:** [https://pypi.org/project/bmll/](https://pypi.org/project/bmll/)
- **Base URL:** `https://reference.data.bmlltech.com`

#### Tags

- Reference Data
- Instruments
- Markets
- Listings

#### Properties

- [Documentation](https://pypi.org/project/bmll/)
- [Portal](https://data.bmlltech.com)

### BMLL Time-Series API

Daily time-series metrics and analytics derived from BMLL's harmonised Level 3 order book history, including classified trades, queried by instrument, listing, or market. Documented publicly through the bmll Python SDK (TimeSeriesClient); the host is live but requires entitled key-pair credentials (probed 403 without auth).

- **Human URL:** [https://pypi.org/project/bmll/](https://pypi.org/project/bmll/)
- **Base URL:** `https://time-series.data.bmlltech.com`

#### Tags

- Time Series
- Analytics
- Order Book
- Metrics

#### Properties

- [Documentation](https://pypi.org/project/bmll/)
- [Portal](https://data.bmlltech.com)

### BMLL Market Data API

Retrieve per-instrument market state and consolidated best bid and offer (CBBO) for listings on a given day, with an async poll-for-result request pattern. Documented publicly through the bmll Python SDK (MarketDataClient); the host is live but requires entitled key-pair credentials (probed 403 without auth).

- **Human URL:** [https://pypi.org/project/bmll/](https://pypi.org/project/bmll/)
- **Base URL:** `https://market-data.data.bmlltech.com`

#### Tags

- Market Data
- Market State
- CBBO
- Quotes

#### Properties

- [Documentation](https://pypi.org/project/bmll/)
- [Portal](https://data.bmlltech.com)

### BMLL APIv2 Query API

Asynchronous dataset query API (initiate query, poll, download results as JSONL/Arrow into pandas or polars) over BMLL datasets, including a timeseries query endpoint. An OpenAPI definition exists at https://api.data.bmlltech.com/openapi.json but it returned HTTP 401 Unauthorized when probed, so it could not be harvested. Documented publicly through the bmll Python SDK (ApiV2Client).

- **Human URL:** [https://pypi.org/project/bmll/](https://pypi.org/project/bmll/)
- **Base URL:** `https://api.data.bmlltech.com`

#### Tags

- Datasets
- Query
- Async
- Historical Data

#### Properties

- [Documentation](https://pypi.org/project/bmll/)
- [Portal](https://data.bmlltech.com)

## Common Properties

- [Website](https://bmlltech.com/)
- [Portal](https://data.bmlltech.com)
- [Documentation](https://www.bmlltech.com/products/bmll-data-feed/documentation)
- [GitHub Organization](https://github.com/bmlltech)
- [LinkedIn](https://www.linkedin.com/company/bmll)
- [Blog](https://www.bmlltech.com/knowledge-hub)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
