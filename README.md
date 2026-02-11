# Statistische Analyse der Energieerzeugung in Deutschland (2020–2025)

Dieses Projekt bietet eine datengestützte Untersuchung der stündlichen Stromerzeugung in Deutschland. Es deckt den Zeitraum von 2020 bis Anfang 2025 ab und analysiert die Dynamik verschiedener Energiequellen wie Wind, Solar, Kernkraft und fossile Brennstoffe.

##  Projektübersicht
Das Hauptziel dieser Analyse ist es, die Zeitreihendaten der deutschen Energieerzeugung zu verstehen, ihre Stationarität statistisch zu beweisen und eine Basisprognose zu erstellen.

### Kernfunktionen:
- **Datenvorverarbeitung:** Reinigung und Umwandlung von stündlichen Rohdaten in tägliche Durchschnittswerte (Resampling).
- **Statistische Tests:** Anwendung des Augmented Dickey-Fuller (ADF) Tests.
- **Zeitreihen-Analyse:** Visualisierung von Trends und Autokorrelation (ACF/PACF).
- **Prognose:** Erstellung eines Vorhersagemodells mit Evaluierung der Genauigkeit.

---

##  Analyseergebnisse

### 1. Stationaritätsprüfung (ADF-Test)
Um die Eignung der Daten für Zeitreihenmodelle zu prüfen, wurde der ADF-Test durchgeführt:
- **ADF-Statistik:** -6.84
- **p-Wert:** 1.77e-09
**Fazit:** Da der p-Wert extrem niedrig ist, ist die Zeitreihe **stationär**. Dies ermöglicht zuverlässige statistische Vorhersagen.

### 2. Modellgenauigkeit (RMSE)
Die Vorhersagequalität wurde mit dem Root Mean Squared Error gemessen:
- **RMSE:** 244.97
*Interpretation: Bei einer täglichen Erzeugung im Bereich von mehreren tausend MWh deutet dieser Wert auf eine sehr geringe Abweichung und eine hohe Modellpräzision hin.*

---

##  Technologien und Bibliotheken
Das Projekt wurde mit **Python 3** entwickelt und nutzt folgende Bibliotheken:
- `pandas` - Datenmanipulation
- `matplotlib` - Datenvisualisierung
- `statsmodels` - Statistische Tests und Modelle
- `scikit-learn` - Evaluierung der Metriken (RMSE)
- `numpy` - Numerische Berechnungen

---


