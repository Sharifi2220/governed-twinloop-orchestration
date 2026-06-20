# Concept overview

Governed TwinLoop Orchestration is a local-first pattern for using AI agents while preserving explicit human authority. It separates bounded execution from governance so that progress occurs through visible assignments, reports, review decisions, and approved records.

## Core principles

1. **Human authority:** A human defines the objective, acceptable boundary, publication scope, and final disposition.
2. **Strategic clarification:** Strategic support helps clarify goals, architecture, risks, and decisions before or after execution.
3. **Bounded execution:** A worker receives a narrow task with allowed resources, prohibited content, expected output, and stop conditions.
4. **Mandatory reporting:** The worker returns evidence, uncertainties, and a recommendation instead of silently expanding its task.
5. **Independent review:** A supervisor evaluates the report, local evidence, and applicable gates before continuation.
6. **Controlled continuation:** Another execution cycle begins only after a governance decision permits it.
7. **Reviewed external state:** External repositories or publication channels contain only reviewed and approved snapshots.

## Intended value

The pattern makes delegated work easier to inspect, interrupt, and explain. It helps expose scope drift, missing access, uncertain claims, boundary violations, and premature external publication before they become downstream actions.

## Limits

This is a conceptual governance pattern, not a guarantee of safety or correctness. It does not replace legal, security, privacy, domain, or organizational review. This repository neither supplies an implementation nor prescribes an operational deployment.

Continue with the [two-loop architecture](two-loop-architecture.md), [role model](role-model.md), and [safety and stop gates](safety-and-stop-gates.md).
