# Paper Submission Checklist

Completed from `Project-Management/templates/paper-submission-checklist.md`.

Status: **MANUSCRIPT READY; POST/SEND PENDING**. The manuscript, citation, style, build, and PDF gates pass for public circulation. No PhilPapers posting and no direct send to Amie Thomasson has been made. Final PhilPapers account/portal confirmation still has to happen in Brett's browser.

## Review Resolution


- [x] Roughdraft note incorporated: the current route is PhilPapers plus a direct send to Thomasson herself.

- [x] This checklist is being used as a release gate and record, not as a request for prose approval.

- [x] Remaining stop conditions narrowed to Brett's final approval, PhilPapers account/portal confirmation, and any email action that requires Brett's address book.

## Submission Record


- [x] Project: `thomasson-kinds-projectibility`.

- [x] Submission type: public manuscript circulation.

- [x] Targets: PhilPapers item posting and direct scholarly send to Amie Thomasson.

- [x] PhilPapers target URL recorded: `https://philpapers.org/help/submit.html`.

- [ ] PhilPapers portal/policy confirmation: command-line access hit Cloudflare, so this has to be confirmed through Brett's normal browser/account before posting.

- [x] Canonical source file: `main.tex`.

- [x] Canonical PDF: `main.pdf`.

- [x] Public repository: `https://github.com/BrettRey/thomasson-kinds-projectibility`.

- [x] License: CC BY 4.0 in `LICENSE`; repository status records the same.

- [x] Supplement/data package: none.

- [ ] Exact posted/sent archive path: not created because no posting/sending has happened.

- [x] Date checked: 2026-06-30.

- [x] Agent/model assisting: OpenAI Codex (GPT-5).

## 1. Submission Decision


- [x] Target fit provisionally checked for public philosophy-paper circulation.

- [x] PhilPapers route is public and non-blind; the current PDF fits that route.

- [ ] PhilPapers current portal instructions and subject categories still need in-browser confirmation.

- [x] Direct send to Thomasson is scholarly correspondence, not journal submission.

- [x] Prior related work noted: sister SFL paper cited as `reynolds2026thomassonSFLReview`.

- [x] Coauthors/collaborators: not applicable; sole-authored manuscript.

- [x] Blind-review constraints: not applicable to this PhilPapers/direct-send route.

- [ ] Future journal policy not checked; public posting may matter if the paper is later submitted to an anonymous or preprint-restricted venue.

- [ ] Direct recipient address and final cover note not verified in this checklist.

## 2. Objection And Source Gate


- [x] Major model-review points triaged in `notes/revision-intake-plan.md` and converted into edits, adapted decisions, or rejected decisions.

- [x] Opus 4.8 review triaged in `notes/opus-4.8-revision-plan.md` and converted into targeted edits.

- [x] GPT-Pro rhetoric review triaged in `notes/gpt-pro-rhetoric-pass-plan.md` and converted into restrained prose edits.

- [x] Level pass saved as `notes/full-level-pass.md`.

- [x] Metaphor audit saved as `notes/metaphor-audit.md`.

- [x] Source verification notes exist in `notes/source-verification.md`.

- [x] Two citations were added after the checklist pass: Lipski 2020 and Martinez 2017; both were already present in the central bibliography and DOI links were checked.

- [x] Citation-key validation passed after revision: 16 cited keys, 0 missing.

- [x] No unresolved placeholders found in `main.tex`, project metadata, or submission-relevant notes.

- [x] Projectibility audit complete:
  - Framing: GREEN. Abstract and introduction state projectibility-first realism as adding graded support, failure conditions, and demotion rules.
  - Profile definition: GREEN. Section 5 distinguishes category, profile, and kind claim before examples.
  - Mechanism handling: GREEN. Boyd/HPC paragraph says mechanisms are one source of support, not the kindhood criterion.
  - Examples: GREEN. `weed`, `fish`, `platypus`, and species examples cash out in projections and demotion.
  - Positioning: GREEN. Boyd is introduced as closest realist ally, then narrowed so projectibility isn't reduced to HPC.
  - Conclusion: GREEN. Final paragraph cashes out the account in defeasible expectations, failures, and tests.

Overall: projectibility is structural, not decorative.

## 3. Manuscript Content Gate


- [x] Title, abstract, keywords, and conclusion match the actual contribution.

- [x] Introduction states the problem and claim type.

- [x] Final section stays within the body's argument.

- [x] Content objections from the latest review were adopted, adapted, or rejected.

- [x] Presentation pass complete for redundancy, framing, title pressure, abstract, transitions, and conclusion.

- [x] Level/category audit complete; the four levels are named and mapped to sections.

- [x] Terminological hygiene audit complete; no `class/classify/classification`, `HPC`, `deep structure`, `contested`, or `specialized` drift found in `main.tex`.

- [x] Review-board/model-review usage converted into concrete edits or explicit decisions.

- [x] Rhetorical framing checked; the governing frame is field/jurisdiction/testing rather than combat.

- [x] Metaphor audit complete and saved.

- [x] Humour/wit: restrained; one dry `fish`/cladogram line retained because it compresses the field-relativity point.

- [x] Brett-preferences pass complete: concrete examples retained, direct contrasts preserved, AI-tic scan passed via central style guard and manual review.

- [x] Local preference promoted: `support grades` changed to `graded support`; introductory field definition tightened.

- [x] No unresolved placeholders remain.

- [x] Figures/tables/appendices/supplements: not applicable.

- [x] Data/code/ethics/REB/funding/competing interests: not applicable for current philosophy paper; acknowledgements and AI-use disclosure are present.

- [x] AI-use disclosure is present and names OpenAI Codex (GPT-5).

## 4. Blind Review And Metadata Gate

Current PDF is **not anonymous**, which is correct for PhilPapers and direct send.


- [x] Author, affiliation, ORCID, contact, acknowledgements, and PDF author metadata are present.

- [x] PDF metadata checked: title, keywords, and author are present; page count is 8.

- [x] DOCX metadata: not applicable; no DOCX produced.

- [ ] Reviewer-facing anonymized files aren't prepared; prepare a separate copy only if a later journal target needs anonymous review.

- [ ] Portal-generated reviewer PDF: not applicable.

- [ ] Separate title page/cover letter/declarations: not applicable for current route.

## 5. Build And File Gate


- [x] Central house-style scan passed on `main.tex`.

- [x] Paragraph-length guard passed: no body paragraphs over 100 words.

- [x] Level/category, terminological-hygiene, metaphor-frame, and projectibility checks complete.

- [x] `git diff --check` passed after checklist cleanup.

- [x] Full XeLaTeX/Biber build passed: `xelatex -interaction=nonstopmode -halt-on-error -output-directory=. main.tex && biber main && xelatex -interaction=nonstopmode -halt-on-error -output-directory=. main.tex && xelatex -interaction=nonstopmode -halt-on-error -output-directory=. main.tex`.

- [x] Quick XeLaTeX rebuild passed after final copy-paste cleanup.

- [x] Build log scanned: no unresolved citations, unresolved references, missing files, font errors, severe overfull boxes, or package errors.

- [x] Standing warnings only: fancyhdr head-height / one-sided header warnings and microtype footnote patch warning.

- [x] `pdftotext` spot check passed: title, author, abstract, examples, headings, and references extract sensibly.

- [x] Named spacing defects checked and absent: `readingwould`, `platypusexample`, `theworld`, `usestableto`, `R.A.Wilson`, `Newinterdisciplinary`, `Khalidi,M. A.`, bad Thomasson DOI spacing, `support grades`, `HPC`.

- [x] `pdfinfo` checked: 8 pages; title, keywords, and author metadata present; not encrypted.

- [x] PDF visually spot-checked: page 1 and references/final page rendered correctly.

- [x] Source package: not required for current PhilPapers/direct-send route.

- [x] Standalone bibliography is present as `references.bib` plus project-local `references-local.bib`.

- [ ] If any source package is uploaded later, exclude private notes, review simulations, local paths, and session artifacts.

## 6. Preprint-Specific Gate


- [x] Preprint route: PhilPapers public item posting.

- [ ] PhilPapers current portal rules and category fields require in-browser confirmation before posting.

- [x] Current PDF is public/non-blind and suitable in form for a public preprint route.

- [x] Title, author metadata, abstract, keywords, and acknowledgements are present in the PDF.

- [x] License is available at repository level as CC BY 4.0.

- [x] Coauthor/collaborator approval: not applicable.

- [x] Uploaded PDF candidate would be `main.pdf`.

- [ ] Subject categories and any PhilPapers portal fields still require Brett/account selection.

- [ ] Posting confirmation/URL not available because no posting has happened.

## 7. Direct-Send Gate


- [x] Exact attachment candidate: `main.pdf`.

- [x] Direct-send route is non-blind and can use the public PDF.

- [ ] Recipient address not verified in this checklist.

- [ ] Cover note not drafted in this checklist.

- [ ] Send confirmation not available because no email has been sent.

## 8. Journal-Specific Gate

Not applicable to the current route.


- [ ] No current journal instructions checked.

- [ ] No article type, word limit, abstract limit, reference style, or portal file role checked.

- [ ] No cover letter, title page, declarations, reviewer suggestions, or portal preview prepared.

- [ ] Future journal submission should start from a fresh target-specific check.

## 9. Final Submit/Post Gate


- [x] Exact PDF candidate opened/visually checked: `main.pdf`.

- [x] Exact public source of truth identified: public GitHub repository plus `main.pdf`.

- [ ] PhilPapers portal fields not entered.

- [ ] Direct-send email not prepared or sent.

- [ ] Brett final approval to post/send: not recorded.

## 10. After Posting Or Sending

Not applicable yet. No posting or direct send was made.


- [ ] Save PhilPapers item URL.

- [ ] Save sent-email record or exact sent attachment path.

- [ ] Archive exact posted/sent PDF.

- [ ] Update `STATUS.md`.

- [ ] Update `DECISIONS.md` if the PhilPapers/direct-send route becomes the source-of-truth circulation decision.

- [ ] Update portfolio/CV/website/status surfaces if a public URL is created.

- [ ] Commit and push after Brett asks to ship this checklist/update.

- [ ] Record any divergence between posted version and working version if later edits continue.

## Stop Conditions

Active before any post/send:


- [x] Brett final approval to post/send isn't recorded.

- [x] PhilPapers portal rules, subject categories, and fields require Brett/account confirmation.

- [x] Direct recipient address and cover note aren't verified.

Inactive for current route:


- [x] Coauthor/collaborator approval missing: not applicable.

- [x] Required ethics/REB status missing: not applicable.

- [x] Source carrying a central claim not checked: no current unresolved source-check flag.

- [x] Level/category or terminology drift remains: no.

- [x] Governing metaphor imports unwanted entailment: no.

- [x] Unresolved placeholders, citation gaps, or unverified claims remain: no current flag.

- [x] Build/log/PDF extraction failure: no.

- [x] Reviewer-facing file leaks identity in blind submission: not relevant to PhilPapers/direct send.

- [x] Public preprint file accidentally anonymous/local-only/missing acknowledgements: no.

- [x] Source ZIP contains private notes/correspondence/review simulations/local paths: source ZIP not being uploaded.

- [x] LLM reviewer-prompt sanitizing changed subject matter: no current flag.
