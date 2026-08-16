# Contributing to RouteFoundry Technologies repositories

Thank you for helping improve RouteFoundry Technologies projects.

These are the organization-wide defaults. A repository may define stricter or project-specific requirements that take precedence.

## Before making changes

- Read the repository README, architecture notes and contribution guidance.
- Confirm there is an issue, task or agreed scope for non-trivial work.
- Keep changes focused. Avoid unrelated refactors in the same pull request.
- Never commit credentials, secrets, private customer information or production data.

## Branches

Create work on a dedicated branch from the repository's current default branch.

Use short, descriptive names such as:

- `feat/contact-workflow`
- `fix/deployment-timeout`
- `docs/security-boundary`
- `chore/dependency-maintenance`

Do not work directly on `main` unless a repository explicitly documents a different workflow.

## Commits

Write concise commit messages that describe the outcome of the change. Prefer conventional prefixes where they fit, including `feat:`, `fix:`, `docs:`, `test:`, `ci:`, `chore:` and `refactor:`.

Keep commits reviewable and do not rewrite shared history without agreement.

## Validation

Run the repository's documented checks before requesting review. This may include formatting, linting, type checks, tests, builds, security checks or deployment validation.

If a check cannot be run locally, say so clearly in the pull request and explain why.

## Pull requests

A pull request should:

- explain what changed and why;
- identify the relevant issue or work item where one exists;
- describe validation performed;
- call out security, privacy, data, migration or deployment impact;
- include screenshots or evidence when the user interface or production behaviour changes; and
- avoid combining unrelated work.

Do not merge with unresolved review findings unless the repository's owners have explicitly accepted the risk.

## Security and privacy

Treat customer data, credentials, secrets, access tokens, infrastructure details and non-public business information as confidential.

Do not open a public issue for a suspected vulnerability. Follow the instructions in `SECURITY.md` instead.

## Ownership and licensing

Contributing code does not by itself change the ownership or licensing terms of a repository. Contributors must comply with any applicable employment, contractor, contributor, confidentiality, intellectual-property or licensing agreements.

Do not introduce third-party code, assets or dependencies unless their licence and intended use are compatible with the repository.

## Questions

If a repository does not make the expected process clear, raise the question before implementing a broad or irreversible change.
