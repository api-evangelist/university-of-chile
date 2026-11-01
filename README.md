# University of Chile

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

The University of Chile (Universidad de Chile, UChile) is the country's oldest public university, founded in 1842 in Santiago, and Chile's largest research institution (ROR 047gc3g35, domain uchile.cl). Its programmable footprint is entirely scholarly infrastructure and is real but SMALL: the institution self-hosts a Dataverse research data repository at datos.uchile.cl (Dataverse 5.13, build 1244-79d6e57, administered from repositoriodedatos@uchile.cl) and a DSpace institutional repository at repositorio.uchile.cl, and both answer machine calls today — a Dataverse REST API and OAI-PMH provider on the first, a DSpace 6 REST API and OAI-PMH provider on the second. It also runs U-Campus (ucampus.uchile.cl), the academic-management platform built in-house at the Facultad de Ciencias Físicas y Matemáticas, whose /api/ path answers with structured JSON but is authenticated and undocumented. What UChile does NOT have is engineering of its own behind any of it: every contract on those hosts is the product's, generated by Dataverse or DSpace and identical to every other deployment of that software, so no OpenAPI is carried in this repo. There is no central developer portal, no self-service key issuance, no published API terms of use (the Dataverse install answers apiTermsOfUse with "There are no API Terms of Use"), no llms.txt and no security.txt. The institution is a registrant rather than a publisher: a DataCite member (UCHILE) and repository client (UCHILE.DATAVERSE, prefix 10.34691, 5,709 DOIs) and a Crossref member (id 3330, prefix 10.5354, 2,330 current DOIs). Library discovery runs on Ex Libris Primo VE (catalogo.uchile.cl, institution code 56UDC_INST) as a tenant, not as a UChile contract. No UChile Shibboleth or SAML identity provider is published in the eduGAIN metadata aggregate, and Chile's COFRe federation carries no uchile.cl entity — the one strong institution-operated identity surface most universities have is absent here.

**Areas:** Education · Higher Education · University · Public University · Research Data · Research Repository · Open Access · OAI-PMH · Dataverse · DSpace · Persistent Identifiers · Chile

## University of Chile on APIs.io

Everything profiled for University of Chile is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-chile/](https://apis.io/providers/university-of-chile/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [UChile Research Data Repository API (Dataverse)](https://apis.io/apis/university-of-chile/datos-dataverse-api/) — The University of Chile self-hosts a Dataverse installation at datos.uchile.cl on its own network (200.89.78.15, the same /16 as uchile.cl), administered…
- [UChile Research Data Repository OAI-PMH](https://apis.io/apis/university-of-chile/datos-oai-pmh/) — OAI-PMH 2.0 provider on the University of Chile Dataverse installation. Confirmed live on 2026-09-01: ?verb=Identify returned 200 with repositoryName…
- [Repositorio Académico OAI-PMH](https://apis.io/apis/university-of-chile/repositorio-oai-pmh/) — OAI-PMH 2.0 provider on the University of Chile institutional repository (Repositorio Académico), managed by SISIB and built on DSpace. CONFIRMED LIVE on…
- [Repositorio Académico DSpace REST API](https://apis.io/apis/university-of-chile/repositorio-dspace-rest/) — The DSpace 6 REST API on the University of Chile institutional repository, not catalogued before this run. Confirmed live and open for read on 2026-09-01:…
- [U-Campus Academic Management API](https://apis.io/apis/university-of-chile/ucampus-api/) — U-Campus is the University of Chile's own academic and curricular management platform, built in-house by the Área de Infotecnologías of the Facultad de…
- [U-Cursos API](https://apis.io/apis/university-of-chile/ucursos-api/) — U-Cursos is the course-management platform used across University of Chile faculties, built on the same U-Campus codebase and now productised by Centro…
- [Catálogo Bibliotecas UChile (Ex Libris Primo VE)](https://apis.io/apis/university-of-chile/catalogo-primo/) — Library discovery for the University of Chile runs on Ex Libris (Clarivate) Primo VE at catalogo.uchile.cl, institution code 56UDC_INST. Probed 2026-09-01:…
- [DataCite membership and repository registration](https://apis.io/apis/university-of-chile/datacite-membership/) — The University of Chile is a DataCite member, not a DataCite operator. Evidenced 2026-09-01 from the DataCite REST API: provider UCHILE (memberType…
- [Crossref membership](https://apis.io/apis/university-of-chile/crossref-membership/) — The University of Chile is a Crossref member, id 3330, primary name "Universidad de Chile", DOI prefix 10.5354, with 2,330 current DOIs recorded at probe…
- [ROR organization record](https://apis.io/apis/university-of-chile/ror-record/) — The University of Chile's Research Organization Registry record: https://ror.org/047gc3g35, established 1842, declared domain uchile.cl, last modified…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (4)

The data models the API reads and writes.

- [Moved to /providers/university-of-chile/](https://apis.io/schemas/university-of-chile/university-of-chile-datafile/)
- [Moved to /providers/university-of-chile/](https://apis.io/schemas/university-of-chile/university-of-chile-dataset/)
- [Moved to /providers/university-of-chile/](https://apis.io/schemas/university-of-chile/university-of-chile-dataverse/)
- [Moved to /providers/university-of-chile/](https://apis.io/schemas/university-of-chile/university-of-chile-search-item/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Moved to /providers/university-of-chile/](https://apis.io/json-structure/university-of-chile/university-of-chile-dataset-structure/)
- [Moved to /providers/university-of-chile/](https://apis.io/json-structure/university-of-chile/university-of-chile-dataverse-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Chile Context](https://apis.io/jsonld/university-of-chile/university-of-chile-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Chile Research Data and Repository Vocabulary](https://apis.io/vocabularies/university-of-chile/university-of-chile-vocabulary/)

#### Examples (2)

Example requests and responses.

- [University Of Chile Info Version Example](https://apis.io/examples/university-of-chile/university-of-chile-info-version-example/)
- [University Of Chile Search Example](https://apis.io/examples/university-of-chile/university-of-chile-search-example/)

#### Collections (24)

Postman and Open Collection request collections.

- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-access-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-admin-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-batch-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-builtin-users-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-datasets-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-datatags-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-dataverses-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-edit-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-files-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-harvest-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-inbox-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-info-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-ingest-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-licenses-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-mail-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-meta-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-metadatablocks-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-mydata-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-notifications-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-pids-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-roles-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-search-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-users-api/)
- [Moved to /providers/university-of-chile/](https://apis.io/collections/university-of-chile/open-university-of-chile-workflows-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Moved to /providers/university-of-chile/](https://apis.io/rules/university-of-chile/university-of-chile-jsonschema-spectral-rules/)
- [Moved to /providers/university-of-chile/](https://apis.io/rules/university-of-chile/university-of-chile-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Chile Domain Security](https://apis.io/security/university-of-chile/university-of-chile-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Chile Plans Pricing](https://apis.io/plans/university-of-chile/university-of-chile-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Chile Rate Limits](https://apis.io/rate-limits/university-of-chile/university-of-chile-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Chile Finops](https://apis.io/finops/university-of-chile/university-of-chile-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://uchile.cl/)
- [Documentation](https://guides.dataverse.org/en/latest/api/)
- [GitHub](https://github.com/eol-uchile)

## API Evangelist rating

**Kin Score 16.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 14.3 |
| Contract governance | 18.2 |
| Operational transparency | 7.9 |
| Developer ergonomics | 9.5 |
| Access clarity | 5.3 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 18.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-chile/](https://apis.io/providers/university-of-chile/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Chile: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-chile/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
