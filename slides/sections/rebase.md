# Rebase

---

## Rebase

- `git rebase TARGET SOURCE`
- Bewegt Branch nach `TARGET`
- Erzeugt neue Commits
- Alte Commit werden "unerreichbar"
- Evtl. zweiten Branch anlegen
 - Vergleich alt zu neu
 - "Nur zur Sicherheit"

---

<!-- .element data-background="white" data-background-iframe="https://git-school.github.io/visualizing-git/" data-background-interactive -->

---

## Workflow

1. `git checkout -b feature`
2. `git commit`
3. `git checkout master`
4. `git pull`
5. `git rebase master feature`
6. `git checkout master`
7. `git merge --ff-only feature`
8. `git push`
9. `git branch -d feature`

---

## Alternative

Statt

1. `git rebase master feature`
2. `git checkout master`
3. `git merge --ff-only feature`

evtl.

1. `git rebase master feature`
2. `git rebase feature master`

---

## Konflikte

- Jeder Commit kann einen Konflikt erzeugen
- Viele kleine anstatt einem großen (bei merge)
- AUSGABE DER BEFEHLE LESEN!
- Konflikt beheben
- `git add FILES`
- `git rebase --continue`
- Im Notfall: git rebase --abort

---

## Rebase -i

- Macht das selbe wie normaler rebase
- Öffnet aber Editor mit Liste von Commits
 - Mögliche Befehle unter der Liste
- Reihenfolge und Operation anpassen
 - Vertauschen von Commits erzeugt evtl. zwei Konflikte

---

## Rebase -i

- pick -- Commit verwenden
- drop -- Commit ignorieren
 - Zeile löschen funktioniert auch
 - Commit ist dann weg!
- edit -- Hier für Änderungen anhalten
 - git commit --amend
- reword -- Commit-Message in Editor öffnen
- squash -- Commit mit vorigem vereinen
 - Öffnet Editor mit beiden Commit-Messages
- fixup -- Commit mit vorigem vereinen
 - Benutzt Commit-Message vom ersten Commit

---

## Wie und Wofür?

- Bugfix Commits verschwinden lassen
 - "Perfekter Code"
 - Alle Commits lauffähig
- Änderungen zur Infrastruktur von Feature trennen
- Bessere Commit-Message
- Mehrere Iterationen oft einfacher
- Erlaubt häufige, kleine Commits
 - Im Zweifelsfall: `git commit`
