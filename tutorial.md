# Comandos com Exemplos

## Git

- `git status`  
  Exibe o estado atual do repositório.  
  **Exemplo:**  
  ```bash
  git status
  ```

- `git add .`  
  Adiciona todas as mudanças ao staging.  
  **Exemplo:**  
  ```bash
  git add .
  ```

- `git diff`  
  Mostra diferenças entre arquivos modificados.  
  **Exemplo:**  
  ```bash
  git diff
  ```

- `git commit --amend -m "mensagem"`  
  Altera a mensagem do último commit.  
  **Exemplo:**  
  ```bash
  git commit --amend -m "Corrige mensagem do commit anterior"
  ```

- `git diff --staged`  
  Mostra diferenças dos arquivos que estão no staging.  
  **Exemplo:**  
  ```bash
  git diff --staged
  ```

- `git shortlog`  
  Mostra um resumo dos commits por autor.  
  **Exemplo:**  
  ```bash
  git shortlog
  ```

- `git reflog`  
  Lista as alterações recentes do HEAD.  
  **Exemplo:**  
  ```bash
  git reflog
  ```

- `git branch`  
  Lista as branches existentes.  
  **Exemplo:**  
  ```bash
  git branch
  ```

- `git checkout`  
  Troca de branch ou restaura arquivos.  
  **Exemplo:**  
  ```bash
  git checkout develop
  ```

- `git branch -m novo_nome`  
  Renomeia a branch atual.  
  **Exemplo:**  
  ```bash
  git branch -m feature-login
  ```

- `git diff branch1 branch2`  
  Mostra as diferenças entre duas branches.  
  **Exemplo:**  
  ```bash
  git diff main develop
  ```

## Git + GitHub

- `git remote add origin git@github.com:nome/repositorio.git`  
  Adiciona repositório remoto.  
  **Exemplo:**  
  ```bash
  git remote add origin git@github.com:usuario/projeto.git
  ```

- `git remote -v`  
  Lista os repositórios remotos.  
  **Exemplo:**  
  ```bash
  git remote -v
  ```

- `git push`  
  Envia os commits para o repositório remoto.  
  **Exemplo:**  
  ```bash
  git push origin main
  ```

- `git remote remove origin`  
  Remove um repositório remoto.  
  **Exemplo:**  
  ```bash
  git remote remove origin
  ```

- `git pull`  
  Atualiza o repositório local com alterações remotas.  
  **Exemplo:**  
  ```bash
  git pull origin main
  ```

- `git remote show origin`  
  Mostra detalhes do repositório remoto.  
  **Exemplo:**  
  ```bash
  git remote show origin
  ```

## Merge e Pull Request (PR)

- `git merge nome_da_branch`  
  Faz merge da branch especificada na atual.  
  **Exemplo:**  
  ```bash
  git merge develop
  ```

- `git merge --abort`  
  Cancela um merge em andamento.  
  **Exemplo:**  
  ```bash
  git merge --abort
  ```

- `git merge --continue`  
  Continua o merge após resolver conflitos.  
  **Exemplo:**  
  ```bash
  git merge --continue
  ```

## Tags (leves e anotadas)

- `git tag nome_da_tag`  
  Cria uma tag leve.  
  **Exemplo:**  
  ```bash
  git tag v1.0.0
  ```

- `git tag`  
  Lista todas as tags.  
  **Exemplo:**  
  ```bash
  git tag
  ```

- `git tag -d nome_da_tag`  
  Remove uma tag localmente.  
  **Exemplo:**  
  ```bash
  git tag -d v1.0.0
  ```

- `git tag -a nome_da_tag -m "Descrição"`  
  Cria uma tag anotada.  
  **Exemplo:**  
  ```bash
  git tag -a v1.1.0 -m "Versão com novas funcionalidades"
  ```

- `git show nome_da_tag`  
  Mostra informações da tag.  
  **Exemplo:**  
  ```bash
  git show v1.1.0
  ```

- `git push origin v2025`  
  Envia uma tag para o repositório remoto.  
  **Exemplo:**  
  ```bash
  git push origin v1.0.0
  ```

- `git push origin main --delete v2025`  
  Remove uma tag do repositório remoto.  
  **Exemplo:**  
  ```bash
  git push origin main --delete v1.0.0
  ```

## Outros Comandos Úteis

- `git checkout -- nome_do_arquivo`  
  Restaura o arquivo modificado.  
  **Exemplo:**  
  ```bash
  git checkout -- README.md
  ```

- `git revert hash_do_commit`  
  Reverte um commit criando um novo.  
  **Exemplo:**  
  ```bash
  git revert a1b2c3d
  ```

- `git stash`  
  Armazena alterações temporariamente.  
  **Exemplo:**  
  ```bash
  git stash
  ```

- `git stash apply`  
  Aplica o stash mais recente.  
  **Exemplo:**  
  ```bash
  git stash apply
  ```

- `git stash pop`  
  Aplica e remove o stash mais recente.  
  **Exemplo:**  
  ```bash
  git stash pop
  ```

- `git push origin main --force`  
  Força o envio da branch (cuidado ao usar).  
  **Exemplo:**  
  ```bash
  git push origin main --force
  ```
