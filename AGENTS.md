# INKWE Motion / AVIDO — Engineering and Preservation Rules

This repository is historical video-studio work within the unified INKWENATIVE / INKWE AI ecosystem. Preserve its history and evolve it as a specialist creative capability, not a competing central AI brain.

- Retain the AVIDO project lineage and the approved INKWE Motion identity.
- Do not assume this standalone repository is the canonical implementation: reconcile it with the nested video-generator in Kheswa1/inkwecham-ai and any creative modules in IC-AI-CITY before moving code.
- Preserve existing branches, assets, prompts, storyboards and API contracts until reviewed.
- Treat all provider credentials as server-side secrets.
- Validate provider API versions, model availability, licensing/terms, request limits and actual costs.
- Model generation as an asynchronous state machine; distinguish queued, submitted, running, succeeded, failed, cancelled and unknown.
- A provider's accepted request is not proof that an output rendered, was stored, or can be retrieved.
- Persist job identifiers, provenance, provider/model version, prompt/parameters, timestamps, costs and output references where permitted.
- Use idempotency, safe retries, cancellation and bounded concurrency to prevent duplicate spend.
- Do not publish or incur material provider spend without required user/owner authorization.
- Protect generated media with authentication, authorization and storage access controls.
- Never claim a feature, integration or rendered asset is operational without current evidence.
- Code review does not authorize provider spend, publishing, merging or deployment.
