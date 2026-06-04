# Trinity College Dublin (trinity-college-dublin)

Trinity College Dublin (the University of Dublin), founded in 1592, is Ireland's oldest university and is ranked #98 in the QS World University Rankings 2025. This repository catalogs its public developer/API footprint as an [APIs.json](https://apisjson.org) profile. Trinity does not operate a dedicated developer portal or documented open-API program; its real, standards-based API surfaces are the Library's TARA institutional repository (DSpace / OAI-PMH) and Digital Collections (Hyrax/Samvera / IIIF), both reachable interactively but fronted by bot-mitigation.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/trinity-college-dublin/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=trinity-college-dublin-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Ireland, Library, Repository, Open Access, IIIF, OAI-PMH

## APIs

- **TARA OAI-PMH (Trinity's Access to Research Archive)** — DSpace open-access institutional repository exposing an OAI-PMH metadata harvesting interface. Docs: https://libguides.tcd.ie/TARA · Site: https://www.tara.tcd.ie/
- **TCD Digital Collections (IIIF)** — Hyrax/Samvera digital asset repository serving IIIF Presentation manifests for digitised manuscripts including the Book of Kells. Docs: https://www.tcd.ie/library/dris/ · Site: https://digitalcollections.tcd.ie/ · Source: https://github.com/TCDLibrary/TCD-Hyrax-Web-App

## Plans

- [plans/trinity-college-dublin-plans-pricing.yml](plans/trinity-college-dublin-plans-pricing.yml)

## Rate Limits

- [rate-limits/trinity-college-dublin-rate-limits.yml](rate-limits/trinity-college-dublin-rate-limits.yml)

## FinOps

- [finops/trinity-college-dublin-finops.yml](finops/trinity-college-dublin-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tcd.ie/
- GitHub: https://github.com/TCDLibrary
- LinkedIn: https://www.linkedin.com/school/trinity-college-dublin/
- Library: https://www.tcd.ie/library/
- Source Code: https://github.com/TCDLibrary/TCD-Hyrax-Web-App
- Authentication (federated identity): https://www.heanet.ie/services/identity-access/edugate

## Notes

- No dedicated developer portal or documented open-API program was found for Trinity College Dublin as of 2026-06-03.
- TARA (tara.tcd.ie) is a DSpace repository with an OAI-PMH interface, but the host is behind Cloudflare bot-mitigation and returns HTTP 403 to unattended programmatic clients; it loads normally in an interactive browser.
- Digital Collections (digitalcollections.tcd.ie) is a Hyrax/Samvera platform that serves IIIF manifests; the manifest URL returns HTTP 200 but the body is a reCAPTCHA interstitial for automated requests rather than JSON.
- Federated identity uses HEAnet Edugate / eduGAIN SAML, which is institutional SSO and not a public developer API.
- No endpoints were fabricated; every URL was probed live (see review.yml for HTTP statuses).

## Maintainers

- Kin Lane — kin@apievangelist.com
