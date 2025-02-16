# Wahlvorhersage mit Lineare Regression

Dieses Projekt verwendet historische Wahldaten, um mithilfe von Linearer Regression die Wahlergebnisse für zukünftige Wahlen vorherzusagen.

## Datenquelle

Die verwendeten Daten wurden von [dawum.de](https://dawum.de/Bundestag/#Chronik) bereitgestellt. Diese können regelmäßig aktualisiert werden, um die Vorhersagen auf dem neuesten Stand zu halten.

Zum aktuellen Zeitpunkt besteht die Möglichkeit, die Daten als CSV-Datei herunterzuladen und in den Notebooks zu verwenden. Die verwendete CSV-Datei enthält die historischen Wahlergebnisse von Bundestagswahlen in Deutschland.

## Verwendung

1. **Daten herunterladen**: Besuchen Sie [dawum.de](https://dawum.de/Bundestag/#Chronik) und laden Sie die aktuelle CSV-Datei herunter.
2. **Daten laden und analysieren**: Importieren Sie die CSV-Datei in das Notebook und führen Sie die darin enthaltenen Schritte zur Datenvorverarbeitung und Analyse aus.
3. **Vorhersage berechnen**: Mit der Linearen Regression werden Vorhersagen für die nächsten Wahlergebnisse getroffen.

## Struktur des Projekts

- **Datenverarbeitung und Modellierung**: Das Notebook enthält Code zur Datenvorbereitung, wie das Entfernen von `NaN`-Werten, das Umwandeln von Daten und die Berechnung von Durchschnittswerten.
- **Vorhersage**: Ein Modell der linearen Regression wird verwendet, um die Verteilung der Wählerstimmen für die nächste Wahl zu schätzen.
- **Visualisierung**: Am Ende wird eine Visualisierung der Vorhersage als Kreisdiagramm (Pie Chart) erzeugt.

## Anmerkung

Bitte beachten Sie, dass die Ergebnisse der Vorhersage auf historischen Daten basieren und die tatsächlichen Wahlergebnisse variieren können. Es wird empfohlen, die Daten regelmäßig zu aktualisieren, um die Vorhersagen aktuell zu halten.
