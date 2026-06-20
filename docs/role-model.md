# Role model

The pattern defines logical responsibilities, not particular products, identities, or technical privileges. One person or system may support more than one role, but execution and approval should remain visibly distinct.

## Human authority

The human authority owns the purpose, risk posture, and final decision. This role sets scope, resolves escalations, approves external publication, and may stop work at any time. Accountability is not delegated to an agent.

## Strategic support

A strategic support function helps clarify objectives, structure decisions, assess risks, and review whether the documented model remains coherent. It does not replace the human authority and does not authorize execution on its own.

## Operational supervisor

The operational supervisor translates human intent into bounded tasks, checks worker reports, reviews local evidence, and recommends or records an outcome: approve, revise, or stop. The supervisor must not treat missing evidence as successful completion and must return consequential or unclear decisions to human authority.

## Bounded worker

The bounded worker acts only within the assigned task card. It records what it did, distinguishes created output from drafts or proposals, and stops when a prerequisite or gate is reached. It may recommend a next step but does not authorize continuation, publication, merge, or release.

## Repository and record roles

The primary work area may be local. Local version control supports traceability, comparison, and rollback. A public or external repository should contain only reviewed and approved snapshots, not unchecked experiments, private implementation logic, secrets, or internal working material.

## Illustrative working model

In one possible tool-assisted workflow, **Hermes** may serve as the operational supervisor while **Codex** serves as the bounded local worker. These are illustrative role assignments, not requirements or claims of a guaranteed technical connection. If direct tool integration is unavailable, a human may transfer a task card and return the worker report for review.

## Separation rule

A worker report is evidence for review, not approval. A supervisor recommendation is not automatic authorization. The human authority retains the right to accept, revise, reject, publish, withhold, or terminate the work.
