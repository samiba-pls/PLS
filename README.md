# PLS

- `index.html` – die Seite (3D-Würfel + Heatmaps, lädt `data.json`); Heatmaps direkt: `index.html#heatmap`
- `data.json` – Daten, wird automatisch aus der Excel erzeugt
- `KI_Pflege_Anwendungsbeispiele.xlsx` – Quelle der Wahrheit (Blatt „Anwendungen")
- `tools/excel_to_json.py` – Konvertierung (lokal: `python tools/excel_to_json.py`), gibt Warnungen bei leeren Feldern aus
- `.github/workflows/update-data.yml` – erzeugt `data.json` neu, sobald die Excel hochgeladen wird


