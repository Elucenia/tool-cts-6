<!-- ELUCENIA technical documentation · cts-6 · de · no clinical/professional/rights approval -->

# CTS-6 (Karpaltunnelsyndrom)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/cts-6)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Taubheitsgefühl überwiegend oder ausschließlich im Versorgungsgebiet des Nervus medianus

`dorm`

### Nächtliches Taubheitsgefühl

`noturna`

### Atrophie und/oder Schwäche der Thenarmuskulatur

`atrofia`

### Positiver Phalen-Test

`phalen`

### Verlust der Zweipunktdiskrimination (\> 6 mm)

`dpp`

### Positives Tinel-Zeichen über dem Karpaltunnel

`tinel`

## Fassung der Methode

CTS-6/Graham 2006: 6 gewichtete Karpaltunnelkriterien; klinische Untersuchung

## Dokumentierte Formel

Summe: Taubheit im Medianusgebiet 3,5; nachts 4; Thenaratrophie/-schwäche 5; Phalen positiv 5; Verlust der Zweipunktdiskrimination 4,5; Tinel positiv 4. Gesamt 0–26.

## Grenzen und Population

Die Entwicklung nach Graham 2006 nutzte Expertenkonsens und Fallgeschichten mit kombinierten klinischen Kriterien; die im Abstract beschriebene Validierung verglich Modellwahrscheinlichkeiten mit den Urteilen eines weiteren Gremiums. Dieses Design belegt allein nicht die Leistung gegenüber elektrophysiologischer Untersuchung in jeder klinischen Population. Sechs-Item-Punktzahl, Schwelle und Altersbereich müssen im vollständigen Methodentext geprüft werden.

## Referenzen

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
