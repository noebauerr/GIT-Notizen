# Notizen wie GIT funktioniert

Links zur Markdown Language:
- https://www.it-talents.de/blog/it-talents/tutorial-einstieg-in-markdown-zur-schnellen-formatierung-von-readme-dateien
- https://dillinger.io/ Markdown Editor

Links zu Git:
- https://git-scm.com/download
- https://github.github.com/training-kit/downloads/de/github-git-cheat-sheet/
- https://www.git-scm.com/book/de/v2
- https://gitahead.github.io/gitahead.com/
- https://learngitbranching.js.org/?locale=de_DE

### im Zuge vom HPI Kurs (juni 2020) editiert

- git init             - erstellt ein neues lokales Repository
- git add              - fügt Dateien vom working Directory zur Staging Area hinzu, auch Wildcard möglich
- git commit -m 'info' - aktualisiert dann das Repository
- git commit --amend -m 'jetzt der richtige Text' - ersetzt die alte Commit Message
- git remove *.jpg     - entfernt dann Dateien

- git remote ?       - lädt ein lokales Repo ins Internet zB auf GitHub
- git clone https:/github.com/noebauerr/repo repo - cloned das Github Repo auf ein lokales Repo

- git push    - lädt die Änderungen dann ins Online Repo bei Github

- git fetch origin   - lädt die aktuelle Version von einem anderen Repository runter
- git merge          - integriert den branch in den aktuellen

- git pull    - führt fetch und merge aus, beide Befehle in einem

- git status

- git config --list

- git branch <name> - erstellt einen branch
- git branch -d <name> - einen nicht mehr benötigten Branch löschen
- git checkout <branch> - wechseln von Branches, setzt den HEAD (Zeiger) auf einen anderen Branch
- git checkout -b <newbranchname> - legt einen neuen Branch an und wechselt gleich
- git merge <branch> - zusammenführen von Branches

- git log - zeigt commit Historie an
- git log -p oder --patch zeigt die Unterschiede an
- git log --graph zeigt auch die Branches ein bisschen an
- git log --graph --oneline noch kompakter
- git log --stat
- git log --pretty finde ich nicht so toll
  
- git reset HEAD~ - zurück auf den vorletzten Commit, Arbeitsverzeichnis hat aber noch alle Änderungen gespeichert
- git reset --hard HEAD~ - zurück auf den vorletzten Commit und Arbeitsverzeichnis auch auf die alte Version setzen
- git checkout -- <datei> - Änderungen an Datei verwerfen
  
