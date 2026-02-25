# Datensätze

Dieses Verzeichnis enthält die im Projekt verwendeten Datensätze:

- `data_PDA.csv`: Rohdaten (Textsegmente, Metadaten)
- `data_PDA_labeled.csv`: Manuell annotierter Datensatz (zusätzliches Label-Feld)

## Spaltenbeschreibung

### `data_PDA.csv`
- `text_segment_id` (int): fortlaufende ID des Textsegments
- `company_name` (str): Unternehmensname
- `company_url` (str): Unternehmens-Website (Root)
- `source_url` (str): Quelle des extrahierten Textsegments
- `is_pdf` (bool): Kennzeichnung, ob Quelle ein PDF war
- `text_segment` (str): Textsegment (englischsprachig)

### `data_PDA_labeled.csv`
Enthält alle Spalten aus `data_PDA.csv` und zusätzlich:
- `labels` (str): manuelle Annotation (Multi-Label; projektspezifisches Schema)

## Nutzungshinweis (Webseiten-Texte)
Die Textsegmente basieren auf öffentlich zugänglichen Unternehmenswebseiten und werden im Rahmen einer akademischen
Lehrveranstaltung bereitgestellt. Inhalte können urheberrechtlich geschützt sein. Eine Weiterverwendung sollte
die jeweiligen Nutzungsbedingungen/Urheberrechte der Originalquellen berücksichtigen.
