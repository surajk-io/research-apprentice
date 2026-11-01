# Research Apprentice

A prompts-only, experimental workflow for **real AI-safety research and learning to do research**.

The AI does broad delegable work (retrieval, synthesis, verification, routine coding). The human retains consequential research decisions and practices learning-critical reasoning. We prioritize clear evidence and manageable conversational steps over maximal answer length.

## Start here

1. Put the text in [PROJECT_INSTRUCTIONS.md](PROJECT_INSTRUCTIONS.md) into a dedicated ChatGPT Project's instructions. Existing Project instructions should be replaced or reconciled, not left in conflict. Repository files do **not** automatically become active ChatGPT instructions.
2. Make the [phase playbooks](phases/) available to the assistant (as project files, connected GitHub files, or pasted context) when that phase is relevant.
3. Start a chat with the concrete goal and boundaries. Example:

   > Use Research Apprentice. I need to understand the theory behind this exact question before attempting an answer myself. Provide minimum sufficient background; do not draft the answer. Stop after my independent attempt and your critique.

4. At any point, say **“consolidate”**, **“give me the evidence”**, **“I'm stuck”**, **“answer directly”**, or **“stop the exercise”**. These are controls, not tests of the human.

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

## Evidence and iteration

- [Pilot 1: reward-hacking environment design](pilots/2026-11-02-reward-hacking.md)
- **Status: v0.1 candidate protocol.** One productive interaction is not evidence of reliability or learning gains. Test on more cases, record deviations, and revise.
- Preserve clear boundaries between observed evidence, research interpretation, speculation, and assistant-generated suggestions.

## What this is not

Not a software agent, automatic research pipeline, or rigid quiz tutor. Not a commitment to run an experiment just because a question is interesting. No claims that any single prompt can guarantee compliance.

## Ownership

The human chooses research areas, important uncertainties, experimental commitments, and what conclusions to accept. The AI may recommend and challenge, but must not silently take those decisions.
