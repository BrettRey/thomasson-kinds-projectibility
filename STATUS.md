# Status -- thomasson-kinds-projectibility

## Current state (2026-06-30)

Public-ready draft repository. The paper now has a source-backed seven-page LaTeX draft, verified project-local bibliography entries, vendored central house-style/build files, and a CC BY 4.0 license. `make` succeeds with XeLaTeX/Biber.

The argument has been updated after intake of Thomasson 2014, Thomasson 2020, Thomasson 2025, Dupré 1993, and Magnus 2012. The live framing is projectibility-first, not HPC-first: Thomasson is treated as a close ally whose account does not engage the anti-essentialist realist projectibility tradition. The newer pressure point is field-relative: ordinary linguistic practice is itself a field, and metaphysics is another, so ordinary use is not automatically a neutral court over hard ontology.

## Next action

Develop the current draft into a full article. The next substantive expansion should strengthen the residual-disagreement section: distinguish Thomasson's internal questions about actual terms from external conceptual-engineering questions about what terms/concepts should be used. Then strengthen the omitted anti-essentialist realist tradition and projectibility-profile sections using Brett's recent kinds papers as the internal framework.

## Blockers

- Update the acknowledgements if later drafts use additional models or tools.
- Confirm absence claims against legitimate print indexes before submission.
- Re-check direct quotations against the PDFs before finalizing; current page anchors are draft anchors.

## Decisions

See `DECISIONS.md`.

## Pending Brett

- Confirm final working title and whether this should remain a full article or become a tighter critical note.
- Select target venue after the draft has enough shape for venue matching.
- Decide whether the ordinary-language-as-field objection should become the central framing or remain a pressure point inside the projectibility argument.

### 2026-06-30 Session Notes

- Added an explicit definition of `function`: role in a practice, not causal mechanism, biological purpose, or syntactic slot.
- Added the field-relative ordinary-language objection: ordinary linguistic practice and hard metaphysics are both fields; ordinary use can discipline metaphysical practice only with field-relative justification.
- Added a compact proper-name/proper-noun example to show the semantic/syntactic level distinction without making the argument depend on SFL.
- Tightened terminology: avoid `class`, `classify`, and `classification`; prefer category/profile/kind-claim/projectibility vocabulary.
- Reframed SFL detachment as philosophical rather than mainly sociological: SFL may have independent merits, but Thomasson's metaphysical conclusion doesn't need its grammatical architecture.
- Verification: central house-style checker clean; `class/classify` guard clean; `git diff --check` clean; `make` succeeds with only standing fancyhdr/microtype warnings.
