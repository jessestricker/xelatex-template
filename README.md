# XeLaTeX-Template

This repository contains a general-purpose template for writing articles
with XeLaTeX.

## Compiling

The easiest way to compile the documents using this template is to run
_latexmk_. This requires an installed Perl distribution and the
[latexmk](https://www.ctan.org/pkg/latexmk).

```bash
latexmk --pdf --xelatex --outdir=out document.tex
```

The compiled document can then be found at `out/document.pdf`.

## Font

The body text and mathematical formulas are set in _Libertinus Serif_,
the headings and all other sans-serif text is set in _Libertinus Sans_.

The typewriter font used is _Fira Code_, which is especially nice for
typsetting source code because of its use of programming ligatures.

**Links:**

- [Libertinus](https://github.com/alif-type/libertinus)
- [Fira Code](https://github.com/tonsky/FiraCode)

## Dependencies

- [KOMA-Script](https://www.ctan.org/pkg/koma-script) –
  document class `scrartcl` for better page layout
- [babel](https://www.ctan.org/pkg/babel) –
  language support, translation of labels
- [csquotes](https://www.ctan.org/pkg/csquotes) –
  typographic correct quotations
- [hyperref](https://www.ctan.org/pkg/hyperref) –
  hyperlinks in PDF output, references with label
- [microtype](https://www.ctan.org/pkg/microtype) –
  improved typography system
- [mathtools](https://www.ctan.org/pkg/mathtools) –
  AMS math tools
- [fontspec](https://www.ctan.org/pkg/fontspec),
  [unicode-math](https://www.ctan.org/pkg/unicode-math) –
  font selecting in XeTeX
- [siunitx](https://www.ctan.org/pkg/siunitx) –
  typographic correct SI units & quantities
- [booktabs](https://www.ctan.org/pkg/booktabs),
  [tabularx](https://www.ctan.org/pkg/tabularx) –
  professional tables
- [biblatex](https://www.ctan.org/pkg/biblatex) –
  better bibliography
