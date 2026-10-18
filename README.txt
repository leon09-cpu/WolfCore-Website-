WOLFCORE WEBSITE - INSTALLATION AUF IPHONE / IPAD

1. ZIP in der Dateien-App öffnen und entpacken.
2. Enthalten: index.html, style.css, script.js.
3. Zur Veröffentlichung ein GitHub-Konto erstellen.
4. Auf github.com ein neues öffentliches Repository erstellen, z.B. wolfcore-site.
5. Über Add file / Upload files die DREI Dateien ins Stammverzeichnis hochladen und committen.
6. Repository > Settings > Pages > Build and deployment > Deploy from a branch.
7. Branch main, Ordner /(root), Save.
8. Nach Veröffentlichung unter https://DEIN-NAME.github.io/wolfcore-site/ erreichbar.

ALTERNATIVE: Cloudflare Pages mit statischen Dateien veröffentlichen.

WICHTIG:
- Dies ist ein statisches Frontend, kein funktionierendes Bot-Backend.
- Kein Discord-Login, keine echten Profile, keine Bot-Steuerung und keine Live-Statistiken vorhanden.
- Den tatsächlichen Prefix in script.js bei const prefix ändern.
- Discord-Link in index.html prüfen.
- Vor öffentlichem Start Impressum und Datenschutz passend ergänzen.
- Niemals Discord-Token, WhatsApp-Sessions, API-Schlüssel oder .env in Website-Dateien hochladen.
- Für echtes Login/API: serverseitige Authentifizierung, Berechtigungsprüfung, sichere Session-Cookies und HTTPS nötig.
