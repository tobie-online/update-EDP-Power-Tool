# EDP Power Tool – Updates

Öffentliche Update-Quelle des **EDP Power Tools** (JUH Ortsverband Wunstorf-Steinhuder Meer).
Das Programm prüft einmal am Tag `version.txt` und lädt bei einer neueren Version die EXE.

| Datei | Inhalt |
|---|---|
| `EDP Power Tool.exe` | aktuelle Version; Doppelklick bietet die Installation an |
| `version.txt` | Version, SHA-256, Größe, Datum, Änderungen |
| `version.txt.sig` | Signatur über `version.txt` – das Programm installiert nur signierte Updates |

Quellcode, Anleitung und Build liegen im privaten Repo `tobie-online/edp-power-tool`.
Dateien hier nicht von Hand ändern: Ohne passende Signatur nimmt das Programm kein Update an.
