<!--
SPDX-FileCopyrightText: 2024 Johannes Keyser, Amalaswintha Leh

SPDX-License-Identifier: CC-BY-4.0
-->

# Vortragsfolien

Die Folien sind als Markdown-Datei definiert, siehe [slides.md](slides.md).

Um daraus eine PDF-Version zu erstellen, können Sie [Pandoc](https://pandoc.org/) benutzen:

```
pandoc -t beamer --pdf-engine=lualatex slides.md -o slides.pdf
```

_Tipp: Mit Pandoc-Argument `--incremental` werden die Punkte einer Folie auch einzeln aufdeckbar._
