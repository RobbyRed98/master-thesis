# Thesis

## Setup

### Latex

#### Ubuntu (>= 20.04)

```bash
$ apt update
$ apt install texlive texlive-latex-extra texlive-bibtex-extra texlive-lang-german texlive-plain-generic texlive-font-utils texlive-science latexmk
```

## Build

### BASH / Ubuntu Server

```bash
$ latexmk document.tex -interaction=nonstopmode -file-line-error -pdf
```

## Structure

Thesis-Aufbau:
1. Einführung
    1. Warum interessant?
    1. Hinweis auf bereits existierendes Paper. 
1. Theoretische Grundlagen 
    1. kurze Übersicht Graph vs. relational
    1. SQL vs. Gremlin vs. Cypher (noch unsicher)
1. Db2graph
    1. Ansatz (Hybrid)
    1. Funktionsweise
    1. Einschränkungen
    1. Hinweise verschiedene Versionen
1. Analyse-Methode
    1. Bewertungskriterien
        - Erweiterbarkeit -- Wie viel Plugin- & Framework-Unterstützung?
        - Performance -- Wie hoch im Vergleich zu Neo4j? (Hauptfokus) (beinhaltet Linkbench-Impls)
        - (optional) Usablility (Tooling + Konfiguration-Aufwand) vs. Neo4j
1. Evaluation & Ergebnisse
    1. Performance-Messungen mit Linkbench
    1. Erweiterbarkeit Neo4j Plugins + Framework-Support
    1. (optional) Usablility (Tooling + Konfiguration-Aufwand) vs. Neo4j
1. Diskussion
1. Fazit 

### Deprecated 

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





