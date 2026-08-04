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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

DISQO is a Glendale, California consumer-insights and advertising-measurement company that
operates a first-party, fully opted-in consumer panel and sells programmatic access to it.

- Website: https://www.disqo.com/
- Developer portal: https://developer.disqo.com/
- Documentation: https://developer.disqo.com/documentation/

## APIs profiled

| API | Base URL | Auth | Docs |
|---|---|---|---|
| Audience Projects API | `https://projects-api.audience.disqo.com` | HTTP Basic | [docs](https://developer.disqo.com/docs/audience-api/) |
| Audience Feasibility API | `https://feasibility-api.audience.disqo.com` | HTTP Basic | [docs](https://developer.disqo.com/docs/audience-api/) |
| Audience Custom Questions API | `https://custom-questions-api.audience.disqo.com` | HTTP Basic | [docs](https://developer.disqo.com/docs/audience-api/) |
| CoReg API | `https://coreg.us.sjapis.com/api` | `Authorization: ApiKey` | [docs](https://developer.disqo.com/docs/coreg-api/) |

## What DISQO publishes

- A public **Postman collection** for the Audience API (18 requests), linked from the docs — captured
  verbatim in `postman/`.
- A dated **changelog** embedded in the Audience API documentation — captured in `changelog/`.
- A full parallel **DEMO/sandbox environment** on `disqo-demo.com`, with `verify` endpoints — `sandbox/`.
- An **llms.txt** at `https://www.disqo.com/llms.txt` — captured verbatim in `llms/`.
- A published **error-code registry** and callback status/substatus vocabulary — `errors/`.

## What DISQO does not publish

Recorded as evidence of absence, with the probe results, in the artifacts:

- **No OpenAPI / Swagger.** Probed nine spec paths against all three Audience API hosts (all `401` —
  HTTP Basic is enforced at the edge for every path) and against the docs and marketing hosts (all
  `404`). See `conformance/disqo-conformance.yml`.
- **No `/.well-known/` surface at all** — no `security.txt`, no `api-catalog`, no agent card. See
  `well-known/disqo-well-known.yml`.
- **No official SDK on any package registry**, and no `github.com/disqo` organization. See `packages/`.
- **No status page, no SLA, no deprecation policy.** See `lifecycle/`.
- **No idempotency, no pagination, no documented rate limits.** See `conventions/`.
- **No trust center or named certification.** See `conformance/`.

Each artifact carries a `gaps_to_push_back_to_provider` block naming the gap and where DISQO should
publish the fix.
