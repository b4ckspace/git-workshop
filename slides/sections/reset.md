# git reset

---

## Reset auf Dateien

- `git reset [COMMIT] -- PATHS`
- Dateien im Staging auf `COMMIT/HEAD` bringen

---

## Reset auf aktuellen Branch

- `git reset COMMIT`
- Branch auf `COMMIT` setzen
 - `--soft` - Dateien und Staging unverändert
 - `--mixed` - (default) Staging mit ändern
 - `--hard` - alles verwerfen
 - `--merge` -
 - `--keep` -

---

## Use Cases

- Un-Commit
 - `git reset HEAD^`
- Branch zurücksetzen
 - `git reset --hard COMMIT`
 - Änderungen vorher in Commit!
 - Commits vorher in anderen Branch!

---

## Commits

- `HEAD`
- `HEAD^` (und `HEAD^^`, `HEAD^^^`, …)
- `HEAD~N`, z. B. `HEAD~5`

---

## git reflog

- Geschichte des Arbeitsverzeichnisses
- Welcher Branch war wann was?
- Selten nötig

---

## Split Commit

- `git reset HEAD^`
- `git add -p`
- `git commit`
- ...
- Als Teil von rebase `-i`
 - "edit" für den Patch
