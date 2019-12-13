## Begriffe

---

### Projekt

- (Quell-)Text und weitere Dateien
- Versionen der jeweiligen Dateien
- Personen

---

### Repository

> **Ein Repository** (englisch für Lager, Depot oder auch Quelle; Plural: Repositories), auch – direkt aus dem Lateinischen entlehnt – Repositorium (Pl. Repositorien), **ist ein verwaltetes Verzeichnis zur Speicherung und Beschreibung von digitalen Objekten für ein digitales Archiv**.

<small style="font-size: 0.5em">Quelle: Seite „Repository“. In: Wikipedia, Die freie Enzyklopädie. Bearbeitungsstand: 20. Oktober 2019, 09:02 UTC. URL: https://de.wikipedia.org/w/index.php?title=Repository&oldid=193287297 (Abgerufen: 12. Dezember 2019, 10:24 UTC)</small>

Notes:
- wie Datenbank

---

### Commit

- gegenwärtigen Stand des Projektes als eine Version sichern
- bestimmte Dateien
- Metadaten:
	- Name
	- Zeitstempel
	- Dateirechte
	- Beschreibung: Titel und ggf. Text („Commit Message“)
- am besten kleine in sich geschlossene Schritte

Note:
- englisch für "festlegen", "begehen"

---

### Working Tree

aktueller oder älterer Stand einer Version in Form eines Verzeichnisbaumes aus herkömmlichen Dateien<br />
→ keine Spezialsoftware zur Bearbeitung der Dateien in der Repository notwendig

Notes:
- auch: Work Tree, Work(ing) Copy, Arbeitsverzeichnis, Arbeitskopie

---

### Checkout

Eine lokale Arbeitskopie aus den aktuellen (oder auch anderen) Dateien einer Repository erstellen.

---

### Stage / Index

- Vormerken von Dateien für einen Commit
- Zustand zwischen ungeänderten Dateien einer vorherigen Version bzw. noch unbekannten Dateien und einem Commit

Notes:
- auch: Staging Area

---

### Branch

- Abspaltung von einer Version („Entwicklungszweig“)
- ermöglicht parallele Entwicklung von Unterschiedlichen Versionen
- Änderungen können dabei von einem Branch auch in einem anderen wieder einfließen
- Hauptentwicklungszweig: „master“
- aktuellster Stand eines Entwicklungszweiges: „head“

Notes:
- englisch "branch" für "Zweig"

---

<img class="plain stretch" style="height: 600px; background: none" src="images/stash-branching_model.png" alt="" /><br />

Notes:
- Quelle: https://blog.oio.de/2014/09/22/git-workflows-teil-2-workflows-meistern/

---

## Zusammenhänge

![Areas](images/areas.svg) <!-- .element class="stretch plain" -->

---

## Zustände von Dateien

![Areas](images/lifecycle.svg) <!-- .element class="stretch plain" -->

