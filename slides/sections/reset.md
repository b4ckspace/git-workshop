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

<!-- .element style="text-align:left" -->

<code style="font-size:0.6em">
<span style="color:olive;">8613f2f</span> HEAD@{0}: commit: Add &quot;final&quot; versions of PDF files<br />
<span style="color:olive;">f6fff1f</span> HEAD@{1}: commit: Fix errors marked by Grammarly<br />
<span style="color:olive;">208c88e</span> HEAD@{2}: reset: moving to HEAD<br />
<span style="color:olive;">208c88e</span> HEAD@{3}: commit: Fix heading for appendix<br />
<span style="color:olive;">a090675</span> HEAD@{4}: commit: Switch to twosided layout<br />
<span style="color:olive;">eedddea</span> HEAD@{5}: commit: Add draft for future work and conclusion<br />
<span style="color:olive;">59a0d39</span> HEAD@{6}: commit: Fix capitalization<br />
<span style="color:olive;">f2a9d73</span> HEAD@{7}: commit: Finish draft for evaluation and move weights<br />
<span style="color:olive;">d56fd5e</span> HEAD@{8}: commit: Fix another load of errors<br />
<span style="color:olive;">72bf49a</span> HEAD@{9}: commit: Add plots of evaluation results<br />
<span style="color:olive;">7c4bd25</span> HEAD@{10}: commit: Move note from implementation to evaluation<br />
</code>

---

## Split Commit

- `git reset HEAD^`
- `git add -p`
- `git commit`
- ...
- Als Teil von rebase `-i`
 - "edit" für den Patch
