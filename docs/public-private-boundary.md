# Public/private boundary

This repository is intentionally limited to public documentation. Every contribution must be understandable and useful without exposing private implementation material.

## Suitable for publication

- high-level concepts and terminology
- role responsibilities and decision rights
- generic task, report, and review templates
- abstract control-flow diagrams
- public citation and license metadata
- neutral, non-sensitive illustrative examples

## Must remain private

- exact private or production prompts
- detailed automation rules and production playbooks
- customer-, employee-, or partner-specific workflows or data
- hidden scoring, ranking, or decision logic
- credentials, secrets, tokens, private keys, or access details
- private configuration, internal paths, endpoints, or infrastructure topology
- operational deployment, incident-response, or bypass instructions
- material whose publication is restricted by law, contract, policy, or confidentiality

## Publication test

Before adding content, ask:

1. Does it reveal how to reconstruct a private implementation?
2. Does it expose a real organization, person, system, customer, or control value?
3. Does it turn a conceptual explanation into an operational playbook?
4. Is its ownership, permission, or publication status uncertain?

If any answer is yes or uncertain, stop. Omit the detail, replace it with an abstract description, or request human review outside the public repository.

## Safe abstraction

Describe the responsibility rather than the private prompt, the decision point rather than hidden scoring logic, and the class of control rather than its production configuration. Redaction alone is insufficient when surrounding details can reconstruct sensitive information.

This boundary applies to source files, examples, issue text, pull requests, commit messages, and repository history.
