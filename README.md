# Kadena

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

> **No longer operating.** This company or product has shut down, been discontinued, or been deprecated. This profile is kept as a historical record and is not maintained or rated.

**Status:** ceased-operations

Kadena was a layer-1 Proof-of-Work blockchain platform built around Chainweb, a braided, parallelized Nakamoto-consensus protocol that scales Bitcoin-style security across many chains for high transaction throughput, together with Pact, its human-readable, Turing-incomplete smart-contract language. Kadena exposed two primary public APIs: the Chainweb Node API (P2P and service endpoints for cuts, blocks, headers, payloads, the mempool, mining, and node info) and the Pact REST API (local, send, poll, listen, spv) for submitting and querying smart-contract transactions on mainnet and testnet. The developer surface includes the kadena.js TypeScript client libraries, the pactjs CLI for type generation, and extensive docs at docs.kadena.io. Kadena Eco supported an ecosystem of dApps, the Marmalade NFT standard, and tooling. NOTE: Kadena the company announced it would cease operations on 2025-10-21; Kadena Mainnet stopped producing blocks on 2025-11-15 and the kadena-io GitHub organization was archived on 2025-12-23. A community edition (kda-community) forked from mainnet on 2025-11-08 and continues the open-source protocol. This profile documents the public API surface as published.

**Areas:** Company · Web3 · Blockchain · Smart Contracts · Proof of Work · Layer 1 · Cryptocurrency · Developer Tools · Decentralized

## Kadena on APIs.io (historical record)

Everything profiled for Kadena is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kadena/](https://apis.io/providers/kadena/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Kadena Block API](https://apis.io/apis/kadena/kadena-block-api/) — These endpoints return whole blocks, headers and payloads, from the chain database. Generally, blocks are returned in ascending order and include orphaned…
- [Kadena Blockhash API](https://apis.io/apis/kadena/kadena-blockhash-api/) — These endpoints return block hashes from the chain database. Generally, block hashes are returned in ascending order and include hashes from orphaned…
- [Kadena Config API](https://apis.io/apis/kadena/kadena-config-api/) — The config API from Kadena — 1 operation(s) for config.
- [Kadena Cut API](https://apis.io/apis/kadena/kadena-cut-api/) — A cut represents a distributed state of a chainweb. It references one block header for each chain, such that those blocks are pairwise concurrent. Two…
- [Kadena Endpoint Listen API](https://apis.io/apis/kadena/kadena-endpoint-listen-api/) — The endpoint-listen API from Kadena — 1 operation(s) for endpoint-listen.
- [Kadena Endpoint Local API](https://apis.io/apis/kadena/kadena-endpoint-local-api/) — The endpoint-local API from Kadena — 1 operation(s) for endpoint-local.
- [Kadena Endpoint Poll API](https://apis.io/apis/kadena/kadena-endpoint-poll-api/) — The endpoint-poll API from Kadena — 1 operation(s) for endpoint-poll.
- [Kadena Endpoint Private API](https://apis.io/apis/kadena/kadena-endpoint-private-api/) — The endpoint-private API from Kadena — 1 operation(s) for endpoint-private.
- [Kadena Endpoint Send API](https://apis.io/apis/kadena/kadena-endpoint-send-api/) — The endpoint-send API from Kadena — 1 operation(s) for endpoint-send.
- [Kadena Endpoint Spv API](https://apis.io/apis/kadena/kadena-endpoint-spv-api/) — The endpoint-spv API from Kadena — 1 operation(s) for endpoint-spv.
- [Kadena Header API](https://apis.io/apis/kadena/kadena-header-api/) — These endpoints return block headers from the chain database. Similar to the block endpoints, block headers are generally returned in ascending order and…
- [Kadena Mempool API](https://apis.io/apis/kadena/kadena-mempool-api/) — Mempool P2P endpoints for communication between mempools. Endusers are not supposed to use these endpoints directly. Instead, the respective Pact endpoints…
- [Kadena Mining API](https://apis.io/apis/kadena/kadena-mining-api/) — The Mining API of Chainweb node is disabled by default. It can be enabled and configured in the configuration file. The mining API consists of the following…
- [Kadena Misc API](https://apis.io/apis/kadena/kadena-misc-api/) — The misc API from Kadena — 7 operation(s) for misc.
- [Kadena Payload API](https://apis.io/apis/kadena/kadena-payload-api/) — Raw literal Block Payloads in the form in which they are stored on the chain. By default only the payload data is returned which is sufficient for…
- [Kadena Peer API](https://apis.io/apis/kadena/kadena-peer-api/) — The P2P communication between chainweb-nodes is sharded into several independent P2P network. The `cut` network is exchanging consensus state. There is also…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [kadena](https://apis.io/servers/kadena/kadena/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Kadena Agentic Access](https://apis.io/agentic-access/kadena/kadena-agentic-access/)

#### Collections (16)

Postman and Open Collection request collections.

- [Kadena Chainweb Node block API](https://apis.io/collections/kadena/open-kadena-block-api/)
- [Kadena Chainweb Node block blockhash API](https://apis.io/collections/kadena/open-kadena-blockhash-api/)
- [Kadena Chainweb Node block config API](https://apis.io/collections/kadena/open-kadena-config-api/)
- [Kadena Chainweb Node block cut API](https://apis.io/collections/kadena/open-kadena-cut-api/)
- [Kadena Chainweb Node block endpoint-listen API](https://apis.io/collections/kadena/open-kadena-endpoint-listen-api/)
- [Kadena Chainweb Node block endpoint-local API](https://apis.io/collections/kadena/open-kadena-endpoint-local-api/)
- [Kadena Chainweb Node block endpoint-poll API](https://apis.io/collections/kadena/open-kadena-endpoint-poll-api/)
- [Kadena Chainweb Node block endpoint-private API](https://apis.io/collections/kadena/open-kadena-endpoint-private-api/)
- [Kadena Chainweb Node block endpoint-send API](https://apis.io/collections/kadena/open-kadena-endpoint-send-api/)
- [Kadena Chainweb Node block endpoint-spv API](https://apis.io/collections/kadena/open-kadena-endpoint-spv-api/)
- [Kadena Chainweb Node block header API](https://apis.io/collections/kadena/open-kadena-header-api/)
- [Kadena Chainweb Node block mempool API](https://apis.io/collections/kadena/open-kadena-mempool-api/)
- [Kadena Chainweb Node block mining API](https://apis.io/collections/kadena/open-kadena-mining-api/)
- [Kadena Chainweb Node block misc API](https://apis.io/collections/kadena/open-kadena-misc-api/)
- [Kadena Chainweb Node block payload API](https://apis.io/collections/kadena/open-kadena-payload-api/)
- [Kadena Chainweb Node block peer API](https://apis.io/collections/kadena/open-kadena-peer-api/)

#### Overlays (2)

OpenAPI overlays, including conversational phrasing for each operation.

- [Kadena Chainweb Overlay](https://apis.io/overlays/kadena/kadena-chainweb-overlay/)
- [Kadena Pact Overlay](https://apis.io/overlays/kadena/kadena-pact-overlay/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Kadena Domain Security](https://apis.io/security/kadena/kadena-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://kadena.io)
- [Documentation](https://docs.kadena.io)
- [Getting started](https://docs.kadena.io/build/quickstart)
- [API reference](https://kadena-io.github.io/chainweb-openapi/)
- [Changelog](https://docs.kadena.io/changelogs/chainweb-node)
- [Blog](https://medium.com/kadena-io)
- [GitHub](https://github.com/kadena-io)

## API Evangelist rating

**Not rated** — this company is recorded as no longer operating, so no score is published. If it is in fact operating, say so on this repository and it will be re-profiled.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kadena: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kadena/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
