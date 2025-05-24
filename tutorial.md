# Comandos

## Git
- git status
- git add .
- git diff
- git commit --amend -m "menssagem"
- git diff --staged
- git shortlog
- git reflog
- git branch
- git checkout
- git branch -m `novo nome da branch`
- git diff `branch1` `branch2`

## Git + GitHub
- git aremote add origin `git@github.com:nome/coisa.git`
- git remote -v
- git push
- git remote remove origin
- git pull
- git remote show origin

---

### Git:  merge e pull request (PR)
- git merge `nome da branch a qual se quer fazer merge`
- git merge --abort
- git merge --continue

--

### Tags (leves, anotadas)

- git  tag `nome da tag` (ex.: v2025)
- git tag
- git tag -d nome da tag

- git tag -a `nome da tag` -m `Pequena Descrição`
- git show ``nome da tag`
- git push origin v2025
- git push origin main --delete v2025

---
- git commit --amend
- git checkout -- `nome do arquivo`
