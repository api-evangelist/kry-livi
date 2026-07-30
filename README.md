# KRY | LIVI

KRY International AB is Europe's largest digital-first healthcare provider, founded in Stockholm in 2015 by Johannes Schildt. It delivers primary and specialist care through a mobile and web app — video and chat consultations with doctors, nurses, psychologists and physiotherapists — alongside a network of physical clinics. The company trades as **KRY** in Sweden, Norway and Germany and as **Livi** in the United Kingdom and France, and reports 14M+ patient appointments, 4,000+ healthcare professionals and 60+ clinics. Beyond consumer care it sells digital clinical capacity to public payers (NHS, Swedish regions), employers, insurers and Employee Assistance Programmes.

Backed by: index-ventures

## API posture

**KRY | LIVI publishes no public API.** There is no developer portal, API reference, OpenAPI specification, SDK, CLI, MCP server, webhook catalogue or GitHub organisation. `api.kry.se` and `docs.kry.se` resolve but are not public developer surfaces. Patient authentication in Sweden runs on BankID. Partner and payer integrations are handled under contract rather than through a self-serve API programme. Its vulnerability disclosure policy does name "APIs" as in scope, confirming APIs exist — they are simply not publicly documented.

Accordingly this profile carries identity, security and compliance artifacts only; no spec-derived artifacts are possible, and none have been fabricated.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Regulatory / data-protection conformance | `conformance/kry-livi-conformance.yml` | searched |
| Vulnerability disclosure policy | `security/kry-livi-vulnerability-disclosure.yml` | searched |
| Domain security posture | `security/kry-livi-domain-security.yml` | probed |
| `/.well-known/` probe record (all 404) | `well-known/kry-livi-well-known.yml` | searched |
| llms.txt | `llms/kry-livi-llms.txt` | generated |

## Key links

- Website (SE): https://www.kry.se/en/ — Livi (UK): https://www.livi.co.uk/
- About: https://www.kry.se/en/about/
- Press: https://www.kry.se/press/
- Partner solutions: https://uk-partners.livi.co.uk/
- Vulnerability disclosure: https://www.kry.se/vulnerability-disclosure/ (security@kry.se)
- Data security and AI: https://www.kry.se/en/information-on-data-ai/
