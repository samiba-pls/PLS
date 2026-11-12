# PLS

- `index.html`    Landingpage
- `Pflegedatenbank.html` Anwendungsbeispiele zu KI in der Pflege
  - `data.json` – Daten, wird automatisch aus der Excel erzeugt
  - `KI_Pflege_Anwendungsbeispiele.xlsx` – Datenbank (Blatt „Anwendungen")
  - `tools/excel_to_json.py` – Konvertierung (lokal: `python tools/excel_to_json.py`), gibt Warnungen bei leeren Feldern aus
  - `.github/workflows/update-data.yml` – erzeugt `data.json` neu, sobald die Excel hochgeladen wird
- Datenbasispyramide.html
- Datenwürfel.html


