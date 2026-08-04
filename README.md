# University of Chile (university-of-chile)

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

The University of Chile (Universidad de Chile, UChile) is Chile's oldest public university, founded in 1842 in Santiago, and ranked #139 in the QS World University Rankings 2025. Its public, machine-readable footprint centers on open scholarly infrastructure — a Dataverse research data repository and a DSpace institutional repository — rather than a single branded developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-chile/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-chile-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Data, Repository, OAI-PMH, Dataverse, Chile

## APIs

- **UChile Research Data Repository (Dataverse API)** — Dataverse 5.13 (confirmed live) exposing the standard Dataverse REST/Search API. Docs: https://guides.dataverse.org/en/latest/api/ — Repository: https://datos.uchile.cl/
- **Repositorio Academico OAI-PMH** — DSpace institutional repository with an OAI-PMH 2.0 harvesting interface (base: `https://repositorio.uchile.cl/oai/request`). Documented in OpenDOAR/ROAR; returned HTTP 503 at review time. Docs: https://repositorio.uchile.cl/page/acerca

## Plans

- plans/university-of-chile-plans-pricing.yml

## Rate Limits

- rate-limits/university-of-chile-rate-limits.yml

## FinOps

- finops/university-of-chile-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://uchile.cl/
- GitHub: https://github.com/eol-uchile
- SourceCode: https://github.com/open-uchile
- LinkedIn: https://www.linkedin.com/school/universidad-de-chile/

## Notes

- No general-purpose, self-service developer portal with API keys was confirmed. Cataloged APIs are open scholarly infrastructure accessed via open standards.
- The Dataverse API was confirmed live (`/api/info/version` returned version 5.13).
- The DSpace OAI-PMH endpoint is documented in OpenDOAR/ROAR but returned an intermittent HTTP 503 during this review; treat as documented-but-unconfirmed.
- The official GitHub orgs (eol-uchile, open-uchile) host Open edX forks for the university's online-education platform, not a public API.
- LinkedIn returned a 999 anti-bot status and was not verified live.

## Maintainers

- Kin Lane — kin@apievangelist.com
