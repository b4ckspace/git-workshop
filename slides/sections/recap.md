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
 - `git init`  <!-- .element class="fragment" -->
- Kopie erstellen
 - `git clone`  <!-- .element class="fragment" -->

---

## Repositories

- Änderungen holen
 - `git pull` <!-- .element class="fragment" -->
 - `git fetch`  <!-- .element class="fragment" -->
- Änderungen hochladen
 - `git push` <!-- .element class="fragment" -->

---

## Commits
- Änderungen ins Staging hinzufügen
 - `git add` <!-- .element class="fragment" -->
- Commit erstellen
 - `git commit` <!-- .element class="fragment" -->
 - `git commit -a` <!-- .element class="fragment" -->

---

## Status
- Dateien im Arbeitsverzeichnis
 - `git status` <!-- .element class="fragment" -->
- Änderungen im Arbeitsverzeichnis
 - `git diff` <!-- .element class="fragment" -->
- Änderungen im Staging-Bereich
 - `git diff --staged` <!-- .element class="fragment" -->
 - `git diff --cached` <!-- .element class="fragment" -->
- Bisherige/letzte Commits
 - `git log` <!-- .element class="fragment" -->

---

## Merge Workflow

- `git checkout -b feature` <!-- .element class="fragment" -->
- `git commit` <!-- .element class="fragment" -->
- `git checkout master`  <!-- .element class="fragment" -->
- `git pull` <!-- .element class="fragment" -->
- `git merge feature` <!-- .element class="fragment" -->
- `git push` <!-- .element class="fragment" -->
