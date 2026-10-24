# AI Evaluation Work Samples

**Brian Desmond Shaw | Self-directed, AI-assisted evaluation practice | Public case-study preview (v0.1, October 2026)**

This repository documents a small, source-grounded investigation of model-generated narration, instruction delivery, and the correction of an invalid trial. The objective is to make individual claims inspectable, including counterexamples, uncertainty and attribution—not to claim a validated model benchmark.

**Read first:** [Case 01 — Instruction delivery, source fidelity and evaluation adjudication](cases/01-instruction-delivery-and-adjudication/README.md).

## What is here

- [10 historically sourced review items](data/items.csv), each pointing to a limited [source/output evidence excerpt](evidence/excerpts/). These are *AI-curated candidate items*, not ten independent human labels.
- [Source-fidelity rubric v1.0](rubrics/source-fidelity-v1.md), with supported, contradicted, unsupported, observation-only, unscorable and excluded-invalid categories.
- [Record of a disclosed invalid input](evidence/correction-run13.md), and [correction history](corrections/CHANGELOG.md).
- [Blank first-pass annotation worksheet](data/author_review_template.csv), to be completed by Brian. A future release will preserve his personally recorded rationales separately from AI review.
- [Attribution](methods/attribution.md), [reproduction limits](methods/reproduction.md), and [privacy approach](methods/privacy.md).

## Why this is relevant to AI evaluation

The underlying historical exchanges include Brian reporting and correcting a wrong-source experimental run, initiating reruns, and challenging overbroad judgments: for example, absence of explicit AI self-identification is not the same as actively claiming to be human. These are **documented collaborative actions**, not proof of independent annotation accuracy or production evaluator performance.

The excerpts allow a reviewer to check concrete questions: When did a narration turn an unfinished option into a requirement? When did another output preserve the source's pending status? Did a chat instruction arrive in the subsequently recorded wording? The data deliberately contains both discrepancies and correct counterexamples.

## Authorship and scope

**Brian Desmond Shaw**: project direction; historically documented questions, corrections, selected experiments, tool use, and observations. **AI assistants**: substantial historical analysis, curation of these ten items, rubric design, document drafting, and this public package. **NotebookLM**: generated the historical narration transcripts. See [contribution detail](methods/attribution.md).

**Not claimed:** a model-compliance percentage, a controlled causal prompt experiment, an independently verified provider execution log, a peer-reviewed study, Brian-authored scores for these ten items, paid production annotations, or independently written programming code.

The original full creative manuscript, private conversation archive, private source records and original generated audio **are not published**. Public excerpts are limited and source-linked, but lack independent provider receipts. Transcription artifacts may remain.

## How to inspect the exhibits

Open [items.csv](data/items.csv), choose an item, read its linked excerpt, apply [the rubric](rubrics/source-fidelity-v1.md), and compare the response to the given source. [Reproduction notes](methods/reproduction.md) explain what can and cannot be checked from this derivative record.

**Next planned evidence:** Brian's personally documented short labels/rationales on these already-seen historical cases (disclosed as reannotation), followed by an unfamiliar, blinded pairwise-response exercise. See [Next steps](NEXT_STEPS.md).

**Professional links:** [LinkedIn](https://www.linkedin.com/in/bdesmondshaw/) · [GitHub](https://github.com/desmondoctavian).
