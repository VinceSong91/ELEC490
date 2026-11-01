# ASCC Blueprint — Blank LaTeX Template

This is a clean writing template in the original proposal formatting. Previous report prose, tables, figures and citations have been removed from the report sections. The title page retains your group metadata and logo; edit `metadata.tex` to change them.

All sections have headings and LaTeX `%` comments with rubric-based writing prompts. Comments do not appear in the PDF. Write below the comments in `sections/*.tex`.

## Build

```bash
chmod +x build.sh
./build.sh
```

The rubric allows **10 pages maximum from Introduction through Conclusion**, excluding front matter, references and appendices. It calls for 12pt text, 1.5 spacing, IEEE citations, a project logo, more than eight milestones and at least five tests in the body.

To cite sources, add verified entries to `references.bib` and uncomment `\printbibliography[heading=none]` in `sections/12-references.tex`.
