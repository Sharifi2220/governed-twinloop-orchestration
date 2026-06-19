# Safety and stop gates

A stop gate is a condition that returns control to human governance. It prevents the worker from resolving material uncertainty by guessing or silently broadening its authority.

## Common stop gates

Stop and report when:

- private prompts, secrets, credentials, personal data, or restricted material would be exposed;
- required access or evidence is unavailable;
- the requested action exceeds the allowed files, systems, or objective;
- a legal, licensing, privacy, security, or safety uncertainty requires qualified judgment;
- a claim cannot be verified and would be misleading if stated as fact;
- instructions conflict or the intended target is ambiguous in a consequential way;
- execution would require an unapproved merge, publication, release, deployment, or external message;
- continuing would cross the [public/private boundary](public-private-boundary.md).

## Stop response

1. Stop before the gated action.
2. Preserve safe evidence without exposing restricted content.
3. State what was completed and what was not.
4. Identify the gate and the decision or access needed.
5. Return control to the supervisor or human authority.

## Gate design

Gates should be explicit, observable, and tied to a decision owner. They should not reveal private control thresholds or hidden scoring logic in public documentation.

Stopping is a valid governed outcome, not a failed execution loop.
