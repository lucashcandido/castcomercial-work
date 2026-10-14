# Cast Comercial – Entrada (work.castcomercial.com)

Zeiterfassung an den Einfahrten der Parkanlagen. Ein Gerät pro Parkanlage: Nummernschild eingeben → die Zeit läuft. ✕ beendet das Parken und zeigt die Dauer (Preis folgt).

- **Einrichtung:** Parkanlage wählen und den Code eingeben, der in app.castcomercial.com → Ajustes → Entradas steht, oder dort den QR-Code der Parkanlage scannen.
- **Daten:** im privaten Repo `castcomercial-work-data`, eine Datei pro Parkanlage und Monat (`<lot>/<YYYY-MM>.json`).
- **Zugang:** Der Token kann nur dieses Repo erreichen. Er liegt verschlüsselt in `work-access.json` im Repo der App und wird mit dem Code entschlüsselt. Die Geräte haben keinen Zugang zu app.castcomercial.com oder zu den Kundendaten.
