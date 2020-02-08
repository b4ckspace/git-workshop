# Rebase

---

## Rebase

- git rebase TARGET SOURCE
- Move branch else where
- Creates new commits
- Old patches become lost
- Create second branch
 - For Savety
 - Or Comfort

---

<!-- .element data-background="white" data-background-iframe="https://git-school.github.io/visualizing-git/" data-background-interactive -->

---

## Workflow

- git checkout -b feature
- git commit
- git checkout master
- git pull
- git rebase master feature
- git checkout master
- git merge --ff-only feature
- git push
- git branch -d feature

---

## Conflicts

- Each Commit may conflict
- Many small conflicts instead of a big one
- READ THE OUTPUT!
- Resove conflict
- git add involved files
- git rebase --continue
- git rebase --abort
 - if all goes wrong

---

## Rebase -i

- Same as normal rebase
- But editor with changes
 - Descriptions of commands underneeth
- Rearrange the patches at will
 - Changing order may create two conflicts

---

## Rebase -i

- pick -- keep commit
- drop -- remove commit
 - deleting line also works
- edit -- stop here and allow making changes
 - git commit --amend
- reword -- reopen commit message
- squash -- combine with previous commit
 - open editor with commit messages
- fixup -- combine with previous commit
 - Use first commit message

