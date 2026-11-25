KODIAQ KOSTEN – OFFLINE PWA

Enthaltene Dateien:
- index.html: Kostenrechner
- manifest.json: App-Metadaten
- service-worker.js: Offline-Cache
- icon-192.png / icon-512.png: App-Symbole
- .nojekyll: GitHub Pages-Datei

Einrichtung mit GitHub Pages:
1. ZIP unter Windows entpacken.
2. Auf github.com einloggen/registrieren.
3. Neues Repository anlegen, z. B. kodiaq-kosten. Für kostenlose GitHub Pages muss das Repository öffentlich sein. Der Inhalt dieser App enthält keine persönlichen Daten.
4. Im Repository auf Add file > Upload files gehen.
5. ALLE Dateien aus dem entpackten Ordner hochladen (auch .nojekyll; falls versteckte Dateien nicht angezeigt werden, später separat anlegen).
6. Commit changes.
7. Repository Settings > Pages öffnen.
8. Bei Build and deployment: Source „Deploy from a branch“ auswählen.
9. Branch „main“, Ordner „/(root)“ auswählen und Save.
10. Warten, bis die Seite veröffentlicht ist. Unter Settings > Pages wird die Website-Adresse angezeigt, typischerweise https://DEIN-NUTZER.github.io/kodiaq-kosten/.
11. Die Adresse zunächst in Safari auf dem iPhone öffnen und warten, bis die App vollständig geladen ist. Die Service-Worker-Dateien werden dabei gespeichert.
12. Safari > Teilen > Zum Home-Bildschirm > „Als Web-App öffnen“ aktivieren > Hinzufügen.
13. App-Symbol starten. Zum Offline-Test Flugmodus einschalten und die App erneut öffnen.

Hinweise:
- Erstinstallation/Cache erfordert Internet. Danach ist die App für die Berechnung offline nutzbar.
- Bei Updates die neuen Dateien erneut auf GitHub hochladen; die App online öffnen, damit der Cache aktualisiert wird. Falls eine Änderung nicht erscheint, App schließen und erneut öffnen.
- Die Eingabewerte werden lokal im Browser auf diesem iPhone gespeichert.
