# Case 01 — Instruction delivery, source fidelity, and evaluator adjudication

**Status:** Public evidence preview; first-person item-level annotations remain pending.  
**Material:** Reported NotebookLM Audio Overview experiments using a historical *No More Conquistadors!* source document.  
**Scope:** Source-grounded output review and correction handling, **not** a validated comparison of prompt effectiveness.

## Question

When a model synthesizes material from multiple sources and instructions, can its narration accurately preserve what is finished, pending, inferred, or unsupported? How should an evaluator respond when an experimental input or the evaluator's own criterion proves wrong?

## Visible observations

- **Source-status handling:** Run 12 says some proposed stage mechanics remain in development but also says the document *insists* on particular mechanisms. The source says those very mechanisms **cannot be promoted to canon without a later ruling**. Compare [E02](../../evidence/excerpts/E02.md).
- **Correct counterexample:** Run 4 accurately states that the same mechanics are still pending a ruling. Compare [E03](../../evidence/excerpts/E03.md).
- **Unfounded explanation:** Run 11 reinterprets nine unwritten scene-connection briefs as deliberately preserving actors' freedom. The source describes them as work the author still needs to write. Compare [E01](../../evidence/excerpts/E01.md).
- **Correct counterexample:** Run 6 describes those briefs as parameters for scenes to be written later. Compare [E04](../../evidence/excerpts/E04.md).
- **Instruction and handoff observations:** The records show an instruction file being discussed in Run 11 and differences between recorded chat requests and subsequently reported populated instructions in Runs 5 and 6. Compare [E08](../../evidence/excerpts/E08.md), [E09](../../evidence/excerpts/E09.md), and [E10](../../evidence/excerpts/E10.md). These text records are **not provider-level proof** of effective hidden instructions.

## Corrections and adjudication

The [participant correction record](../../evidence/correction-run13.md) documents why the original Run 13 was invalid for its intended filename comparison. Brian explicitly reported that he had accidentally used the Run 11 transcript as its primary source rather than the NMC master; the original must remain excluded. A corrected replacement was later provided. The replacement cannot isolate a filename effect because it is a single output with incomplete generation receipts.

Historical conversations also record Brian challenging a broad criterion that interpreted failure to introduce oneself as AI as proof of *pretending to be human*. Silence about identity and affirmative false human representation are different outcomes. Similarly, praise cannot be classified as fabricated merely because it is enthusiastic: the evidence and reasoning must be considered. Those adjudication findings come from an AI-assisted audit and participant conversations; the present item-level worksheet does not purport to be Brian's fresh independent judgment.

## Inspectable case materials

- [Ten numbered evidence items](../../data/items.csv), each with exact file/line context.
- [Blank author annotation worksheet](../../data/author_review_template.csv).
- [Rubric v1](../../rubrics/source-fidelity-v1.md) with outcome categories and severity anchors.
- [Correction log](../../corrections/CHANGELOG.md) and [reproduction limits](../../methods/reproduction.md).

## What this does **not** prove

No general source-fidelity rate, controlled prompt-causation result, model-version finding, benchmarking across independent test sets, or independently observed UI/backend state. Earlier AI-generated interpretations should not be counted as Brian's own written analyses.

**Provisional public takeaway:** An evaluation should preserve the source's status and attribution, score precise claims rather than tone alone, include correct examples, and remove invalid trials rather than hiding or pooling them.
