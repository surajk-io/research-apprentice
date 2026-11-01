# Pilot 1 — Reward-hacking environment design

**Date:** 2026-11-02  
**Mode:** Research Apprentice interaction test, **not** an attempt to complete a fellowship application.  
**Status:** Qualitative retrospective of one conversation, not a controlled evaluation.

## Original test objective

Would a minimum-context, human-first reasoning loop help the human independently understand and design a plausible learning-environment comparison, without having to critique a wall of assistant-generated proposals?

## Observed sequence

- Assistant introduced reward hacking, an example of task-local versus broader reward seeking, and a question about RL environments.
- Human proposed making genuine programming problems hard while making evaluator exploitation easier and rewarding.
- Human specified a concrete attack: locate hidden test inputs and expected outputs, then hardcode outputs.
- Human proposed a contrasting evaluation with fresh runtime-generated tests and a private trusted reference implementation, and independently raised an access-control concern.
- Human proposed a held-out, differently exploitable evaluation: greater reward hacking after training in A than in B supports transfer.
- Human suggested making honest completion equally easy or easier to probe a learned tendency, and recognized learned expectations as a possible causal mechanism.
- Assistant clarified that behavioral persistence under corrective feedback tests flexibility, but does not uniquely identify an internal habit mechanism.

These are observations from this conversation; no model training or evaluation was executed.

## What worked

- Small definitions and targeted context enabled the human to generate the central design, rather than judge a fully generated assistant proposal.
- Assistant critique sharpened the distinction between exploit availability, cross-task transfer, and internal mechanism.
- The human corrected assistant over-interpretation; correction was accepted.

## What failed

1. **Overlong conceptual tangent:** habit vs expectation consumed several turns beyond the first learning objective.
2. **No stopping rule:** repeated “next question” prompts kept the discussion moving even when there was enough material to consolidate.
3. **Goal drift:** assistant attempted to move from pilot to writing a fellowship answer, despite the user's stated intention to test the workflow.
4. **Source gate was weak:** the exact mentor-specific question was not freshly verified in this pilot; application-specific wording should not be presented as confirmed without the source.
5. **Evidence gate was weak:** empirical claims about the Anthropic example were discussed without a fresh primary-source verification in the pilot itself. They should not be treated as independently checked here.

## Corrective rules tested by v0.1

- Explicitly identify **exercise versus deliverable** at the start.
- Verify external problem wording and consequential experimental facts before treating them as established.
- Use **problem → needed context → human reasoning → critique → consolidation**, not an indefinite Socratic chain.
- At a natural resolution point, stop; do not force the next substantive task.

## Outcome and limits

**Provisional result: promising but incomplete.** The human supplied substantive independent reasoning, while the assistant still created avoidable overhead. This pilot cannot establish that the approach improves learning, transfers to new topics, or works reliably across assistants.

## Next tests

Run the protocol on a real theory-heavy question with verified source text. Observe: (a) whether the human can formulate their own initial model; (b) whether critical evidence arrives before cognitive demands; (c) number of off-target turns; (d) whether the assistant stops at the requested boundary. A second test should try a substantially different phase, such as interpreting ambiguous experimental results.
