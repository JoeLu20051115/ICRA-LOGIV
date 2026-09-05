# ICRA 2027 paper starter

This folder is prepared for an ICRA 2027 contributed-paper initial submission using the official PaperCept `ieeeconf` class and `IEEEtran` BibTeX style.

## Overleaf

1. Upload every file and the `figures` folder to a blank Overleaf project.
2. Set `main.tex` as the main document.
3. Select pdfLaTeX as the compiler and compile.

## Submission checks

- Keep the initial submission double-anonymous: remove names, affiliations, acknowledgments, grant numbers, and identifying self-references.
- Use US Letter, 10 pt, conference mode and do not change the class margins.
- The current ICRA 2027 initial-submission limit is eight pages total, including references.
- Recheck the official Call for Papers before submission: https://2027.ieee-icra.org/contribute/call-for-icra-2027-papers-now-accepting-submissions/

## Local compilation

```sh
latexmk -pdf main.tex
```
