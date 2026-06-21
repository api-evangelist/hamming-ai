# Hamming AI (hamming-ai)

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
