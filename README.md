# Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o desafio de projeto.

## Links úteis
[Sintaxe Basica Markdown](https://www.markdownguide.org/cheat-sheet/#basic-syntax)

## Nível Comando Função

## Básico	
git init - Inicia um repositório local
git clone URL - Clona um repositório do GitHub
git status - Mostra status dos arquivos (modificados/não versionados)
git add .	- Adiciona todos os arquivos para commit
git commit -m "msg" - Salva alterações com mensagem
git push origin main - Envia commits para o repositório remoto
git pull origin main - Atualiza com alterações do GitHub
git log	- Mostra histórico de commits

 ## Intermediário 
 git branch - nome	Cria uma branch
 git checkout - nome	- Muda para a branch escolhida
 git checkout -b nome - Cria e entra na branch
 git merge nome - Mescla branch ao código atual
 git diff - Mostra diferenças entre alterações
 git reset --soft HEAD~1	- Desfaz último commit (mantendo alterações)
 git reset --hard HEAD~1	- Desfaz último commit e apaga alterações
 git remote add origin URL	- Conecta repo local ao remoto

 ## Avançado	
 git rebase main	- Reorganiza histórico de commits
 git rebase -i HEAD~3 - Rebase interativo (editar commits antigos)
 git stash	- Guarda alterações sem commit
 git stash pop	- Recupera alterações guardadas
 git tag v1.0	- Marca uma versão no código
 git cherry-pick hash - Aplica commit específico em outra branch
 git reflog	- Mostra todo histórico, até commits "apagados"
 git submodule add URL	- Adiciona repositório dentro de outro
 git branch -d nome	- Apaga branch já mesclada
