# Advanced Data Engineering Projekt – Spotify-Datenanalyse mit Apache Spark

## Projektbeschreibung
Dieses Projekt simuliert ein Big Data Problem durch die Verarbeitung von Spotify-Daten mit Apache Spark. Ziel ist es, eine Spark-Anwendung zu entwickeln, die effizient skaliert und fehlertolerant ist. Dazu werden Datensätze analysiert und Tests zur Skalierbarkeit sowie Fehler-Toleranz durchgeführt.

## Ordnerstruktur
- **`data/`**  
  - **`images/`** → Enthält Bilder, die in den Jupyter-Notebooks eingebunden sind.  
  - **`100 Spotify Dataset.zip`** → Enthält 100 Pickle-Dateien für die Datenverarbeitung.
  - **`1000 Spotify Dataset.zip`** → Enthält 1000 Pickle-Dateien für die Datenverarbeitung.
  - **`10.000 Spotify Dataset.zip`** → Enthält 10.000 Pickle-Dateien für die Datenverarbeitung.
  - **`main_dataset.zip`** → Enthält über 200.000 Musik-Datensätze.
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
  1. Lade ein Dataset aus dem Ordner `data/` herunter, z. B. `100 Spotify Dataset.zip`.
  2. Lade die main_dataset aus dem Ordner `data/` herunter.
  3. Entpacke die Dateien.
  4. Passe den **Pfad** zu den Pickle- und CSV-Dateien ganz oben im Notebook an.  
  5. Führe die **Initialzelle** einmal aus, um die CSV-Datei zu bereinigen und eine neue bereinigte Datei lokal zu speichern.  
  6. Anschließend können die weiteren Datenverarbeitungen durchgeführt werden.  

### Analyse-Notebooks
- **`2_Scaling_Observation.ipynb`**  
  Untersuchung der Skalierbarkeit der Spark-Anwendung.  

- **`3_Fault_Tolerance.ipynb`**  
  Dokumentation und Analyse von Fehlertoleranz und Durchführung von Tests.  
