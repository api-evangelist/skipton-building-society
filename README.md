# Skipton Building Society (skipton-building-society)

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
