# Bar-Olympiade – Firebase-Version

## GitHub Pages
Den Inhalt dieses Ordners in dein GitHub-Repository hochladen und bestehende Dateien ersetzen.

## Firebase vor dem Start
1. Authentication → Sign-in method → Anonymous aktivieren.
2. Realtime Database → Rules öffnen und den Inhalt von `database.rules.json` einsetzen und veröffentlichen.
3. GitHub Pages neu laden. Auf jedem Handy muss die App über dieselbe veröffentlichte URL geöffnet werden.

## Rollen / Hinweise
- Der Ersteller ist das Admin-Gerät und kann Ergebnisse korrigieren.
- Neue Teilnehmer werden automatisch dem nächsten freien Teamplatz zugewiesen.
- Ein Team kann nur Ergebnisse von Spielen eintragen, an denen es beteiligt ist.
- Die Datenbankregeln schützen Ergebnis-Schreibvorgänge. Admin- und Teamzuordnung werden über die Firebase-UID kontrolliert.
