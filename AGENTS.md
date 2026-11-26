# AAAI-27 paper

Project directory: `/Users/stef/Local documents/Thesis into paper/phalcon_paper`.

GitHub repository: https://github.com/StefRasing/phalcon_paper. The user uses this repository to sync with Overleaf.

## Chat titles

On the first turn in a fork, rename the current chat as soon as its scope is known. Use the Codex `set_thread_title` action with the current chat as the target. If the scope changes, update the title.

- Paper-wide work uses `0 Topic`, for example `0 Paper Planning`.
- Work on a chapter or paper section uses its index in the agreed outline followed by its name, for example `2 Methods`. Use that index even if the PDF hides section numbers. If the index has yet to be agreed, wait to assign it. These examples are title formats, not an outline.

## Files and builds

- The user handles Git pushes manually when ready to sync with Overleaf. Do not push unless the user explicitly requests it.
- After making manuscript changes, or when the user asks to review changes they made, compile the complete paper locally and provide a link to the refreshed PDF. Fix compilation errors caused by your changes before handing over the result. Report any remaining build failure clearly.
- Edit `paper.tex` and add citations to `references.bib`. The manuscript uses the local AAAI 2027 style and anonymous submission mode. Use `../Template/AnonymousSubmission2027.tex` and `../Template/CameraReady2027.tex` as reference copies of the author guidelines.
- Compile from the repository root with `latexmk -pdf -interaction=nonstopmode -halt-on-error -outdir="<build directory>" paper.tex`. The local TeX installation is under `/Library/TeX/texbin`. After a successful build, copy `paper.pdf` to `../output/pdf/paper.pdf` for review. For review comments, identify the PDF page and the matching source passage.
- Same-directory forks share the same manuscript files. Keep chapter edits scoped to the assigned section and preserve changes from other chats.

## Submission rules

- AAAI-27 Main Technical Track allows up to 7 pages of content and 9 pages total. Pages 8–9 are reserved for references. Figures, tables, ethics statements, and any appendix in the main PDF count within the 7 content pages.
- An optional technical appendix can be uploaded as a separate supplementary PDF outside the main paper's page limit. The supplementary instructions list no page cap. Include essential methods, evidence, and proof ideas in the main paper because reviewers may skip the supplement.
- For anonymous review, omit author names, affiliations, acknowledgements, and identifying information in supplementary material. Keep the AAAI two-column US Letter format, the template package and font settings, and the AAAI BibTeX style. Consult the original author kit before adding packages or changing layout.
- Camera-ready publication has a separate allowance. The standard allocation is 7 content pages plus up to 2 pages for acknowledgements and references. AAAI lists an option to purchase up to 2 additional technical pages.

Use this summary for routine writing. Consult the official pages when an edge case or a change of track or submission stage matters.

- [Submission instructions](https://aaai.org/conference/aaai/aaai-27/submission-instructions/)
- [Supplementary material](https://aaai.org/conference/aaai/aaai-27/supplementary-material/)
- [Camera-ready publication](https://aaai.org/conference/aaai/aaai-27/paper-publication-and-conference-attendance/)
