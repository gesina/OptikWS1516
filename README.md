# Vorlesungsmitschrift Experimentalphysik III – Wellen und Quanten
Dies sind die Quellen einer Vorlesungsmitschrift der Vorlesung
*Experimentalphysik III (Wellen und Quanten)*, kurz Optik, an der
Universität Regensburg im Wintersemester 2015/2016.

## Dateiübersicht
- Hauptdatei: `OptikSkriptWS1516.tex`
- reguläre Kapitel: `Kapitel/OptikSkriptWS1516_Kap0[1-9].tex`
- Kapitel im Anhang: `Kapitel/OptikSkriptWS1516_KapA[1-2].tex`
- Literatur: `OptikSkriptWS1516_literature.bib`
- LaTeX-Konfigurationen: `OptikSkriptWS1516_config.tex`
- LaTeX-Definitionen (Kürzel, Operatoren, etc.): `OptikSkriptWS1516_definitions.tex`

## Bilder
Aus urheberrechtlichen Gründen kann das Bildmaterial nicht eingebunden
werden.
Fehlenden Bilder sind im Quellcode mit `%% IMAGE MISSING` (und
evtl. näherer Erläuterung zur Quelle) markiert.

## Kompilieren
(Getestete) Systemvoraussetzungen: `TeXLive 2016`-Distribution

Zum Kompilieren folgende Befehle (in dieser Reihenfolge) ausführen:

```bash
pdflatex OptikSkriptWS1516.tex
makeindex OptikSkriptWS1516.nlo -s nomencl.ist -o OptikSkriptWS1516.nls
makeindex OptikSkriptWS1516
biber OptikSkriptWS1516
pdflatex OptikSkriptWS1516.tex
```
