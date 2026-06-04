# Chalmers University of Technology (chalmers-university-of-technology)

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
