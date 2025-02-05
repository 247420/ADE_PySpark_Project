# Advanced Data Engineering Projekt – Spotify-Datenanalyse mit Apache Spark

## Projektbeschreibung
Dieses Projekt simuliert ein Big Data Problem durch die Verarbeitung von Spotify-Daten mit Apache Spark. Ziel ist es, eine Spark-Anwendung zu entwickeln, die effizient skaliert und fehlertolerant ist. Dazu werden Datensätze analysiert und Tests zur Skalierbarkeit sowie Fehler-Toleranz durchgeführt.

## Ordnerstruktur
- **`data/`**  
  - **`images/`** → Enthält Bilder, die in den Jupyter-Notebooks eingebunden sind.  
- **`project/`**  
  Enthält die Jupyter-Notebooks des Projekts.

## Jupyter-Notebooks
- **`1_Spotify_Data_Analysis_Explanation.ipynb`** → Hauptprojektdatei mit ausführlicher Erklärung des Codes, des Big-Data-Problems und möglicher Anwendungen der Ergebnisse.  
- **`2_Scaling_Observation.ipynb`** → Analyse der Skalierbarkeit der Spark-Anwendung.  
- **`3_Fault_Tolerance.ipynb`** → Dokumentation und Analyse von Fehlertoleranz-Tests.  
- **`4_Spotify_Data_Analysis_Raw.ipynb`** → Vollständiger Code in einer einzigen Zelle für einfache Reproduzierbarkeit.  

## Nutzung

### Ausführbare Notebooks
- **`1_Spotify_Data_Analysis_Explanation.ipynb`**  
  Vollständiger Code mit Erklärung. Kann direkt ausgeführt werden.  

- **`4_Spotify_Data_Analysis_Raw.ipynb`**  
  Vollständiger Code in einer Zelle, ideal für schnelle Reproduktion. **Wichtig**:  
  1. Lade ein Dataset und die main_dataset.csv.
  2. Entpacke die Dateien.
  3. Passe den **Pfad** zu den Pickle- und CSV-Dateien ganz oben im Notebook an.  
  4. Führe die **Initialzelle** einmal aus, um die CSV-Datei zu bereinigen und eine neue bereinigte Datei lokal zu speichern.  
  5. Anschließend können die weiteren Datenverarbeitungen durchgeführt werden.  

### Analyse-Notebooks
- **`2_Scaling_Observation.ipynb`**  
  Untersuchung der Skalierbarkeit der Spark-Anwendung.  

- **`3_Fault_Tolerance.ipynb`**  
  Dokumentation und Analyse von Fehlertoleranz und Durchführung von Tests.  
