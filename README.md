# Elementus

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

Elementus is a New York blockchain intelligence company founded in 2017 that attributes on-chain
addresses to real-world entities across multiple chains, and sells that attribution graph to
compliance, investigations and market-intelligence teams. Its public API surface is the Attribution
API, a key-authenticated REST service at `attribution-api.elementus.io` that resolves batches of
blockchain addresses to a beneficial owner, custodian, entity name and OFAC/SDN sanction status.

**As of the 2026-08-12 probe, no Elementus web host resolves.** The `elementus.io` apex publishes no
address record, `www.elementus.io` is NXDOMAIN, and both `attribution-api.elementus.io` and
`app.elementus.io` are dangling CNAMEs pointing at AWS resources that no longer exist. The DNS zone
itself is still live on Cloudflare and still routes mail to Google Workspace, so the domain has not
been released — the public presence has been withdrawn. Everything documented in this profile was
reconstructed from Elementus' own public GitHub organization, the only first-party surface that was
reachable.

- Website (unresolvable as of 2026-08-12): https://www.elementus.io/
- GitHub organization (live): https://github.com/elementus-io
- API example client (live): https://github.com/elementus-io/api-example
