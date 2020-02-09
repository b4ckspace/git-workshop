# GitHub Workflow

---

## Basic setup

- Fork Repository auf GitHub
 - eigenes Repository
- git clone UPSTREAMURL
 - "origin"
- git remote add private URL
 - "private" Remote
 - oder GitHub Username

---

## Pull Request

- Eigenen Branch benutzen
- git push private
- Auf GitHub PullRequest anlegen
- Ggf. Branch fixen
- git push --force private
- Profit
- Branch löschen
 - git branch -d feature
 - git push private --delete feature
 - git fetch --all --prune

---

## Master

- Finger weg!
- Notfalls:
 - git commit -a -m tmp
 - git checkout -b arg master
 - git checkout master
 - git reset --hard origin/master
