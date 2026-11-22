# koljakrause.com

Mein Blog. Gebaut mit GitHub Pages (Jekyll), Design angelehnt an Bear Blog.

## Neuen Artikel veröffentlichen (der einfache Weg)

1. **koljakrause.com/schreiben/** öffnen (vorher bei GitHub eingeloggt sein)
2. Titel eintippen, auf **Weiter zu GitHub** klicken
3. Text in die Vorlage schreiben (Leerzeile = neuer Absatz)
4. Oben rechts **Commit changes…**, dann nochmal **Commit changes**
5. Nach ca. 1 Minute ist der Artikel live

## Manuell (falls die Seite mal nicht geht)

Im Ordner `_posts` auf **Add file → Create new file** klicken.
Dateiname: `JJJJ-MM-TT-titel-ohne-umlaute.md`, z. B. `2026-12-01-mein-gedanke.md`

Inhalt:

```
---
title: "Mein Gedanke"
---

Erster Absatz.

Zweiter Absatz.
```

## Markdown-Spickzettel

| Schreibst du | Ergibt |
|---|---|
| `**fett**` | **fett** |
| `*kursiv*` | *kursiv* |
| `## Zwischenüberschrift` | Zwischenüberschrift |
| `[Linktext](https://...)` | Link |
| `> Zitat` | Zitat |
| `- Punkt` | Aufzählung |

## Artikel bearbeiten oder löschen

Datei in `_posts` anklicken → Stift-Symbol (bearbeiten) oder `…` → Delete file.

## Aufbau

- `_posts/` – die Artikel (eine Markdown-Datei pro Artikel)
- `_layouts/` – HTML-Gerüst der Seiten
- `style.css` – Aussehen
- `_config.yml` – Titel, Beschreibung, Domain
- `CNAME` – eigene Domain (kommt nach dem Domainkauf dazu)
