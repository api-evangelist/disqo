# DISQO

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

DISQO is a Glendale, California consumer-insights and advertising-measurement company that operates a first-party, fully opted-in consumer panel and sells programmatic access to it. Its public API surface is the DISQO Audience API — a RESTful, HTTP Basic authenticated set of services for checking sample feasibility, creating and managing survey projects and quotas, attaching custom screening questions, and managing included/excluded panelist and project lists — plus a redirect/callback tracking contract that returns panelists to DISQO with an HMAC-SHA256 signed status. A separate CoReg API validates email addresses for co-registration flows. DISQO also sells Brand Lift, Outcomes Lift, Research Management and cross-platform ad measurement products on top of the same panel.

**Areas:** Company · Audiences · Market Research · Surveys · Consumer Insights · Advertising Measurement · Panel · Brand Lift · Data · Analytics

## DISQO on APIs.io

Everything profiled for DISQO is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/disqo/](https://apis.io/providers/disqo/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [DISQO Audience Projects API](https://apis.io/apis/disqo/disqo-audience-projects-api/) — Create, list, retrieve, update and delete survey Projects and their Quotas against the DISQO panel, and manage the included-users, excluded-users and…
- [DISQO Audience Feasibility API](https://apis.io/apis/disqo/disqo-audience-feasibility-api/) — Estimate the number of panelists — feasible completes — available for a given set of qualifications, country, device mix, length of interview and incidence…
- [DISQO Audience Custom Questions API](https://apis.io/apis/disqo/disqo-audience-custom-questions-api/) — List, retrieve and create client-specific custom screening questions that can be attached to a project as pre-screening qualifications beyond the standard…
- [DISQO CoReg API](https://apis.io/apis/disqo/disqo-coreg-api/) — Validate an email address for co-registration flows — checks address format, whether the address already exists in the DISQO system, and optionally runs an…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [disqo](https://apis.io/servers/disqo/disqo/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Disqo Authentication](https://apis.io/security/disqo/disqo-authentication/)
- [Disqo Domain Security](https://apis.io/security/disqo/disqo-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.disqo.com/)
- [Documentation](https://developer.disqo.com/documentation/)
- [Getting started](https://developer.disqo.com/docs/audience-api/)
- [API reference](https://developer.disqo.com/docs/audience-api/)
- [Support](https://www.disqo.com/contact-us/)
- [Blog](https://developer.disqo.com/blog/)
- [Terms of service](https://www.disqo.com/legal/api-managed-services-terms/)
- [Privacy policy](https://www.disqo.com/privacy-policy/)

## API Evangelist rating

**Kin Score 29.9** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 0.0 |
| Contract governance | 4.5 |
| Operational transparency | 15.8 |
| Developer ergonomics | 68.6 |
| Access clarity | 21.1 |

**Agent readiness 17.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/disqo/](https://apis.io/providers/disqo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for DISQO: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/disqo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
