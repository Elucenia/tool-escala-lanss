<!-- ELUCENIA technical documentation · escala-lanss · de · no clinical/professional/rights approval -->

# LANSS-Schmerzskala

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-lanss)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Fühlt sich der Schmerz wie eine ungewöhnliche, unangenehme Hautempfindung an (Nadelstiche, Kribbeln, elektrische Schläge)?

`a1`

### Sieht die Haut im schmerzhaften Bereich durch den Schmerz anders als normal aus (fleckig, gerötet oder rosa)?

`a2`

### Macht der Schmerz die Haut ungewöhnlich berührungsempfindlich (Beschwerden bei leichter Berührung oder enger Kleidung)?

`a3`

### Tritt der Schmerz in Ruhe plötzlich anfallsartig ohne erkennbaren Grund auf (elektrische Schläge, stechender Schmerz)?

`a4`

### Erweckt der Schmerz das Gefühl, dass sich die Hauttemperatur verändert hat (Hitze, Brennen)?

`a5`

### Untersuchung: Allodynie (Schmerz oder Beschwerden beim Streichen mit Watte über den schmerzhaften Bereich im Vergleich zu einem normalen Bereich)

`b6`

### Untersuchung: veränderte Nadelreizschwelle (ein Stich mit einer 23G-Nadel wird im schmerzhaften Bereich anders wahrgenommen: stärker oder schwächer)

`b7`

## Fassung der Methode

LANSS/Bennett 2001: 5 Symptome+2 Zeichen, Gesamt 0–24, Grenzwert ≥12; brasilianisches Portugiesisch Schestatsky 2011

## Dokumentierte Formel

Teil A (Fragebogen): Items mit 5, 5, 3, 2 und 1 Punkt. Teil B (Sensibilitätsprüfung): Allodynie 5; veränderte Nadelstichschwelle 3. Gesamt 0 bis 24; Grenzwert ≥12.

## Grenzen und Population

LANSS kombiniert Symptome mit Zeichen aus der Sensibilitätsuntersuchung, um das Überwiegen eines neuropathischen Mechanismus bei chronischen Schmerzen zu untersuchen. Untersuchungsitems dürfen nicht als bloße Selbstauskunft behandelt werden. Die zitierte brasilianische Validierung zertifiziert weder die Implementierung noch neue Übersetzungen.

## Referenzen

- [Bennett M. The LANSS Pain Scale: the Leeds assessment of neuropathic symptoms and signs. Pain, 2001.](https://doi.org/10.1016/S0304-3959(00)00482-6)

- [Schestatsky P et al. Brazilian Portuguese validation of the Leeds Assessment of Neuropathic Symptoms and Signs for patients with chronic pain. Pain Med, 2011.](https://doi.org/10.1111/j.1526-4637.2011.01221.x)

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
