# ResWare (resware)

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

### ResWare Files & Orders API

Create and manage title/escrow files (orders) — the core transaction records carrying file number, property, parties, and status through the closing lifecycle.

- **Human URL:** [https://www.qualia.com/resware/](https://www.qualia.com/resware/)

### ResWare Documents API

Retrieve, upload, and generate documents attached to a file — closing packages, executed documents, and auto-generated forms (the REST-oriented surface, e.g. `/Api/files/:file_id/documents`).

- **Human URL:** [https://www.qualia.com/resware/](https://www.qualia.com/resware/)

### ResWare Contacts API

The people and organizations on a file — buyers, sellers, lenders, agents, vendors — their roles and mappings to partner-side identifiers.

- **Human URL:** [https://www.qualia.com/resware/](https://www.qualia.com/resware/)

### ResWare Tasks API

ResWare's action-based tasks and multi-directional workflow steps that drive a file through its lifecycle.

- **Human URL:** [https://www.qualia.com/resware/](https://www.qualia.com/resware/)

### ResWare Accounting API

Escrow accounting — trust ledgers, receipts and disbursements, reconciliation, and remittance data tied to a file.

- **Human URL:** [https://www.qualia.com/resware/](https://www.qualia.com/resware/)

### ResWare Notes API

Read and write notes and activity entries on a file; partners post status updates and messages back into ResWare.

- **Human URL:** [https://www.qualia.com/resware/](https://www.qualia.com/resware/)

### ResWare Partners API

ResWare's partner-integration framework — the proxy/partner web-service messages that exchange orders, documents, and status with external vendors (signing/RON, recording, search, LOS, wire protection, and more). This is the primary SOAP/XML (WCF) integration surface.

- **Human URL:** [https://www.qualia.com/resware-integrations/](https://www.qualia.com/resware-integrations/)

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
