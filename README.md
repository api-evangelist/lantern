# Lantern

Lantern (legal entity Employer Direct Healthcare, LLC dba Lantern Specialty Care) is a US specialty care platform that connects members with high-quality, lower-cost care for surgery, cancer and infusion therapy. Founded in 2011 as SurgeryPlus, it serves employers, public-sector employers, labor union trusts, health plans and benefits consultants through a hand-selected "Network of Excellence" of specialists plus dedicated care teams that navigate members through a treatment journey.

Backed by: insight-partners — https://lanterncare.com/

## API surface

Lantern publishes **no public developer program** as of 2026-07-19: no developer portal, API documentation, OpenAPI/AsyncAPI specification, SDKs, CLI, MCP server, Postman collection, status page, or `/.well-known/` discovery documents. `developers.`, `docs.` and `api.lanterncare.com` do not resolve. Any integration is presumably contracted privately with employer/health-plan customers.

## Artifacts in this repo

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/lantern-domain-security.yml` | probed |
| Trust center | `security/lantern-trust-center.yml` | searched |
| Well-known probe (all 404) | `well-known/lantern-well-known.yml` | searched |
| llms.txt | `llms/lantern-llms.txt` | generated |
