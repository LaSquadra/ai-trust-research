# Optional future validation
**Self-contained comparison specification. Unimplemented and unexecuted.** Execution would require a separately approved environment, scope and recovery plan. Hardware work is not required.

## Question
Does additional receiver evidence improve reconstruction, and does using that same evidence at runtime improve outcomes beyond unchanged local enforcement?

## Comparison arms
| Arm | Evidence and decision behavior | Purpose |
|---|---|---|
| A: controller records | Local controls plus the controller's own records; no added receiver-evidence reconciliation. | Baseline. |
| B: retrospective reconciliation | Same local controls, with added receiver evidence compared after execution. | Test visibility and reconstruction benefit over A. |
| C: runtime reconciliation | Same controls and evidence sources as B, but permitted runtime decisions use that evidence. | Test intervention benefit over B. |

Hold receiver enforcement, credential scope, workload and faults constant. Shared OS permissions versus enforced isolation are a separate factor applied identically across all arms. Hidden scoring truth means synthetic fixture facts available only to the evaluator; runtime decisions must not read them.

## Bounded cases
Reuse the investigation's existing case families: revoked authority with queued work, missing or delayed observations, and managed-tool versus direct-executable attempts. Include valid renewed authority, a committed effect with a lost receipt, and unrelated benign completion. Use synthetic credentials and effects. This public specification requires no private experiment identifiers or lab documents.

## Measures and falsifier
Measure prohibited/duplicate effects, useful completion, unnecessary restriction, unknown outcomes, restriction timing, reconstruction accuracy and sensitive bytes retained. Score credential-file access, credential use and receiver acceptance separately. Distinguish prevention, detection, containment and recovery.

If simpler receiver-local enforcement matches or beats these outcomes, reconciliation has not earned its complexity. Report null and negative results, source failures, attribution limits and cost. Publish the tested threat envelope rather than generalizing to production.

See the [worked example](WORKED-EXAMPLE.md). No execution is needed to close this research phase.
