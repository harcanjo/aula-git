# GIT E GITHUB

Guia prático para iniciantes.
[Video tutorial da Rocketseat](https://www.youtube.com/watch?v=2alg7MQ6_sI)

### Instalação

https://git-scm.com/download

### SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto.
- [x] Você deseja verificar mudanças feitas no seu projeto.
- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção.
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.
- [x] Você quer colocar seu projeto na nuvem.
- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time.
- [x] Você precisa resolver um conflito.
- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.
- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
- [x] Você precisa recupera algo deletado.

### Comandos usados na aula

- `git init` // Inicia a linha do tempo
- `git add nomedoarquivo.txt` // Adiciona ou atualiza mudanças para a linha do tempo
- `git add .` // Adiciona todas mudanças para a linha do tempo
- `git commit -m "mensagem do commit"` // Adiciona um ponto na linha do tempo
- `git commit -am "mensagem do commit"` // Adiciona a alteração e já faz o commit
- `git log` // Visualiza os pontos na linha do tempo / commit
- `git status` // Informa o estado das alterações do nosso projeto
- `git show numerodocommit` // Apresenta deternimado ponto na história
- `git show` // Mostra o último ponto na história
- `git branch nomedabranch` // Cria a branch
- `git checkout nomedabranch` // Acessa a branch
- `git branch` // Gerencia novas linhas do tempo
- `git merge nomedabranch` // Adiciona a branch para a branch atual
- `git checkout -b teste` // Cria a branch e já acessa
- `git branch -D nomedabranch` // Deleta a branch
- `git remote add origin https://github.com/harcanjo/aula-git.git` // Depois de criado o repositorio no GitHub, liga o repositório à nuvem
- `git remote -v` // Mostra os repositorios remotos
- `git push -u origin master` // Envia o projeto a primeira vez
- `git push` // Envia alterações locais para o repositório remoto
- `git config credential.helper store` // Salva as credenciais
- `git clone https://github.com/nomedoprojeto.git` // Clona o repositorio remoto para sua máquina
- `git pull` // Atualiza o projeto local com as alterações feitas no projeto remoto
- `git checkout numerodocommit -- nomedoarquivo` // Recupera um arquivo na linha do tempo, pega o arquivo no commit
- `git checkout -- nomedoarquivo` // Recupera um arquivo no tempo atual, pega o arquivo deletado
