# Tipalti (tipalti)

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

Tipalti is a global accounts payable and mass payments automation platform that enables businesses to onboard suppliers, process payments across 196 countries in 120 currencies, automate invoice management, and maintain tax compliance. The platform provides both a modern REST API and a legacy SOAP API for programmatic integration with payee management, payment processing, procurement workflows, and financial reporting.

APIs.json: https://raw.githubusercontent.com/api-evangelist/tipalti/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tipalti-api-evangelist&utm_content=repo

## Tags

- Accounts Payable
- Mass Payments
- Global Payments
- Payee Onboarding
- Invoice Management
- Tax Compliance
- Procurement
- Financial Automation
- Fintech
- B2B Payments

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Tipalti REST API | Modern REST API for payee onboarding, payment processing, invoice management, and procurement workflows using OAuth 2.0 and JSON | https://developer.tipalti.com/ |
| Tipalti SOAP API | Legacy SOAP-based API (v14) for Payer and Payee functions including payee registration and payment processing | https://soap-support.tipalti.com/Content/Topics/APIs/Intro.htm |
| Tipalti Procurement REST API | REST API for purchase order and purchase requisition management, designed for batch integration workflows | https://help.tipalti.com/hc/en-us/articles/30718248220823-Procurement-REST-API-documentation |

## Plans / Rate Limits / FinOps

| Resource | Path |
|----------|------|
| Plans & Pricing | [plans/tipalti-plans-pricing.yml](plans/tipalti-plans-pricing.yml) |
| Rate Limits | [rate-limits/tipalti-rate-limits.yml](rate-limits/tipalti-rate-limits.yml) |
| FinOps | [finops/tipalti-finops.yml](finops/tipalti-finops.yml) |

**Pricing summary:** Accounts Payable plans start at $99/month; Mass Payments plans start at $249/month. Both include unlimited users with per-transaction fees on top. Premium and Elite tiers are custom-priced.

**Rate limits:** Procurement REST API allows up to 5 update requests per minute and 1 read per 10 minutes. General REST API limits are enforced per account; HTTP 429 is returned when limits are exceeded.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://tipalti.com/ |
| Documentation | https://developer.tipalti.com/ |
| GitHub Organization | https://github.com/tipalti |
| LinkedIn | https://www.linkedin.com/company/tipalti |
| X | https://x.com/tipalti |
| Blog | https://tipalti.com/blog/ |
| Pricing | https://tipalti.com/pricing/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
