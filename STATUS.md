# Status -- thomasson-kinds-projectibility

## Current state (2026-07-01)

Public repository is pushed and buildable at commit `a9150e0` (`Trim projectibility examples`). The paper is now posted as a PhilArchive preprint: `https://philarchive.org/rec/REYFWF`. It has a source-backed LaTeX/PDF draft with verified project-local bibliography entries, vendored central house-style/build files, and a CC BY 4.0 license. `make` succeeds with XeLaTeX/Biber.

The live framing is projectibility-first, not mechanism-first. Thomasson is treated as a close ally whose function-first conceptual engineering handles many standard cases. The residual disagreement is demotion discipline: once a field and projection are fixed, stable projection failure can defeat kind-standing even when the category remains useful.

Section 5 now uses `fish` as the worked cross-field foil, `jade` as a brief convergence/control case, and `definiteness` as the single-field separating case. `Weed` and the worked `platypus` example were removed from the section. The paper also now includes field-individuation and projective-success replies in section 6, splits the Thomasson citation bundle, adds the NDPR review sentence in section 3, and acknowledges Claude Opus 4.8 review ideas.

The uploadable PDF exists at `Reynolds-Thomasson-Kinds-Projectibility.pdf`; it is an untracked generated artifact copied from the current build. Recommended PhilPapers categories were Natural Kinds primary; Conceptual Engineering and Metaontology secondary; Scientific Practice optional.

## Next action

If sharing now, send Thomasson the pair of public links: the SFL review (`https://lingbuzz.net/lingbuzz/010101`, `https://philarchive.org/rec/REYAMS`) and this projectibility article (`https://philarchive.org/rec/REYFWF`). A later journal submission should get a fresh venue-specific check.

## Blockers

- Direct-send cover note still needs final approval.
- Future journal submission needs a fresh venue-specific check, especially if anonymous review or preprint policy matters.

## Decisions

See `DECISIONS.md`.

## Pending Brett

- Decision whether to send both public preprints to Thomasson now.
- Direct-send cover note.

### 2026-06-30 Session Notes

- Added an explicit definition of `function`: role in a practice, not causal mechanism, biological purpose, or syntactic slot.
- Added the field-relative ordinary-language objection: ordinary linguistic practice and hard metaphysics are both fields; ordinary use can discipline metaphysical practice only with field-relative justification.
- Added a compact proper-name/proper-noun example to show the semantic/syntactic level distinction without making the argument depend on SFL.
- Tightened terminology: avoid `class`, `classify`, and `classification`; prefer category/profile/kind-claim/projectibility vocabulary.
- Reframed SFL detachment as philosophical rather than mainly sociological: SFL may have independent merits, but Thomasson's metaphysical conclusion doesn't need its grammatical architecture.
- Added the race divergence case and a demotion rule: retention/usefulness can survive while kind-standing fails for a field-specific projection.
- Added verified central-bibliography citations to Lipski 2020 and Martinez 2017 to avoid making the Boyd/HPC contrast look like a mechanism-only straw target.
- Added a restrained rhetoric pass: category/profile/kind-claim parallelism, kitchen/cladogram line, vote/veto line, and risk conclusion.
- Verification: central house-style checker clean; `class/classify` guard clean; `git diff --check` clean; `make` succeeds with only standing fancyhdr/microtype warnings.
- Shipped public GitHub commit `f325759` (`Sharpen projectibility demotion argument`) to `master`.
- Post-ship review identified that `race` should stay, if at all, as Thomasson convergence rather than the divergence case.
- Post-ship review identified that Martinez 2017 should be treated as a grounding objection to Slater-style groundless SPC, not grouped with Lipski/Slater as pushing against mechanism/ground constraints.
- Candidate next divergence case: `jade`, contrasting lapidary/art-historical/market projections with mineralogical demotion into jadeite/nephrite profiles; Brett flagged that it may be too well worked.
- Remaining mechanical fixes before circulation: change `syntactic account of function` to `grammar-internal account of function`; fix the spaced Thomasson 2025 DOI in the rendered PDF.

### 2026-06-30 Session Notes (night)

- Rebuilt section 5 around the settled structure: standard cases don't separate the views; a separating case must hold the field fixed while coordination survives and the projection fails.
- Removed the section 5 worked `weed` and `platypus` examples; kept `fish` as the cross-field foil and `jade` as a brief convergence/control case.
- Adopted `definiteness` as the single-field separating case, with English nominal grammar using the category for both diagnostic coordination and a form--meaning projection.
- Added field-individuation language: fields are epistemically stabilized by shared questions, admissible evidence, defeaters, and repair moves.
- Added a section 6 reply explaining why projective success isn't reducible to successful conceptual functioning.
- Split the Thomasson citations for `jade`, `race`, and `fish`; added the NDPR review sentence; fixed the Martinez positioning; acknowledged Claude Opus 4.8 review ideas.
- Verification: `make` succeeds; `git diff --check` clean; no undefined citations/references or rerun warnings found; only standing fancyhdr/microtype warnings remain.
- Shipped public GitHub commit `a9150e0` (`Trim projectibility examples`) to `master`.
- Created uploadable PDF `Reynolds-Thomasson-Kinds-Projectibility.pdf`; it remains untracked as a generated upload artifact.
- Recommended PhilPapers categories: Natural Kinds primary; Conceptual Engineering and Metaontology secondary; Scientific Practice optional.

### 2026-07-01 Publication Update

- PhilArchive preprint is live: `https://philarchive.org/rec/REYFWF`.
- Portfolio, website publications page, CV source, central bibliography, and Thomasson people card were updated to include the preprint.
- Drafted direct-send cover note at `submission/email-to-thomasson-2026-07-01.md`.
