# University of Chile (university-of-chile)

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
