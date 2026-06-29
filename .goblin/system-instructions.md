# Laitto Spec Executor Instructions

These instructions apply when implementing work in `anttileppa/laitto-spec`.

## Source Of Truth Rule

- `swagger.yaml` is the source of truth for shared REST contract changes.
- Keep changes tightly scoped and backward-compatibility conscious unless the issue explicitly calls for breaking change work.

## Validation

- Ensure the OpenAPI document remains syntactically valid.

## Escalate When

- The contract change is underspecified across backend and clients.
- The issue requires broad migration planning across multiple repositories.

## PR Expectations

- Open a draft PR.
- Include `Part of anttileppa/laitto#<issue-number>` in the PR body.
- Call out downstream regeneration expectations for backend, UI, and mobile.