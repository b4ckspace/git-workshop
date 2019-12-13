## Vereinfachtes Beispiel

Note:
- vereinfachtes Beispiel

---

`$`
<!-- .element style="font-size: 1.5em; text-align: left" -->

---

`$ git init myproject`
<!-- .element style="font-size: 1.5em; text-align: left" -->

Notes:
- erstellt Verzeichnis myproject und verstecktes Unterverzeichnis .git
- Fehler: "*** Please tell me who you are."

---

```text
$ git init myproject
Initialized empty Git repository in /Users/martin/myproject/.git/
$
```
<!-- .element style="font-size: 1em; text-align: left; white-space: pre-wrap" -->

---

```text
$ cd myproject
myproject$
```
<!-- .element style="font-size: 1.5em; text-align: left" -->

---

```text
myproject$ git add myfile
```
<!-- .element style="font-size: 1.2em; text-align: left" -->

---

```text
myproject$
```
<!-- .element style="font-size: 1.2em; text-align: left" -->

---

```text
myproject$ git commit -m "Initial commit"
```
<!-- .element style="font-size: 1.2em; text-align: left; white-space: pre-wrap" -->

Notes:
- Parameter `-m` eher die Ausnahme
	- normalerweise: 

---

```text
myproject$ git commit -m "Initial commit"
myproject$
```
<!-- .element style="font-size: 1.2em; text-align: left; white-space: pre-wrap" -->

---

```text
$ git config --global user.name "Luca Mustermensch"
$ git config --global user.email luca@mustermensch.de
```
<!-- .element style="font-size: 1em; text-align: left; white-space: pre-wrap" -->

Notes:
- wichtig: Anführungszeichen bei user.name (wg. Leerzeichen)
- Ort für globale Konfiguration: ~/.gitconfig
- Ort für lokale Konfiguration: .git/config

---

<!-- .element data-background="white" data-background-iframe="https://git-school.github.io/visualizing-git/" data-background-interactive -->

Notes:
- https://github.com/git-school/visualizing-git
- undo, clear
