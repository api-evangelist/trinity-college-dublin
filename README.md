# Trinity College Dublin

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

Trinity College Dublin, the University of Dublin, founded in 1592, is Ireland's oldest university and a legal deposit library for Ireland and the United Kingdom since 1801. Trinity operates no public developer portal, publishes no OpenAPI, issues no API keys and runs no documented open-API programme — and this profile says so rather than padding the gap. What Trinity does operate, and what is recorded here, is standards-based scholarly and identity infrastructure: a self-hosted Shibboleth Identity Provider on its own domain (idp.tcd.ie, scope tcd.ie) registered in HEAnet's Edugate federation and exported to eduGAIN; a Microsoft Entra ID tenant with live OIDC discovery; an OpenSearch 1.1 description document authored by Trinity's own Digital and Web team; DataCite consortium membership with five prefixes and 16,031 DOIs across five registered repositories; and Crossref membership. Its two flagship repositories — TARA (DSpace) and Digital Collections (Hyrax/Samvera, home of the Book of Kells) — sit on Trinity's own hosts but are fronted by Cloudflare and F5 bot-mitigation that returns a challenge to every unattended client, so they are live but not machine-callable. eDeposit Ireland, the national legal-deposit repository Trinity Library administers, is the one repository that answers a harvester, and it does so as a tenant on Atmire's Open Repository platform rather than as Trinity's own engineering.

**Areas:** University · Higher Education · Education · Ireland · Research Repository · Identity Federation · Library · Open Access · Digital Collections · IIIF · OAI-PMH · Shibboleth

## Trinity College Dublin on APIs.io

Everything profiled for Trinity College Dublin is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/trinity-college-dublin/](https://apis.io/providers/trinity-college-dublin/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Trinity Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/trinity-college-dublin/shibboleth-idp/) — Trinity's own Shibboleth IdP, self-hosted on its own registrable domain: idp.tcd.ie resolves through idpha.tcd.ie to 134.226.14.232, inside Trinity's…
- [Trinity Microsoft Entra ID tenant (OIDC + SAML metadata)](https://apis.io/apis/trinity-college-dublin/entra-id-tenant/) — Trinity's Microsoft Entra ID tenant, d595be8d-b306-45f4-8064-9e5b82fbe52b, resolved from the tcd.ie domain hint. OpenID Connect discovery and SAML…
- [TARA OAI-PMH (Trinity's Access to Research Archive)](https://apis.io/apis/trinity-college-dublin/tara-oai/) — TARA is Trinity's open-access institutional repository, a DSpace deployment on Trinity's own host (www.tara.tcd.ie) with its own DataCite repository…
- [TCD Digital Collections (IIIF Presentation)](https://apis.io/apis/trinity-college-dublin/digital-collections-iiif/) — The Library of Trinity College Dublin's Hyrax/Samvera digital asset repository, on Trinity's own host and built from Trinity's own open-source application…
- [eDeposit Ireland — OAI-PMH and DSpace REST](https://apis.io/apis/trinity-college-dublin/edeposit-ireland/) — Ireland's national legal-deposit digital repository, administered by the Library of Trinity College Dublin (OAI-PMH Identify reports adminEmail…
- [Trinity College Dublin site OpenSearch description](https://apis.io/apis/trinity-college-dublin/opensearch/) — An OpenSearch 1.1 description document served as application/xml from Trinity's own domain and explicitly authored by Trinity — the document's own Developer…
- [DataCite consortium membership (provider TCD)](https://apis.io/apis/trinity-college-dublin/datacite-registrant/) — Trinity is a DataCite consortium organization, symbol TCD, country IE, linked to https://ror.org/02tyrky19. It holds five prefixes (10.25546, 10.48495,…
- [Crossref membership (member 49418)](https://apis.io/apis/trinity-college-dublin/crossref-member/) — Crossref member 49418, "Trinity College Dublin, the University of Dublin", holding prefix 10.69731. As of the 2026-09-01 probe the member record reports…
- [ROR organization record (02tyrky19)](https://apis.io/apis/trinity-college-dublin/ror-record/) — Trinity's Research Organization Registry identifier, https://ror.org/02tyrky19, the canonical machine-readable organizational identity used across DataCite,…
- [Library opening hours and room booking (Springshare LibCal)](https://apis.io/apis/trinity-college-dublin/libcal/) — Trinity Library's LibCal tenancy on Springshare's platform, tcd-ie.libcal.com. The public widget endpoint api_hours_today.php returns a machine-parseable…
- [Library subject and research guides (Springshare LibGuides)](https://apis.io/apis/trinity-college-dublin/libguides/) — Trinity Library's LibGuides tenancy at libguides.tcd.ie, the published documentation surface for TARA and for the Library's generative-AI referencing…
- [Trinity Research Support System (RSS)](https://apis.io/apis/trinity-college-dublin/research-support-system/) — Trinity's own research information system at rss.tcd.ie, resolving through tcdlocalportalha.tcd.ie to 134.226.14.238 inside Trinity's own network. Sign-in…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Trinity College Dublin Context](https://apis.io/jsonld/trinity-college-dublin/trinity-college-dublin-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Trinity College Dublin Authentication](https://apis.io/security/trinity-college-dublin/trinity-college-dublin-authentication/)
- [Trinity College Dublin Domain Security](https://apis.io/security/trinity-college-dublin/trinity-college-dublin-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Trinity College Dublin Plans Pricing](https://apis.io/plans/trinity-college-dublin/trinity-college-dublin-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Trinity College Dublin Rate Limits](https://apis.io/rate-limits/trinity-college-dublin/trinity-college-dublin-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Trinity College Dublin Finops](https://apis.io/finops/trinity-college-dublin/trinity-college-dublin-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.tcd.ie/)
- [Documentation](https://www.tcd.ie/library/)
- [Support](https://www.tcd.ie/itservices/our-services/it-service-desk/)
- [Terms of service](https://www.tcd.ie/disclaim/)
- [Privacy policy](https://www.tcd.ie/privacy/)
- [GitHub](https://github.com/TCDLibrary)

## API Evangelist rating

**Kin Score 23.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 26.2 |
| Access clarity | 26.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
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

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/trinity-college-dublin/](https://apis.io/providers/trinity-college-dublin/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Trinity College Dublin: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/trinity-college-dublin/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
