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
$ apt install texlive texlive-latex-extra texlive-lang-german texlive-plain-generic texlive-bibtex-extra latexmk
```

## Build

### BASH / Ubuntu Server

```bash
$ latexmk document.tex -interaction=nonstopmode -file-line-error -pdf
```

## Structure

1. Einleitung
1. Datenbanken
    1. Relationale Datenbanken
    1. Dokumentdatenbanken
    1. Graphdatenbanken
1. Konzept & Stand DB2Graph
    1. Modell
    1. Mapping
    1. Funktionsweise
    1. Abfragesprache
    1. Unterstützung von Programmiersprachen
    1. Fähigkeiten
    1. Einschränkungen
1. Client-seitige Ergänzungsframeworks
1. Erweiterung um Abfragesprachen
1. Benchmarks
    1. Linkbench
        1. Datenmodell
        1. Einschränkungen
        1. Messungen
        1. Ergebnisse
        1. Vergleich
    1. SNB
1. Use Cases
1. Fazit





