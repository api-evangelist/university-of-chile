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

The University of Chile (Universidad de Chile, UChile) is Chile's oldest public university, founded in 1842 in Santiago, and ranked #139 in the QS World University Rankings 2025. Its public, machine-readable footprint centers on open scholarly infrastructure — a Dataverse research data repository and a DSpace institutional repository — rather than a single branded developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-chile/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-chile-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Public University, Research Data, Research Repository, Open Access, OAI-PMH, Dataverse, DSpace, Persistent Identifiers, Chile, Latin America, Spanish Language

## APIs

Every surface carries an `x-operator` in `apis.yml`: **institution** (UChile runs the endpoint), **tenant** (UChile's account on a vendor platform), **registry** (UChile is registered in it).

- **UChile Research Data Repository API (Dataverse)** — `institution` — Dataverse 5.13 self-hosted at `https://datos.uchile.cl/api`, open for unauthenticated read (confirmed live 2026-09-01). The contract it serves at `/openapi` is the Dataverse product contract and is deliberately NOT carried here.
- **UChile Research Data Repository OAI-PMH** — `institution` — `https://datos.uchile.cl/oai`, advertising Datacite, oai_datacite, dataverse_json, oai_dc, oai_ddi.
- **Repositorio Académico OAI-PMH** — `institution` — `https://repositorio.uchile.cl/oai/request`, CONFIRMED LIVE 2026-09-01 (the June 2026 pass recorded an intermittent 503), advertising twelve metadata prefixes.
- **Repositorio Académico DSpace REST API** — `institution` — `https://repositorio.uchile.cl/rest`, DSpace 6, open for read. Not catalogued before this run.
- **U-Campus Academic Management API** — `institution` — `https://ucampus.uchile.cl/api`, built in-house at FCFM; live but authenticated and undocumented.
- **U-Cursos API** — `tenant` — `https://www.u-cursos.cl/api`, on the Ucampus platform's own domain, not uchile.cl.
- **Catálogo Bibliotecas UChile** — `tenant` — Ex Libris Primo VE, institution code 56UDC_INST.
- **DataCite membership** — `registry` — provider UCHILE, client UCHILE.DATAVERSE, prefix 10.34691 (5,709 DOIs).
- **Crossref membership** — `registry` — member 3330, prefix 10.5354 (2,330 current DOIs).
- **ROR organization record** — `registry` — https://ror.org/047gc3g35.

## Plans

- plans/university-of-chile-plans-pricing.yml

## Rate Limits

- rate-limits/university-of-chile-rate-limits.yml

## FinOps

- finops/university-of-chile-finops.yml

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://uchile.cl/
- GitHub: https://github.com/eol-uchile
- SourceCode: https://github.com/open-uchile
- LinkedIn: https://www.linkedin.com/school/universidad-de-chile/

## Notes

- No general-purpose, self-service developer portal with API keys was confirmed. Cataloged APIs are open scholarly infrastructure accessed via open standards.
- **2026-09-01 attribution correction.** This repo previously carried 24 OpenAPIs titled "UChile Research Data Repository (Dataverse API) …", split by tag from one document, plus 49 collections, 4 JSON Schemas titled "Dataverse Dataset/DataFile/Collection", 2 JSON Structures, 2 Spectral rulesets and an agentic-access profile claiming 419 operations. All of it derives from a single **Dataverse product contract** the June 2026 pass captured from `datos.uchile.cl/openapi` and rebranded with a UChile title — the live document is titled "Deployed Resources" and is identical to every Dataverse 5.13 deployment. 84 files were removed. The endpoint is UChile's; the contract is IQSS's and belongs in Dataverse's own repo.
- The Dataverse API was re-confirmed live 2026-09-01 (`/api/info/version` → 200, version 5.13 build 1244-79d6e57; `/api/search?q=*&type=dataset` → 200, 156 datasets).
- The DSpace OAI-PMH endpoint at `repositorio.uchile.cl/oai/request` is now CONFIRMED LIVE (`?verb=Identify` → 200), correcting the June 2026 "documented-but-unconfirmed" note. Its `adminEmail` is still the DSpace default `dspace-help@myu.edu` — the institution's to fix.
- **No identity federation.** UChile publishes no Shibboleth/SAML IdP in the eduGAIN aggregate (10,615 entities searched, zero uchile matches), and Chile's COFRe federation carries no uchile.cl entity. `idp.uchile.cl` and `pasaporte.uchile.cl` are NXDOMAIN. `api.uchile.cl` resolves to 200.89.77.21 but answers nothing on 80 or 443.
- No `llms.txt` and no `.well-known/security.txt` on any institution host; the Dataverse install states it has no API terms of use.
- The official GitHub orgs (eol-uchile, open-uchile) host Open edX forks for the university's online-education platform, not a public API.
- LinkedIn returned a 999 anti-bot status; per the pipeline a bot challenge grades LIVE, not dead.

## Maintainers

- Kin Lane — kin@apievangelist.com
