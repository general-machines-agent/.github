# General Machines AI

We are a research and engineering lab studying how AI systems behave when they meet real software, stores, and physical operations. Our method is to run agents against live environments, preserve the full trace, verify outcomes against system state, and turn repeated failures into datasets, evaluations, and open tooling.

## Machine Commerce

[Machine Commerce](https://machinecommerce.co) is our applied research program for agentic commerce. The [Agentic Shopping Lab](https://github.com/masti-ai/agentic-shopping-lab) runs shopping agents on real stores, records every tool call, model message, screenshot, and result, then checks the claimed outcome against the cart itself. It compares routes such as the plain web, Shopify APIs, MCP/UCP, WebMCP, ACP, and computer use. The standard follows the evidence rather than being fixed in advance.

Current evidence includes a 9,960-episode back-catalog, 223 already-judged journeys, and a 670-journey failure audit. That audit is now driving work on verifier false-fails, trace provenance, rate-limit handling, geographic drift, hidden-fact leakage, and state-verified benchmark design. No research episode submits a real payment.

The lab is private while store traces and evaluation methods are being cleaned for release. We plan to publish versioned methods, aggregate results, trace schemas, benchmark artifacts, and standards findings without exposing private shopper or merchant data.

## Applied systems

These systems are where we test the research against production constraints. Their repositories are private and visible only to current collaborators.

- [Villa Planogram](https://github.com/masti-ai/villa-planogram-dashboard) - a retail shelf-compliance system with mobile capture, an operator dashboard, a CRUD backend, and a YOLO + SigLIP + FAISS + SAM ML pipeline.
- [Villa Banner Studio](https://github.com/masti-ai/villa-banner-pipeline) - a campaign-artwork pipeline that works with real SKU packaging, staged themes, and a white-label API.
- [ALC AI Villa](https://github.com/masti-ai/alc-ai-villa) - a hospitality concierge and recommendation system with catalog search, persistent preferences, cart operations, and operator tooling.

## Open source

- [OpenKT](https://github.com/masti-ai/OpenKT-ai) - a shared context layer for teams and their AI agents, with source attribution and access control applied inside retrieval.
- [OpenKT plugins](https://github.com/masti-ai/openkt-plugins) - installable OpenKT packaging for Claude Code, Codex, and Hermes.
- [Gas Town](https://github.com/masti-ai/gastown) - a multi-agent workspace manager for running and coordinating coding agents.

## Work with us

OpenKT welcomes contributions through its [contribution guide](https://github.com/masti-ai/OpenKT-ai/blob/main/CONTRIBUTING.md). Useful work includes retrieval and permission tests, MCP client support, local-model evaluation, documentation, and plugin packaging.

For Machine Commerce, we want to hear from researchers and builders working on shopping-agent evaluation, deterministic outcome verification, trace formats, commerce protocols, and safe live-store measurement. The lab repository and raw traces remain private for now; public methods and artifacts will be released in versioned form as they are ready.

- [generalmachines.ai](https://generalmachines.ai)
- [machinecommerce.co](https://machinecommerce.co)

*Deepwork Labs Pte. Ltd. (Singapore)*
