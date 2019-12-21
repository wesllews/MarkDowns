# Comandos GitHUB

Configuração de usuário:

`git config --global user.name "Nome"`

`git config --global user.email "email"`

## Comandos Básicos
* `git init` // inicia a linha do tempo

Manejo de Arquivo:
* `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
* `git rm nome\do\arquivo` // Deixa de monitorar o Arquivo
* `git commit -a -m "Mensagem"` // adiciona um ponto na linha do tempo

Visualização de versões:
* `git log` // visualiza os pontos na linha do tempo(Histórico) / commit
* `git reflog` // Mostra os detalhes de cada pontos na linha do tempo
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história

Branches (Ramos)
* `git branch` // Mostra a lista de branches
* `git branch nome_do_branch` // Cria um novo branch
* `git branch -d nome_do_branch` // Apaga um branch

* `git checkout` // manipula as linhas do tempo
* `git merge` // unir linhas do tempo
* `git push` // envia alterações locais para o repositório remoto
* `git clone` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto
