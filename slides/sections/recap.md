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

---

<a href="https://learngitbranching.js.org/?NODEMO&command=importTreeNow%20%7B%22branches%22%3A%7B%22master%22%3A%7B%22remoteTrackingBranchID%22%3A%22o/master%22%2C%22remote%22%3Afalse%2C%22target%22%3A%22C1%22%2C%22id%22%3A%22master%22%2C%22type%22%3A%22branch%22%7D%2C%22o/master%22%3A%7B%22remoteTrackingBranchID%22%3Anull%2C%22remote%22%3Afalse%2C%22target%22%3A%22C1%22%2C%22id%22%3A%22o/master%22%2C%22type%22%3A%22branch%22%7D%7D%2C%22commits%22%3A%7B%22C0%22%3A%7B%22type%22%3A%22commit%22%2C%22parents%22%3A%5B%5D%2C%22author%22%3A%22Peter%20Cottle%22%2C%22createTime%22%3A%22Thu%20Feb%2013%202020%2014%3A37%3A28%20GMT+0100%20%28Central%20European%20Standard%20Time%29%22%2C%22commitMessage%22%3A%22Quick%20commit.%20Go%20Bears%21%22%2C%22id%22%3A%22C0%22%2C%22rootCommit%22%3Atrue%7D%2C%22C1%22%3A%7B%22type%22%3A%22commit%22%2C%22parents%22%3A%5B%22C0%22%5D%2C%22author%22%3A%22Peter%20Cottle%22%2C%22createTime%22%3A%22Thu%20Feb%2013%202020%2014%3A37%3A28%20GMT+0100%20%28Central%20European%20Standard%20Time%29%22%2C%22commitMessage%22%3A%22Quick%20commit.%20Go%20Bears%21%22%2C%22id%22%3A%22C1%22%7D%7D%2C%22tags%22%3A%7B%7D%2C%22HEAD%22%3A%7B%22id%22%3A%22HEAD%22%2C%22target%22%3A%22master%22%2C%22type%22%3A%22general%20ref%22%7D%2C%22originTree%22%3A%7B%22branches%22%3A%7B%22master%22%3A%7B%22remoteTrackingBranchID%22%3Anull%2C%22remote%22%3Afalse%2C%22target%22%3A%22C1%22%2C%22id%22%3A%22master%22%2C%22type%22%3A%22branch%22%7D%7D%2C%22commits%22%3A%7B%22C0%22%3A%7B%22type%22%3A%22commit%22%2C%22parents%22%3A%5B%5D%2C%22author%22%3A%22Peter%20Cottle%22%2C%22createTime%22%3A%22Thu%20Feb%2013%202020%2014%3A37%3A37%20GMT+0100%20%28Central%20European%20Standard%20Time%29%22%2C%22commitMessage%22%3A%22Quick%20commit.%20Go%20Bears%21%22%2C%22id%22%3A%22C0%22%2C%22rootCommit%22%3Atrue%7D%2C%22C1%22%3A%7B%22type%22%3A%22commit%22%2C%22parents%22%3A%5B%22C0%22%5D%2C%22author%22%3A%22Peter%20Cottle%22%2C%22createTime%22%3A%22Thu%20Feb%2013%202020%2014%3A37%3A37%20GMT+0100%20%28Central%20European%20Standard%20Time%29%22%2C%22commitMessage%22%3A%22Quick%20commit.%20Go%20Bears%21%22%2C%22id%22%3A%22C1%22%7D%7D%2C%22tags%22%3A%7B%7D%2C%22HEAD%22%3A%7B%22target%22%3A%22master%22%2C%22id%22%3A%22HEAD%22%2C%22type%22%3A%22general%20ref%22%7D%7D%7D;clear">Visuelle Demo</a>
