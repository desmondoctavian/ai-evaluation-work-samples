# Reproduction, source records and limitations

## What a reviewer can reproduce now

1. Open any `evidence/excerpts/E*.md` file.
2. Compare the quoted source passages with quoted output passages at their listed original line numbers.
3. Use `rubrics/source-fidelity-v1.md` to classify that one claim and write a source-anchored rationale.
4. Contrast one failure with one local correct example (E02 vs E03; E01 vs E04).
5. Check the released excerpt files' SHA-256 digests in `manifests/SHA256SUMS`.

The digest identifies only the **public derivative excerpt files**, not their historical creation time or the authenticity of the original model's execution context.

## What cannot be replicated from this package

- The original model/backend, random state, prompt routing or complete notebook source inventory.
- The exact audio from transcript text, transcription accuracy, or product UI state.
- A causal effect of renaming an instruction file or changing tone: settings, prompts, source sets, time and stochastic variation were not all held constant.
- An accuracy rate or generalizable behavior estimate across a predefined sample.

## Source register (private originals withheld)

`S` = `NO_MORE_CONQUISTADORS_Complete_Governing_Master_v8.md`  
`R4`, `R5`, `R6`, `R7`, `R11`, `R12` = corresponding `nmcv8.nkotb*.2ND-RUN.md` transcript artifacts.  
`R13_bad` and `R13_fixed` are historically distinct. The first was invalid for the intended comparison.

An independent auditor can check **the frozen excerpts supplied here**; verifying them against the entire original archive would require separate authorized source access. The names and line references are descriptive audit locators, not external links to private files.
