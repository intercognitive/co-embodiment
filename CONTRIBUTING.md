# Contributing

This repository is for public exploration of co-embodiment as a standards problem.

## What Belongs Here

Good contributions include:

- Focused problem statements
- Deployment evidence from real environments
- Use cases that expose interoperability gaps
- Terminology clarifications
- Working drafts for capability, permission, arbitration, or spatial context models
- Links to canonical implementations in member repositories
- Questions that need working-group discussion

Implementation-specific changes should go to the canonical implementation repository. For example, changes to the Auki SDK should be proposed in [`aukilabs/auki-sdk`](https://github.com/aukilabs/auki-sdk).

## Issue Types

Use issues to make work visible and actionable.

Suggested issue prefixes:

- `Question:` for unresolved conceptual or governance questions
- `Use case:` for a domain or deployment scenario
- `Draft:` for a proposed model, schema, or protocol sketch
- `Implementation:` for links to implementation trials or feedback from code
- `Terminology:` for glossary additions or refinements

## From Exploration to IOSP

This repository should not treat every idea as a standard.

The expected flow is:

```text
Discussion -> Issue -> Working draft -> Candidate IOSP -> implementation trial -> Accepted IOS
```

A working draft may become a candidate IOSP when it has:

- a clear interoperability problem,
- at least one champion,
- interested implementers,
- a proposed standard surface,
- documented safety, privacy, and security considerations,
- and enough discussion to show where the hard questions are.

The organization-level IOSP process is documented in [`intercognitive/.github`](https://github.com/intercognitive/.github/blob/main/CONTRIBUTING.md).

## Pull Requests

Pull requests should be focused and easy to review.

For documentation changes:

- Explain why the change is needed.
- Link related issues or discussions.
- Keep terminology consistent with `GLOSSARY.md`.
- Update the README or charter when contributor-facing process changes.
- Avoid presenting working drafts as accepted standards.

Commit messages should be clear and can use Conventional Commits:

```text
docs: add retail co-embodiment use case
docs: define embodied capability manifest
```

## AI Agents

AI agents may help draft and organize material, but should not resolve standards ambiguity on their own.

When in doubt:

- surface the ambiguity,
- propose a question or follow-up issue,
- and ask before advancing maturity stage, changing process, or creating claims of consensus.
