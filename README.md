# Schulvorfälle – Janno · PWA via GitHub Pages

Eine Progressive Web App zur Dokumentation von Schulvorfällen,
optimiert für iPhone (Safari, Spracheingabe).

---

## Deployment auf GitHub Pages (Schritt-für-Schritt)

### Voraussetzungen
- Kostenloser GitHub-Account: https://github.com/join

---

### Schritt 1 – Neues Repository anlegen
1. Auf github.com einloggen
2. Oben rechts auf „+" → „New repository"
3. Repository-Name: `janno-schule` (oder beliebig)
4. Auf „Public" stellen (wird für GitHub Pages benötigt)
5. Auf „Create repository" klicken

---

### Schritt 2 – Dateien hochladen
1. Im neuen Repository auf „uploading an existing file" klicken
2. Folgende Dateien aus dem ZIP hochladen:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - Ordner `icons/` mit `icon-192.png` und `icon-512.png`
3. Auf „Commit changes" klicken

---

### Schritt 3 – GitHub Pages aktivieren
1. Im Repository auf „Settings" (Zahnrad oben rechts)
2. Links im Menü: „Pages"
3. Unter „Branch": `main` auswählen, Ordner `/ (root)` lassen
4. Auf „Save" klicken
5. Nach ca. 1–2 Minuten erscheint die URL:
   `https://IHR-USERNAME.github.io/janno-schule/`

---

### Schritt 4 – Auf dem iPhone installieren
1. Safari auf dem iPhone öffnen
2. Die GitHub-Pages-URL aufrufen
3. Unten auf das **Teilen-Symbol** (Viereck mit Pfeil nach oben) tippen
4. Nach unten scrollen → „**Zum Home-Bildschirm**" tippen
5. Name bestätigen → „Hinzufügen"

Die App erscheint nun wie eine normale App auf dem Homescreen. ✓

---

## Hinweise

- **Datenspeicherung**: Alle Vorfälle werden lokal im iPhone-Speicher
  (localStorage) gespeichert – keine Cloud, keine fremden Server.
- **Offline-Fähigkeit**: Nach dem ersten Aufruf funktioniert die App
  auch ohne Internetverbindung.
- **Export**: Über den CSV-Export können Daten an den Computer
  übertragen und z.B. in Excel geöffnet werden.
- **Dark Mode**: Die App unterstützt automatisch den iPhone-Dark-Mode.
