# Manage OpenAPI via GitHub Demo (demo-openapi)

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

This is a demo repository showing how GitHub can be used to manage an API contract using an APIs.json index plus an OpenAPI definition and supporting artifacts. The API used in the demo is the APIs.io Search API, which exposes search and submission endpoints over the APIs.io index. The repository is referenced by an API Evangelist blog post on managing OpenAPI in GitHub.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/demo-openapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/demo-openapi/refs/heads/main/apis.yml)

## Scope

- **Position:** Producer
- **Access:** 1st-Party

## Tags

- APIs.json
- Demo
- GitHub
- OpenAPI
- Reference
- Search

## Timestamps

- **Created:** 2024-10-31
- **Modified:** 2026-04-28

## APIs

### APIs.io Search API

Demo OpenAPI for the APIs.io Search API, exposing keyword search of APIs in the APIs.io index plus a submit endpoint that accepts a valid APIs.json document for inclusion. Used here purely as a demonstration subject for the GitHub-based API management workflow.

- **Human URL:** [https://developer.apis.io/documentation/](https://developer.apis.io/documentation/)
- **Base URL:** `https://search-api.apis.io/`

#### Tags

- APIs.io
- Demo
- Search
- Submit

#### Properties

- [Documentation](https://developer.apis.io/documentation/)
- [OpenAPI](openapi/openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open A P I Review](openapi/openapi-review.yml)
- [Rules](rules/apis-io-search-api-rules.yml)
- [Capabilities](capabilities/apis-io-search-api-capabilities.yml)
- [Teams](common/team.yml)
- [Use Cases](common/use-cases.yml)

## Common Properties

- [Blog Post](https://github.com/api-evangelist/demo-openapi)
- [Canonical Repo](https://github.com/api-evangelist/search-api)
- [A P Is Io](https://apis.io)
- [Developer](https://developer.apis.io)
- [Support Email](mailto:kin@apievangelist.com)
- [Vocabulary](vocabulary/demo-openapi-vocabulary.yml)
- [JSON-LD](json-ld/demo-openapi-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
