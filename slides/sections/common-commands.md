## Geläufigste Befehle

---

`git init`
<!-- .element style="font-size: 3em" -->

Erstellen einer Repository

---

`git status`
<!-- .element style="font-size: 3em" -->

Zeigt den Status der Dateien im Arbeitsverzeichnis

---

`git add ...`
<!-- .element style="font-size: 3em" -->

„Vormerken“ einer (oder mehrerer) Dateien
fügt diese zum Index/Stage hinzu (daher auch „Stagen“)

---

`git commit -m "..."`
<!-- .element style="font-size: 2em" -->

Erstellen eines Commits aus den Änderungen im Index mit der Nachricht `"..."`

Optional:<br />
Parameter `-a`: Änderungen an bekannten Dateien automatisch dem Commit hinzufügen (Staging überspringen)<br />
z.B.: `git commit -am "Added missing files"`

---

`git diff [DATEI]`
<!-- .element style="font-size: 2em" -->

Zeigt Unterschiede zwischen geänderten Dateien und dem letzten Commit an (als Diff, falls möglich)

Optional:<br />
Paramenter `--staged`: Zeigt Unterschiede zwischen Datei(en) in der Stage und dem letzten Commit an

---

`git log`
<!-- .element style="font-size: 3em" -->

Zeigt Commit-Verlauf (Historie) des aktuellen Entwicklungszweigs

---

`git checkout [branch]`
<!-- .element style="font-size: 2em" -->

Wechseln zu einem Entwicklungszweig mit dem Namen `[branch]`. Das Arbeitsverzeichnis wird automatisch angepasst.

---

`git branch [name]`
<!-- .element style="font-size: 2em" -->

Anzeigen der verfügbaren Entwicklungszweige

Erstellen eines neuen Entwicklungszweigs mit dem Namen `[name]` auf der Basis des aktuellen Commits.

Optional:<br  />
Parameter `-d`: Löschen des angegebenen Entwicklungszweigs

---

`git clone URL`
<!-- .element style="font-size: 2em" -->

Kopie von der Repository unter der URL `URL` herunterladen

---

`git pull`
<!-- .element style="font-size: 2em" -->

Änderungen von der URL herunterladen und versuchen es auf das Arbeitsverzeichnis anzuwenden

Note:
- `git fetch` + `git merge`

---

`git push`
<!-- .element style="font-size: 2em" -->

Lokale Änderungen hochladen und auf dem Server aktualisieren

Notes:
- erfordert i.d.R. Rechte zum Ändern
