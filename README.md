# Skipton Building Society (skipton-building-society)

Skipton Building Society is a UK mutual building society founded in 1853 and headquartered in Skipton, North Yorkshire. It is the fourth-largest building society in the United Kingdom, owned by and run for its members, and is the parent of the wider Skipton Group. Skipton is authorised by the Prudential Regulation Authority (PRA) and regulated by the Financial Conduct Authority (FCA) and PRA. Its core business is retail savings and residential mortgages; it does not offer personal current accounts. In UK Open Banking (PSD2 / OBIE) Skipton has historically been a *consumer* of Open Banking data (e.g. Experian-powered mortgage affordability checks) rather than an account-servicing payment service provider (ASPSP) publishing a public developer platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/skipton-building-society/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/skipton-building-society/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Building Society
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Mortgages
- Savings
- Account Information
- Payments

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## Open Banking Posture

Skipton exposes **no public developer portal** (no `developer.skipton.co.uk`), and is **not listed** among the CMA9 or the wider set of UK banks and building societies that publish live Open Banking Open Data or Read/Write APIs. `api.skipton.co.uk` exists but returns a generic Apache `403 Forbidden` on all probed paths (it is not a documented API gateway). The API entries below therefore represent the **shared OBIE standard** the society would conform to if it published these surfaces — they are explicitly **unverified** for Skipton and are not a Skipton API contract.

## APIs

### Skipton Open Banking Open Data API (OBIE Standard)

The UK Open Banking Open Data standard — public, unauthenticated reference data (branches, ATMs, personal and business current accounts, unsecured SME loans, commercial credit cards). A live Skipton Open Data host was not confirmed.

- **Human URL:** [https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

#### Tags

- Open Data
- Branches
- ATMs

#### Properties

- [OpenAPI](openapi/obie-opendata-openapi.json) — harvested verbatim from the OBIE `opendata-api-spec-compiled` repository (shared standard, Swagger 2.0, v1.3)
- [Documentation](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)
- [API Reference](https://github.com/OpenBankingUK/opendata-api-spec-compiled)

### Skipton Account & Transaction Information API (OBIE Read/Write Standard)

Account and Transaction Information Services (AIS) per the OBIE Read/Write API Standard — FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 strong customer authentication). Skipton ASPSP publication is unverified.

- **Human URL:** [https://openbankinguk.github.io/read-write-api-site3/](https://openbankinguk.github.io/read-write-api-site3/)

#### Tags

- Account Information
- AISP

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### Skipton Payment Initiation API (OBIE Read/Write Standard)

Payment Initiation Services (PIS) per the OBIE Read/Write API Standard — FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA). Skipton ASPSP publication is unverified.

- **Human URL:** [https://openbankinguk.github.io/read-write-api-site3/](https://openbankinguk.github.io/read-write-api-site3/)

#### Tags

- Payment Initiation
- PISP

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### Skipton Confirmation of Funds API (OBIE Read/Write Standard)

Confirmation of Funds Services (CBPII) per the OBIE Read/Write API Standard — FAPI-secured (OAuth2/OIDC, mutual-TLS, PSD2 SCA). Skipton ASPSP publication is unverified.

- **Human URL:** [https://openbankinguk.github.io/read-write-api-site3/](https://openbankinguk.github.io/read-write-api-site3/)

#### Tags

- Confirmation of Funds
- CBPII

#### Properties

- [Documentation](https://openbankinguk.github.io/read-write-api-site3/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

## Common Properties

- [Website](https://www.skipton.co.uk/)
- [About](https://www.skipton.co.uk/about-us)
- [Branch Locator](https://www.skipton.co.uk/help-and-support/branch-finder)
- [Support](https://www.skipton.co.uk/help-and-support/contact-us)
- [Security](https://www.skipton.co.uk/help-and-support/fraud-and-security)
- [Blog / Press Office](https://www.skipton.co.uk/press-office)
- [Terms of Service](https://www.skipton.co.uk/legal-notice)
- [Privacy Policy](https://www.skipton.co.uk/privacy-policy)
- [LinkedIn](https://www.linkedin.com/company/skipton-building-society)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
