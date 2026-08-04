# Hamming AI (hamming-ai)

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

Hamming AI is a testing, evaluation, and observability platform for voice and LLM AI agents. Its REST API runs experiments and voice/call test runs against your agents, manages datasets, registers custom scorers and evaluations, and ingests traces, logs, and production call logs for monitoring. A prompt optimizer and registry round out the platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hamming-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hamming-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Voice Agents
- LLM
- Testing
- Evaluation
- Observability

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Hamming Experiments & Test Runs API

Create experiments, start and end experiment items, and update experiment status to run repeatable evaluation runs against agent and LLM outputs over a dataset.

- **Human URL:** [https://docs.hamming.ai/guides/evaluations](https://docs.hamming.ai/guides/evaluations)
- **Base URL:** `https://app.hamming.ai/api/rest`

#### Tags

- Experiments
- Test Runs
- Evaluation

#### Properties

- [Documentation](https://docs.hamming.ai/guides/evaluations)
- [API Reference](https://docs.hamming.ai/guides/voice-agent-api)
- [OpenAPI](openapi/hamming-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hamming-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hamming-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hamming Voice & Call Testing API

Run a voice agent against a dataset of scenarios by placing simulated outbound calls, create LiveKit rooms for direct agent-to-agent test runs, and retrieve the calls produced by a voice experiment with their scoring status.

- **Human URL:** [https://docs.hamming.ai/guides/voice-agent-api](https://docs.hamming.ai/guides/voice-agent-api)
- **Base URL:** `https://app.hamming.ai/api/rest`

#### Tags

- Voice Agents
- Call Testing
- LiveKit

#### Properties

- [Documentation](https://docs.hamming.ai/guides/voice-agent-api)
- [API Reference](https://docs.hamming.ai/guides/voice-agent-testing)
- [OpenAPI](openapi/hamming-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hamming-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hamming-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hamming Datasets API

List, create, and load datasets of test cases and conversation scenarios used as inputs for experiments and voice test runs.

- **Human URL:** [https://docs.hamming.ai/guides/voice-agent-testing](https://docs.hamming.ai/guides/voice-agent-testing)
- **Base URL:** `https://app.hamming.ai/api/rest`

#### Tags

- Datasets
- Test Cases
- Scenarios

#### Properties

- [Documentation](https://docs.hamming.ai/guides/voice-agent-testing)
- [OpenAPI](openapi/hamming-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hamming-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hamming-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hamming Scorers & Evaluations API

Register custom scoring functions that compute scores over experiment results, complementing Hamming's library of built-in evaluation metrics.

- **Human URL:** [https://docs.hamming.ai/guides/custom-scores](https://docs.hamming.ai/guides/custom-scores)
- **Base URL:** `https://app.hamming.ai/api/rest`

#### Tags

- Scorers
- Evaluations
- Metrics

#### Properties

- [Documentation](https://docs.hamming.ai/guides/custom-scores)
- [OpenAPI](openapi/hamming-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hamming-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hamming-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hamming Monitoring & Tracing API

Ingest traces and logs from instrumented agents and forward production voice call logs (e.g. provider call-ended payloads) for continuous monitoring of agent health and reliability in production.

- **Human URL:** [https://docs.hamming.ai/guides/monitoring](https://docs.hamming.ai/guides/monitoring)
- **Base URL:** `https://app.hamming.ai/api/rest`

#### Tags

- Monitoring
- Tracing
- Observability

#### Properties

- [Documentation](https://docs.hamming.ai/guides/monitoring)
- [API Reference](https://docs.hamming.ai/guides/voice-agent-monitoring)
- [OpenAPI](openapi/hamming-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hamming-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hamming-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hamming Prompt Optimizer & Registry API

List and fetch versioned, labeled prompts from the Hamming prompt registry to manage and optimize prompts used by agents under test.

- **Human URL:** [https://docs.hamming.ai/guides/evaluations](https://docs.hamming.ai/guides/evaluations)
- **Base URL:** `https://app.hamming.ai/api/rest`

#### Tags

- Prompts
- Optimization
- Registry

#### Properties

- [Documentation](https://docs.hamming.ai/guides/evaluations)
- [OpenAPI](openapi/hamming-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hamming-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hamming-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/HammingHQ)
- [LinkedIn](https://www.linkedin.com/company/hammingai)
- [Website](https://hamming.ai/)
- [Documentation](https://docs.hamming.ai)
- [Plans](plans/hamming-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/hamming-ai-rate-limits.yml)
- [Fin Ops](finops/hamming-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
