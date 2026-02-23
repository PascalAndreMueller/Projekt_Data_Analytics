# Transformationskompetenzen deutschsprachiger Automobilzulieferer im Kontext batterieelektrischer Fahrzeuge

Eine datengetriebene Identifikation von Zuliefererprofilen mittels webbasierter Textanalyse und maschinellem Lernen.

**Verfasser:** Pascal André Müller  
**Modul:** Projekt Data Analytics (M.Sc. Data Analytics, JLU Gießen, WiSe 25/26)

## Abstract
Die technologische Transformation vom Verbrennungsmotor zum batterieelektrischen Fahrzeug (BEV) erzwingt eine Neuausrichtung der Zuliefererindustrie, deren Fortschritt durch statische Wirtschaftszweigklassifikationen nur unzureichend erfasst wird. Dieses Projekt entwickelt und validiert ein datengetriebenes Framework, das Unternehmenswebseiten mittels maschinellen Lernens analysiert, um technologische Transformationskompetenzen deutschsprachiger Automobilzulieferer granular zu identifizieren. Auf Basis eines kuratierten Korpus von 285 englischsprachigen Textsegmenten aus 31 DACH-Unternehmen wird ein Data-Centric-AI-Ansatz (inkl. SetFit) verfolgt.

## Repository-Struktur
- `data/`: Enthält die Rohdaten (`data_PDA.csv`) sowie die gelabelten Daten (`data_PDA_labeled.csv`).
- `notebooks/`: Jupyter Notebooks für das Preprocessing der ungelabelten Daten (`Code_data_unlabeled_github.ipynb`) sowie für das Training und die Auswertung der gelabelten Daten (`Code_data_labeled_github.ipynb`).

## Reproduzierbarkeit & Installation
Um den Code lokal auszuführen, klone das Repository und installiere die benötigten Abhängigkeiten:

```bash
git clone <REPO-URL>
cd <REPO-NAME>

python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows (PowerShell):
# .venv\Scripts\Activate.ps1

pip install -r requirements.txt
jupyter lab
```
