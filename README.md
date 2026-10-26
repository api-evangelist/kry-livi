# KRY | LIVI

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
