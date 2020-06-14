# Notizen wie GIT funktioniert

Links zur Markdown Language:
- https://www.it-talents.de/blog/it-talents/tutorial-einstieg-in-markdown-zur-schnellen-formatierung-von-readme-dateien
- https://dillinger.io/ Markdown Editor

Links zu Git:
- https://git-scm.com/download
- https://www.git-scm.com/book/de/v2

### im Zuge vom HPI Kurs (juni 2020) editiert

- git init             - erstellt ein neues lokales Repository
- git add              - fügt Dateien vom working Directory zur Staging Area hinzu, auch Wildcard möglich
- git commit -m 'info' - aktualisiert dann das Repository
- git remove *.jpg     - entfernt dann Dateien

- git remote ?       - lädt ein lokales Repo ins Internet zB auf GitHub
- git clone https:/github.com/noebauerr/repo repo - cloned das Github Repo auf ein lokales Repo

- git push    - lädt die Änderungen dann ins Online Repo bei Github

- git fetch origin   - lädt die aktuelle Version von einem anderen Repository runter
- git merge          - und verbindet es dann

- git pull    - führt fetch und merge aus, beide Befehle in einem

- git status

- git config --list

- git branch <name> - erstellt einen branch
- git checkout <branch> - wechseln von Branches
- git merge <branch> - zusammenführen von Branches
- git log - zeigt commit Historie an
  
- git reset HEAD <datei> - unstaging von Dateien
- git checkout -- <datei> - Änderungen an Datei verwerfen
  
