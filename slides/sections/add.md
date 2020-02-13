# git add++

---

## git add

- `git add -p`
 - `git add -i`
- Teile (hunks) der Änderungen ins Staging
 - split - Änderung weiter aufteilen
 - edit - Änderung in Editor anpassen
- Dannach: `git commit`

---

## git add -p

``` text
y - stage this hunk
n - do not stage this hunk
q - quit; do not stage this hunk or any of the remaining ones
a - stage this hunk and all later hunks in the file
d - do not stage this hunk or any of the later hunks in the file
g - select a hunk to go to
/ - search for a hunk matching the given regex
j - leave this hunk undecided, see next undecided hunk
J - leave this hunk undecided, see next hunk
k - leave this hunk undecided, see previous undecided hunk
K - leave this hunk undecided, see previous hunk
s - split the current hunk into smaller hunks
e - manually edit the current hunk
? - print help
```

Notes:
- wichtige Befehle: y, n, s, e

---

<asciinema-player src="asciinemas/git-add-p.cast" font-size="large"></asciinema-player>

---

## git add -i

``` text
*** Commands ***
  1: status    2: update    3: revert    4: add untracked
  5: patch     6: diff      7: quit      8: help
```
