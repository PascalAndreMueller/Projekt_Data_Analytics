# Transformationskompetenzen deutschsprachiger Automobilzulieferer im Kontext batterieelektrischer Fahrzeuge

Eine datengetriebene Identifikation von Zuliefererprofilen mittels webbasierter Textanalyse und maschinellem Lernen.

**Verfasser:** Pascal André Müller  
**Modul:** Projekt Data Analytics (M.Sc. Data Analytics, JLU Gießen, WiSe 25/26)

## Abstract
Die technologische Transformation vom Verbrennungsmotor zum batterieelektrischen Fahrzeug (BEV) erzwingt eine Neuausrichtung der Zuliefererindustrie, deren Fortschritt durch statische Wirtschaftszweigklassifikationen nur unzureichend erfasst wird. Dieses Projekt entwickelt und validiert ein datengetriebenes Framework, das Unternehmenswebseiten mittels maschinellen Lernens analysiert, um technologische Transformationskompetenzen deutschsprachiger Automobilzulieferer granular zu identifizieren. Auf Basis eines kuratierten Korpus von 285 englischsprachigen Textsegmenten aus 31 DACH-Unternehmen wird ein Data-Centric-AI-Ansatz (inkl. SetFit) verfolgt.

## Repository-Struktur
- `data/`: Rohdaten (`data_PDA.csv`) sowie gelabelte Daten (`data_PDA_labeled.csv`) inkl. Codebook/Metadaten (`data/README.md`).
- `notebooks/`: Jupyter Notebooks für Preprocessing/Labeling (Pilotphase) und Modelltraining/Evaluation (manuell gelabelter Datensatz).
- `requirements.txt`: Python-Abhängigkeiten für eine lokale Ausführung.
- `LICENSE`: Lizenz des Codes.
- `CITATION.cff`: Zitierhinweise für dieses Repository.

## Reproduzierbarkeit & Installation
Um den Code lokal auszuführen, klone das Repository und installiere die benötigten Abhängigkeiten:

```bash
git clone https://github.com/PascalAndreMueller/Projekt_Data_Analytics.git
cd Projekt_Data_Analytics

python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows (PowerShell):
# .venv\Scripts\Activate.ps1

pip install -r requirements.txt
jupyter lab
```

### Hinweis zu den Notebooks (Colab-Herkunft)
Die Notebooks wurden ursprünglich in **Google Colab** erstellt. Entsprechend können einzelne Zellen
Colab-spezifische Pfade (z. B. `/content/...`) oder Installationskommandos enthalten. Für eine lokale Ausführung
empfiehlt sich, die Abhängigkeiten über `requirements.txt` zu installieren und Dateipfade auf die im Repository
enthaltenen Dateien unter `data/` anzupassen (Details siehe `data/README.md` und `notebooks/README.md`).

