# Chalmers University of Technology (chalmers-university-of-technology)

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

Chalmers University of Technology is a private technical university in Gothenburg, Sweden, ranked #139 in the QS World University Rankings 2025. This repository catalogs the institution's public, machine-readable developer/API footprint as an [APIs.json](http://apisjson.org) profile. Chalmers' confirmed public surfaces center on research information and library/repository services rather than a single unified developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/chalmers-university-of-technology/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=chalmers-university-of-technology-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Library, OAI-PMH, Sweden

## APIs

- **Chalmers Research API** — research projects, publications, funders and collaborations. Docs: https://api.research.chalmers.se/Help (root: https://api.research.chalmers.se/)
- **Chalmers Research OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the Chalmers Research portal. Docs: https://research.chalmers.se/oai-pmh/general/?verb=Identify
- **Chalmers Open Digital Repository (ODR) OAI-PMH** — OAI-PMH 2.0 metadata harvesting for student theses and special collections. Docs: https://odr.chalmers.se/server/oai/request?verb=Identify

## Plans

- [plans/chalmers-university-of-technology-plans-pricing.yml](plans/chalmers-university-of-technology-plans-pricing.yml)

## Rate Limits

- [rate-limits/chalmers-university-of-technology-rate-limits.yml](rate-limits/chalmers-university-of-technology-rate-limits.yml)

## FinOps

- [finops/chalmers-university-of-technology-finops.yml](finops/chalmers-university-of-technology-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.chalmers.se/en/
- GitHub: https://github.com/ChalmersLibrary
- LinkedIn: https://www.linkedin.com/school/chalmers-university-of-technology/
- Source Code: https://github.com/ChalmersLibrary

## Notes

All APIs and endpoints listed here were verified against live HTTP responses where possible. The Chalmers Research API root, the Chalmers Research OAI-PMH interface, and the ODR OAI-PMH interface all responded 200. The legacy Chalmers Publication Library (CPL) OAI-PMH endpoint returned 404 and appears retired/migrated. No published OpenAPI definition and no single consolidated self-service developer portal were confirmed. No separate top-level `chalmers` GitHub organization exists; the `ChalmersLibrary` org is the confirmed institutional code home. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
