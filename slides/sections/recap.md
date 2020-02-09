## Voraussetzungen

* Konzepte
* Elementare Befehle
* Merge Workflow

---

## Konzepte

- Arbeitsverzeichnis
- Staging/Cache
- Commit
- Patch
- Parent
- Branch
- Repository

---

## Repositories

- Neu erstellen
 - git init
- Kopie erstellen
 - git clone

---

## Repositories

- Änderungen holen
 - git pull
 - git fetch
- Änderungen hochladen
 - git push

---

## Commits
- Änderungen ins Staging hinzufügen
 - git add
- Commit erstellen
 - git commit
 - git commit -a

---

## Status
- Dateien im Arbeitsverzeichnis
 - git status
- Änderungen im Arbeitsverzeichnis
 - git diff
- Änderungen im Staging-Bereich
 - git diff --staged
 - git diff --cached
- Bisherige/letzte Commits
 - git log

---

## Merge Workflow

- git checkout -b feature
- git commit
- git checkout master
- git pull
- git merge feature
- git push
