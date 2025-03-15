# MotionClassifier

**Projektgruppe:** Markus Artemov und Chris Carstensen

## Projektübersicht

MotionClassifier ist ein Projekt zur Klassifizierung, insbesondere zur Unterscheidung zwischen Sprüngen und Kniebeugen. Das Ziel ist es, mithilfe von maschinellem Lernen und Signalverarbeitungstechniken Bewegungsmuster zu analysieren und korrekt zu klassifizieren.

## Projektstruktur

- **csv_training/**: Enthält Trainingsdatensätze im CSV-Format.
- **csv_test/**: Beinhaltet Testdatensätze im CSV-Format.
- **model/**: Speichert trainierte Modelle und zugehörige Dateien.
- **prep.ipynb**: Notebook zur Datenvorbereitung und -verarbeitung.
- **train.ipynb**: Notebook zum Training des Klassifikationsmodells.
- **test.ipynb**: Notebook zur Evaluierung des Modells mit Testdaten.
- **plot.ipynb**: Notebook zur Visualisierung der Ergebnisse und Daten.

## Anforderungen

- **Programmiersprache**: Python 3.x
- **Bibliotheken**:
  - NumPy
  - pandas
  - scikit-learn
  - Matplotlib
  - Jupyter Notebook

Stellen Sie sicher, dass alle erforderlichen Bibliotheken installiert sind, bevor Sie die Notebooks ausführen.

## Installation

1. Klonen Sie das Repository:
   ```bash
   git clone https://github.com/MarkusArtemov/MotionClassifier.git
   ```

2. Wechseln Sie in das Projektverzeichnis:
   ```bash
   cd MotionClassifier
   ```

3. Erstellen Sie eine virtuelle Umgebung:
   ```bash
   python -m venv env
   ```

4. Aktivieren Sie die virtuelle Umgebung:
   - **Für Windows**:
     ```bash
     .\env\Scripts\activate
     ```
   - **Für macOS/Linux**:
     ```bash
     source env/bin/activate
     ```

5. Installieren Sie die erforderlichen Bibliotheken:
   ```bash
   pip install -r requirements.txt
   ```
   *Hinweis: Erstellen Sie eine `requirements.txt`-Datei mit den oben genannten Bibliotheken und deren Versionen.*

## Nutzung

1. Starten Sie Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Öffnen Sie die Notebooks in folgender Reihenfolge:
   - **prep.ipynb**: Führen Sie die Datenvorbereitung durch.
   - **train.ipynb**: Trainieren Sie das Modell mit den vorbereiteten Daten.
   - **test.ipynb**: Evaluieren Sie die Modellleistung mit Testdaten.
   - **plot.ipynb**: Visualisieren Sie die Ergebnisse und Daten.

Folgen Sie den Anweisungen in jedem Notebook, um den gesamten Prozess durchzuführen.

## Daten

Die Trainings- und Testdatensätze befinden sich in den Verzeichnissen `csv_training/` und `csv_test/`. Stellen Sie sicher, dass die Daten korrekt formatiert sind und den Anforderungen der Notebooks entsprechen.

