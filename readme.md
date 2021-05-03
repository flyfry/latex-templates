# LaTeX Templates

Templates for LaTeX to write the documents or the reports with ease.

## License

### 3EC-experiment-report/text/dummytext.tex, root.pdf

Copyright (C) 2021, flyfry.

**These files are not distributed under MIT license.**
DO NOT redistribute without permission.

### Other files

MIT license. See LICENSE file on this directory for details.

## Contents

### 3EC-experiment-report

For experiment report which taken in 3EC.

<!-- ### general-tdu-report

For the general report. (you can download the cover file at TDU website) -->

## Describes

This repository gives the templete files for LaTeX.
You must prepare cover file (which distributed from university) if required, and place the file properly position. (see file directories tree)

File directories tree:

```tree
.
├── 3EC-experiment-report
│   ├── cover
│   │   ├── cover.pdf         <= Dummy file
│   │   └── coverpage.tex
│   ├── images                <= Not included
│   ├── preemble.tex
│   ├── references_ja.bib
│   ├── root.pdf
│   ├── root.tex
│   ├── sections
│   │   ├── consideration.tex
│   │   ├── discussion.tex
│   │   ├── equipments.tex
│   │   ├── experiments.tex
│   │   └── introduction.tex
│   └── text
│       └── dummytext.tex     <= Not distributed under MIT license
├── LICENSE
└── readme.md
```

## Recommended environment

| Name       | Version                                | Note            |
| ---------- | -------------------------------------- | --------------- |
| `platex`   | `e-pTeX 3.141592653-p3.9.0-210218-2.6` | `TeX Live 2021` |
| `upbibtex` | `0.99d-j0.33-u1.27`                    | `TeX Live 2021` |

(Recommended: LaTeX Environment: `TeX Live 2021`.)
Otherwise, you might have to rewrite .tex file partially.
