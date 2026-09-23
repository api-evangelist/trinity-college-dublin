# Trinity College Dublin (trinity-college-dublin)

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

Trinity College Dublin (the University of Dublin), founded in 1592, is Ireland's oldest university and a legal deposit library for Ireland and the United Kingdom since 1801. This repository catalogs its public developer/API footprint as an [APIs.json](https://apisjson.org) profile. Trinity operates **no public developer portal, no OpenAPI, no API keys and no open-API programme**. What it does operate — and what is recorded here — is standards-based scholarly and identity infrastructure, with every surface carrying an `x-operator` saying who actually runs the thing it describes.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/trinity-college-dublin/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=trinity-college-dublin-api-evangelist&utm_content=repo

## Type

- University / Public Research University — Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, Ireland, Research Repository, Identity Federation, Library, Open Access, Digital Collections, IIIF, OAI-PMH, Shibboleth, DataCite, Legal Deposit

## Surfaces, by operator

**Institution-operated** (Trinity's own hosts and Trinity's own artifacts)

- **Trinity Shibboleth Identity Provider (SAML 2.0 metadata)** — `https://idp.tcd.ie/idp/shibboleth`, HTTP 200 `application/xml`. Self-hosted on Trinity's own network (idpha.tcd.ie → 134.226.14.232), `shibmd:Scope` of `tcd.ie`, registered in HEAnet's Edugate federation and exported to eduGAIN. The strongest machine-readable contract Trinity publishes.
- **TARA OAI-PMH (Trinity's Access to Research Archive)** — DSpace institutional repository on Trinity's host, DataCite repository `TCD.TARA`. Both `/oai/request` and `/server/oai/request` return a Cloudflare 403 interstitial to unattended clients. Live, not machine-callable.
- **TCD Digital Collections (IIIF Presentation)** — Hyrax/Samvera repository built from Trinity's own open-source app, DataCite repository `TCD.DIGCOLLS`. Every path, including work manifests, returns a soft-200 reCAPTCHA interstitial from an F5 Distributed Cloud edge.
- **Trinity College Dublin site OpenSearch description** — `https://www.tcd.ie/assets/xml/tcd-opensearch/tcd-opensearch.xml`, HTTP 200 `application/xml`, whose own `<Developer>` element reads "Trinity College Dublin, Digital and Web team".
- **Trinity Research Support System (RSS)** — `rss.tcd.ie` on Trinity's own network, entirely SAML-gated. No anonymous read; there is no Pure/Elsevier tenancy (pure.tcd.ie and tcd.elsevierpure.com do not resolve).

**Federation**

- **Trinity Microsoft Entra ID tenant** — tenant `d595be8d-b306-45f4-8064-9e5b82fbe52b`, resolved from the `tcd.ie` domain hint. OIDC discovery and SAML federation metadata both answer unauthenticated. Microsoft's host and contract; Trinity's tenant and identities.

**Tenant** (Trinity's data and service identity, someone else's contract)

- **eDeposit Ireland** — Ireland's national legal-deposit repository, administered by Trinity Library (`adminEmail: edepositadmin@tcd.ie`) and registered as DataCite repository `TCD.EDEPOSITIRE`. The one Trinity-administered repository that answers a harvester: OAI-PMH `Identify`, `ListMetadataFormats` (12 prefixes) and `ListSets` all return 200, and the REST root self-reports DSpace 7.6. `www.edepositireland.ie` CNAMEs to `edepositireland.cname.openrepository.com` — Atmire's Open Repository platform.
- **Library opening hours and room booking** — Springshare LibCal at `tcd-ie.libcal.com`; the public hours widget answers, the LibCal 1.1 JSON API returns 403 without a key Trinity has not published.
- **Library subject and research guides** — Springshare LibGuides at `libguides.tcd.ie`.

**Registry** (memberships — facts about Trinity, never Trinity's contract)

- **DataCite** — consortium organization `TCD`, linked to `https://ror.org/02tyrky19`, five prefixes, five repositories, 16,031 DOIs.
- **Crossref** — member 49418, prefix `10.69731`, zero deposited DOIs as of the probe.
- **ROR** — `https://ror.org/02tyrky19`.

## Artifacts

- [conformance/trinity-college-dublin-domain-standards.yml](conformance/trinity-college-dublin-domain-standards.yml) — education-regime conformance: shibboleth, saml, oai-pmh, datacite, crossref, each with a probed location
- [authentication/trinity-college-dublin-authentication.yml](authentication/trinity-college-dublin-authentication.yml)
- [plans/trinity-college-dublin-plans-pricing.yml](plans/trinity-college-dublin-plans-pricing.yml)
- [rate-limits/trinity-college-dublin-rate-limits.yml](rate-limits/trinity-college-dublin-rate-limits.yml)
- [finops/trinity-college-dublin-finops.yml](finops/trinity-college-dublin-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.tcd.ie/
- Documentation: https://www.tcd.ie/library/
- GitHub Organization: https://github.com/TCDLibrary
- LinkedIn: https://www.linkedin.com/school/trinity-college-dublin/
- Identity Federation: https://www.tcd.ie/itservices/our-services/edugate---federated-access/
- Research Repository: https://www.tcd.ie/library/riss/tara/
- Library Catalog: https://www.tcd.ie/library/opub/catalogues.php
- Course Catalog: https://www.tcd.ie/courses/
- Research Computing: https://www.tchpc.tcd.ie/
- AI Policy: https://www.tcd.ie/academic-affairs/what-we-do/whats-new/generative-ai-statement/
- AI Tooling: https://www.tcd.ie/itservices/keeping-it-secure/artificial-intelligence-ai/
- Privacy Policy: https://www.tcd.ie/privacy/
- Terms of Service: https://www.tcd.ie/disclaim/
- Support: https://www.tcd.ie/itservices/our-services/it-service-desk/

## Notes

- Re-profiled 2026-09-01 under the API Evangelist university pipeline, which settles operator attribution before saving anything. No vendor contract is saved in this repository and none was found to remove.
- Coverage is `gated` / `bot_blocked`: Trinity's two own repository surfaces refuse unattended clients (Cloudflare 403 on TARA; soft-200 reCAPTCHA on Digital Collections). Neither is dead and neither is an authentication wall.
- `api.tcd.ie`, `data.tcd.ie` and `developer.tcd.ie` do not resolve. `https://www.tcd.ie/llms.txt` returns 404.
- Education-regime standards evidenced: shibboleth, saml, oai-pmh, datacite, crossref. Not evidenced and deliberately not claimed: scim, lti, oneroster, ed-fi, caliper, qti — Trinity runs Blackboard Learn and Tribal SITS, but neither exposes a publicly probeable conformance surface.
- No endpoints were fabricated; every URL above was probed live on 2026-09-01 with a browser User-Agent.

## Maintainers

- Kin Lane — kin@apievangelist.com
