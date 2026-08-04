# ResWare (resware)

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

ResWare is customizable title and escrow production software for real estate closings. It was originally built by **Adeptive Software Corporation** and was **acquired by Qualia Labs in December 2020**; it now ships as **ResWare 10** within the Qualia ecosystem. ResWare is an on-premises, workflow-driven platform covering title and escrow production (action-based tasks and multi-directional workflows), document management and auto-generation, secure communications, and escrow accounting with reconciliation and remittance.

**Access model — gated partner/integration API.** ResWare does not operate a public, self-serve developer portal. API access is provided to partners and customers through an integration/partner program and an "API assistance" package (developer support hours, REST/WCF code samples, and documentation). Pricing is on request. Developer/partner contact: `sales@adeptivesw.com`. A gated knowledge base lives at `knowledge.resware.com`.

**Transport — SOAP/XML web services (WCF) plus REST.** ResWare's integration API is historically a **SOAP/XML web-service API** built on **Windows Communication Foundation (WCF)** — using Microsoft's binary protocol by default, with Basic Authentication available on request — complemented by **newer REST APIs** for document handling (endpoint paths such as `/Api/files/search` and `/Api/files/:file_id/documents` have been observed in partner integrations). There is **no public WebSocket API**. Because ResWare publishes no public API reference or OpenAPI, this entry does **not** fabricate a REST surface; the logical service areas below are modeled from partner-integration behavior.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/resware/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/resware/refs/heads/main/apis.yml)

## Tags

- Title
- Escrow
- Real Estate
- Closing
- Title Production
- SOAP
- XML
- WCF
- Partner API
- Gated
- Qualia

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs (logical service areas — modeled)

> The following are logical service areas modeled from ResWare partner integrations. ResWare's integration API is a gated SOAP/XML (WCF) + REST partner surface with no public API reference, so endpoints are modeled rather than fabricated.








## Common Properties

- [LinkedIn](https://www.linkedin.com/company/qualia-labs)
- [Website](https://resware.com)
- [Website (Qualia product page)](https://www.qualia.com/resware/)
- [Documentation (Integrations)](https://www.qualia.com/resware-integrations/)
- [Support Portal](https://knowledge.resware.com)
- [Contact](mailto:sales@adeptivesw.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
