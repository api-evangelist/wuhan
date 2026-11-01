# Wuhan University

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

Wuhan University (武汉大学, WHU), founded in 1893 in Wuhan, Hubei, is a comprehensive public research university under China's Ministry of Education, a Double First-Class and former Project 985 institution, and is strongest in surveying, remote sensing, geoinformatics and GNSS. It operates no public developer portal, no open data portal and no documented public API: api., data., open. and developer. under whu.edu.cn do not resolve, /.well-known/apis.json, llms.txt, security.txt, robots.txt and sitemap.xml all return 404 on both the Chinese and English sites, and no OpenAPI, AsyncAPI or GraphQL contract exists anywhere in this profile. What it does operate, on its own CERNET address space, is an identity estate and a bulk research-data archive. Wuhan University runs a Shibboleth SAML 2.0 identity provider registered in CARSI, China's national research-and-education federation and a production eduGAIN member, and a campus CAS single-sign-on server that publishes a live OpenID Connect discovery document — the only conforming, self-describing, machine-readable contract WHU serves to the anonymous public, and it is the SSO product's shape rather than WHU engineering. It also operates one of the IGS Global Data Centers: the International GNSS Service's own data-access page names Wuhan University and links ftp://igs.gnsswhu.cn/, an anonymously listable archive of GPS, BDS, MGEX, high-rate and IERS products. Library discovery is an Ex Libris Aleph tenancy on a WHU host, and the registrar system is behind campus SSO. The institution's only evidenced education-regime conformance is SAML and Shibboleth; it is not a DataCite or Crossref depositing member, and no institution-operated OAI-PMH endpoint was found.

**Areas:** Education · Higher Education · University · Research · China · Identity Federation · SSO · Research Data · GNSS · Library · Open Source

## Wuhan University on APIs.io

Everything profiled for Wuhan University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/wuhan/](https://apis.io/providers/wuhan/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Wuhan University Shibboleth Identity Provider (SAML 2.0)](https://apis.io/apis/wuhan/shibboleth-idp/) — WHU's federated login, published as a SAML 2.0 EntityDescriptor at https://idp.whu.edu.cn/idp/shibboleth (HTTP 200, application/xml, 14,864 bytes). Declares…
- [Wuhan University Campus Single Sign-On (CAS / OpenID Connect / SAML)](https://apis.io/apis/wuhan/cas-sso/) — The campus authentication server at cas.whu.edu.cn/authserver, which every institutional application redirects into, running the Wisedu CAS distribution. It…
- [IGS Data Center at Wuhan University (GNSS archive)](https://apis.io/apis/wuhan/igs-data-center/) — One of the International GNSS Service's Global Data Centers, operated by Wuhan University's GNSS Research Center. The archive is anonymously listable over…
- [CARSI membership (CERNET Authentication and Resource Sharing Infrastructure)](https://apis.io/apis/wuhan/carsi/) — Wuhan University is a registered identity provider in CARSI, China's national research-and-education identity federation, operated from Peking University…
- [ROR registry entry (Research Organization Registry)](https://apis.io/apis/wuhan/ror/) — Wuhan University is registered in ROR as https://ror.org/033vjfk17 (active, established 1893), cross-walked to GRID grid.49470.3e, ISNI 0000 0001 2331 6153,…
- [Wuhan University Library catalog (Ex Libris Aleph tenant)](https://apis.io/apis/wuhan/opac/) — The library's online public access catalog at opac.lib.whu.edu.cn, running Ex Libris Aleph — the root document is Aleph's own session bootstrap ("Aleph main…
- [Wuhan University academic affairs / registrar system (SSO-gated)](https://apis.io/apis/wuhan/jwgl/) — The institutional teaching-administration and course-registration system. jwgl.whu.edu.cn is live and redirects unauthenticated callers to…
- [Geomatics and Information Science of Wuhan University (journal platform)](https://apis.io/apis/wuhan/journal-platform/) — WHU's own journal publishing platform at ch.whu.edu.cn (115.156.123.29, WHR-CERNET), hosting 武汉大学学报·信息科学版 / Geomatics and Information Science of Wuhan…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Wuhan Context](https://apis.io/jsonld/wuhan/wuhan-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Wuhan Authentication](https://apis.io/security/wuhan/wuhan-authentication/)
- [Wuhan Domain Security](https://apis.io/security/wuhan/wuhan-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Wuhan Scopes](https://apis.io/scopes/wuhan/wuhan-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Wuhan Plans Pricing](https://apis.io/plans/wuhan/wuhan-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Wuhan Rate Limits](https://apis.io/rate-limits/wuhan/wuhan-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Wuhan Finops](https://apis.io/finops/wuhan/wuhan-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://en.whu.edu.cn)
- [GitHub](https://github.com/WHUIR)

## API Evangelist rating

**Kin Score 18.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 21.4 |
| Access clarity | 5.3 |

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

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/wuhan/](https://apis.io/providers/wuhan/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Wuhan University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/wuhan/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
