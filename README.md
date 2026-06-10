# Latex Template

This serves a general Latex template to easily start into whatever formal work needs to be written. :)

[Short subject description / summary]

---

## Overview

[General task details]

---

## Features

* [Features or whatsoever]

---

## Structure

<!-- STRUCTURE:START -->
```text
.
├── appendix
│   └── .gitkeep
├── chapter
│   ├── appendix.tex
│   ├── description.tex
│   └── introduction.tex
├── figures
│   └── .gitkeep
├── literature
│   └── literature.bib
├── pages
│   ├── acronyms.tex
│   └── cover.tex
├── Scripts
│   └── update-structure.ps1
├── .gitignore
├── LatexTemplate.tex
├── LICENSE
└── README.md
```
<!-- STRUCTURE:END -->

This section is generated automatically and reflects the current folder layout of the repository. You can update it by running `update-structure.ps1` in a PowerShell terminal:

```bash
.\Scripts\update-structure.ps1
```

---

## Building the Document

If the report is written in LaTeX, compile using:

```bash
pdflatex report.tex
```

Or use `latexmk` for automated compilation:

```bash
latexmk -pdf report.tex
```

If using Word or another editor, export the final version as PDF before submission.

---

## Project Goals

* **Goal**: [...]
* **Approach**: [...]
* **Deliverable**: [...]

Submission deadline: **[...]**

---

## Requirements

* [...]

---

## License

This repository contains academic work created for university purposes.
See the [LICENSE](LICENSE) file for details.