# Thesis

## Setup

### Latex

#### Ubuntu (<= 18.10)

```bash
sudo apt update
sudo apt install texlive texlive-latex-extra texlive-bibtex-extra texlive-lang-german texlive-plain-generic texlive-font-utils texlive-science latexmk
```

#### Ubuntu (>= 19.04)

```bash
$ apt update
$ apt install texlive texlive-latex-extra texlive-lang-german texlive-generic-extra texlive-bibtex-extra latexmk
```

## Build

### BASH / Ubuntu Server

```bash
$ latexmk document.tex -interaction=nonstopmode -file-line-error -pdf
```