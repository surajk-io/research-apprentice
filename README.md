# Research Apprentice

A prompts-only, experimental workflow for **rigorous research across disciplines while learning to think and work as an independent researcher**.

The AI does broad delegable work (retrieval, synthesis, verification, routine coding). The human retains consequential research decisions and practices learning-critical reasoning. We prioritize clear evidence and manageable conversational steps over maximal answer length.

## Start here

1. Put the text in [PROJECT_INSTRUCTIONS.md](PROJECT_INSTRUCTIONS.md) into a dedicated ChatGPT Project's instructions. Existing Project instructions should be replaced or reconciled, not left in conflict. Repository files do **not** automatically become active ChatGPT instructions.
2. Enable GitHub access or another way for the assistant to retrieve the live public repository. At each new research exercise, the assistant must read this README, the current [PROJECT_INSTRUCTIONS.md](PROJECT_INSTRUCTIONS.md), and the relevant [phase playbook](phases/) from the canonical repository; re-fetch the playbook when phases change. Do not maintain uploaded duplicates as authoritative methodology. If retrieval fails, the assistant must disclose the limitation and any fallback. Research evidence and project-specific materials can still be kept as project sources.
3. Start a chat with the concrete goal and boundaries. Example:

   > Use Research Apprentice. I need to understand the theory behind this exact question before attempting an answer myself. Provide minimum sufficient background; do not draft the answer. Stop after my independent attempt and your critique.

4. At any point, say **“consolidate”**, **“give me the evidence”**, **“I'm stuck”**, **“answer directly”**, or **“stop the exercise”**. These are controls, not tests of the human.

## Operating modes
Choose the allocation of reasoning separately from the research phase. The default is **collaborative research** (scientific output plus protected human reasoning); **learning** prioritizes human practice, and **delegated research** prioritizes an explicitly bounded deliverable. Ask explicitly before switching the overall objective. Routine direct answers and artifact requests are local delegation, not blanket mode changes. When deadlines threaten the learning objective, reduce scope or explicitly delegate; preserve skipped consequential reasoning as learning debt and offer a later evidence-first or fresh transfer exercise.

## What a normal reasoning loop looks like

**Problem → necessary definitions → relevant evidence → precise objective → human attempt → focused feedback → consolidate or continue.**

Not every reply needs all those headings. Background research may happen at great depth behind the scenes; the conversational foreground should be small.

## Research phases

1. [Orient](phases/01-orient.md): map the field, then inspect pivotal evidence.
2. [Form questions](phases/02-form-questions.md): identify an important, currently live uncertainty.
3. [Novelty kill](phases/03-novelty-kill.md): aggressively test whether the question has already been answered or weakened.
4. [Design experiment](phases/04-design-experiment.md): human attempts the causal design before AI critique.
5. [Interpret and update](phases/05-interpret-and-update.md): inspect results before constructing the explanation.

The phase playbooks are carried over from the existing Research Apprentice Project material; this repository adds a stricter **turn-level interaction protocol**.

AI safety is the first case study used to develop and test this workflow, not a limitation on its scope.

## Evidence and iteration

- [Pilot 1: reward-hacking environment design](pilots/2026-11-02-reward-hacking.md)
- [Sprint retrospective: AI × Epistemics](pilots/2026-11-16-ai-epistemics.md)
- **Status: v0.6.1 candidate protocol.** The pilot and subsequent feedback, including the AI × Epistemics sprint, informed the current instructions; they are not evidence of reliability or learning gains. v0.4 emphasizes conditional critique, symmetric scrutiny of AI reasoning, faithful interpretation of human claims, and explanatory depth without excessive information density. v0.5 adds epistemic independence, evidence-proportional revision, independent AI review, and caution about retrospective accounts of model reasoning. v0.6 adds explicit operating modes, deadline safeguards, lightweight reasoning provenance and recovery of missed learning, as well as stronger design/interpretation checkpoints. v0.6.1 compresses the embedded instructions below ChatGPT's character limit; detailed guidance remains in the playbooks. Test on more cases, record deviations, and revise.
- Preserve clear boundaries between observed evidence, research interpretation, speculation, and assistant-generated suggestions.

## What this is not

Not a software agent, automatic research pipeline, or rigid quiz tutor. Not a commitment to run an experiment just because a question is interesting. No claims that any single prompt can guarantee compliance.

## Ownership

The human chooses research areas, important uncertainties, experimental commitments, and what conclusions to accept. The AI may recommend and challenge, but must not silently take those decisions.
