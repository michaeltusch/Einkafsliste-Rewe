# Einkaufslisten – GitHub Pages Setup

Diese vier Dateien ergeben zusammen deine Einkaufslisten-App, gehostet über GitHub Pages. Das löst nebenbei auch das Problem, dass die Häkchen und Sounds in der Chat-Vorschau nicht funktioniert haben – über GitHub Pages läuft die Seite in einem echten Browser mit vollem JavaScript, nicht nur als Vorschau.

## Schritt für Schritt (ca. 5 Minuten)

1. Gehe auf [github.com](https://github.com) und logge dich ein (oder lege kostenlos einen Account an, falls noch nicht vorhanden).
2. Klicke oben rechts auf **+** → **New repository**.
3. Vergib einen Namen, z. B. `einkaufslisten`. Sichtbarkeit kann **Public** bleiben (nötig für die kostenlose GitHub-Pages-Variante). Erstelle das Repository.
4. Klicke im neuen, leeren Repository auf **uploading an existing file** (oder **Add file → Upload files**).
5. Ziehe alle vier Dateien aus diesem Paket hinein (`index.html`, `einkaufsliste.html`, `einkaufsliste-lidl.html`, `einkaufsliste-baecker-grete.html`) und klicke **Commit changes**.
6. Gehe zu **Settings** (oben im Repository) → **Pages** (linke Seitenleiste).
7. Unter **Build and deployment** → **Source** wähle **Deploy from a branch**. Branch: `main`, Ordner: `/ (root)`. Speichern.
8. Nach ein bis zwei Minuten erscheint oben eine grüne Meldung mit deiner Live-URL, etwa:
   `https://DEIN-BENUTZERNAME.github.io/einkaufslisten/`

## Auf dem Homescreen installieren

Öffne diese URL in Safari (iPhone) oder Chrome (Android) auf deinem Handy, dann wie gewohnt "Zum Home-Bildschirm hinzufügen". Da es jetzt eine echte, im Browser laufende Seite ist (kein Chat-Anhang mehr), funktionieren Häkchen, Fortschrittsanzeige, Sounds und der Konfetti-Effekt zuverlässig.

## Updates später

Wenn sich eine Liste ändert, einfach die aktualisierte Datei im GitHub-Repository erneut hochladen (gleicher Dateiname überschreibt die alte Version automatisch) – die Homescreen-Verknüpfung zeigt dann automatisch den neuen Stand.
