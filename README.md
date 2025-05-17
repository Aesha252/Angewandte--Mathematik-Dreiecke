# Wahrscheinlichkeit spitzwinkliger Dreiecke

Dieses Repository enthält unsere Gruppenarbeit für das Modul "Angewandte Mathematik" mit Fokus auf die Wahrscheinlichkeitsberechnung spitzwinkliger Dreiecke unter verschiedenen Zufallsprozessen.

## Aufgabenstellung

Wir untersuchten die Wahrscheinlichkeit, mit der zufällig erzeugte Dreiecke spitzwinklig sind (d.h. alle Winkel < 90°), und zwar unter folgenden Bedingungen:

1. Zufällige Wahl von 2 Winkeln aus dem Intervall (0,π)
2. Zufällige Wahl von 2 Winkeln aus dem Intervall (0,π/2)
3. Zufälliges Setzen von 3 Punkten auf dem Einheitskreis
4. Zufälliges Setzen von 3 Punkten im Einheitsquadrat
5. Zufälliges Setzen von 2 Punkten auf der Strecke [0,1] und Prüfung, ob die 3 resultierenden Teilstücke ein Dreieck bilden können

## Mein Beitrag zur Gruppenarbeit

Als Teil unseres Teams habe ich vor allem an folgenden Aspekten gearbeitet:

- Implementierung der Simulation für Aufgabe 3 (Punkte auf dem Einheitskreis)
- Visualisierung der erzeugten Dreiecke mit matplotlib
- Herleitung des mathematischen Beweises für den 1/4-Anteil spitzwinkliger Dreiecke in Aufgabe 3
- Dokumentation der Ergebnisse und Zusammenführung der Code-Teile

## Umsetzung

Wir haben SageMath mit Python verwendet, um:

1. Monte-Carlo-Simulationen für die verschiedenen Szenarien zu implementieren
2. Die theoretischen Wahrscheinlichkeiten zu berechnen
3. Visualisierungen der erzeugten Dreiecke und ihrer Eigenschaften zu erstellen

## Haupterkenntnisse

- Bei zwei zufälligen Winkeln aus (0,π) können nur in bestimmten Fällen überhaupt Dreiecke gebildet werden
- Bei Punkten auf dem Einheitskreis ist genau 1/4 aller möglichen Dreiecke spitzwinklig
- Die Wahrscheinlichkeit für spitzwinklige Dreiecke variiert je nach Zufallsprozess erheblich

## Code ausführen

Um unseren Code zu verwenden:

```bash
# Repository klonen
git clone [Repository-URL]
cd [Repository-Name]

# SageMath-Notebook starten (falls installiert)
sage -n jupyter

# Alternativ in Google Colab mit SageMath-Kernel ausführen
# Datei hochladen und Kernel auf SageMath umstellen
```

## Dateien im Repository

- `dreiecke_simulation.ipynb`: Hauptnotizbuch mit allen Simulationen und Berechnungen
- `visualisierungen/`: Ordner mit erstellten Grafiken
- `bericht.pdf`: Zusammenfassung unserer Ergebnisse und mathematischen Herleitungen

## Persönliches Fazit

Die Arbeit an diesem Projekt war besonders interessant, da wir mathematische Theorie mit computergestützten Simulationen verbinden konnten. Die Diskrepanz zwischen intuitivem Gefühl und tatsächlichen Wahrscheinlichkeiten bei der Dreiecksbildung war überraschend. Besonders die Aufgabe mit dem Einheitskreis und dem eleganten Beweis für den 1/4-Anteil spitzwinkliger Dreiecke fand ich faszinierend.

SageMath hat sich als leistungsstarkes Werkzeug erwiesen, das mathematische Analyse und Programmierung sinnvoll verbindet und uns ermöglicht hat, komplexe probabilistische Probleme anschaulich zu lösen und zu illustrieren.
