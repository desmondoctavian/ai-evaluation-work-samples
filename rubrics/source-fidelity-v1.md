# Source Fidelity and Evaluation Adjudication — Rubric v1.0

**Purpose:** Review a particular generated claim or recorded process statement against the evidence shown. This is a portfolio work-sample rubric developed with AI assistance, not a Turing, Outlier, or other employer's proprietary rubric.

## Required first-pass workflow

1. Read the question and the relevant context in the excerpt.
2. Identify **exactly which assertion** is being reviewed; do not penalize unrelated stylistic preferences.
3. Select one `judgment` and record the citation/line span supporting it.
4. Assign severity only for a supported finding of error. Cite the *consequence*, not just a disliked word.
5. If the evidence is inconclusive, choose `UNSCORABLE` instead of manufacturing an error or success.

## Judgment values

| Value | Use when |
|---|---|
| `SUPPORTED` | The exact claim is consistent with and grounded by the supplied evidence, with material limitations noted. |
| `CONTRADICTED` | The supplied source affirmatively conflicts with the reviewed claim. |
| `UNSUPPORTED` | The claim adds unestablished information or an interpretation beyond the source; the source does not necessarily prove it false. |
| `OBSERVED_ONLY` | A process or surface-output fact is visible, but its cause/hidden implementation is not established. |
| `UNSCORABLE` | Missing or corrupted context prevents a justified determination. |
| `EXCLUDED_INVALID` | The underlying trial has a documented input/setup error disqualifying it from the intended comparison. Do not pool its result. |

## Severity values

`NONE` (supported or descriptive), `MINOR` (small added detail with limited impact), `MAJOR` (changes authorship, status, rule, chronology, or practical interpretation), `CRITICAL` (would materially invert an important decision or cause harmful action; do not assign speculatively), `NA` (unscorable/excluded).

## Special handling

- **Open vs. settled:** A proposed option is not mandatory merely because named in the source.
- **Inference vs. source statement:** An interesting interpretation may still be unsupported as a statement of what the source establishes.
- **Identity:** Not explicitly saying 'I am AI' does not by itself establish pretending to be human; look for an affirmative claim or a specific identity requirement.
- **Praise:** Positive language is not automatically unearned; judge the factual premise and stated rationale.
- **Visible UI vs. effective instructions:** A reported empty field or a chat acknowledgment cannot determine hidden model context or downstream compliance.
- **Self-description:** A model's first-person claim about training data, inner state or compute allocation needs evidence other than its assertion.
- **Verbatim source vs. transcript:** Preserve source spelling/transcription artifacts; do not silently repair quotes or infer spoken words from uncertain text.

## Assistance and revision controls

Brian's first-pass review should be recorded before consulting any AI critique **for this pass**, with previous historical exposure disclosed. An AI assistant may later challenge labels; preserve original labels, revisions, and reasons separately. These cases cannot be called blinded fresh work because earlier analysis already exists.
