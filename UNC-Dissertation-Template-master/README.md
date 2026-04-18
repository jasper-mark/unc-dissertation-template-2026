# UNC Dissertation Template (Updated for 2026)

This repository is a heavily updated version of [Björn B. Brandenburg](https://people.mpi-sws.org/~bbb/)'s UNC dissertation [LaTeX template](https://www.cs.unc.edu/~bbb/), with prior contributions from [Chelsea Estancona](https://clestancona.wixsite.com/chelseaestancona).

This version has been significantly revised and was successfully used for dissertation submission and approval at UNC in **2026** using **AMA citation style (biblatex)**.

---

## Overview

UNC dissertation formatting requirements evolve frequently, and official documentation can be ambiguous in practice. This template reflects a **working, approved implementation** that satisfies current Graduate School formatting expectations as of 2026.

It is intended to serve as a **practical, reproducible starting point** rather than a rigid standard. If you use this template, you are strongly encouraged to verify requirements with the Graduate School and adapt as needed.

---

## Key Updates (2026 Version)

### Formatting & Layout
- Standardized font sizes across:
  - Title page
  - Chapter titles
  - Section and subsection headers
- Chapter number and title placed on the **same line**
- Centered Table of Contents heading
- Appendix titles adjusted to maintain **1" top margin compliance**
- Footnotes set to be slightly smaller but still readable (no extreme scaling)
- Improved spacing and consistency across front matter and chapters

---

### Bibliography & Citations
- Migrated fully to **`biblatex` with AMA style**
  ```latex
  \usepackage[citestyle=ama, bibstyle=ama]{biblatex}
- Improved handling of long references to prevent overfull lines
- Cleaner integration with dissertation formatting requirements

### Glossaries & Acronyms
- Integrated glossary support using:
  ```latex
  \usepackage[acronym,nonumberlist]{glossaries}
- Added optional hover tooltips in PDF (Adobe Acrobat) for acronym expansion
- Supports first-use expansion + subsequent abbreviation automatically

### Codebase Cleanup
- Removed legacy / domain-specific macros from original template
- Removed unused or redundant packages
- Simplified and reorganized preamble for stability and readability
- Improved compatibility with modern LaTeX distributions

## Additional Features

- Support for:
  - Supplementary figures (`supfigure`)
  - Algorithm environments (`algorithm2e`)
  - Flexible tables (`tabularx`)
- Optional layout grid for debugging margins
- Commenting utilities for drafting and revision
- Modular structure (`frontmatter/`, `common/`, chapter files, appendices)

---

## Notes for Users

- Some formatting in this template is intentionally fixed to comply with UNC requirements. It is recommended to preserve core layout structure unless you are confident in the changes.
- Always verify your final PDF against current Graduate School guidelines, as requirements may change.
- This template assumes use of a modern LaTeX distribution and compilation with `biber`.

---

## Contributing

If you successfully use this template for a future submission:
- Consider forking and updating
- Submit a pull request with any fixes or improvements
- Share formatting changes required by the Graduate School

This repository is intended to remain a living resource for UNC PhD students.

---

## Final Note

If you’re using this template, you’re likely close to finishing your dissertation.

It may not feel like it—but you are.