# DAT-SKI Material

Aufgaben, Demos, Lösungen und Daten für das Modul DAT-SKI.
Die Anleitung mit Screenshots steht in der [Wissensdatenbank](https://abbts-dat-ski.github.io/wissensdatenbank/python_installation/).

## Einmal einrichten

In PyCharm: **Clone Repository**, URL `https://github.com/ABBTS-DAT-SKI/material.git` (Ordner: Vorschlag von PyCharm, nicht in OneDrive).
Oder in PowerShell, zum Beispiel für VS Code:

```bash
git clone https://github.com/ABBTS-DAT-SKI/material.git C:\DAT-SKI
```

## Jede Woche

In PyCharm: oben links auf den Branch **main** klicken, dann **Update Project** (`Ctrl+T`).
Oder im Terminal (PyCharm oder PowerShell im Material-Ordner):

```bash
git pull
```

## Regeln, damit `git pull` immer funktioniert

- Bearbeite die Notebooks direkt. Eine veröffentlichte Datei ändert sich nie mehr, deshalb überschreibt `git pull` deine Arbeit nicht.
- Die Folien liegen als PDF im Ordner des Unterrichtsblocks, zum Beispiel `Unterrichtsblock-1/UB1_Folien.pdf`.
- Lösungen kommen nach dem Unterricht als neue Dateien in `Unterrichtsblock-N/Loesungen/`.
- Eigene Dateien gibst du einen eigenen Namen, zum Beispiel `meine_notizen.ipynb`. Lege keine Ordner `Unterrichtsblock-N` für künftige Blöcke an.
- Kein `git add` und kein `git commit` nötig.
