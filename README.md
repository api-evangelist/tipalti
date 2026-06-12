# Tipalti (tipalti)

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
