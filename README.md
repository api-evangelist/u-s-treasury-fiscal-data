# U.S. Treasury Fiscal Data (u-s-treasury-fiscal-data)

The U.S. Treasury Bureau of the Fiscal Service manages the government's finances including collecting revenue, paying federal bills, managing federal debt, and producing the nation's financial accounts. Their Fiscal Data API provides free, open access to federal financial data through a standardized RESTful API covering 80+ datasets. Key datasets include the Debt to the Penny (daily public debt outstanding), Treasury Reporting Rates of Exchange (quarterly foreign currency rates), Average Interest Rates on U.S. Treasury Securities, Daily Treasury Statements, Monthly Treasury Statements, and U.S. savings bond data. No authentication required.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/u-s-treasury-fiscal-data/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Federal Government, Finance, Treasury, National Debt, Exchange Rates, Economics

## Timestamps

- **Created:** 2024-12-25
- **Modified:** 2026-05-03

## APIs

### Treasury Fiscal Data API

The U.S. Treasury Fiscal Data API provides free, open access to federal financial data published by the Bureau of the Fiscal Service. Covers 80+ datasets including the Debt to the Penny dataset, Treasury Reporting Rates of Exchange, average interest rates on Treasury securities, Daily Treasury Statements, Monthly Treasury Statements, U.S. savings bond redemption tables, and public debt outstanding by security type. No authentication required. Supports filtering, sorting, field selection, and pagination.

**Human URL:** [https://fiscaldata.treasury.gov/](https://fiscaldata.treasury.gov/)

#### Tags:

 - National Debt, Exchange Rates, Treasury Statements, Securities, Federal Finance

#### Properties

- [Documentation](https://fiscaldata.treasury.gov/api-documentation/)
- [GettingStarted](https://fiscaldata.treasury.gov/api-documentation/)
- [OpenAPI](openapi/treasury-fiscal-data-api-openapi.yaml)
- [Debt Record Schema](json-schema/treasury-debt-record-schema.json)
- [Exchange Rate Record Schema](json-schema/treasury-exchange-rate-record-schema.json)
- [Interest Rate Record Schema](json-schema/treasury-interest-rate-record-schema.json)
- [Daily Treasury Statement Record Schema](json-schema/treasury-daily-treasury-record-schema.json)
- [Monthly Treasury Statement Record Schema](json-schema/treasury-monthly-treasury-record-schema.json)
- [JSON-LD](json-ld/treasury-fiscal-data-api-context.jsonld)
- [Debt Record Example](examples/treasury-debt-record-example.json)
- [Exchange Rate Record Example](examples/treasury-exchange-rate-record-example.json)

## Common Properties

- [Website](https://fiscaldata.treasury.gov/)
- [Documentation](https://fiscaldata.treasury.gov/api-documentation/)
- [SpectralRules](rules/treasury-fiscal-data-api-rules.yml)
- [Vocabulary](vocabulary/u-s-treasury-fiscal-data-vocabulary.yaml)
- [Fiscal Data Intelligence Capability](capabilities/fiscal-data-intelligence.yaml)

## Features

| Name | Description |
|------|-------------|
| No Authentication Required | All Treasury Fiscal Data API endpoints are publicly accessible without API keys or registration, enabling immediate programmatic access. |
| Flexible Field Selection | Use the fields parameter to request only the specific data fields needed, reducing response payload size and improving performance. |
| Advanced Filtering | Filter datasets using field:operator:value syntax supporting equality, range, and set membership operators across any field in the dataset. |
| Pagination Support | All endpoints support page[number] and page[size] pagination with metadata indicating total record count and total pages available. |
| Multiple Output Formats | API responses available in JSON, XML, and CSV formats suitable for programmatic consumption, data warehousing, and spreadsheet analysis. |
| Comprehensive Coverage | 80+ datasets covering all major Bureau of the Fiscal Service financial reports from the Debt to the Penny to Monthly Treasury Statements. |

## Use Cases

| Name | Description |
|------|-------------|
| National Debt Tracking | Journalists, economists, and citizens monitor daily changes in U.S. public debt outstanding including amounts held by the public and intragovernmental holdings. |
| Exchange Rate Research | Federal agencies, researchers, and businesses use Treasury exchange rates for reporting foreign currency transactions in accordance with federal accounting standards. |
| Budget Analysis | Policy analysts and budget offices track federal government receipts and outlays from Monthly Treasury Statements to assess deficit trends. |
| Interest Rate Monitoring | Economists and investors track average interest rates on Treasury securities to analyze government borrowing costs and monetary policy. |
| Treasury Cash Management | Financial researchers analyze Daily Treasury Statement data to understand federal government cash flows and liquidity management. |

## Integrations

| Name | Description |
|------|-------------|
| FRED Economic Database | Federal Reserve Economic Database (FRED) integrates Treasury Fiscal Data series for economic research and modeling applications. |
| USASpending.gov | Federal spending transparency portal uses Bureau of the Fiscal Service data alongside Treasury Fiscal Data for comprehensive spending analysis. |
| Federal Accounting Standards | Treasury exchange rates and fiscal data support OMB/FASAB-compliant financial reporting across federal agencies and programs. |
| fiscaldata.treasury.gov | The official Treasury Fiscal Data portal provides data visualization, dataset explorer, and download tools built on the same API. |

## Artifacts

### OpenAPI

- [treasury-fiscal-data-api-openapi.yaml](openapi/treasury-fiscal-data-api-openapi.yaml)

### JSON Schema

- [treasury-fiscal-meta-schema.json](json-schema/treasury-fiscal-meta-schema.json)
- [treasury-fiscal-links-schema.json](json-schema/treasury-fiscal-links-schema.json)
- [treasury-debt-record-schema.json](json-schema/treasury-debt-record-schema.json)
- [treasury-debt-to-penny-response-schema.json](json-schema/treasury-debt-to-penny-response-schema.json)
- [treasury-exchange-rate-record-schema.json](json-schema/treasury-exchange-rate-record-schema.json)
- [treasury-exchange-rate-response-schema.json](json-schema/treasury-exchange-rate-response-schema.json)
- [treasury-interest-rate-record-schema.json](json-schema/treasury-interest-rate-record-schema.json)
- [treasury-interest-rate-response-schema.json](json-schema/treasury-interest-rate-response-schema.json)
- [treasury-daily-treasury-record-schema.json](json-schema/treasury-daily-treasury-record-schema.json)
- [treasury-daily-treasury-statement-response-schema.json](json-schema/treasury-daily-treasury-statement-response-schema.json)
- [treasury-monthly-treasury-record-schema.json](json-schema/treasury-monthly-treasury-record-schema.json)
- [treasury-monthly-treasury-statement-response-schema.json](json-schema/treasury-monthly-treasury-statement-response-schema.json)
- [treasury-generic-fiscal-response-schema.json](json-schema/treasury-generic-fiscal-response-schema.json)
- [treasury-error-response-schema.json](json-schema/treasury-error-response-schema.json)

### JSON Structure

- [treasury-fiscal-meta-structure.json](json-structure/treasury-fiscal-meta-structure.json)
- [treasury-fiscal-links-structure.json](json-structure/treasury-fiscal-links-structure.json)
- [treasury-debt-record-structure.json](json-structure/treasury-debt-record-structure.json)
- [treasury-debt-to-penny-response-structure.json](json-structure/treasury-debt-to-penny-response-structure.json)
- [treasury-exchange-rate-record-structure.json](json-structure/treasury-exchange-rate-record-structure.json)
- [treasury-exchange-rate-response-structure.json](json-structure/treasury-exchange-rate-response-structure.json)
- [treasury-interest-rate-record-structure.json](json-structure/treasury-interest-rate-record-structure.json)
- [treasury-interest-rate-response-structure.json](json-structure/treasury-interest-rate-response-structure.json)
- [treasury-daily-treasury-record-structure.json](json-structure/treasury-daily-treasury-record-structure.json)
- [treasury-daily-treasury-statement-response-structure.json](json-structure/treasury-daily-treasury-statement-response-structure.json)
- [treasury-monthly-treasury-record-structure.json](json-structure/treasury-monthly-treasury-record-structure.json)
- [treasury-monthly-treasury-statement-response-structure.json](json-structure/treasury-monthly-treasury-statement-response-structure.json)
- [treasury-generic-fiscal-response-structure.json](json-structure/treasury-generic-fiscal-response-structure.json)
- [treasury-error-response-structure.json](json-structure/treasury-error-response-structure.json)

### JSON-LD

- [treasury-fiscal-data-api-context.jsonld](json-ld/treasury-fiscal-data-api-context.jsonld)

### Examples

- [treasury-fiscal-meta-example.json](examples/treasury-fiscal-meta-example.json)
- [treasury-fiscal-links-example.json](examples/treasury-fiscal-links-example.json)
- [treasury-debt-record-example.json](examples/treasury-debt-record-example.json)
- [treasury-debt-to-penny-response-example.json](examples/treasury-debt-to-penny-response-example.json)
- [treasury-exchange-rate-record-example.json](examples/treasury-exchange-rate-record-example.json)
- [treasury-exchange-rate-response-example.json](examples/treasury-exchange-rate-response-example.json)
- [treasury-interest-rate-record-example.json](examples/treasury-interest-rate-record-example.json)
- [treasury-interest-rate-response-example.json](examples/treasury-interest-rate-response-example.json)
- [treasury-daily-treasury-record-example.json](examples/treasury-daily-treasury-record-example.json)
- [treasury-daily-treasury-statement-response-example.json](examples/treasury-daily-treasury-statement-response-example.json)
- [treasury-monthly-treasury-record-example.json](examples/treasury-monthly-treasury-record-example.json)
- [treasury-monthly-treasury-statement-response-example.json](examples/treasury-monthly-treasury-statement-response-example.json)
- [treasury-generic-fiscal-response-example.json](examples/treasury-generic-fiscal-response-example.json)
- [treasury-error-response-example.json](examples/treasury-error-response-example.json)

## Capabilities

### Shared Per-API Definitions

- [Treasury Fiscal Data API](capabilities/shared/treasury-fiscal-data-api.yaml) — 5 operations for national debt, exchange rates, interest rates, and Treasury statements

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Fiscal Data Intelligence](capabilities/fiscal-data-intelligence.yaml) | Treasury Fiscal Data API | 5 | Economist, Policy Analyst, Financial Journalist, Budget Analyst |

## Vocabulary

- [U.S. Treasury Fiscal Data Vocabulary](vocabulary/u-s-treasury-fiscal-data-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 5 actions, 1 workflow, and 5 personas across federal fiscal data domains

## Rules

- [Treasury Fiscal Data API Rules](rules/treasury-fiscal-data-api-rules.yml) — 32 rules across 13 categories enforcing Treasury API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
