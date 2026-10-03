# DAT-SKI Material

Aufgaben, Demos, Lösungen und Daten für das Modul DAT-SKI.
Die Anleitung steht in der [Wissensdatenbank](https://abbts-dat-ski.github.io/wissensdatenbank/material_downloads/).

## Einmal einrichten

```bash
mkdir C:\DAT-SKI
cd C:\DAT-SKI
git clone https://github.com/ABBTS-DAT-SKI/material.git
```

## Jede Woche

```bash
cd C:\DAT-SKI\material
git pull
```

## Regeln, damit `git pull` immer funktioniert

- Bearbeite die Notebooks direkt. Eine veröffentlichte Datei ändert sich nie mehr, deshalb überschreibt `git pull` deine Arbeit nicht.
- Lösungen kommen nach dem Unterricht als neue Dateien in `Unterrichtsblock-N/Loesungen/`.
- Eigene Dateien gibst du einen eigenen Namen, zum Beispiel `meine_notizen.ipynb`. Lege keine Ordner `Unterrichtsblock-N` für künftige Blöcke an.
- Kein `git add` und kein `git commit` nötig.
