# GitHub Workflow

---

## Basic setup

- Fork Repository auf GitHub
 - eigenes Repository
- `git clone UPSTREAMURL`
 - "origin"
- `git remote add private URL`
 - "private" Remote
 - oder GitHub Nutzername als Name für Remote

---

## Pull Request

1. Eigenen Branch benutzen
2. `git push private`
3. Auf GitHub Pull Request (PR) anlegen
4. Ggf. Branch fixen
5. `git push --force private`
6. Profit

---

## Branch löschen

1. `git branch -d feature`
2. `git push private --delete feature`
3. `git fetch --all --prune`

---

## Master

- Finger weg!
- Notfalls:
 - `git commit -a -m tmp`
 - `git checkout -b arg master`
 - `git checkout master`
 - `git reset --hard origin/master`
