# DAT-SKI Material

Aufgaben, Demos, Lösungen und Daten für das Modul DAT-SKI.
Die Anleitung mit Screenshots steht in der [Wissensdatenbank](https://abbts-dat-ski.github.io/wissensdatenbank/python_installation/).

## Einmal einrichten

In PyCharm: **Clone Repository**, URL `https://github.com/ABBTS-DAT-SKI/material.git`, Ordner `C:\DAT-SKI`.
Oder in PowerShell, zum Beispiel für VS Code:

```bash
git clone https://github.com/ABBTS-DAT-SKI/material.git C:\DAT-SKI
```

## Jede Woche

Im Terminal von PyCharm (oder in PowerShell im Ordner `C:\DAT-SKI`):

```bash
git pull
```

## Regeln, damit `git pull` immer funktioniert

- Bearbeite die Notebooks direkt. Eine veröffentlichte Datei ändert sich nie mehr, deshalb überschreibt `git pull` deine Arbeit nicht.
- Die Folien liegen als PDF im Ordner des Unterrichtsblocks, zum Beispiel `Unterrichtsblock-1/UB1_Folien.pdf`.
- Lösungen kommen nach dem Unterricht als neue Dateien in `Unterrichtsblock-N/Loesungen/`.
- Eigene Dateien gibst du einen eigenen Namen, zum Beispiel `meine_notizen.ipynb`. Lege keine Ordner `Unterrichtsblock-N` für künftige Blöcke an.
- Entpacke keine ZIP-Dateien in diesen Ordner, sonst bricht `git pull` ab.
- Kein `git add` und kein `git commit` nötig.
