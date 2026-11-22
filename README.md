# Workbook Builder

Turn a teacher's scaffolding document into a student workbook.

**Use it:** https://rakeshjivan.github.io/Workbook-Builder/

## How it works

1. Choose your scaffolding Word file (.docx), drop it on the page, or paste the text.
2. Each step and each numbered section becomes its own page: a heading, the instructions beside a pencil icon, a grey header bar, and a writing box for every bullet point.
   - "Identify at least two competitors" becomes a table with a row per competitor (plus an optional extra row).
   - An "Examples … may include:" list becomes a hint under the pencil.
   - Sections that don't fit on one page continue on the next.
3. Edit the wording in the text box on the left; the pages update as you type.
4. Download as **Word** (to edit further) or as a **fillable PDF** (students type straight into the boxes).

### Writing the scaffolding as text

```
# Step 1: Investigate the area
Research the location and identify:
- population characteristics
- transport access
```

`#` starts a heading (a step or section starts a new page), `-` is a point that becomes a box, and any other line is an instruction.

## Privacy

Everything happens in your browser. Documents are never uploaded anywhere.

## Built with

A single `index.html` file, plus [JSZip](https://stuk.github.io/jszip/) for Word files and [pdf-lib](https://pdf-lib.js.org/) for the fillable PDF, both loaded from public CDNs.
