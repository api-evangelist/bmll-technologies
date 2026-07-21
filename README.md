# BMLL Technologies (bmll-technologies)

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
